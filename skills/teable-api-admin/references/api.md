# admin Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `41`

## Operations

### GET /admin/audit-logs

- Method: `GET`
- Path: `/admin/audit-logs`
- Parameters: `7`
- Request Body: `no`
- Response Codes: `200`
- Description: Get audit logs with filtering and pagination

### GET /admin/enterprise-license

- Method: `GET`
- Path: `/admin/enterprise-license`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get enterprise license information

### POST /admin/enterprise-license

- Method: `POST`
- Path: `/admin/enterprise-license`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Create a enterprise license

### GET /admin/enterprise-license/status

- Method: `GET`
- Path: `/admin/enterprise-license/status`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get enterprise license expiration status

### PATCH /admin/enterprise-license/{licenseId}

- Method: `PATCH`
- Path: `/admin/enterprise-license/{licenseId}`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Update a enterprise license by license ID

### GET /admin/observability/workflow

- Method: `GET`
- Path: `/admin/observability/workflow`
- Parameters: `9`
- Request Body: `no`
- Response Codes: `200`
- Description: get observability workflow list

### GET /admin/observability/workflow/summary

- Method: `GET`
- Path: `/admin/observability/workflow/summary`
- Parameters: `7`
- Request Body: `no`
- Response Codes: `200`
- Description: Retrieves a summary of workflow observability

### DELETE /admin/observability/workflow/{workflowId}

- Method: `DELETE`
- Path: `/admin/observability/workflow/{workflowId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a workflow observability

### POST /admin/observability/workflow/{workflowId}/deactivate

- Method: `POST`
- Path: `/admin/observability/workflow/{workflowId}/deactivate`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Deactivate a workflow observability

### GET /admin/observability/workflow/{workflowId}/run-history

- Method: `GET`
- Path: `/admin/observability/workflow/{workflowId}/run-history`
- Parameters: `4`
- Request Body: `no`
- Response Codes: `200`
- Description: get workflow run history

### GET /admin/organization

- Method: `GET`
- Path: `/admin/organization`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: Get paginated organizations for the instance

### POST /admin/organization

- Method: `POST`
- Path: `/admin/organization`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a new organization

### DELETE /admin/organization/{organizationId}

- Method: `DELETE`
- Path: `/admin/organization/{organizationId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete an organization by organization ID for admin

### GET /admin/organization/{organizationId}/admin

- Method: `GET`
- Path: `/admin/organization/{organizationId}/admin`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get organization admin users

### PUT /admin/organization/{organizationId}/admin

- Method: `PUT`
- Path: `/admin/organization/{organizationId}/admin`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update organization admin status for a user

### PATCH /admin/plugin/{pluginId}/publish

- Method: `PATCH`
- Path: `/admin/plugin/{pluginId}/publish`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Publish a plugin

### PATCH /admin/plugin/{pluginId}/unpublish

- Method: `PATCH`
- Path: `/admin/plugin/{pluginId}/unpublish`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Admin unpublish a plugin

### Export admin reward list as CSV

- Method: `GET`
- Path: `/admin/reward/export/{spaceId}`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: Export all reward records for a specific space as CSV file. Supports filtering by date range.

### Get admin reward list

- Method: `GET`
- Path: `/admin/reward/list`
- Parameters: `10`
- Request Body: `no`
- Response Codes: `200`
- Description: Get paginated and filtered list of reward for admin management. Supports filtering by space, status, platform, verification result, and search.

### Get admin reward overview by spaces

- Method: `GET`
- Path: `/admin/reward/overview`
- Parameters: `5`
- Request Body: `no`
- Response Codes: `200`
- Description: Get aggregated reward statistics grouped by space for admin management. Returns pending, approved, consumed, available and expiring amounts per space.

### Get all spaces with reward records

- Method: `GET`
- Path: `/admin/reward/spaces`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a list of all spaces that have reward records for admin filtering

### Get admin reward detail

- Method: `GET`
- Path: `/admin/reward/{rewardId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get detailed information of a specific reward including full metadata

### GET /admin/setting

- Method: `GET`
- Path: `/admin/setting`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get the instance settings

### PATCH /admin/setting

- Method: `PATCH`
- Path: `/admin/setting`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Get the instance settings

### GET /admin/setting/ai-key-stats

- Method: `GET`
- Path: `/admin/setting/ai-key-stats`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get per-key usage statistics for AI Gateway API keys

### POST /admin/setting/batch-test-llm

- Method: `POST`
- Path: `/admin/setting/batch-test-llm`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Batch test all configured LLM models to verify compatibility with AI field features

### PATCH /admin/setting/logo

- Method: `PATCH`
- Path: `/admin/setting/logo`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Upload logo

### GET /admin/setting/public

- Method: `GET`
- Path: `/admin/setting/public`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get the public instance settings

### PUT /admin/setting/set-mail-transport-config

- Method: `PUT`
- Path: `/admin/setting/set-mail-transport-config`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Set mail transporter

### POST /admin/setting/test-api-key

- Method: `POST`
- Path: `/admin/setting/test-api-key`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Test API key validity for AI Gateway or v0, optionally test attachment transfer modes

### POST /admin/setting/test-llm

- Method: `POST`
- Path: `/admin/setting/test-llm`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Test LLM provider configuration

### GET /admin/setting/test-public-access

- Method: `GET`
- Path: `/admin/setting/test-public-access`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Test if this Teable instance is publicly accessible from the internet

### GET /admin/space

- Method: `GET`
- Path: `/admin/space`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: Get paginated spaces for the instance

### DELETE /admin/space/{spaceId}

- Method: `DELETE`
- Path: `/admin/space/{spaceId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a space by space ID for admin

### PATCH /admin/space/{spaceId}

- Method: `PATCH`
- Path: `/admin/space/{spaceId}`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: update enterprise space information

### GET /admin/user

- Method: `GET`
- Path: `/admin/user`
- Parameters: `4`
- Request Body: `no`
- Response Codes: `200`
- Description: Get paginated users for the instance

### DELETE /admin/user/{userId}

- Method: `DELETE`
- Path: `/admin/user/{userId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a user by user ID for admin

### PATCH /admin/user/{userId}

- Method: `PATCH`
- Path: `/admin/user/{userId}`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update a user info

### PATCH /admin/user/{userId}/admin

- Method: `PATCH`
- Path: `/admin/user/{userId}/admin`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Set or unset admin privilege for a user

### DELETE /admin/user/{userId}/permanent-delete

- Method: `DELETE`
- Path: `/admin/user/{userId}/permanent-delete`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Permanent delete a user by user ID for admin

### POST /admin/user/{userId}/restore-delete

- Method: `POST`
- Path: `/admin/user/{userId}/restore-delete`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Restore a deleted user
