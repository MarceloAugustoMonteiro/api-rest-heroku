# Rest API Heroku
REST API with CRUD for Clients and Services for testing with Heroku.

Testing in Postman:

Link API: https://api-rest-cliente-servico.herokuapp.com

**POST Method (add):**

https://api-rest-cliente-servico.herokuapp.com/api/clientes

Example in JSON format:

{
"nome" : "Joao",
"cpf" : "35853358022",
"servicos": [
        {
            "descricao": "teste",
            "valor": "200"
        }
    ]
}

GET Method (query):

https://api-rest-cliente-servico.herokuapp.com/api/clientes/ "enter the Client ID you want to query"

Example: https://api-rest-cliente-servico.herokuapp.com/api/clientes/1

PUT Method (update):

https://api-rest-cliente-servico.herokuapp.com/api/clientes/ "enter the Client ID you want to update"

Example: https://api-rest-cliente-servico.herokuapp.com/api/clientes/2

Example in JSON format:

{
"nome" : "Maria",
"cpf" : "28255630058",
"servicos": [
        {
            "descricao": "Isso e um teste",
            "valor": "450"
        }
    ]
}

DELETE Method (delete):

https://api-rest-cliente-servico.herokuapp.com/api/clientes/ "enter the Client ID you want to delete"

Example: https://api-rest-cliente-servico.herokuapp.com/api/clientes/3






