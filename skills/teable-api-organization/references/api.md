# organization Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `31`

## Operations

### GET /instance/organization

- Method: `GET`
- Path: `/instance/organization`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get instance organization, only for enterprise edition

### GET /organization/department

- Method: `GET`
- Path: `/organization/department`
- Parameters: `4`
- Request Body: `no`
- Response Codes: `200`

### GET /organization/department-user

- Method: `GET`
- Path: `/organization/department-user`
- Parameters: `6`
- Request Body: `no`
- Response Codes: `200`

### GET /organization/me

- Method: `GET`
- Path: `/organization/me`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get my organization

### GET /organization/{organizationId}

- Method: `GET`
- Path: `/organization/{organizationId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get organization

### GET /organization/{organizationId}/department

- Method: `GET`
- Path: `/organization/{organizationId}/department`
- Parameters: `4`
- Request Body: `no`
- Response Codes: `200`

### POST /organization/{organizationId}/department

- Method: `POST`
- Path: `/organization/{organizationId}/department`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`

### PUT /organization/{organizationId}/department-scope

- Method: `PUT`
- Path: `/organization/{organizationId}/department-scope`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update department scope

### DELETE /organization/{organizationId}/department-user

- Method: `DELETE`
- Path: `/organization/{organizationId}/department-user`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`

### GET /organization/{organizationId}/department-user

- Method: `GET`
- Path: `/organization/{organizationId}/department-user`
- Parameters: `6`
- Request Body: `no`
- Response Codes: `200`

### POST /organization/{organizationId}/department-user

- Method: `POST`
- Path: `/organization/{organizationId}/department-user`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`

### PATCH /organization/{organizationId}/department-user/department

- Method: `PATCH`
- Path: `/organization/{organizationId}/department-user/department`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`

### PATCH /organization/{organizationId}/department-user/move

- Method: `PATCH`
- Path: `/organization/{organizationId}/department-user/move`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`

### DELETE /organization/{organizationId}/department/{departmentId}

- Method: `DELETE`
- Path: `/organization/{organizationId}/department/{departmentId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`

### GET /organization/{organizationId}/department/{departmentId}

- Method: `GET`
- Path: `/organization/{organizationId}/department/{departmentId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`

### PATCH /organization/{organizationId}/department/{departmentId}/move

- Method: `PATCH`
- Path: `/organization/{organizationId}/department/{departmentId}/move`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`

### PATCH /organization/{organizationId}/department/{departmentId}/rename

- Method: `PATCH`
- Path: `/organization/{organizationId}/department/{departmentId}/rename`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`

### GET /organization/{organizationId}/me

- Method: `GET`
- Path: `/organization/{organizationId}/me`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get organization me

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

### POST /organization/{organizationId}/users

- Method: `POST`
- Path: `/organization/{organizationId}/users`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
