# space-manage Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `5`

## Operations

### GET /enterprise/{organizationId}/space-manage

- Method: `GET`
- Path: `/enterprise/{organizationId}/space-manage`
- Parameters: `4`
- Request Body: `no`
- Response Codes: `200`
- Description: Get space manage list

### GET /enterprise/{organizationId}/space-manage/count

- Method: `GET`
- Path: `/enterprise/{organizationId}/space-manage/count`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get space manage list total

### GET /enterprise/{organizationId}/space-manage/{spaceId}

- Method: `GET`
- Path: `/enterprise/{organizationId}/space-manage/{spaceId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get space manage detail

### POST /enterprise/{organizationId}/space-manage/{spaceId}/add-organization

- Method: `POST`
- Path: `/enterprise/{organizationId}/space-manage/{spaceId}/add-organization`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `201`
- Description: Add space to organization

### DELETE /enterprise/{organizationId}/space-manage/{spaceId}/remove-organization

- Method: `DELETE`
- Path: `/enterprise/{organizationId}/space-manage/{spaceId}/remove-organization`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Remove space from organization
