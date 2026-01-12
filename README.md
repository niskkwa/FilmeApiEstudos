# Cinema API

API REST desenvolvida em ASP.NET Core utilizando Entity Framework Core para persistência de dados.

O objetivo do projeto é gerenciar filmes, cinemas, endereços e sessões, trabalhando com relacionamentos entre entidades e boas práticas no desenvolvimento de APIs.

---

## Tecnologias

- ASP.NET Core MVC
- Entity Framework Core
- C#
- MySQL / SQL Server
- Swagger

---

## Descrição

A API é responsável pelo cadastro e consulta das seguintes entidades:

- **Filme**: representa os filmes disponíveis para exibição.
- **Cinema**: representa um cinema físico.
- **Endereço**: informações de localização do cinema.
- **Sessão**: representa uma exibição de um filme em um cinema.

As entidades possuem relacionamento entre si, modelados utilizando o Entity Framework Core.

---

## Relacionamentos

- Um cinema possui um endereço (1:1)
- Um cinema pode possuir várias sessões (1:N)
- Um filme pode possuir várias sessões (1:N)

---

## Funcionalidades

- Cadastro, edição, remoção e consulta de filmes
- Cadastro de cinemas e seus endereços
- Criação de sessões associadas a filmes e cinemas
- Documentação dos endpoints via Swagger
