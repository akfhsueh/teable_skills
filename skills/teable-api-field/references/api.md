# field Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `12`

## Operations

### Delete multiple fields

- Method: `DELETE`
- Path: `/table/{tableId}/field`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Permanently remove multiple fields from the specified table

### List fields

- Method: `GET`
- Path: `/table/{tableId}/field`
- Parameters: `4`
- Request Body: `no`
- Response Codes: `200`
- Description: Retrieve a list of fields in a table with optional filtering

### Create field

- Method: `POST`
- Path: `/table/{tableId}/field`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a new field in the specified table with the given configuration

### GET /table/{tableId}/field/delete-references

- Method: `GET`
- Path: `/table/{tableId}/field/delete-references`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get resources that reference the given fields (for delete impact analysis)

### Delete field

- Method: `DELETE`
- Path: `/table/{tableId}/field/{fieldId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Permanently remove a field from the specified table

### Get a field

- Method: `GET`
- Path: `/table/{tableId}/field/{fieldId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Retrieve detailed information about a specific field by its ID

### Update field

- Method: `PATCH`
- Path: `/table/{tableId}/field/{fieldId}`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update common properties of a field (name, description, dbFieldName). For other property changes, use the convert field API

### Auto-fill a field by AI

- Method: `POST`
- Path: `/table/{tableId}/field/{fieldId}/auto-fill`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Automatically generate suggestions for filling a specific field

### Convert field type

- Method: `PUT`
- Path: `/table/{tableId}/field/{fieldId}/convert`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Convert field to a different type with automatic type casting and symmetric field handling

### Duplicate field

- Method: `POST`
- Path: `/table/{tableId}/field/{fieldId}/duplicate`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `201`
- Description: Duplicate field

### Get linked records for filter

- Method: `GET`
- Path: `/table/{tableId}/field/{fieldId}/filter-link-records`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Retrieve associated records that match the view filter configuration for a linked field

### Stop auto-fill a field by AI

- Method: `POST`
- Path: `/table/{tableId}/field/{fieldId}/stop-fill`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Stop auto-fill a field by AI
