# dashboard Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `14`

## Operations

### GET /base/{baseId}/dashboard

- Method: `GET`
- Path: `/base/{baseId}/dashboard`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a list of dashboards in base

### POST /base/{baseId}/dashboard

- Method: `POST`
- Path: `/base/{baseId}/dashboard`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a new dashboard

### DELETE /base/{baseId}/dashboard/{dashboardId}/plugin/{pluginInstallId}

- Method: `DELETE`
- Path: `/base/{baseId}/dashboard/{dashboardId}/plugin/{pluginInstallId}`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: Remove a plugin from a dashboard

### GET /base/{baseId}/dashboard/{dashboardId}/plugin/{pluginInstallId}

- Method: `GET`
- Path: `/base/{baseId}/dashboard/{dashboardId}/plugin/{pluginInstallId}`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a dashboard install plugin by id

### PATCH /base/{baseId}/dashboard/{dashboardId}/plugin/{pluginInstallId}/rename

- Method: `PATCH`
- Path: `/base/{baseId}/dashboard/{dashboardId}/plugin/{pluginInstallId}/rename`
- Parameters: `3`
- Request Body: `yes`
- Response Codes: `200`
- Description: Rename a plugin in a dashboard

### PATCH /base/{baseId}/dashboard/{dashboardId}/plugin/{pluginInstallId}/update-storage

- Method: `PATCH`
- Path: `/base/{baseId}/dashboard/{dashboardId}/plugin/{pluginInstallId}/update-storage`
- Parameters: `3`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update storage of a plugin in a dashboard

### PATCH /base/{baseId}/dashboard/{dashboardId}/rename

- Method: `PATCH`
- Path: `/base/{baseId}/dashboard/{dashboardId}/rename`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Rename a dashboard by id

### DELETE /base/{baseId}/dashboard/{id}

- Method: `DELETE`
- Path: `/base/{baseId}/dashboard/{id}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a dashboard by id

### GET /base/{baseId}/dashboard/{id}

- Method: `GET`
- Path: `/base/{baseId}/dashboard/{id}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a dashboard by id

### Duplicate a dashboard

- Method: `POST`
- Path: `/base/{baseId}/dashboard/{id}/duplicate`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Duplicate a dashboard

### PATCH /base/{baseId}/dashboard/{id}/layout

- Method: `PATCH`
- Path: `/base/{baseId}/dashboard/{id}/layout`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update a dashboard layout by id

### POST /base/{baseId}/dashboard/{id}/plugin

- Method: `POST`
- Path: `/base/{baseId}/dashboard/{id}/plugin`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `201`
- Description: Install a plugin to a dashboard

### Duplicate a dashboard installed plugin

- Method: `POST`
- Path: `/base/{baseId}/dashboard/{id}/plugin/{installedId}/duplicate`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Duplicate a dashboard installed plugin

### GET /plugin/chart/{pluginInstallId}/dashboard/{positionId}/query

- Method: `GET`
- Path: `/plugin/chart/{pluginInstallId}/dashboard/{positionId}/query`
- Parameters: `4`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a dashboard install plugin query by id
