# integrity Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `2`

## Operations

### GET /integrity/base/{baseId}/link-check

- Method: `GET`
- Path: `/integrity/base/{baseId}/link-check`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Check integrity of link fields in a base

### POST /integrity/base/{baseId}/link-fix?tableId={tableId}

- Method: `POST`
- Path: `/integrity/base/{baseId}/link-fix?tableId={tableId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `201`
- Description: Fix integrity of link fields in a base
