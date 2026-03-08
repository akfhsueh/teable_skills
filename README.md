# Teable API Skills

AI skills for your self-hosted [Teable](https://teable.io) server. With these skills loaded into your AI assistant, you can ask it to create tables, define fields, set up views, and generate scripts to replicate your exact database structure — all through natural language.

**Last API retrieval:** Feb 27, 2026
**Tested version:** `ghcr.io/teableio/teable:0.5.0-alpha-1.10.0-build.1002`

---

## Background

### Why Teable instead of managing SQL + Redis yourself?

1. **No infrastructure overhead** — Teable bundles PostgreSQL and Redis into a single deployable container. You skip connection pooling, schema migrations, index tuning, and cache invalidation config.
2. **Spreadsheet UI out of the box** — non-technical teammates can read and edit data without touching SQL or a database client.
3. **REST API included** — every table and view is instantly queryable via a documented OpenAPI endpoint, which is exactly what these skills are built on.
4. **Role-based access control** — fine-grained permissions per space, base, and table without writing your own auth layer.
5. **Self-hosted and open source** — your data stays on your infrastructure, no vendor lock-in, and you can inspect or fork the codebase.

### Teable vs. the alternatives

| | Teable |
|---|---|
| **Airtable** | Airtable imposes row limits per base and charges per seat. Its automation and integration options are relatively rigid — you work within their approved connector list. Teable is self-hosted, row-unlimited, and exposes a full REST API you can script freely. |
| **Notion** | Notion is excellent for docs, wikis, and lightweight databases, but its target audience leans toward knowledge management and team notes. Teable is purpose-built as a database-first platform, making it the better fit when structured data, filtering, and programmatic access matter more than rich text pages. |
| **Smartsheet** | Smartsheet is strong for project/resource management and enterprise workflows but carries enterprise pricing to match. Teable gives you a similar grid interface without the cost floor, and because it's self-hosted you control data residency and compliance entirely. |

---

## How to Generate / Update the Skills

### Step 1 — Extract the Swagger spec from your Teable instance

1. Start your Teable server and open `http://127.0.0.1:3000/docs` in a browser.
2. Open DevTools (`F12`) and go to the **Console** tab.
3. Paste and run the following snippet:

```js
(function() {
    const data = JSON.stringify(window.ui.specSelectors.specJson().toJSON(), null, 2);
    const blob = new Blob([data], { type: 'application/json' });
    const url = window.URL.createObjectURL(blob);
    const a = document.createElement('a');
    a.href = url;
    a.download = 'swagger-spec.json';
    a.click();
    window.URL.revokeObjectURL(url);
})();
```

This downloads `swagger-spec.json` to your machine.

### Step 2 — Generate the skills folder

Place `swagger-spec.json` in a working directory, then use an AI coding tool (e.g. OpenAI Codex, Claude Code) with a prompt such as:

> "Split this swagger-spec.json into a `skills/` folder. For each API tag, create a subfolder named `teable-api-<tag>/` containing a `SKILL.md` (summary, endpoints, example usage) and a `references/` subfolder with `api.md` and `openapi.json` filtered to that tag's paths."

The result is a `skills/` directory structured like this repo.

### Step 3 — Download and merge into your existing skills folder

Download the generated zip (or clone/pull this repo), then merge with your existing Claude Code skills folder:

```bash
# Unzip the downloaded archive
unzip teable_skills.zip -d teable_skills_tmp

# Merge into your existing skills directory (adjust destination path as needed)
cp -r teable_skills_tmp/skills/* ~/.claude/skills/

# Clean up
rm -rf teable_skills_tmp
```

Or, if you cloned this repo directly:

```bash
cp -r /path/to/teable_skills/skills/* ~/.claude/skills/
```

---

## Keeping Skills Up to Date

Teable releases may add, remove, or change API endpoints. To check for drift:

1. Extract a fresh `swagger-spec.json` from your updated instance (Step 1 above).
2. Diff it against the previous spec:

```bash
diff <(jq 'keys' swagger-spec-old.json) <(jq 'keys' swagger-spec-new.json)
# or for a full path-level diff:
diff <(jq '[.paths | keys[]]' swagger-spec-old.json | sort) \
     <(jq '[.paths | keys[]]' swagger-spec-new.json | sort)
```

3. If differences are found, re-run Step 2 to regenerate the affected skill files and re-merge.

---

## Usage

Once the skills are in your Claude Code skills folder, you can ask things like:

- "Create a Projects table in my Teable base with fields for name, status, due date, and assignee."
- "Write a script that pulls all records from the Tasks table where status is 'In Progress'."
- "Set up a new base with three linked tables: Clients, Projects, and Invoices."

The AI will use the appropriate skill files to call the correct Teable API endpoints.
