# table Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `17`

## Operations

### List tables

- Method: `GET`
- Path: `/base/{baseId}/table`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Retrieve a list of all tables in the specified base, including their basic information and configurations.

### Create table

- Method: `POST`
- Path: `/base/{baseId}/table/`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a new table in the specified base with customizable fields, views, and initial records. Default configurations will be applied if not specified.

### Delete table

- Method: `DELETE`
- Path: `/base/{baseId}/table/{tableId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Move a table to trash. The table can be restored within the retention period.

### Get table details

- Method: `GET`
- Path: `/base/{baseId}/table/{tableId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Retrieve detailed information about a specific table, including its schema, name, and configuration.

### Get abnormal indexes

- Method: `GET`
- Path: `/base/{baseId}/table/{tableId}/abnormal-index`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `201`
- Description: Retrieve a list of abnormal database indexes for a specific table by index type. This helps identify potential performance or maintenance issues.

### Get activated index

- Method: `POST`
- Path: `/base/{baseId}/table/{tableId}/activated-index`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `201`
- Description: Get the activated index of a table

### Update db table name

- Method: `PUT`
- Path: `/base/{baseId}/table/{tableId}/db-table-name`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update the physical database table name. Must be 1-63 characters, start with letter or underscore, contain only letters, numbers and underscore, and be unique within the base.

### Get default view id

- Method: `GET`
- Path: `/base/{baseId}/table/{tableId}/default-view-id`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get default view id

### Update table description

- Method: `PUT`
- Path: `/base/{baseId}/table/{tableId}/description`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update or remove the description of a table. Set to null to remove the description.

### Duplicate a table

- Method: `POST`
- Path: `/base/{baseId}/table/{tableId}/duplicate`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Duplicate a table

### Update table tcon

- Method: `PUT`
- Path: `/base/{baseId}/table/{tableId}/icon`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update the emoji icon of a table. The icon must be a valid emoji character.

### Toggle table index

- Method: `POST`
- Path: `/base/{baseId}/table/{tableId}/index`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `201`
- Description: Toggle table index

### Repair table index

- Method: `PATCH`
- Path: `/base/{baseId}/table/{tableId}/index/repair`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `201`
- Description: Repair table index

### Update table name

- Method: `PUT`
- Path: `/base/{baseId}/table/{tableId}/name`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update the display name of a table. This will not affect the underlying database table name.

### Update table order

- Method: `PUT`
- Path: `/base/{baseId}/table/{tableId}/order`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update the display order of a table in the base. This affects the order in which tables are shown in the UI.

### Permanently delete table

- Method: `DELETE`
- Path: `/base/{baseId}/table/{tableId}/permanent`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Permanently delete a table and all its data. This action cannot be undone.

### Get table permissions

- Method: `GET`
- Path: `/base/{baseId}/table/{tableId}/permission`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Retrieve the current user's permissions for a table, including access rights for table operations, views, records, and fields.
