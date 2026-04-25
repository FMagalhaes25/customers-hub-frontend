# Cadastro de Clientes (Frontend)

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-6-3178C6?logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-8-646CFF?logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4-06B6D4?logo=tailwindcss&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-1-5A29E4?logo=axios&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)

Aplicacao frontend para cadastro e listagem de clientes, com integracao HTTP para API.

## Funcionalidades

- Listar clientes
- Cadastrar cliente (nome e e-mail)
- Remover cliente
- Exibir status do cliente (ATIVO/INATIVO)

## Stack

- React 19
- TypeScript
- Vite
- Tailwind CSS
- Axios

## Requisitos

- Node.js 20+
- npm 10+
- API backend em execucao


Configure a URL base da API:

```env
VITE_API_BASE_URL=http://localhost:3333
```


## Instalacao

```bash
npm install
```

## Execucao

```bash
npm run dev
```

Por padrao, o projeto abre em `http://localhost:5173`.

## Scripts

- `npm run dev`: inicia ambiente de desenvolvimento
- `npm run build`: gera build de producao
- `npm run preview`: executa preview local da build
- `npm run lint`: roda o lint do projeto

## Estrutura do Projeto

```text
src/
  App.tsx
  main.tsx
  index.css
  services/
    api.ts
  types/
    Customer.ts
```

## API Esperada

Endpoints utilizados pelo frontend:

- `GET /customers`
- `POST /customer`
- `DELETE /customer?id=<id>`

## Licenca

Este projeto pode ser distribuido sob a licenca MIT.
