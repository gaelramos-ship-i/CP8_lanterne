# Veille 

Node version: v24.13.1

`npm install -g pnpm`
pnpm version : 11.19.0

Dépendance: 
- cors
- express

Scripts:
- "start": "node api/index.js",
- "dev": "node --watch api/index.js",
- "check": "node --check api/index.js && node --check tests/api.test.js",
- "test": "node tests/api.test.js