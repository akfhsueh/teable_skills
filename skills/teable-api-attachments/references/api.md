# attachments Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `4`

## Operations

### POST /attachments/notify/{token}

- Method: `POST`
- Path: `/attachments/notify/{token}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `201`
- Description: Get Attachment information

### POST /attachments/signature

- Method: `POST`
- Path: `/attachments/signature`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: Retrieve upload signature.

### POST /attachments/upload/{token}

- Method: `POST`
- Path: `/attachments/upload/{token}`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Upload attachment

### GET /attachments/{token}

- Method: `GET`
- Path: `/attachments/{token}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Upload attachment
