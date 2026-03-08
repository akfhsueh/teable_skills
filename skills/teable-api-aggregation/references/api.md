# aggregation Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `8`

## Operations

### Get aggregated statistics

- Method: `GET`
- Path: `/table/{tableId}/aggregation`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Returns statistical aggregations of table data based on specified functions and grouping criteria

### Get daily calendar data

- Method: `GET`
- Path: `/table/{tableId}/aggregation/calendar-daily-collection`
- Parameters: `9`
- Request Body: `no`
- Response Codes: `200`
- Description: Returns records and count distribution across dates based on specified date range and fields

### Get group points

- Method: `GET`
- Path: `/table/{tableId}/aggregation/group-points`
- Parameters: `7`
- Request Body: `no`
- Response Codes: `200`
- Description: Returns the distribution and count of records across different group points in the view

### Get record index

- Method: `GET`
- Path: `/table/{tableId}/aggregation/record-index`
- Parameters: `14`
- Request Body: `no`
- Response Codes: `200`
- Description: Returns the 0-based row index of a specific record in the current query context (respecting view filters, sort order, link filters)

### Get total row count

- Method: `GET`
- Path: `/table/{tableId}/aggregation/row-count`
- Parameters: `9`
- Request Body: `no`
- Response Codes: `200`
- Description: Returns the total number of rows in a view based on applied filters and criteria

### Get total count of search

- Method: `GET`
- Path: `/table/{tableId}/aggregation/search-count`
- Parameters: `5`
- Request Body: `no`
- Response Codes: `200`
- Description: Returns the total count of records matching the specified search criteria and filters

### Get record indices for search

- Method: `GET`
- Path: `/table/{tableId}/aggregation/search-index`
- Parameters: `9`
- Request Body: `no`
- Response Codes: `200`
- Description: Returns the indices and record IDs of records matching the search criteria

### Get task status collection

- Method: `GET`
- Path: `/table/{tableId}/aggregation/task-status-collection`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Returns records and count distribution across task status based on specified date range and fields
