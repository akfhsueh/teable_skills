# comment Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `13`

## Operations

### GET /comment/{tableId}/count

- Method: `GET`
- Path: `/comment/{tableId}/count`
- Parameters: `18`
- Request Body: `no`
- Response Codes: `200`
- Description: Get record comment counts by query

### GET /comment/{tableId}/{recordId}/attachment/{path}

- Method: `GET`
- Path: `/comment/{tableId}/{recordId}/attachment/{path}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get record comment attachment url

### GET /comment/{tableId}/{recordId}/count

- Method: `GET`
- Path: `/comment/{tableId}/{recordId}/count`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get record comment count

### POST /comment/{tableId}/{recordId}/create

- Method: `POST`
- Path: `/comment/{tableId}/{recordId}/create`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `201`
- Description: create record comment

### GET /comment/{tableId}/{recordId}/list

- Method: `GET`
- Path: `/comment/{tableId}/{recordId}/list`
- Parameters: `6`
- Request Body: `no`
- Response Codes: `200`
- Description: Get record comment list

### DELETE /comment/{tableId}/{recordId}/subscribe

- Method: `DELETE`
- Path: `/comment/{tableId}/{recordId}/subscribe`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: unsubscribe record comment

### GET /comment/{tableId}/{recordId}/subscribe

- Method: `GET`
- Path: `/comment/{tableId}/{recordId}/subscribe`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: get record comment subscribe detail

### POST /comment/{tableId}/{recordId}/subscribe

- Method: `POST`
- Path: `/comment/{tableId}/{recordId}/subscribe`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `201`
- Description: subscribe record comment's active

### DELETE /comment/{tableId}/{recordId}/{commentId}

- Method: `DELETE`
- Path: `/comment/{tableId}/{recordId}/{commentId}`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: delete record comment

### GET /comment/{tableId}/{recordId}/{commentId}

- Method: `GET`
- Path: `/comment/{tableId}/{recordId}/{commentId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get record comment detail

### PATCH /comment/{tableId}/{recordId}/{commentId}

- Method: `PATCH`
- Path: `/comment/{tableId}/{recordId}/{commentId}`
- Parameters: `3`
- Request Body: `yes`
- Response Codes: `200`
- Description: update record comment

### DELETE /comment/{tableId}/{recordId}/{commentId}/reaction

- Method: `DELETE`
- Path: `/comment/{tableId}/{recordId}/{commentId}/reaction`
- Parameters: `3`
- Request Body: `yes`
- Response Codes: `200`
- Description: delete record comment reaction

### POST /comment/{tableId}/{recordId}/{commentId}/reaction

- Method: `POST`
- Path: `/comment/{tableId}/{recordId}/{commentId}/reaction`
- Parameters: `3`
- Request Body: `yes`
- Response Codes: `201`
- Description: create record comment reaction
