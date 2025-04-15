# 📦 App Promoções

Este é um projeto completo que consiste em uma aplicação mobile para visualização de promoções de mercados, com um back-end desenvolvido em Node.js e um front-end mobile em React Native utilizando Expo.

## 🔗 Visão Geral

- ✅ API RESTful com gerenciamento de mercados, categorias e cupons de desconto
- ✅ Aplicativo mobile com navegação moderna e responsiva
- ✅ Banco de dados SQLite com ORM Prisma
- ✅ Código modular com boas práticas de organização

---

## 📁 Estrutura do Projeto

```bash
AppPromocoes-main/
├── api/           # Back-end com Node.js, Express e Prisma
├── setup/         # Front-end mobile com React Native e Expo Router
└── Readme.md      # Documentação do projeto
```

---

## 🖥️ Back-end (API)

### Tecnologias Utilizadas

- **Node.js** – Ambiente de execução JavaScript
- **Express** – Framework para construção da API REST
- **Prisma** – ORM para integração com banco de dados
- **SQLite** – Banco de dados local e leve
- **TypeScript** – Tipagem estática para maior segurança

### Comandos

```bash
# Instalar dependências
cd api
npm install

# Rodar o servidor (porta 3333)
npx ts-node-dev src/server.ts

# Rodar seed (dados iniciais)
npx ts-node prisma/seed.ts
```

### Estrutura da API

- `GET /markets` – Listar mercados
- `GET /categories` – Listar categorias
- `GET /coupons` – Listar cupons/promos
- Rotas separadas em controllers e arquivos próprios

---

## 📱 Front-end Mobile (Expo App)

### Tecnologias Utilizadas

- **React Native** – Criação de interfaces mobile nativas
- **Expo Router** – Navegação com rotas baseadas em arquivos
- **TypeScript** – Tipagem no app mobile

### Comandos

```bash
# Instalar dependências
cd setup
npm install

# Rodar o app (Expo Go ou emulador)
npx expo start
```

### Funcionalidades

- Tela inicial com mercados
- Detalhes dos mercados e promoções
- Navegação entre páginas com Expo Router
- Assets personalizados (ícones, splash, logo)


## 🧑‍💻 Autor

Desenvolvido por **Geraldo Luiz**  

