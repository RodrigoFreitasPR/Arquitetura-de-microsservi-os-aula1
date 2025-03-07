Demo Spring Boot Application
Esta é uma aplicação simples desenvolvida com Spring Boot que oferece uma API REST básica.

Endpoints
1. GET /api/hello
Retorna uma mensagem simples: "Hello World!"
2. GET /api/soma?a=2&b=3
Recebe dois parâmetros a e b e retorna a soma dos valores.
Exemplo de resposta: "Soma: 5"
Como Executar a Aplicação
Pré-requisitos
Java 8 ou superior instalado.
Maven instalado.
Passos
Clone o repositório:

bash
Copiar
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
Execute a aplicação com o comando:

bash
Copiar
mvn spring-boot:run
Ou, se preferir, compile o projeto e execute o arquivo JAR gerado:

bash
Copiar
mvn clean package
java -jar target/demo-0.0.1-SNAPSHOT.jar
A aplicação estará rodando em http://localhost:8080.

Teste os Endpoints
GET /api/hello: Visite http://localhost:8080/api/hello no seu navegador ou use uma ferramenta como Postman.
GET /api/soma?a=2&b=3: Visite http://localhost:8080/api/soma?a=2&b=3 para ver o resultado da soma.
