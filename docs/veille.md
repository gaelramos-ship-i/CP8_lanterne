# Veille CP8_Lanterne

## Arborescence du projet
```text
CP8_Lanterne/           
│   ├── data
│       └── curiosities.json
│   └── index.js
├── docs/                   
│   ├── deploiement-vercel.md
│   ├── validation.md
│   └── veille.md
├── tests/ 
│   └── api.test.js
├── .env.example           
├── .gitignore             
├── package.json          
├── README.md 
└── vercel.json          
```

## Détails utiles: 

**Le point d'entré express** : `index.js`.

**Dépendances:** 
- cors
- express

**Installation de pnpm :** `npm install -g pnpm`

**Versions:**
- Node version: v24.13.1
- pnpm version : 11.19.0

**Scripts:**
- "start": "node api/index.js",
- "dev": "node --watch api/index.js",
- "check": "node --check api/index.js && node --check tests/api.test.js",
- "test": "node tests/api.test.js

## Les routes

- /health
- /curiosities
- /curiosities/:slug

## Fichiers non transmis dans git 

- node_modules/
- .env
- vercel.json