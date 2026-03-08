# automation Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `30`

## Operations

### GET /base/{baseId}/workflow

- Method: `GET`
- Path: `/base/{baseId}/workflow`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: get automation workflow list in base

### POST /base/{baseId}/workflow

- Method: `POST`
- Path: `/base/{baseId}/workflow`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a automation workflow

### POST /base/{baseId}/workflow/{tableId}/filter-link-records

- Method: `POST`
- Path: `/base/{baseId}/workflow/{tableId}/filter-link-records`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: get automation workflow list in base

### DELETE /base/{baseId}/workflow/{workflowId}

- Method: `DELETE`
- Path: `/base/{baseId}/workflow/{workflowId}`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: delete a automation workflow

### GET /base/{baseId}/workflow/{workflowId}

- Method: `GET`
- Path: `/base/{baseId}/workflow/{workflowId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: get a automation workflow

### PUT /base/{baseId}/workflow/{workflowId}

- Method: `PUT`
- Path: `/base/{baseId}/workflow/{workflowId}`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: update a automation workflow

### POST /base/{baseId}/workflow/{workflowId}/action

- Method: `POST`
- Path: `/base/{baseId}/workflow/{workflowId}/action`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a automation workflow action

### DELETE /base/{baseId}/workflow/{workflowId}/action/{actionId}

- Method: `DELETE`
- Path: `/base/{baseId}/workflow/{workflowId}/action/{actionId}`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: delete a automation workflow action

### GET /base/{baseId}/workflow/{workflowId}/action/{actionId}

- Method: `GET`
- Path: `/base/{baseId}/workflow/{workflowId}/action/{actionId}`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: get a automation workflow action

### PUT /base/{baseId}/workflow/{workflowId}/action/{actionId}

- Method: `PUT`
- Path: `/base/{baseId}/workflow/{workflowId}/action/{actionId}`
- Parameters: `3`
- Request Body: `yes`
- Response Codes: `200`
- Description: update a automation workflow action

### POST /base/{baseId}/workflow/{workflowId}/action/{actionId}/duplicate

- Method: `POST`
- Path: `/base/{baseId}/workflow/{workflowId}/action/{actionId}/duplicate`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: duplicate a automation workflow action

### GET /base/{baseId}/workflow/{workflowId}/action/{actionId}/script-input

- Method: `GET`
- Path: `/base/{baseId}/workflow/{workflowId}/action/{actionId}/script-input`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: Get script integrations for a workflow action

### PUT /base/{baseId}/workflow/{workflowId}/active

- Method: `PUT`
- Path: `/base/{baseId}/workflow/{workflowId}/active`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: active or inactive a automation workflow

### GET /base/{baseId}/workflow/{workflowId}/active-snapshot

- Method: `GET`
- Path: `/base/{baseId}/workflow/{workflowId}/active-snapshot`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get the currently active (published) snapshot of a workflow. Returns the version that is actually running, as opposed to the draft version returned by getWorkflow.

### POST /base/{baseId}/workflow/{workflowId}/duplicate

- Method: `POST`
- Path: `/base/{baseId}/workflow/{workflowId}/duplicate`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: duplicate a automation workflow

### POST /base/{baseId}/workflow/{workflowId}/logic

- Method: `POST`
- Path: `/base/{baseId}/workflow/{workflowId}/logic`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a automation workflow logic

### DELETE /base/{baseId}/workflow/{workflowId}/logic/{logicId}

- Method: `DELETE`
- Path: `/base/{baseId}/workflow/{workflowId}/logic/{logicId}`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: delete a automation workflow logic

### GET /base/{baseId}/workflow/{workflowId}/logic/{logicId}

- Method: `GET`
- Path: `/base/{baseId}/workflow/{workflowId}/logic/{logicId}`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: get a automation workflow logic

### PUT /base/{baseId}/workflow/{workflowId}/logic/{logicId}

- Method: `PUT`
- Path: `/base/{baseId}/workflow/{workflowId}/logic/{logicId}`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: update a automation workflow logic

### PUT /base/{baseId}/workflow/{workflowId}/order

- Method: `PUT`
- Path: `/base/{baseId}/workflow/{workflowId}/order`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update workflow order

### Permanently delete workflow

- Method: `DELETE`
- Path: `/base/{baseId}/workflow/{workflowId}/permanent`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Permanently delete a workflow and all its data. This action cannot be undone.

### GET /base/{baseId}/workflow/{workflowId}/run

- Method: `GET`
- Path: `/base/{baseId}/workflow/{workflowId}/run`
- Parameters: `5`
- Request Body: `no`
- Response Codes: `200`
- Description: get automation workflow run history list

### GET /base/{baseId}/workflow/{workflowId}/run/summary

- Method: `GET`
- Path: `/base/{baseId}/workflow/{workflowId}/run/summary`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: get automation workflow run summary statistics

### GET /base/{baseId}/workflow/{workflowId}/run/{runId}

- Method: `GET`
- Path: `/base/{baseId}/workflow/{workflowId}/run/{runId}`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: get automation workflow run list

### POST /base/{baseId}/workflow/{workflowId}/test-all

- Method: `POST`
- Path: `/base/{baseId}/workflow/{workflowId}/test-all`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: test a automation workflow all

### POST /base/{baseId}/workflow/{workflowId}/test/{nodeId}

- Method: `POST`
- Path: `/base/{baseId}/workflow/{workflowId}/test/{nodeId}`
- Parameters: `3`
- Request Body: `yes`
- Response Codes: `200`
- Description: test a automation workflow node

### POST /base/{baseId}/workflow/{workflowId}/trigger

- Method: `POST`
- Path: `/base/{baseId}/workflow/{workflowId}/trigger`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a automation workflow trigger

### GET /base/{baseId}/workflow/{workflowId}/trigger/{triggerId}

- Method: `GET`
- Path: `/base/{baseId}/workflow/{workflowId}/trigger/{triggerId}`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: get a automation workflow trigger

### PUT /base/{baseId}/workflow/{workflowId}/trigger/{triggerId}

- Method: `PUT`
- Path: `/base/{baseId}/workflow/{workflowId}/trigger/{triggerId}`
- Parameters: `3`
- Request Body: `yes`
- Response Codes: `200`
- Description: update a automation workflow trigger

### POST /base/{baseId}/workflow/{workflowId}/trigger/{triggerId}/generate-webhook-token

- Method: `POST`
- Path: `/base/{baseId}/workflow/{workflowId}/trigger/{triggerId}/generate-webhook-token`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: Generate a new webhook token for the trigger
