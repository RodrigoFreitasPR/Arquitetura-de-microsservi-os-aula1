_Demo Spring Boot Application_


Esta é uma aplicação simples desenvolvida com Spring Boot que oferece uma API REST básica.

Endpoints
1. GET /api/hello
Retorna uma mensagem simples: "Hello World!"
2. GET /api/soma?a=2&b=3
Recebe dois parâmetros a e b e retorna a soma dos valores.
Exemplo de resposta: "Soma: 5"

_Passos_

Clone o repositório

Execute a aplicação com o comando: mvn spring-boot:run

A aplicação estará rodando em http://localhost:8080

_Teste os Endpoints_


GET /api/hello: Visite http://localhost:8080/api/hello no seu navegador ou use uma ferramenta como Postman.


GET /api/soma?a=2&b=3: Visite http://localhost:8080/api/soma?a=2&b=3 para ver o resultado da soma.
