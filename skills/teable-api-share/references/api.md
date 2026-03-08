# share Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `14`

## Operations

### GET /share/{shareId}/view

- Method: `GET`
- Path: `/share/{shareId}/view`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: get share view info

### GET /share/{shareId}/view/aggregations

- Method: `GET`
- Path: `/share/{shareId}/view/aggregations`
- Parameters: `10`
- Request Body: `no`
- Response Codes: `200`
- Description: Get share view aggregations

### POST /share/{shareId}/view/auth

- Method: `POST`
- Path: `/share/{shareId}/view/auth`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: share view auth password

### GET /share/{shareId}/view/calendar-daily-collection

- Method: `GET`
- Path: `/share/{shareId}/view/calendar-daily-collection`
- Parameters: `8`
- Request Body: `no`
- Response Codes: `200`
- Description: Get calendar daily collection for the share view

### GET /share/{shareId}/view/collaborators

- Method: `GET`
- Path: `/share/{shareId}/view/collaborators`
- Parameters: `6`
- Request Body: `no`
- Response Codes: `200`
- Description: View collaborators in a view with a user field selector.

### GET /share/{shareId}/view/copy

- Method: `GET`
- Path: `/share/{shareId}/view/copy`
- Parameters: `16`
- Request Body: `no`
- Response Codes: `200`
- Description: Copy operations in Share view

### POST /share/{shareId}/view/form-submit

- Method: `POST`
- Path: `/share/{shareId}/view/form-submit`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: share form view submit new record

### GET /share/{shareId}/view/group-points

- Method: `GET`
- Path: `/share/{shareId}/view/group-points`
- Parameters: `6`
- Request Body: `no`
- Response Codes: `200`
- Description: Get group points for the share view

### GET /share/{shareId}/view/link-records

- Method: `GET`
- Path: `/share/{shareId}/view/link-records`
- Parameters: `6`
- Request Body: `no`
- Response Codes: `200`
- Description: In a view with a field selector, link the records list of the associated field selector to get the. Linking the desired ones inside the share view should fetch the ones that have already been selected.

### Button click

- Method: `POST`
- Path: `/share/{shareId}/view/record/{recordId}/{fieldId}/button-click`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: Button click

### GET /share/{shareId}/view/records

- Method: `GET`
- Path: `/share/{shareId}/view/records`
- Parameters: `17`
- Request Body: `no`
- Response Codes: `200`
- Description: Get records for the share view

### GET /share/{shareId}/view/row-count

- Method: `GET`
- Path: `/share/{shareId}/view/row-count`
- Parameters: `8`
- Request Body: `no`
- Response Codes: `200`
- Description: Get row count for the share view

### GET /share/{shareId}/view/search-count

- Method: `GET`
- Path: `/share/{shareId}/view/search-count`
- Parameters: `5`
- Request Body: `no`
- Response Codes: `200`
- Description: Get share view search result count with query

### GET /share/{shareId}/view/search-index

- Method: `GET`
- Path: `/share/{shareId}/view/search-index`
- Parameters: `9`
- Request Body: `no`
- Response Codes: `200`
- Description: Get share view record index with search query
