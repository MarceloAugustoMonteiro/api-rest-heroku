# apiRestHeroku
:boom: API REST com CRUD de Clientes e Serviços para teste com Heroku. :point_right:	

Testando no Postman:

Link API na nuvem com Heroku: https://api-rest-cliente-servico.herokuapp.com

Método POST (adicionar):

https://api-rest-cliente-servico.herokuapp.com/api/clientes

Exemplo em formato JSON:

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

Método GET (consultar):

https://api-rest-cliente-servico.herokuapp.com/api/clientes/"digite o ID do Cliente em que deseja consultar"

Exemplo: https://api-rest-cliente-servico.herokuapp.com/api/clientes/1

Método PUT (atualizar):

https://api-rest-cliente-servico.herokuapp.com/api/clientes/"digite o ID do Cliente em que deseja atualizar"

Exemplo: https://api-rest-cliente-servico.herokuapp.com/api/clientes/2

Exemplo em formato JSON:

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

Método DELETE (excluir):

https://api-rest-cliente-servico.herokuapp.com/api/clientes/"digite o ID do Cliente em que deseja excluir"

Exemplo: https://api-rest-cliente-servico.herokuapp.com/api/clientes/3






