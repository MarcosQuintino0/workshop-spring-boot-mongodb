
# Projeto: Web services com Spring Boot e MongoDb
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/MarcosQuintino0/workshop-spring-boot-mongodb/blob/main/LICENSE) 

# Sobre o projeto
Esse sistema é uma "simulação de uma rede social" onde temos o usuario que tem posts e comentarios

## Modelo conceitual
![Modelo Conceitual](https://github.com/MarcosQuintino0/Assets/blob/main/modeloRede.PNG)

## Algumas das Funcionalidades
- Criação de usuários: É possível enviar uma requisição POST para a rota /users com os dados do usuário (name, email) no formato JSON para criar um novo usuário.

- Consulta de usuários: Envia uma requisição GET para a rota /users para obter a lista de todos os usuario. É possível também enviar uma requisição GET para a rota /users/{id} para obter os detalhes de um user específico.

- Consulta de um Post: Envia uma requisição GET para a rota /posts/fullsearch para obter a lista de todos os posts.

- Consulta de um Post especifico: Envia uma requisição GET para a rota /posts/{id} para obter a lista de todos os posts.

![Modelo Conceitual](https://github.com/MarcosQuintino0/Assets/blob/main/test1.PNG)
![Modelo Conceitual](https://github.com/MarcosQuintino0/Assets/blob/main/test2.PNG)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- Maven
- Postman
- MongoDB
# Como executar o projeto

## Back end
Pré-requisitos: 
Java 11;
MongoDB instalado;

```bash
# clonar repositório
1 - git clone https://github.com/MarcosQuintino0/workshop-spring-boot-mongodb

# entrar na pasta do projeto back end
2 -cd workshop-spring-boot-mongodb

# executar o projeto
3 -mvn spring-boot:run

4 -Abra o Postman ou outra ferramenta de sua preferência para enviar requisições HTTP para a aplicação.

5 -Para testar algumas funcionalidades da aplicação, envie as seguintes requisições HTTP:
◉ Criação de usuário: Envie uma requisição POST para a rota /users com os dados do usuário (name, email) no formato JSON.
◉ Consulta de usuário: Envie uma requisição GET para a rota /users.

# Autor

Marcos André Quintino

https://www.linkedin.com/in/marcos-andre-quintino/
