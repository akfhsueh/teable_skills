# user Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `10`

## Operations

### POST /organization/{organizationId}/users

- Method: `POST`
- Path: `/organization/{organizationId}/users`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`

### PATCH /user/avatar

- Method: `PATCH`
- Path: `/user/avatar`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update user avatar

### PATCH /user/lang

- Method: `PATCH`
- Path: `/user/lang`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update user language

### GET /user/last-visit

- Method: `GET`
- Path: `/user/last-visit`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get user last visited resource

### POST /user/last-visit

- Method: `POST`
- Path: `/user/last-visit`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: Update or create user last visit record

### GET /user/last-visit/base-node

- Method: `GET`
- Path: `/user/last-visit/base-node`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get user last visited base node

### GET /user/last-visit/list-base

- Method: `GET`
- Path: `/user/last-visit/list-base`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`

### GET /user/last-visit/map

- Method: `GET`
- Path: `/user/last-visit/map`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get user last visited resource map

### PATCH /user/name

- Method: `PATCH`
- Path: `/user/name`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update user name

### PATCH /user/notify-meta

- Method: `PATCH`
- Path: `/user/notify-meta`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update user notification meta
