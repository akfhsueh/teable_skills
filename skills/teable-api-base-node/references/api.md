# base node Endpoints

- Source API: `Teable App`
- Version: `1.0.0`
- Endpoint count: `12`

## Operations

### POST /base/{baseId}/node

- Method: `POST`
- Path: `/base/{baseId}/node`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Create a hierarchical node for a base

### POST /base/{baseId}/node/folder

- Method: `POST`
- Path: `/base/{baseId}/node/folder`
- Parameters: `1`
- Request Body: `yes`
- Response Codes: `200`
- Description: Create a folder node in base

### DELETE /base/{baseId}/node/folder/{folderId}

- Method: `DELETE`
- Path: `/base/{baseId}/node/folder/{folderId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a node folder and move its children to parent

### PATCH /base/{baseId}/node/folder/{folderId}

- Method: `PATCH`
- Path: `/base/{baseId}/node/folder/{folderId}`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Rename a node folder

### GET /base/{baseId}/node/list

- Method: `GET`
- Path: `/base/{baseId}/node/list`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get list nodes of a base

### GET /base/{baseId}/node/tree

- Method: `GET`
- Path: `/base/{baseId}/node/tree`
- Parameters: `1`
- Request Body: `no`
- Response Codes: `200`
- Description: Get tree nodes for a base

### DELETE /base/{baseId}/node/{nodeId}

- Method: `DELETE`
- Path: `/base/{baseId}/node/{nodeId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Delete a node for a base

### GET /base/{baseId}/node/{nodeId}

- Method: `GET`
- Path: `/base/{baseId}/node/{nodeId}`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Get nodes for a base

### PUT /base/{baseId}/node/{nodeId}

- Method: `PUT`
- Path: `/base/{baseId}/node/{nodeId}`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Update a node for a base

### POST /base/{baseId}/node/{nodeId}/duplicate

- Method: `POST`
- Path: `/base/{baseId}/node/{nodeId}/duplicate`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Duplicate a node for a base

### PUT /base/{baseId}/node/{nodeId}/move

- Method: `PUT`
- Path: `/base/{baseId}/node/{nodeId}/move`
- Parameters: `2`
- Request Body: `yes`
- Response Codes: `200`
- Description: Move or reorder a node

### DELETE /base/{baseId}/node/{nodeId}/permanent

- Method: `DELETE`
- Path: `/base/{baseId}/node/{nodeId}/permanent`
- Parameters: `2`
- Request Body: `no`
- Response Codes: `200`
- Description: Permanent delete a node for a base
