# selection Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `6`

## Operations

### Clear selected range content

- Method: `PATCH`
- Path: `/table/{tableId}/selection/clear`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Remove all content from the selected table range

### Copy selected table content

- Method: `GET`
- Path: `/table/{tableId}/selection/copy`
- Parameters: `16`
- Request Body: `no`
- Response Codes: `200`
- Description: Copy content from selected table ranges including headers if specified

### Delete selected range data

- Method: `DELETE`
- Path: `/table/{tableId}/selection/delete`
- Parameters: `16`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete records or fields within the selected table range

### Paste content into selected range

- Method: `PATCH`
- Path: `/table/{tableId}/selection/paste`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Apply paste operation to insert content into the selected table range

### Get ids from range

- Method: `GET`
- Path: `/table/{tableId}/selection/range-to-id`
- Parameters: `17`
- Request Body: `no`
- Response Codes: `200`
- Description: Retrieve record and field identifiers based on the selected range coordinates in a table

### Preview paste operation results

- Method: `PATCH`
- Path: `/table/{tableId}/selection/temporaryPaste`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Preview the results of a paste operation without applying changes to the table
