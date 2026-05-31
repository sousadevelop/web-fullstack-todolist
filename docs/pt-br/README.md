# Full-Stack Todo List

## Visão Geral

Aplicação web de tarefas com frontend em HTML, CSS e JavaScript, API Express e persistência MySQL.

## Problema Resolvido

Permite listar, criar, atualizar e excluir tarefas enquanto demonstra a integração entre frontend, API e banco relacional.

## Stack

JavaScript, HTML, CSS, Node.js, Express, MySQL, Docker

## Arquitetura

`frontend/`: interface estática; `backend/src/router.js`: endpoints; `controllers/`: camada HTTP; `models/`: acesso MySQL; `middlewares/`: validação.

Consulte o [diagrama de arquitetura](../../assets/diagrams/architecture.mmd).

## Instalação

```bash
npm install
Copy-Item .env.example .env
```

## Execução Local

```bash
npm start
```

## Variáveis de Ambiente Esperadas

PORT, MYSQL_HOST, MYSQL_USER, MYSQL_PASSWORD, MYSQL_DB

Use [.env.example](../../.env.example) apenas como referência e nunca versione valores reais.

## Estrutura de Pastas

`frontend/`: interface estática; `backend/src/router.js`: endpoints; `controllers/`: camada HTTP; `models/`: acesso MySQL; `middlewares/`: validação.

## Screenshots

Adicione capturas revisadas em [assets/screenshots/](../../assets/screenshots/) sem dados sensíveis.

## Limitações

O frontend referencia `http://localhost:3000` diretamente e o provisionamento do schema do banco não está automatizado no repositório.

## Próximos Passos

Consulte o [roadmap](../../ROADMAP.md).

## Segurança e Contribuição

Leia [SECURITY.md](../../SECURITY.md) e [CONTRIBUTING.md](../../CONTRIBUTING.md).
