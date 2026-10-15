# Projeto de Desenvolvimento Web com Python e Flask — Módulo 3

## 1. Objetivo do projeto

O objetivo deste projeto foi desenvolver uma API REST utilizando Python e o framework Flask, aplicando conceitos fundamentais de desenvolvimento de aplicações web, criação de endpoints, modelagem de entidades e operações CRUD (Create, Read, Update e Delete).

A aplicação foi desenvolvida para gerenciar usuários, permitindo cadastrar, consultar, atualizar e excluir informações como nome, telefone, endereço e CPF.

## 2. Ferramentas e tecnologias utilizadas

- **Python:** linguagem de programação utilizada para implementar a lógica da aplicação.
- **Flask:** framework responsável pela criação da aplicação web e dos endpoints da API.
- **Flask-SQLAlchemy:** integração entre o Flask e o ORM SQLAlchemy, facilitando a manipulação dos registros do banco de dados.
- **SQLite:** banco de dados relacional utilizado para armazenar as informações dos usuários.
- **JSON:** formato utilizado para enviar e receber dados por meio das requisições HTTP.
- **Google Colab:** ambiente utilizado para desenvolver e executar o código Python.
- **Flask Test Client:** recurso utilizado para testar os endpoints sem a necessidade de disponibilizar um servidor externamente.

## 3. Desenvolvimento da aplicação

Durante o desenvolvimento, foi criada a entidade Usuario, contendo os campos identificador, nome, telefone, endereço e CPF. Em seguida, foram implementadas as rotas da API para realizar as operações de cadastro, consulta individual, listagem, atualização e exclusão de usuários.

Também foram incluídas verificações para tratar dados obrigatórios, impedir o cadastro de CPF duplicado e retornar códigos de status HTTP apropriados para as operações realizadas.

Os testes foram executados por meio do cliente de testes do Flask, simulando requisições HTTP e verificando as respostas da aplicação.

## 4. Resultados alcançados

O projeto permitiu aplicar, na prática, os conceitos de desenvolvimento de APIs com Flask, modelagem de dados com SQLAlchemy, persistência em banco de dados SQLite e comunicação por meio de JSON.

A implementação das operações CRUD demonstrou como uma aplicação Python pode disponibilizar funcionalidades de gerenciamento de dados por meio de endpoints HTTP. Os testes também permitiram verificar os resultados das operações e o tratamento de situações como a consulta de um usuário inexistente.

## 5. Conclusão

O desenvolvimento deste projeto contribuiu para consolidar os conhecimentos de Python para aplicações web, demonstrando o funcionamento de uma API REST e sua integração com um banco de dados relacional.

A atividade estabeleceu uma base prática para o desenvolvimento de aplicações mais completas, que podem evoluir futuramente com autenticação, validação avançada, documentação da API, testes automatizados e implantação em um servidor de produção.
