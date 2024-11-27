# API de Contatos

## Overview

A API de contatos foi desenvolvida em TypeScript, com atributos básicos de um contato, para ser consumida em um Front-End criado pelos Alunos da UniFecaf, [Repositório AQUI](https://github.com/Cx1que/landingPageConectaPlus).


## URLs

Abaixo, seguem as URLs para fazer as requisições no banco de dados Postgres, disponibilizado pelo professor em aula.

+ <b>GET</b> -> http://localhost:3000/api/contacts

+ <b>POST</b> -> http://localhost:3000/api/contacts

+ <b>PUT</b> -> http://localhost:3000/api/contacts/id

+ <b>DELETE</b> -> http://localhost:3000/api/contacts/id

## Exemplo de JSON base


+ Para realizar um POST
```
{
  "name": "Caíque",
  "email": "example@gmail.com",
  "telefone": "XXXXX-XXXX",
  "image": "url-de-imagens"
}
```

+ Para realizar um PUT

    * Id passado como parâmetro na URL + 
```
{
  "name": "Caíque",
  "email": "exampleEmail@gmail.com",
  "telefone": "XXXXX-XXXX",
  "image": "url-de-imagens"
}
```

+ Para realizar um DELETE

    * Id passado como parâmetro na URL
---

### Tecnologias utilizadas

+ TypeScript
+ Postgres
+ Postman
+ Git
