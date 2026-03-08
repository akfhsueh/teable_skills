# trash Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `3`

## Operations

### GET /trash

- Method: `GET`
- Path: `/trash`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get trash list for spaces or bases

### GET /trash/items

- Method: `GET`
- Path: `/trash/items`
- Parameters: `4`
- Request Body: `no`
- Response Codes: `200`
- Description: Get trash items for base or table

### DELETE /trash/{trashId}

- Method: `DELETE`
- Path: `/trash/{trashId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Permanently delete a trash item by trashId
