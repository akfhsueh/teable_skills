# plugin Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `14`

## Operations

### GET /plugin

- Method: `GET`
- Path: `/plugin`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get plugins

### POST /plugin

- Method: `POST`
- Path: `/plugin`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a plugin

### GET /plugin/center/list

- Method: `GET`
- Path: `/plugin/center/list`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a list of plugins center

### GET /plugin/chart/{pluginInstallId}/dashboard/{positionId}/query

- Method: `GET`
- Path: `/plugin/chart/{pluginInstallId}/dashboard/{positionId}/query`
- Parameters: `4`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a dashboard install plugin query by id

### GET /plugin/chart/{pluginInstallId}/plugin-panel/{positionId}/query

- Method: `GET`
- Path: `/plugin/chart/{pluginInstallId}/plugin-panel/{positionId}/query`
- Parameters: `4`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a plugin panel install plugin query by id

### DELETE /plugin/{id}

- Method: `DELETE`
- Path: `/plugin/{id}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a plugin

### PUT /plugin/{id}

- Method: `PUT`
- Path: `/plugin/{id}`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update a plugin

### POST /plugin/{id}/regenerate-secret

- Method: `POST`
- Path: `/plugin/{id}/regenerate-secret`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `201`
- Description: Regenerate a plugin secret

### GET /plugin/{pluginId}

- Method: `GET`
- Path: `/plugin/{pluginId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a plugin

### POST /plugin/{pluginId}/authCode

- Method: `POST`
- Path: `/plugin/{pluginId}/authCode`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Get an auth code

### POST /plugin/{pluginId}/refreshToken

- Method: `POST`
- Path: `/plugin/{pluginId}/refreshToken`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Refresh a token

### PATCH /plugin/{pluginId}/submit

- Method: `PATCH`
- Path: `/plugin/{pluginId}/submit`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Submit a plugin

### GET /plugin/{pluginId}/token

- Method: `GET`
- Path: `/plugin/{pluginId}/token`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Get a token

### PATCH /plugin/{pluginId}/unpublish

- Method: `PATCH`
- Path: `/plugin/{pluginId}/unpublish`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
