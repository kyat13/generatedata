# Changes Required

- ``utils\authUtils.js:55``: comment out getPasswordHash
- create .env at root with:
  - `GD_WEB_DOMAIN`: string
  - `GD_WEB_SERVER_PORT`: number
  - `GD_WEB_USE_HTTPS`: boolean
  - `GD_API_SERVER_PORT`: number