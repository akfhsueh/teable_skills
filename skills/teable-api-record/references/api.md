# record Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `20`

## Operations

### Delete records

- Method: `DELETE`
- Path: `/table/{tableId}/record`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Permanently delete multiple records by their IDs in a single request.

### List records

- Method: `GET`
- Path: `/table/{tableId}/record`
- Parameters: `18`
- Request Body: `no`
- Response Codes: `200`
- Description: Retrieve a list of records with support for filtering, sorting, grouping, and pagination. The response includes record data and optional group information.

### Update multiple records

- Method: `PATCH`
- Path: `/table/{tableId}/record`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update multiple records in a single request with support for field value typecast and record reordering.

### Create records

- Method: `POST`
- Path: `/table/{tableId}/record`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create one or multiple records with support for field value typecast and custom record ordering.

### GET /table/{tableId}/record/collaborators

- Method: `GET`
- Path: `/table/{tableId}/record/collaborators`
- Parameters: `6`
- Request Body: `no`
- Response Codes: `200`
- Description: Get collaborators of a record.

### Submit form

- Method: `POST`
- Path: `/table/{tableId}/record/form-submit`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Submit a record through a form view. This will trigger "When form submitted" automations.

### Get table records history

- Method: `GET`
- Path: `/table/{tableId}/record/history`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Retrieve the change history of all records in a table, including field modifications and user information.

### Delete record

- Method: `DELETE`
- Path: `/table/{tableId}/record/{recordId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Permanently delete a single record by its ID.

### Get record

- Method: `GET`
- Path: `/table/{tableId}/record/{recordId}`
- Parameters: `5`
- Request Body: `no`
- Response Codes: `200`
- Description: Retrieve a single record by its ID with options to specify field projections and output format.

### Update record

- Method: `PATCH`
- Path: `/table/{tableId}/record/{recordId}`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update a single record by its ID with support for field value typecast and record reordering.

### Duplicate record

- Method: `POST`
- Path: `/table/{tableId}/record/{recordId}/duplicate`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a copy of an existing record with optional custom positioning in the view.

### Get record history

- Method: `GET`
- Path: `/table/{tableId}/record/{recordId}/history`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Retrieve the change history of a specific record, including field modifications and user information.

### Get record status

- Method: `GET`
- Path: `/table/{tableId}/record/{recordId}/status`
- Parameters: `19`
- Request Body: `no`
- Response Codes: `200`
- Description: Retrieve the visibility and deletion status of a specific record.

### Auto-fill a cell by AI

- Method: `POST`
- Path: `/table/{tableId}/record/{recordId}/{fieldId}/auto-fill`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: Automatically fill a cell in a specific record and field

### Button click

- Method: `POST`
- Path: `/table/{tableId}/record/{recordId}/{fieldId}/button-click`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: Button click

### Button reset

- Method: `POST`
- Path: `/table/{tableId}/record/{recordId}/{fieldId}/button-reset`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: Button reset

### Insert attachments at anchor

- Method: `POST`
- Path: `/table/{tableId}/record/{recordId}/{fieldId}/insertAttachment`
- Parameters: `3`
- Request Body: `yes`
- Response Codes: `201`
- Description: Insert attachments after the anchor in the cell (append to end if anchor not found or not provided)

### Upload attachment

- Method: `POST`
- Path: `/table/{tableId}/record/{recordId}/{fieldId}/uploadAttachment`
- Parameters: `3`
- Request Body: `yes`
- Response Codes: `201`
- Description: Upload an attachment from a file or URL and append it to the cell

### POST /table/{tableId}/undo-redo/redo

- Method: `POST`
- Path: `/table/{tableId}/undo-redo/redo`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `201`
- Description: Redo the last operation

### POST /table/{tableId}/undo-redo/undo

- Method: `POST`
- Path: `/table/{tableId}/undo-redo/undo`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `201`
- Description: Undo the last operation
