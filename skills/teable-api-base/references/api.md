# base Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `31`

## Operations

### POST /base

- Method: `POST`
- Path: `/base`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a base

### GET /base/access/all

- Method: `GET`
- Path: `/base/access/all`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get base list by query

### Create a base from template or apply a template to a base

- Method: `POST`
- Path: `/base/create-from-template`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a base from template or apply a template to a base

### POST /base/duplicate

- Method: `POST`
- Path: `/base/duplicate`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: duplicate a base

### import a base

- Method: `POST`
- Path: `/base/import`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: import a base

### import a base with SSE progress events

- Method: `POST`
- Path: `/base/import-stream`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `200`
- Description: import a base with SSE progress stream

### GET /base/shared-base

- Method: `GET`
- Path: `/base/shared-base`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`

### DELETE /base/{baseId}

- Method: `DELETE`
- Path: `/base/{baseId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a base by baseId

### GET /base/{baseId}

- Method: `GET`
- Path: `/base/{baseId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a base by baseId

### PATCH /base/{baseId}

- Method: `PATCH`
- Path: `/base/{baseId}`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update a base info

### POST /base/{baseId}/collaborator

- Method: `POST`
- Path: `/base/{baseId}/collaborator`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Add a collaborator to a base

### DELETE /base/{baseId}/collaborators

- Method: `DELETE`
- Path: `/base/{baseId}/collaborators`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a base collaborators

### GET /base/{baseId}/collaborators

- Method: `GET`
- Path: `/base/{baseId}/collaborators`
- Parameters: `7`
- Request Body: `no`
- Response Codes: `200`
- Description: List a base collaborator

### PATCH /base/{baseId}/collaborators

- Method: `PATCH`
- Path: `/base/{baseId}/collaborators`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update a base collaborator

### Get base collaborator user list

- Method: `GET`
- Path: `/base/{baseId}/collaborators/users`
- Parameters: `6`
- Request Body: `no`
- Response Codes: `200`
- Description: Get base collaborator user list

### GET /base/{baseId}/erd

- Method: `GET`
- Path: `/base/{baseId}/erd`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get the erd of a base

### GET /base/{baseId}/export

- Method: `GET`
- Path: `/base/{baseId}/export`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: export a base by baseId

### POST /base/{baseId}/invitation/email

- Method: `POST`
- Path: `/base/{baseId}/invitation/email`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Send invitations by e-mail

### GET /base/{baseId}/invitation/link

- Method: `GET`
- Path: `/base/{baseId}/invitation/link`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: List a invitation link to your

### POST /base/{baseId}/invitation/link

- Method: `POST`
- Path: `/base/{baseId}/invitation/link`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a invitation link to your

### DELETE /base/{baseId}/invitation/link/{invitationId}

- Method: `DELETE`
- Path: `/base/{baseId}/invitation/link/{invitationId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a invitation link to your

### PATCH /base/{baseId}/invitation/link/{invitationId}

- Method: `PATCH`
- Path: `/base/{baseId}/invitation/link/{invitationId}`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update a invitation link to your

### move a base to another space

- Method: `PUT`
- Path: `/base/{baseId}/move`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: move a base to another space

### PUT /base/{baseId}/order

- Method: `PUT`
- Path: `/base/{baseId}/order`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update base order

### DELETE /base/{baseId}/permanent

- Method: `DELETE`
- Path: `/base/{baseId}/permanent`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Permanently delete a base by baseId

### GET /base/{baseId}/permission

- Method: `GET`
- Path: `/base/{baseId}/permission`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a base permission

### publish or unpublish a base

- Method: `PUT`
- Path: `/base/{baseId}/publish`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: publish or unpublish a base

### Sign attachment URLs

- Method: `POST`
- Path: `/base/{baseId}/sign-attachment-urls`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Generate signed URLs for attachment files

### Execute SQL query

- Method: `POST`
- Path: `/base/{baseId}/sql-query`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Execute SQL query on a base

### GET /space/{spaceId}/base

- Method: `GET`
- Path: `/space/{spaceId}/base`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get base list by query

### DELETE /trash/reset-items

- Method: `DELETE`
- Path: `/trash/reset-items`
- Parameters: `4`
- Request Body: `no`
- Response Codes: `200`
- Description: Reset trash items for a base or table
