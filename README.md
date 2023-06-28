# Simple CRUD :coffee:
Este repositório contém um projeto CRUD simples construído usando Java Spring. O objetivo deste repositório é praticar e compartilhar como você pode construir todos os métodos CRUD usando Java Spring.

## Table of Contents

- [Instalação](#instalação)
- [Configuração](#configuração)
- [API Endpoints](#api-endpoints)
- [Banco de Dados](#banco-de-dados)

## Instalação

1. Clone o repositório:

```bash
$ git clone git@github.com:isabelpaiva/crud_java_spring.git
```

2. Instale as dependências com o Maven

## Configuração

1. Inicie a aplicação com o Maven
2. A API estará acessível em http://localhost:8080


## API Endpoints
A API fornece os seguintes endpoints:

```markdown
GET /product - Recupera uma lista de todos os dados.

POST /product - Registra um novo dado.

PUT /product - Altera dados.

DELETE /product/{id} - Inativa dados.
```

## Banco de Dados

O projeto utiliza o PostgresSQL como banco de dados. As migrações de banco de dados necessárias são gerenciadas usando o Flyway.

Para instalar o PostgresSQL localmente, você pode [clicar aqui](https://www.postgresql.org/download/).

