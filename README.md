Repositório para consulta de casas

Url base = http://localhost:3001

POST /register = Faz o cadastro do usuário sendo obrigatório o corpo receber email e password

POST /login = Faz o login do usuário, no corpo deve receber email e password

GET /cities = Busca por todas as cidades (Não precisa de usuario estar logado)

GET /houses = Busca por todas as casas (Necessita do token de usuário logado)
