<h1> CRUD :four: </h1>
<br>

<h2> Este foi o projeto que aprendi no YouTube do Hora de codar</h2>
<p> CRUD é um acrônimo para Create, Read, Update e Delete (criação, consulta, atualização e remoção). São as 4 operações principais em um banco de dados. Ou seja, criação de uma API para integrar com o MongoDB. </p>

<h2> Introdução </h2>
O objetivo é criar um sistema para disponibilizar uma lista com as pessoas cadastradas no banco de dados.

## Tecnologias utilizadas
* VS Code
* Node.JS
* NPM
* Express
* Nodemon
* Mongoose
* Dotenv
* MongoDB

## Ferramentas
Na aplicação foi utilizado o <a href="https://nodejs.org/en/download" target="_blank" > Node.JS </a>  na versão 18.14.0 em LTS.

Na aplicação foi utilizado o <a href="https://www.mongodb.com/pt-br/atlas" target="_blanl" > MongoDB Atlas </a> na nuvem AWS.



## Dependências 
Framework Express na versão 4.18.2 

Biblioteca Dotenv na versão 16.3.2

Biblioteca Mongoose na versão 8.1.0

Biblioteca Nodemon na versão 3.0.3



## Rodando o projeto
- Para rodar o repositório na sua máquina, é necessário clonar o mesmo.
  
- Pra rodar o servidor escreva no terminal:
```
npm run start
```
- Parar de rodar o servidor: no terminal clicar nas teclas de "Ctrl" e "C".

- Caminho da URL para o banco de dados:
```
http://localhost:/3000
```


## Endpoints

| Método | URL             | Descrição                                                                                                                                                                                         |
| ------ | --------------  | ------------------------------------------------------------------------------------------------------ 
| GET    | //          | Mostra uma mensagem teste.
| GET    |//person    | Mostra uma lista com todas as  pessoas no banco. E retorna uma mensagem de sucesso. |
| GET    |//person/:id | Encontra pessoa especifica. E retorna um json com dados cadastrados |
| PATCH  | /person/:id | Atualiza algum dado específico. |
| DELETE | /person/:id  | Deleta algum  a partir do `id` escrito. | 



## Modelagem dos dados

Dados que o projeto possui:

| Descrição                 | Tipo |
| -------------------- | ------------------ |
| id                   | `String` |
| name                 | `String` |
| salary               | Number   |
| approved             | boolean  |




## Status do projeto
:heavy_check_mark: Aplicação finalizada.
