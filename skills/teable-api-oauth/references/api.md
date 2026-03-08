# oauth Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `11`

## Operations

### GET /oauth/client

- Method: `GET`
- Path: `/oauth/client`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get the list of OAuth applications

### POST /oauth/client

- Method: `POST`
- Path: `/oauth/client`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a new OAuth application

### GET /oauth/client/authorized/list

- Method: `GET`
- Path: `/oauth/client/authorized/list`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get the list of authorized applications

### DELETE /oauth/client/{clientId}

- Method: `DELETE`
- Path: `/oauth/client/{clientId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete an OAuth application

### GET /oauth/client/{clientId}

- Method: `GET`
- Path: `/oauth/client/{clientId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get the OAuth application

### PUT /oauth/client/{clientId}

- Method: `PUT`
- Path: `/oauth/client/{clientId}`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update an OAuth application

### POST /oauth/client/{clientId}/revoke-access

- Method: `POST`
- Path: `/oauth/client/{clientId}/revoke-access`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `201`

### POST /oauth/client/{clientId}/revoke-token

- Method: `POST`
- Path: `/oauth/client/{clientId}/revoke-token`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`

### POST /oauth/client/{clientId}/secret

- Method: `POST`
- Path: `/oauth/client/{clientId}/secret`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `201`
- Description: Generate a new OAuth secret

### DELETE /oauth/client/{clientId}/secret/{secretId}

- Method: `DELETE`
- Path: `/oauth/client/{clientId}/secret/{secretId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete the OAuth secret

### GET /oauth/decision/{transactionId}

- Method: `GET`
- Path: `/oauth/decision/{transactionId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get the OAuth application
