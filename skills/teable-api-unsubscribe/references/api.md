# unsubscribe Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `5`

## Operations

### GET /unsubscribe/export-list/{baseId}

- Method: `GET`
- Path: `/unsubscribe/export-list/{baseId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Export unsubscribe list

### POST /unsubscribe/import-list/{baseId}

- Method: `POST`
- Path: `/unsubscribe/import-list/{baseId}`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Import unsubscribe list

### GET /unsubscribe/list/{baseId}

- Method: `GET`
- Path: `/unsubscribe/list/{baseId}`
- Parameters: `4`
- Request Body: `no`
- Response Codes: `200`
- Description: Get paginated unsubscribe list by baseId

### GET /unsubscribe/{token}

- Method: `GET`
- Path: `/unsubscribe/{token}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get unsubscribe information

### POST /unsubscribe/{token}

- Method: `POST`
- Path: `/unsubscribe/{token}`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update subscription status
