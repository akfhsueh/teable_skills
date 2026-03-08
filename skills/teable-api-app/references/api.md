# app Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `9`

## Operations

### Delete app

- Method: `DELETE`
- Path: `/base/{baseId}/app/{appId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete app by its ID.

### POST /base/{baseId}/app/{appId}/deploy

- Method: `POST`
- Path: `/base/{baseId}/app/{appId}/deploy`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `201`
- Description: Deploy app to Vercel

### GET /base/{baseId}/app/{appId}/deploy/status

- Method: `GET`
- Path: `/base/{baseId}/app/{appId}/deploy/status`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get app deployment status

### GET /base/{baseId}/app/{appId}/export-code

- Method: `GET`
- Path: `/base/{baseId}/app/{appId}/export-code`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Export app source code as a ZIP file

### PATCH /base/{baseId}/app/{appId}/files

- Method: `PATCH`
- Path: `/base/{baseId}/app/{appId}/files`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Update app files

### POST /base/{baseId}/app/{appId}/import-code

- Method: `POST`
- Path: `/base/{baseId}/app/{appId}/import-code`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Import app source code from a ZIP file

### Permanently delete app

- Method: `DELETE`
- Path: `/base/{baseId}/app/{appId}/permanent`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Permanently delete an app and all its data. This action cannot be undone.

### PATCH /base/{baseId}/app/{appId}/props

- Method: `PATCH`
- Path: `/base/{baseId}/app/{appId}/props`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Update app props

### POST /base/{baseId}/app/{appId}/run

- Method: `POST`
- Path: `/base/{baseId}/app/{appId}/run`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `201`
- Description: Run the app code
