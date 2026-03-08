# base-share Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `9`

## Operations

### GET /base/{baseId}/share

- Method: `GET`
- Path: `/base/{baseId}/share`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get all shared node IDs for a base

### POST /base/{baseId}/share

- Method: `POST`
- Path: `/base/{baseId}/share`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a base share link

### GET /base/{baseId}/share/node/{nodeId}

- Method: `GET`
- Path: `/base/{baseId}/share/node/{nodeId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a base share by node ID

### DELETE /base/{baseId}/share/{shareId}

- Method: `DELETE`
- Path: `/base/{baseId}/share/{shareId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a base share link

### PATCH /base/{baseId}/share/{shareId}

- Method: `PATCH`
- Path: `/base/{baseId}/share/{shareId}`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update a base share link

### POST /base/{baseId}/share/{shareId}/refresh

- Method: `POST`
- Path: `/base/{baseId}/share/{shareId}/refresh`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Refresh/regenerate a base share link ID

### GET /share/{shareId}/base

- Method: `GET`
- Path: `/share/{shareId}/base`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get shared base information

### POST /share/{shareId}/base/auth

- Method: `POST`
- Path: `/share/{shareId}/base/auth`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Authenticate with password to access shared base

### POST /share/{shareId}/base/copy

- Method: `POST`
- Path: `/share/{shareId}/base/copy`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Copy a shared base to a target space
