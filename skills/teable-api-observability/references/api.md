# observability Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `5`

## Operations

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
