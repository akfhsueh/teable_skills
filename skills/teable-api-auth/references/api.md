# auth Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `18`

## Operations

### POST /auth/add-password

- Method: `POST`
- Path: `/auth/add-password`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: Add password

### PATCH /auth/change-email

- Method: `PATCH`
- Path: `/auth/change-email`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Change email

### PATCH /auth/change-password

- Method: `PATCH`
- Path: `/auth/change-password`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: Change password

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

### POST /auth/reset-password

- Method: `POST`
- Path: `/auth/reset-password`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: Reset password

### POST /auth/send-change-email-code

- Method: `POST`
- Path: `/auth/send-change-email-code`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Send change email code

### POST /auth/send-reset-password-email

- Method: `POST`
- Path: `/auth/send-reset-password-email`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: Send reset password email

### POST /auth/send-signup-verification-code

- Method: `POST`
- Path: `/auth/send-signup-verification-code`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: Send signup verification code

### POST /auth/signin

- Method: `POST`
- Path: `/auth/signin`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: Sign in

### POST /auth/signout

- Method: `POST`
- Path: `/auth/signout`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `201`
- Description: Sign out

### POST /auth/signup

- Method: `POST`
- Path: `/auth/signup`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: Sign up

### GET /auth/temp-token

- Method: `GET`
- Path: `/auth/temp-token`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get temp token

### DELETE /auth/user

- Method: `DELETE`
- Path: `/auth/user`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200, 400`
- Description: Delete user

### GET /auth/user

- Method: `GET`
- Path: `/auth/user`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get user information via access token

### GET /auth/user/me

- Method: `GET`
- Path: `/auth/user/me`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get user information

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
