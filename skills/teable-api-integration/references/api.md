# integration Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `4`

## Operations

### GET /space/{spaceId}/integration

- Method: `GET`
- Path: `/space/{spaceId}/integration`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get integration list by query

### POST /space/{spaceId}/integration

- Method: `POST`
- Path: `/space/{spaceId}/integration`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Create a integration to a space

### DELETE /space/{spaceId}/integration/{integrationId}

- Method: `DELETE`
- Path: `/space/{spaceId}/integration/{integrationId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a integration by integrationId

### PATCH /space/{spaceId}/integration/{integrationId}

- Method: `PATCH`
- Path: `/space/{spaceId}/integration/{integrationId}`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update a integration to a space
