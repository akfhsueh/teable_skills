# view Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `24`

## Operations

### Get view list

- Method: `GET`
- Path: `/table/{tableId}/view`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get view list

### POST /table/{tableId}/view

- Method: `POST`
- Path: `/table/{tableId}/view`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a view

### POST /table/{tableId}/view/plugin

- Method: `POST`
- Path: `/table/{tableId}/view/plugin`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Install a plugin to a view

### DELETE /table/{tableId}/view/{viewId}

- Method: `DELETE`
- Path: `/table/{tableId}/view/{viewId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a view

### GET /table/{tableId}/view/{viewId}

- Method: `GET`
- Path: `/table/{tableId}/view/{viewId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a view

### PUT /table/{tableId}/view/{viewId}/column-meta

- Method: `PUT`
- Path: `/table/{tableId}/view/{viewId}/column-meta`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update view column meta

### PUT /table/{tableId}/view/{viewId}/description

- Method: `PUT`
- Path: `/table/{tableId}/view/{viewId}/description`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update view description

### POST /table/{tableId}/view/{viewId}/disable-share

- Method: `POST`
- Path: `/table/{tableId}/view/{viewId}/disable-share`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `201`
- Description: Disable view share

### POST /table/{tableId}/view/{viewId}/duplicate

- Method: `POST`
- Path: `/table/{tableId}/view/{viewId}/duplicate`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `201`
- Description: Duplicate a view

### POST /table/{tableId}/view/{viewId}/enable-share

- Method: `POST`
- Path: `/table/{tableId}/view/{viewId}/enable-share`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `201`
- Description: Enable view share

### PUT /table/{tableId}/view/{viewId}/filter

- Method: `PUT`
- Path: `/table/{tableId}/view/{viewId}/filter`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update view filter

### GET /table/{tableId}/view/{viewId}/filter-link-records

- Method: `GET`
- Path: `/table/{tableId}/view/{viewId}/filter-link-records`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Getting associated records for a view filter configuration.

### PUT /table/{tableId}/view/{viewId}/group

- Method: `PUT`
- Path: `/table/{tableId}/view/{viewId}/group`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update view group condition

### PUT /table/{tableId}/view/{viewId}/locked

- Method: `PUT`
- Path: `/table/{tableId}/view/{viewId}/locked`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update the locked status of the view

### PUT /table/{tableId}/view/{viewId}/manual-sort

- Method: `PUT`
- Path: `/table/{tableId}/view/{viewId}/manual-sort`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update view raw order

### PUT /table/{tableId}/view/{viewId}/name

- Method: `PUT`
- Path: `/table/{tableId}/view/{viewId}/name`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update view name

### PATCH /table/{tableId}/view/{viewId}/options

- Method: `PATCH`
- Path: `/table/{tableId}/view/{viewId}/options`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update view option

### PUT /table/{tableId}/view/{viewId}/order

- Method: `PUT`
- Path: `/table/{tableId}/view/{viewId}/order`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update view order

### GET /table/{tableId}/view/{viewId}/plugin

- Method: `GET`
- Path: `/table/{tableId}/view/{viewId}/plugin`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a view install plugin by id

### PATCH /table/{tableId}/view/{viewId}/plugin/{pluginInstallId}

- Method: `PATCH`
- Path: `/table/{tableId}/view/{viewId}/plugin/{pluginInstallId}`
- Parameters: `3`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update storage of a plugin in a view

### PUT /table/{tableId}/view/{viewId}/record-order

- Method: `PUT`
- Path: `/table/{tableId}/view/{viewId}/record-order`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update record order in view

### POST /table/{tableId}/view/{viewId}/refresh-share-id

- Method: `POST`
- Path: `/table/{tableId}/view/{viewId}/refresh-share-id`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `201`
- Description: Refresh view share id

### PUT /table/{tableId}/view/{viewId}/share-meta

- Method: `PUT`
- Path: `/table/{tableId}/view/{viewId}/share-meta`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update view share meta

### PUT /table/{tableId}/view/{viewId}/sort

- Method: `PUT`
- Path: `/table/{tableId}/view/{viewId}/sort`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update view sort condition
