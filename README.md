API sing me a Song é uma API desenvolvida em node.js com a função de recomendar e ranquear músicas do youtube

## Requisitos para rodar a API

* npm

* postigres

## Como usar a API?

1 -  Dê um ```git clone``` neste repositório

2 - Na pasta do projeto, dê um ```npm install```

3 - Adicione seus arquivos .env na pasta raiz utilizando o env.example como exemplo

4 - Crie um banco de dados e rode o script do arquivo dump.sql

Há quatro scripts:

para rodar a API em modo de <strong>produção</strong> use: (necessário ter um arquivo .env)

```npm run start```

para rodar a API em modo de <strong>desenvolvimento</strong> use:(necessário ter um arquivo .env.dev)

```npm run start:dev```

para <strong>testar</strong> as rotas da API: (necessário ter um arquivo .env.test)

```npm run test```

para <strong>testar</strong> as rotas da API enquanto contribui no código: (necessário ter um arquivo .env.test)

```npm run test:watch```

para <strong>verificar a cobertura dos testes</strong>

```npm run coverage```
