# plan Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `4`

## Operations

### POST /table/{tableId}/field/plan

- Method: `POST`
- Path: `/table/{tableId}/field/plan`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Generate calculation plan for creating the field

### DELETE /table/{tableId}/field/{fieldId}/plan

- Method: `DELETE`
- Path: `/table/{tableId}/field/{fieldId}/plan`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Generate calculation plan for deleting the field

### GET /table/{tableId}/field/{fieldId}/plan

- Method: `GET`
- Path: `/table/{tableId}/field/{fieldId}/plan`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Generate calculation plan for the field

### PUT /table/{tableId}/field/{fieldId}/plan

- Method: `PUT`
- Path: `/table/{tableId}/field/{fieldId}/plan`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `201`
- Description: Generate calculation plan for converting the field
