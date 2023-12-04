# resumoApiREST

# Api REST e RESTFul
API REST é um estilo arquitetural para projetar serviços web, baseado nos princípios da arquitetura REST.
REST é um acrônimo para Representational State Transfer, que enfatiza a representação dos recursos e a transferência de estado entre o cliente e o servidor.

## Diferenças entre REST e RESTFul
API REST:
Definição Genérica: "API REST" é um termo amplo que se refere a qualquer interface de programação de aplicativos que segue os princípios da arquitetura REST.
Pode não seguir todos os princípios: Uma API REST pode aderir apenas parcialmente aos princípios REST,
e algumas implementações podem incluir características que não são puramente RESTful.
Uso Genérico: O termo não impõe regras específicas sobre como a API deve ser projetada ou implementada.

RESTful:
Implementação Concreta: "RESTful" é um termo mais específico que descreve uma implementação que segue rigorosamente os princípios da arquitetura REST.
Segue Princípios REST: Uma API RESTful adere completamente aos princípios do REST,
como identificação de recursos, representação de recursos, interação sem estado e manipulação de recursos por meio de verbos HTTP.
Estrutura Padronizada: Geralmente, uma API RESTful segue um conjunto de padrões e convenções bem definidos para facilitar a compreensão e o uso.****

## HTTP verbs
GET:
Utilizado para solicitar a representação de um recurso.
Exemplo: GET /users/123

POST:
Utilizado para enviar dados ao servidor para criar um novo recurso.
Exemplo: POST /users

PUT:
Utilizado para atualizar um recurso existente ou criar um novo se não existir.
Exemplo: PUT /users/123
DELETE:
Utilizado para remover um recurso.
Exemplo: DELETE /users/123

PATCH:
Utilizado para aplicar modificações parciais a um recurso.
Exemplo: PATCH /users/123

OPTIONS:
Utilizado para obter as opções de comunicação disponíveis para um recurso ou servidor.
Exemplo: OPTIONS /users

HEAD:
Similar ao GET, mas usado para obter apenas os cabeçalhos (headers) de resposta, sem o corpo da resposta.
Exemplo: HEAD /users/123

TRACE:
Utilizado para solicitar que o servidor retorne o que recebeu, útil para depuração.
Exemplo: TRACE /debug

CONNECT:
Utilizado para estabelecer uma conexão de túnel com o servidor identificado pelo recurso.
Exemplo: CONNECT /example.com:80

## HTTP Status Code
códigos de status HTTP (HTTP status codes) são números de três dígitos que indicam o resultado de uma solicitação HTTP.
Eles são retornados pelo servidor para informar ao cliente sobre o sucesso, falha ou necessidade de ações adicionais na solicitação.

1xx (Informational): Indica que a solicitação foi recebida, continua o processo, ou o cliente deve aguardar.
Exemplos: 100 Continue, 101 Switching Protocols.

2xx (Successful): Indica que a solicitação foi recebida, compreendida e aceita com sucesso.
Exemplos: 200 OK, 201 Created, 204 No Content.

3xx (Redirection): Indica que mais ações precisam ser tomadas para completar a solicitação.
Exemplos: 301 Moved Permanently, 302 Found, 304 Not Modified.

4xx (Client Error): Indica que o cliente fez uma solicitação inválida.
Exemplos: 400 Bad Request, 401 Unauthorized, 403 Forbidden, 404 Not Found.

5xx (Server Error): Indica que houve um erro no servidor ao processar a solicitação.
Exemplos: 500 Internal Server Error, 502 Bad Gateway, 503 Service Unavailable.

---
Autor do resumo: Vinicius L A de H Borba - 01556075
