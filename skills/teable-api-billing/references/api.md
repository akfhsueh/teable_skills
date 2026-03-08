# billing Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `19`

## Operations

### GET /billing/add-on-products

- Method: `GET`
- Path: `/billing/add-on-products`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get add-on products list

### GET /billing/all-products

- Method: `GET`
- Path: `/billing/all-products`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get all products collection

### GET /billing/base-products

- Method: `GET`
- Path: `/billing/base-products`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get base products list

### GET /billing/subscription/license

- Method: `GET`
- Path: `/billing/subscription/license`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get license list

### POST /billing/subscription/license/checkout

- Method: `POST`
- Path: `/billing/subscription/license/checkout`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Get checkout session url for a self-hosted license

### POST /billing/subscription/license/manage-billing

- Method: `POST`
- Path: `/billing/subscription/license/manage-billing`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Manage billing

### GET /billing/subscription/license/manage-billing/availability

- Method: `GET`
- Path: `/billing/subscription/license/manage-billing/availability`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get manage billing portal availability

### GET /billing/subscription/license/{licenseId}

- Method: `GET`
- Path: `/billing/subscription/license/{licenseId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get license details for the self-hosted related subscription

### GET /billing/subscription/summary

- Method: `GET`
- Path: `/billing/subscription/summary`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Retrieves a summary of subscription information across all spaces

### GET /space/{spaceId}/billing

- Method: `GET`
- Path: `/space/{spaceId}/billing`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get space billing details

### GET /space/{spaceId}/billing/credit-detail

- Method: `GET`
- Path: `/space/{spaceId}/billing/credit-detail`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get space credit usage detail by month

### GET /space/{spaceId}/billing/credit-summary

- Method: `GET`
- Path: `/space/{spaceId}/billing/credit-summary`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get space credit summary

### GET /space/{spaceId}/billing/invoice/base-list

- Method: `GET`
- Path: `/space/{spaceId}/billing/invoice/base-list`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get paginated invoice list by spaceId

### GET /space/{spaceId}/billing/manage-portal

- Method: `GET`
- Path: `/space/{spaceId}/billing/manage-portal`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get Stripe customer portal URL for managing billing details

### DELETE /space/{spaceId}/billing/subscription

- Method: `DELETE`
- Path: `/space/{spaceId}/billing/subscription`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: Cancel subscription for a space

### GET /space/{spaceId}/billing/subscription

- Method: `GET`
- Path: `/space/{spaceId}/billing/subscription`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get subscription detail by spaceId

### POST /space/{spaceId}/billing/subscription/checkout

- Method: `POST`
- Path: `/space/{spaceId}/billing/subscription/checkout`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Get checkout session url for a space

### GET /space/{spaceId}/billing/subscription/plan

- Method: `GET`
- Path: `/space/{spaceId}/billing/subscription/plan`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Retrieves the plan subscription

### GET /space/{spaceId}/billing/subscription/summary

- Method: `GET`
- Path: `/space/{spaceId}/billing/subscription/summary`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Retrieves a summary of subscription information for a space
