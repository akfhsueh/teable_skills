# template Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `18`

## Operations

### GET /template

- Method: `GET`
- Path: `/template`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `201`
- Description: get template list

### get template by baseId

- Method: `GET`
- Path: `/template/by-base/{baseId}`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: get template by baseId

### POST /template/category/create

- Method: `POST`
- Path: `/template/category/create`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: create a template category

### GET /template/category/list

- Method: `GET`
- Path: `/template/category/list`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: get template category list

### DELETE /template/category/{templateCategoryId}

- Method: `DELETE`
- Path: `/template/category/{templateCategoryId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `201`
- Description: delete a template category

### PATCH /template/category/{templateCategoryId}

- Method: `PATCH`
- Path: `/template/category/{templateCategoryId}`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: update a template category name

### PUT /template/category/{templateCategoryId}/order

- Method: `PUT`
- Path: `/template/category/{templateCategoryId}/order`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update template category order

### POST /template/create

- Method: `POST`
- Path: `/template/create`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: create a template

### Get template permalink redirect URL

- Method: `GET`
- Path: `/template/permalink/{identifier}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get template redirect URL for permalink

### GET /template/published

- Method: `GET`
- Path: `/template/published`
- Parameters: `5`
- Request Body: `no`
- Response Codes: `201`
- Description: get published template list

### DELETE /template/unpublish/{templateId}

- Method: `DELETE`
- Path: `/template/unpublish/{templateId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `201`
- Description: unpublish a template

### DELETE /template/{templateId}

- Method: `DELETE`
- Path: `/template/{templateId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `201`
- Description: delete a template

### get template detail by templateId

- Method: `GET`
- Path: `/template/{templateId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `201`
- Description: get template detail by templateId

### PATCH /template/{templateId}

- Method: `PATCH`
- Path: `/template/{templateId}`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: update a template

### PUT /template/{templateId}/order

- Method: `PUT`
- Path: `/template/{templateId}/order`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update template order

### PATCH /template/{templateId}/pin-top

- Method: `PATCH`
- Path: `/template/{templateId}/pin-top`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `201`
- Description: pin top a template

### POST /template/{templateId}/snapshot

- Method: `POST`
- Path: `/template/{templateId}/snapshot`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `201`
- Description: create a template snapshot

### Increment template visit count

- Method: `PATCH`
- Path: `/template/{templateId}/visit`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Increment template visit count
