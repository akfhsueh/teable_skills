# authority-matrix Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `15`

## Operations

### GET /base/{baseId}/authority-matrix

- Method: `GET`
- Path: `/base/{baseId}/authority-matrix`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get authority matrix

### PUT /base/{baseId}/authority-matrix

- Method: `PUT`
- Path: `/base/{baseId}/authority-matrix`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update authority matrix

### GET /base/{baseId}/authority-matrix-role

- Method: `GET`
- Path: `/base/{baseId}/authority-matrix-role`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get authority matrix role list

### POST /base/{baseId}/authority-matrix-role

- Method: `POST`
- Path: `/base/{baseId}/authority-matrix-role`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Add authority matrix role

### GET /base/{baseId}/authority-matrix-role-table/{tableId}/filter-link-records

- Method: `GET`
- Path: `/base/{baseId}/authority-matrix-role-table/{tableId}/filter-link-records`
- Parameters: `3`
- Request Body: `no`
- Response Codes: `200`
- Description: Get authority matrix table link records

### DELETE /base/{baseId}/authority-matrix-role/{authorityMatrixRoleId}

- Method: `DELETE`
- Path: `/base/{baseId}/authority-matrix-role/{authorityMatrixRoleId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete authority matrix role

### GET /base/{baseId}/authority-matrix-role/{authorityMatrixRoleId}

- Method: `GET`
- Path: `/base/{baseId}/authority-matrix-role/{authorityMatrixRoleId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get authority matrix role

### PUT /base/{baseId}/authority-matrix-role/{authorityMatrixRoleId}

- Method: `PUT`
- Path: `/base/{baseId}/authority-matrix-role/{authorityMatrixRoleId}`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update authority matrix role

### PATCH /base/{baseId}/authority-matrix-role/{authorityMatrixRoleId}/description

- Method: `PATCH`
- Path: `/base/{baseId}/authority-matrix-role/{authorityMatrixRoleId}/description`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update authority matrix role description

### POST /base/{baseId}/authority-matrix-role/{authorityMatrixRoleId}/duplicate

- Method: `POST`
- Path: `/base/{baseId}/authority-matrix-role/{authorityMatrixRoleId}/duplicate`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `201`
- Description: Duplicate authority matrix role

### PATCH /base/{baseId}/authority-matrix-role/{authorityMatrixRoleId}/name

- Method: `PATCH`
- Path: `/base/{baseId}/authority-matrix-role/{authorityMatrixRoleId}/name`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update authority matrix role name

### PATCH /base/{baseId}/authority-matrix-role/{authorityMatrixRoleId}/status

- Method: `PATCH`
- Path: `/base/{baseId}/authority-matrix-role/{authorityMatrixRoleId}/status`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update authority matrix role status

### PATCH /base/{baseId}/authority-matrix-role/{authorityMatrixRoleId}/user

- Method: `PATCH`
- Path: `/base/{baseId}/authority-matrix-role/{authorityMatrixRoleId}/user`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update authority matrix role user

### PATCH /base/{baseId}/authority-matrix/admin-user

- Method: `PATCH`
- Path: `/base/{baseId}/authority-matrix/admin-user`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update admin user

### PATCH /base/{baseId}/authority-matrix/status

- Method: `PATCH`
- Path: `/base/{baseId}/authority-matrix/status`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Enable authority
