Curso de nodejs das Trilhas do Ignite da Rocketseat.

# Fundamentos Básicos NodeJS.

### Utilizando express como framework para auxiliar na construção das rotas #

 * como instalar o express:
 * *npm install Express*

 ### Utilizando nodemon para deixar a aplicação rodando sem a necessidade de reiniciar a cada alteração #

* Como instalar o nodemon:
 * *npm install -g nodemon*
 * *npm install --save-dev nodemon*

 - Para configurar o nodemon no *package.json* na parte de *scripts* insira: 
    "dev":"nodemon src/index.js"



1 - Tipos de requisição
* GET - Buscar uma informação dentro do servidor.
* POST - Inserir uma informação no servidor.
* PUT - Alterar uma informação no servidor.
* PATCH - Alterar uma informação específica.
* DELETE - Deletar uma informação no servidor.

2 - Tipos de parâmetros
* Route Params => Identificar um recurso editar/deletar/buscar.
* Query Params => Paginação/Filtro
* Body Params => Os objetos inserção/alteração (JSON)