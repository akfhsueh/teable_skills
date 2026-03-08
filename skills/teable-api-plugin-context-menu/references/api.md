# plugin-context-menu Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `8`

## Operations

### GET /table/{tableId}/plugin-context-menu

- Method: `GET`
- Path: `/table/{tableId}/plugin-context-menu`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`

### POST /table/{tableId}/plugin-context-menu/install

- Method: `POST`
- Path: `/table/{tableId}/plugin-context-menu/install`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Install a plugin context menu

### DELETE /table/{tableId}/plugin-context-menu/{pluginInstallId}

- Method: `DELETE`
- Path: `/table/{tableId}/plugin-context-menu/{pluginInstallId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Remove a plugin context menu

### GET /table/{tableId}/plugin-context-menu/{pluginInstallId}

- Method: `GET`
- Path: `/table/{tableId}/plugin-context-menu/{pluginInstallId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`

### PUT /table/{tableId}/plugin-context-menu/{pluginInstallId}/move

- Method: `PUT`
- Path: `/table/{tableId}/plugin-context-menu/{pluginInstallId}/move`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`

### PATCH /table/{tableId}/plugin-context-menu/{pluginInstallId}/rename

- Method: `PATCH`
- Path: `/table/{tableId}/plugin-context-menu/{pluginInstallId}/rename`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Rename a plugin context menu

### GET /table/{tableId}/plugin-context-menu/{pluginInstallId}/storage

- Method: `GET`
- Path: `/table/{tableId}/plugin-context-menu/{pluginInstallId}/storage`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`

### PUT /table/{tableId}/plugin-context-menu/{pluginInstallId}/update-storage

- Method: `PUT`
- Path: `/table/{tableId}/plugin-context-menu/{pluginInstallId}/update-storage`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
