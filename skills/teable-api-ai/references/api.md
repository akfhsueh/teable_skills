# ai Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `4`

## Operations

### POST /api/{baseId}/ai/generate

- Method: `POST`
- Path: `/api/{baseId}/ai/generate`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Generate AI text (non-streaming)

### POST /api/{baseId}/ai/generate-stream

- Method: `POST`
- Path: `/api/{baseId}/ai/generate-stream`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Generate ai stream

### GET /{baseId}/ai/config

- Method: `GET`
- Path: `/{baseId}/ai/config`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get the configuration of ai, including instance and space configuration

### GET /{baseId}/ai/disable-ai-actions

- Method: `GET`
- Path: `/{baseId}/ai/disable-ai-actions`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get the disable ai actions
