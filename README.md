# NLW Expert (Node.js)

Um sistema de votação em tempo real onde os usuários podem criar uma enquete e outros usuários podem votar. O sistema gera um ranking entre as opções e atualiza os votos em tempo real.

## Requisites

- Docker;
- Node.js;

## Setup

- Clone the repository;
- Install dependencies (`npm install`);
- Setup PostgreSQL and Redis (`docker compose up -d`);
- Copy `.env.example` file (`cp .env.example .env`);
- Run application (`npm run dev`);
- Test it! (I personally recommend testing with [Hoppscotch](https://hoppscotch.io/)).

# Aula 1

É hora de começar nosso projeto! Vamos montar o setup com TypeScript, Fastify e Prisma, entender conceitos de API, como método HTTP e rotas, além de colocar a mão na massa para criar nossa primeira tabela utilizando Prisma.

## Iniciando o Projeto

```sh
npm init -y
npm install typescript @types/node -D
npx tsc --init
```

## Convertendo o código de JS para TS

```sh
npm install tsx -D
```

## FastiFy (Cria um servidor automatizar processos)

```sh
npm i fastify
```

## Banco de dados

```sh
npm i prisma -D
npx prisma init
npx prisma migrate dev
npx prisma studio
```

## Docker

## Zod

```sh
npm install zod
```

# Aula 2

A decolagem foi um sucesso e agora é hora de avançar. Vamos dar sequência à criação das nossas rotas! Vamos adicionar as opções da votação e, em seguida, vamos implementar as rotas de buscar uma votação pelo ID e a rota para votar na opção selecionada, validando as lógicas de ação do usuário.

## Fastify Cookie

```sh
npm install fastify/cookie
```
