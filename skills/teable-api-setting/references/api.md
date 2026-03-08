# setting Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `6`

## Operations

### GET /admin/setting/ai-key-stats

- Method: `GET`
- Path: `/admin/setting/ai-key-stats`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get per-key usage statistics for AI Gateway API keys

### POST /admin/setting/batch-test-llm

- Method: `POST`
- Path: `/admin/setting/batch-test-llm`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Batch test all configured LLM models to verify compatibility with AI field features

### PUT /admin/setting/set-mail-transport-config

- Method: `PUT`
- Path: `/admin/setting/set-mail-transport-config`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Set mail transporter

### POST /admin/setting/test-api-key

- Method: `POST`
- Path: `/admin/setting/test-api-key`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Test API key validity for AI Gateway or v0, optionally test attachment transfer modes

### POST /admin/setting/test-llm

- Method: `POST`
- Path: `/admin/setting/test-llm`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Test LLM provider configuration

### GET /admin/setting/test-public-access

- Method: `GET`
- Path: `/admin/setting/test-public-access`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Test if this Teable instance is publicly accessible from the internet
