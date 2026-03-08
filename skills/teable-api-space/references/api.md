# space Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `31`

## Operations

### Get space list

- Method: `GET`
- Path: `/space`
- Parameters: `0`
- Request Body: `no`
- Response Codes: `200`
- Description: Get space list by query

### POST /space

- Method: `POST`
- Path: `/space`
- Parameters: `0`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a space

### GET /space/authentication/providers

- Method: `GET`
- Path: `/space/authentication/providers`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get space authentication providers

### DELETE /space/{spaceId}

- Method: `DELETE`
- Path: `/space/{spaceId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a space by spaceId

### GET /space/{spaceId}

- Method: `GET`
- Path: `/space/{spaceId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a space by spaceId

### PATCH /space/{spaceId}

- Method: `PATCH`
- Path: `/space/{spaceId}`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update a space info

### GET /space/{spaceId}/authentication

- Method: `GET`
- Path: `/space/{spaceId}/authentication`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a space authentication list

### POST /space/{spaceId}/authentication

- Method: `POST`
- Path: `/space/{spaceId}/authentication`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a space authentication

### DELETE /space/{spaceId}/authentication/{id}

- Method: `DELETE`
- Path: `/space/{spaceId}/authentication/{id}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a space authentication

### GET /space/{spaceId}/authentication/{id}

- Method: `GET`
- Path: `/space/{spaceId}/authentication/{id}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a space authentication

### PUT /space/{spaceId}/authentication/{id}

- Method: `PUT`
- Path: `/space/{spaceId}/authentication/{id}`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update a space authentication

### POST /space/{spaceId}/collaborator

- Method: `POST`
- Path: `/space/{spaceId}/collaborator`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Add a collaborator to a space

### DELETE /space/{spaceId}/collaborators

- Method: `DELETE`
- Path: `/space/{spaceId}/collaborators`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a collaborator

### GET /space/{spaceId}/collaborators

- Method: `GET`
- Path: `/space/{spaceId}/collaborators`
- Parameters: `8`
- Request Body: `no`
- Response Codes: `200`
- Description: List a space collaborator

### PATCH /space/{spaceId}/collaborators

- Method: `PATCH`
- Path: `/space/{spaceId}/collaborators`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update a space collaborator

### DELETE /space/{spaceId}/domain-verification

- Method: `DELETE`
- Path: `/space/{spaceId}/domain-verification`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a space domain verification

### GET /space/{spaceId}/domain-verification

- Method: `GET`
- Path: `/space/{spaceId}/domain-verification`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get a space domain verification list

### POST /space/{spaceId}/domain-verification

- Method: `POST`
- Path: `/space/{spaceId}/domain-verification`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Create a space domain verification

### POST /space/{spaceId}/domain-verification/send-verification-email

- Method: `POST`
- Path: `/space/{spaceId}/domain-verification/send-verification-email`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Send space email verification

### GET /space/{spaceId}/integration

- Method: `GET`
- Path: `/space/{spaceId}/integration`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get integration list by query

### POST /space/{spaceId}/integration

- Method: `POST`
- Path: `/space/{spaceId}/integration`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Create a integration to a space

### DELETE /space/{spaceId}/integration/{integrationId}

- Method: `DELETE`
- Path: `/space/{spaceId}/integration/{integrationId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a integration by integrationId

### PATCH /space/{spaceId}/integration/{integrationId}

- Method: `PATCH`
- Path: `/space/{spaceId}/integration/{integrationId}`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update a integration to a space

### POST /space/{spaceId}/invitation/email

- Method: `POST`
- Path: `/space/{spaceId}/invitation/email`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Send invitations by e-mail

### GET /space/{spaceId}/invitation/link

- Method: `GET`
- Path: `/space/{spaceId}/invitation/link`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: List a invitation link to your

### POST /space/{spaceId}/invitation/link

- Method: `POST`
- Path: `/space/{spaceId}/invitation/link`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `201`
- Description: Create a invitation link to your

### DELETE /space/{spaceId}/invitation/link/{invitationId}

- Method: `DELETE`
- Path: `/space/{spaceId}/invitation/link/{invitationId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a invitation link to your

### PATCH /space/{spaceId}/invitation/link/{invitationId}

- Method: `PATCH`
- Path: `/space/{spaceId}/invitation/link/{invitationId}`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update a invitation link to your

### DELETE /space/{spaceId}/permanent

- Method: `DELETE`
- Path: `/space/{spaceId}/permanent`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Permanently delete a space by spaceId

### GET /space/{spaceId}/search

- Method: `GET`
- Path: `/space/{spaceId}/search`
- Parameters: `5`
- Request Body: `no`
- Response Codes: `200`
- Description: Search bases and nodes within a space

### POST /trash/restore/{trashId}

- Method: `POST`
- Path: `/trash/restore/{trashId}`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `201`
- Description: restore a space, base, table, etc.
