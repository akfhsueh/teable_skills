# waitlist Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `4`

## Operations

### POST /auth/invite-waitlist

- Method: `POST`
- Path: `/auth/invite-waitlist`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: Invite waitlist

### POST /auth/join-waitlist

- Method: `POST`
- Path: `/auth/join-waitlist`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Join waitlist

### GET /auth/waitlist

- Method: `GET`
- Path: `/auth/waitlist`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get waitlist

### POST /auth/waitlist-invite-code

- Method: `POST`
- Path: `/auth/waitlist-invite-code`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: Gen waitlist invite code
