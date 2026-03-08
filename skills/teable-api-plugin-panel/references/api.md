# plugin-panel Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `14`

## Operations

### GET /plugin/chart/{pluginInstallId}/plugin-panel/{positionId}/query

- Method: `GET`
- Path: `/plugin/chart/{pluginInstallId}/plugin-panel/{positionId}/query`
- Parameters: `4`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a plugin panel install plugin query by id

### GET /table/{tableId}/plugin-panel

- Method: `GET`
- Path: `/table/{tableId}/plugin-panel`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get all plugin panels

### POST /table/{tableId}/plugin-panel

- Method: `POST`
- Path: `/table/{tableId}/plugin-panel`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a plugin panel

### DELETE /table/{tableId}/plugin-panel/{pluginPanelId}

- Method: `DELETE`
- Path: `/table/{tableId}/plugin-panel/{pluginPanelId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a plugin panel

### GET /table/{tableId}/plugin-panel/{pluginPanelId}

- Method: `GET`
- Path: `/table/{tableId}/plugin-panel/{pluginPanelId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a plugin panel

### Duplicate a plugin panel

- Method: `POST`
- Path: `/table/{tableId}/plugin-panel/{pluginPanelId}/duplicate`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Duplicate a plugin panel

### POST /table/{tableId}/plugin-panel/{pluginPanelId}/install

- Method: `POST`
- Path: `/table/{tableId}/plugin-panel/{pluginPanelId}/install`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `201`
- Description: Install a plugin to a table plugin panel

### PATCH /table/{tableId}/plugin-panel/{pluginPanelId}/layout

- Method: `PATCH`
- Path: `/table/{tableId}/plugin-panel/{pluginPanelId}/layout`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update the layout of a plugin panel

### Duplicate a dashboard installed plugin

- Method: `POST`
- Path: `/table/{tableId}/plugin-panel/{pluginPanelId}/plugin/{installedId}/duplicate`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Duplicate a dashboard installed plugin

### DELETE /table/{tableId}/plugin-panel/{pluginPanelId}/plugin/{pluginInstallId}

- Method: `DELETE`
- Path: `/table/{tableId}/plugin-panel/{pluginPanelId}/plugin/{pluginInstallId}`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: Remove a plugin from a plugin panel

### GET /table/{tableId}/plugin-panel/{pluginPanelId}/plugin/{pluginInstallId}

- Method: `GET`
- Path: `/table/{tableId}/plugin-panel/{pluginPanelId}/plugin/{pluginInstallId}`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a plugin in plugin panel

### PATCH /table/{tableId}/plugin-panel/{pluginPanelId}/plugin/{pluginInstallId}/rename

- Method: `PATCH`
- Path: `/table/{tableId}/plugin-panel/{pluginPanelId}/plugin/{pluginInstallId}/rename`
- Parameters: `3`
- Request Body: `yes`
- Response Codes: `200`
- Description: Rename a plugin in a plugin panel

### PATCH /table/{tableId}/plugin-panel/{pluginPanelId}/plugin/{pluginInstallId}/update-storage

- Method: `PATCH`
- Path: `/table/{tableId}/plugin-panel/{pluginPanelId}/plugin/{pluginInstallId}/update-storage`
- Parameters: `3`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update storage of a plugin in a plugin panel

### PATCH /table/{tableId}/plugin-panel/{pluginPanelId}/rename

- Method: `PATCH`
- Path: `/table/{tableId}/plugin-panel/{pluginPanelId}/rename`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Rename a plugin panel
