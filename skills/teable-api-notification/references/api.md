# notification Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `4`

## Operations

### GET /notifications

- Method: `GET`
- Path: `/notifications`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: List a user notification

### PATCH /notifications/read-all

- Method: `PATCH`
- Path: `/notifications/read-all`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: mark all notifications as read

### GET /notifications/unread-count

- Method: `GET`
- Path: `/notifications/unread-count`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: User notification unread count

### PATCH /notifications/{notificationId}/status

- Method: `PATCH`
- Path: `/notifications/{notificationId}/status`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Patch notification status
