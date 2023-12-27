INSTALLS - npm install --global http-server

CONCEITOS:

Requisição HTTP

URL: https://pokeapi.co/api/v2/pokemon/${id}
${IP = Endereço}/${path = Caminho de identificação do recurso}

IP: https://pokeapi.co
http://127.0.0.1:3000

Path: /api/v2/pokemon

Request Method: GET | POST | PUT | DELETE | PATCH

Querry String:

https://pokeapi.co/api/v2/pokemon?type=grass&name=i
type = grass
name = i

Request Headers:
Como a requisição está configurada

accept-language:
pt-BR
pt;q=0.9
en-US;q=0.8
en;q=0.7

Authorization: Basic | Bearer

Response Headers:
Como a resposta está configurada

EXEMPLO DE BODY:
Request Headers
content-type: application/json

BODY
{
"name": "Teste"
}

EXEMPLO DE REQUISIÇÃO:

URL: http://pokeapi.co/api/v2/pokemon

REQUEST METHOD: GET | POST | PUT | DELETE

REQUEST HEADERS
content-type: application/json

REQUEST BODY
{
"name": "Teste"
}

STATUS CODE: 200 OK

RESPONSE HEADERS

RESPONSE BODY
