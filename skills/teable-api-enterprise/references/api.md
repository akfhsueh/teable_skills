# enterprise Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `28`

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

### GET /organization/{organizationId}

- Method: `GET`
- Path: `/organization/{organizationId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get organization

### PUT /organization/{organizationId}/rename

- Method: `PUT`
- Path: `/organization/{organizationId}/rename`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Rename organization

### GET /organization/{organizationId}/setting

- Method: `GET`
- Path: `/organization/{organizationId}/setting`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get organization setting

### GET /organization/{organizationId}/space

- Method: `GET`
- Path: `/organization/{organizationId}/space`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get organization space

### PUT /organization/{organizationId}/update-auto-space

- Method: `PUT`
- Path: `/organization/{organizationId}/update-auto-space`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update auto space

### DELETE /organization/{organizationId}/user

- Method: `DELETE`
- Path: `/organization/{organizationId}/user`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Delete organization user

### POST /organization/{organizationId}/user

- Method: `POST`
- Path: `/organization/{organizationId}/user`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Add organization user

### GET /organization/{organizationId}/user-exists

- Method: `GET`
- Path: `/organization/{organizationId}/user-exists`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`

### GET /organization/{organizationId}/user/{userId}

- Method: `GET`
- Path: `/organization/{organizationId}/user/{userId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`

### PATCH /organization/{organizationId}/user/{userId}

- Method: `PATCH`
- Path: `/organization/{organizationId}/user/{userId}`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update organization user

### POST /organization/{organizationId}/user/{userId}/activate

- Method: `POST`
- Path: `/organization/{organizationId}/user/{userId}/activate`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Activate organization user

### POST /organization/{organizationId}/user/{userId}/deactivate

- Method: `POST`
- Path: `/organization/{organizationId}/user/{userId}/deactivate`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Deactivate organization user

### GET /organization/{organizationId}/users

- Method: `GET`
- Path: `/organization/{organizationId}/users`
- Parameters: `4`
- Request Body: `no`
- Response Codes: `200`
- Description: Get organization users
