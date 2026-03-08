# chat Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `13`

## Operations

### POST /base/{baseId}/chat/create

- Method: `POST`
- Path: `/base/{baseId}/chat/create`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create chat

### POST /base/{baseId}/chat/execute-script

- Method: `POST`
- Path: `/base/{baseId}/chat/execute-script`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Execute TypeScript code in sandbox for chat tools

### GET /base/{baseId}/chat/history

- Method: `GET`
- Path: `/base/{baseId}/chat/history`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get chat history

### POST /base/{baseId}/chat/resolve-attachments

- Method: `POST`
- Path: `/base/{baseId}/chat/resolve-attachments`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Resolve attachment tokens to presigned URLs

### POST /base/{baseId}/chat/suggestions

- Method: `POST`
- Path: `/base/{baseId}/chat/suggestions`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`

### POST /base/{baseId}/chat/text-extract

- Method: `POST`
- Path: `/base/{baseId}/chat/text-extract`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Extract text content from attachments

### DELETE /base/{baseId}/chat/{chatId}/delete

- Method: `DELETE`
- Path: `/base/{baseId}/chat/{chatId}/delete`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`

### DELETE /base/{baseId}/chat/{chatId}/messages

- Method: `DELETE`
- Path: `/base/{baseId}/chat/{chatId}/messages`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Clear all messages in a chat

### GET /base/{baseId}/chat/{chatId}/messages

- Method: `GET`
- Path: `/base/{baseId}/chat/{chatId}/messages`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get chat messages

### PATCH /base/{baseId}/chat/{chatId}/rename

- Method: `PATCH`
- Path: `/base/{baseId}/chat/{chatId}/rename`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`

### POST /base/{baseId}/chat/{chatId}/stop

- Method: `POST`
- Path: `/base/{baseId}/chat/{chatId}/stop`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Stop an active chat stream and prevent resume

### POST /chat/onboarding/attachments

- Method: `POST`
- Path: `/chat/onboarding/attachments`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Get attachment info by tokens. Used for landing page onboarding flow.

### GET /chat/onboarding/scenarios

- Method: `GET`
- Path: `/chat/onboarding/scenarios`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get onboarding scenarios with presigned URLs for attachments
