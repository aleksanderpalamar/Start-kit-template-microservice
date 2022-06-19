<div align="center">
    <h1>Start Kit Template Microservice</h1>     
</div>
    
<p align="center">   
  <img alt="Made by aleksanderpalamar" src="https://img.shields.io/badge/made%20by-aleksanderpalamar-%237519C1?style=flat-square" >  
</p>
<p align="center">
  <a href="#sobre">About</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#tecnologias">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#como-executar">How to Run</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp; 
</p>

## Sobre

The project is a backend application that aims to facilitate the creation of a microservice using the technologies.

**Collaborate with the project, comment, suggestions, report bugs, help improve the project.❤️**

## Tecnologias

- [NestJS](https://docs.nestjs.com/)
- [Graphql](https://graphql.org/)
- [Apache Kafka](https://kafka.apache.org/)
- [Apollo Client (GraphQL)](https://www.apollographql.com/)

## Como Executar

- ### **Pré-requisitos**

  - You **must** have **[Node.js](https://nodejs.org/en/)** installed on your computer
  - You **must** have **[Git](https://git-scm.com/)** installed and configured on your computer
  - Also, you **must** have a package manager either **[NPM](https://www.npmjs.com/)** or **[Yarn](https://yarnpkg.com/) **.  

1. Make a clone of the repository:

```sh
  $ git clone git@github.com:aleksanderpalamar/Start-kit-template-microservice.git
```

2. Running the Application:

```sh
  # Aplicação web
  $ cd Template-microservice
  # Instalando as dependências do projeto.
  $ yarn # ou npm install
  # Inicie a aplicação web
  $ yarn start # ou npm start
```

3. Create a `.env` file with the following variables:

```sh
  # Variáveis de ambiente
  AUTH0_AUDIENCE=https://api.template.com 
  AUTH0_DOMAIN=dev-0qjqjqjq.auth0.com


  # Database
  DATABASE_URL="postgresql://docker:docker@localhost:5432/mydb?schema=public"
```  

---
<sup>Project developed by [Aleksander Palamar](https://github.com/aleksanderpalamar), [Portfólio](https://www.palamarsolutionit.com.br/).</sup>