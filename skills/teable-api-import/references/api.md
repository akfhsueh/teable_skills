# import Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `3`

## Operations

### GET /import/analyze

- Method: `GET`
- Path: `/import/analyze`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a column info from analyze sheet

### POST /import/{baseId}

- Method: `POST`
- Path: `/import/{baseId}`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: create table from file

### PATCH /import/{baseId}/{tableId}

- Method: `PATCH`
- Path: `/import/{baseId}/{tableId}`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: import table inplace
