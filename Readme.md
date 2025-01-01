# API

Este projeto é uma API RESTful desenvolvida em Node.js que permite gerenciar categorias, mercados e regras promocionais. Utiliza o Prisma como ORM para interagir com um banco de dados SQLite.

A estrutura de pastas é organizada da seguinte forma:

api/
├── .expo
├── node_modules
├── prisma/
├── src/
│   ├── controllers/
│   │   ├── categories-controller.ts
│   │   ├── coupons-controller.ts
│   │   └── markets-controller.ts
│   ├── database/
│   ├── middlewares/
│   │   └── error-handling.ts
│   ├── routes/
│   │   ├── categories-route.ts
│   │   ├── coupons-route.ts
│   │   ├── index.ts
│   │   └── markets-route.ts
│   └── utils/
│       └── server.ts
├── .env
├── .gitignore
├── package-lock.json
└── package.json

# Tecnologias
Node.js: Para a construção do backend.
Express: Para gerenciar a aplicação web.
Prisma: Para interagir com o banco de dados SQLite.
SQLite: Banco de dados utilizado.

O servidor estará em execução na porta 3333.

