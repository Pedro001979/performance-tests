# Performance & Backend Engineering — EBAC Demo Store

![NestJS](https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5%2B-3178C6?logo=typescript&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-ORM-2D3748?logo=prisma&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-API-E10098?logo=graphql&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-Testing-C21325?logo=jest&logoColor=white)

## Sobre o projeto

Backend de referência baseado em **NestJS**, desenvolvido para explorar uma aplicação estruturada com API GraphQL, autenticação, persistência com Prisma e PostgreSQL, documentação e testes automatizados.

O projeto também serve como base para práticas de **qualidade e testes de performance**, conectando desenvolvimento de APIs com validação automatizada e preparação de ambientes reproduzíveis.

## Stack técnica

- **NestJS** — arquitetura modular para aplicações Node.js
- **TypeScript** — desenvolvimento tipado
- **GraphQL / Apollo Server** — camada de API
- **Prisma ORM** — acesso e migrações de banco
- **PostgreSQL** — persistência de dados
- **JWT / Passport / bcrypt** — autenticação e segurança
- **Swagger** — documentação de API
- **Jest / Supertest** — testes automatizados
- **Docker** — infraestrutura local do banco

## Práticas demonstradas

- Estruturação de backend modular
- Autenticação baseada em JWT
- Validação e transformação de dados
- Persistência relacional com Prisma
- Migrations e seed de banco
- Testes automatizados de backend
- Execução de ambiente de banco via Docker
- Integração entre API, banco e camada de testes

## Scripts principais

```bash
npm install

# Desenvolvimento
npm run start:watch

# Build
npm run build

# Testes
npm test

# Gerar Prisma Client
npm run prisma:generate

# Subir PostgreSQL via Docker
npm run docker:db

# Inicializar banco e dados
npm run db:init
```

> Antes de executar o projeto, configure as variáveis de ambiente necessárias para a conexão com o PostgreSQL e demais serviços utilizados pela aplicação.

## Estrutura conceitual

```text
Client / Tests
      │
      ▼
 GraphQL API
      │
      ▼
   NestJS
      │
      ├── Authentication
      ├── Validation
      ├── Business Logic
      └── Prisma ORM
              │
              ▼
          PostgreSQL
```

## Objetivo profissional

Este projeto representa a interseção entre **desenvolvimento backend e engenharia de qualidade**, demonstrando conhecimento sobre APIs, persistência, autenticação e testes — fundamentos importantes para construção de pipelines de qualidade mais completos.

## Autor

**Pedro Ricardo**  
QA Automation | JavaScript | API Testing | Cypress | Appium | Performance Testing

[![GitHub](https://img.shields.io/badge/GitHub-Pedro001979-181717?logo=github)](https://github.com/Pedro001979)

---

Licença: ISC
