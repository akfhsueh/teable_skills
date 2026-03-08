# reward Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `8`

## Operations

### Export admin reward list as CSV

- Method: `GET`
- Path: `/admin/reward/export/{spaceId}`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: Export all reward records for a specific space as CSV file. Supports filtering by date range.

### Get admin reward list

- Method: `GET`
- Path: `/admin/reward/list`
- Parameters: `10`
- Request Body: `no`
- Response Codes: `200`
- Description: Get paginated and filtered list of reward for admin management. Supports filtering by space, status, platform, verification result, and search.

### Get admin reward overview by spaces

- Method: `GET`
- Path: `/admin/reward/overview`
- Parameters: `5`
- Request Body: `no`
- Response Codes: `200`
- Description: Get aggregated reward statistics grouped by space for admin management. Returns pending, approved, consumed, available and expiring amounts per space.

### Get all spaces with reward records

- Method: `GET`
- Path: `/admin/reward/spaces`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a list of all spaces that have reward records for admin filtering

### Get admin reward detail

- Method: `GET`
- Path: `/admin/reward/{rewardId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get detailed information of a specific reward including full metadata

### Claim a reward

- Method: `POST`
- Path: `/space/{spaceId}/reward/claim`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Submit a reward claim (e.g., social share)

### Get reward credit list

- Method: `GET`
- Path: `/space/{spaceId}/reward/credit-list`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get reward credit list for a space

### Get reward details

- Method: `GET`
- Path: `/space/{spaceId}/reward/{rewardId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get details of a specific reward including its verification status
