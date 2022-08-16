<h1 align="center">Capitulo II </h1>
<h4 align="center">Ignite - <a href="https://rocketseat.com.br/" >Rocketseat</a> - Trilha Node js</h4>

## Objetivo

Criar uma aplicação de listagem e cadastro de usuários utilizando os conceitos de SOLID aprendidos.

## Requisitos

### Rotas da aplicação
- [x] POST /users
- [x] PATCH /users/:user_id/admin
- [x] GET /users/:user_id
- [x] GET /users/:user_id

### Específicação dos testes

#### Teste do model
- [x] Should be able to create an user with all props

#### Testes do repositório
- [x] Should be able to create new users
- [x] Should be able to list all users
- [x] Should be able to find user by ID
- [x] Should be able to find user by e-mail address
- [x] Should be able to turn an user as admin

##### Testes de useCases
- [x] Should be able to create new users
- [x] Should not be able to create new users when email is already taken
- [x] Should be able to turn an user as admin
- [x] Should not be able to turn a non existing user as admin
- [x] Should be able to get user profile by ID
- [x] Should not be able to show profile of a non existing user
- [x] Should be able to list all users
- [x] Should not be able to a non admin user get list of all users
- [x] Should not be able to a non existing user get list of all users

## Instalação ##

```bash
# Clone este repositório
$ git clone https://github.com/guerreiru/ignite-introducao-ao-SOLID.git

# Entre na pasta
$ cd ignite-introducao-ao-SOLID

# Instale as dependências
$ yarn ou yarn install

# Execute a aplicação em modo de desenvolvimento
$ yarn dev

# O servidor inciará na porta:3333
acesse <http://localhost:3333>
```

<br>

[![Linkedin Badge](https://img.shields.io/badge/-Fernando%20Guerreiro-1293d2?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/guerreiru/)](https://www.linkedin.com/in/guerreiru/) 
[![Gmail Badge](https://img.shields.io/badge/-dev.fernandoguerreiro@gmail.com-EA4335?style=flat-square&logo=Gmail&logoColor=white&link=mailto:dev.fernandoguerreiro@gmail.com)](mailto:dev.fernandoguerreiro@gmail.com)
