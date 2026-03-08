# authentication Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `6`

## Operations

### GET /enterprise/{organizationId}/authentication

- Method: `GET`
- Path: `/enterprise/{organizationId}/authentication`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a authentication list

### POST /enterprise/{organizationId}/authentication

- Method: `POST`
- Path: `/enterprise/{organizationId}/authentication`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a authentication

### GET /enterprise/{organizationId}/authentication/providers

- Method: `GET`
- Path: `/enterprise/{organizationId}/authentication/providers`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get providers

### DELETE /enterprise/{organizationId}/authentication/{id}

- Method: `DELETE`
- Path: `/enterprise/{organizationId}/authentication/{id}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a authentication

### GET /enterprise/{organizationId}/authentication/{id}

- Method: `GET`
- Path: `/enterprise/{organizationId}/authentication/{id}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a authentication

### PUT /enterprise/{organizationId}/authentication/{id}

- Method: `PUT`
- Path: `/enterprise/{organizationId}/authentication/{id}`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update a authentication
