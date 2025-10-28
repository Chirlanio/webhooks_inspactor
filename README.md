# Webhooks Inspector

Uma aplicação fullstack para inspeção e teste de webhooks, permitindo visualizar e gerenciar chamadas de webhooks em tempo real.

## 💻 Tecnologias

Este projeto foi desenvolvido com as seguintes tecnologias:

### Backend
- Node.js
- Fastify
- TypeScript
- DrizzleORM
- PostgreSQL
- Docker

### Frontend
- React
- TypeScript
- Vite
- TailwindCSS

## 🚀 Como executar

### Pré-requisitos
- Node.js
- pnpm
- Docker

### Configuração

1. Clone o repositório:
```bash
git clone https://github.com/Chirlanio/webhooks_inspactor.git
cd webhooks_inspactor
```

2. Instale as dependências do projeto:
```bash
pnpm install
```

### Executando a API

1. Na pasta `api`, inicie o banco de dados com Docker:
```bash
cd api
docker compose up -d
```

2. Execute as migrações do banco de dados:
```bash
pnpm db:migrate
```

3. Inicie o servidor da API:
```bash
pnpm dev
```

A API estará disponível em `http://localhost:3333`

### Executando o Frontend

1. Em outro terminal, na pasta `web`, inicie a aplicação:
```bash
cd web
pnpm dev
```

O frontend estará disponível em `http://localhost:5173`

## 📝 Funcionalidades

- Criação de endpoints únicos para receber webhooks
- Visualização em tempo real das chamadas recebidas
- Histórico de webhooks recebidos
- Interface intuitiva para teste e depuração

## 📄 Licença

Este projeto está sob a licença MIT.