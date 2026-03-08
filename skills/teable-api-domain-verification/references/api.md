# domain-verification Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `4`

## Operations

### DELETE /enterprise/{organizationId}/domain-verification

- Method: `DELETE`
- Path: `/enterprise/{organizationId}/domain-verification`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a domain verification

### GET /enterprise/{organizationId}/domain-verification

- Method: `GET`
- Path: `/enterprise/{organizationId}/domain-verification`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a domain verification

### POST /enterprise/{organizationId}/domain-verification

- Method: `POST`
- Path: `/enterprise/{organizationId}/domain-verification`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Create a domain verification

### POST /enterprise/{organizationId}/domain-verification/send-verification-email

- Method: `POST`
- Path: `/enterprise/{organizationId}/domain-verification/send-verification-email`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Send email verification
