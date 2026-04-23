# Cenários de Teste - Login

## Caso 1 - Login válido
Dado que o usuário possui cadastro válido
Quando ele insere login e senha corretos
Então deve acessar o sistema

## Caso 2 - Senha inválida
Dado que o usuário possui cadastro válido
Quando ele insere senha incorreta
Então deve exibir mensagem de erro

## Caso 3 - Usuário inexistente
Então deve exibir mensagem de usuário inválido

## Caso 4 - Campo vazio
Dado que o usuário não preenche login e senha
Quando tenta acessar
Então deve exibir mensagem de campos obrigatórios
