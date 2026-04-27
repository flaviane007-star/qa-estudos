# Teste de API - Listagem de Usuários

## Objetivo
Validar o funcionamento do endpoint de listagem de usuários.

## Endpoint
https://jsonplaceholder.typicode.com/users

## Método
GET

## Validações realizadas
- Status code 200 OK
- Retorno de lista de usuários
- Presença dos campos obrigatórios:
  - name
  - email
  - id

## Resultado esperado
A API deve retornar uma lista de usuários com os campos corretamente preenchidos.

## Ferramenta utilizada
Postman

## Teste de erro - usuário inexistente
Endpoint:
https://jsonplaceholder.typicode.com/users/9999

Validação:
- Status 404 Not Found

## Teste de criação de usuário
Método: POST

Validações:
- Status 201 Created
- Retorno de ID
