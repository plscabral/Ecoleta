# ECOLETA

... Aplicação desenvolvida pelo pessoal da rocketseat.
... Plataforma de cadastro de pontos de coletas de lixos.

# Tecnology
> Node
> Typescript
> Sqlite3
> Knex

# Commands
> npm init --y
> npm i typescript -D
> npx tsc -init
> npm i express
> npm i @types/express -D
> npm i knex
> npm i sqlite3

# Commands Knex crate migrations
> npx knex --knexfile knexfile.ts migrate:latest

# Command knex create seeds
> npx knex --knexfile knexfile.ts seed:run

... Para rotear arquivos estáricos usamos esse método do express
> app.use('/uploads', express.static(path.resolve(__dirname, '..', 'uploads')))

... Nomes adotados pela comunidade
> index -> Obter uma listagem
> show -> Obter um único registro da listagem
> create
> update,
> delete