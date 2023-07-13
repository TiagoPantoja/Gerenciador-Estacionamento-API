# Gerenciador-Estacionamento-API
Esta é uma API REST desenvolvida com o framework Spring Boot, utilizando a linguagem Java. A API é voltada para fornecer funcionalidades relacionadas ao gerenciamento de veículos no estacionamento de um condomínio.

## Tecnologias Utilizadas

- Java 17
- Spring Boot 3.1
- Spring Data JPA 3.1.1
- Maven
- HATEOAS
- Lombok
- PostgreSQL

## Pré-requisitos

- JDK 8 ou superior
- Maven

## Configuração do Projeto
1. Clone o repositório do projeto: `https://github.com/TiagoPantoja/Gerenciador-Estacionamento-API.git`
2. Navegue até o diretório raiz do projeto: `cd src`
3. Compile o projeto com o Maven: `mvn compile`
4. Execute o projeto: `mvn spring-boot:run`

A API estará disponível em `http://localhost:8080/gerenciador`

## Dependências
O projeto utiliza as seguintes dependências:

`spring-boot-starter-web`: Fornece as dependências necessárias para criar uma aplicação web com Spring Boot.

`spring-boot-devtools`: Fornece ferramentas de desenvolvimento para agilizar o processo de desenvolvimento.

`lombok`: Biblioteca que simplifica a criação de classes Java, gerando automaticamente os getters, setters, construtores e outros métodos comuns.

`spring-boot-starter-test`: Fornece as dependências necessárias para realizar testes na aplicação.

`spring-boot-starter-data-jpa`: Fornece suporte ao Spring Data JPA para persistência de dados.

## Banco de Dados
O projeto utiliza um banco de dados PostgreSQL para armazenar os dados dos médicos e dos pacientes. Certifique-se de ter um servidor PostgreSQL em execução e atualize as configurações de conexão no arquivo `application.properties` com as informações corretas do seu banco de dados.

## Executando o Projeto
Para executar o projeto, você pode utilizar o comando abaixo:

`mvn spring-boot:run`

A aplicação será iniciada e estará disponível no endereço `http://localhost:8080`.

## Endpoints
### Veículos

- `POST`: Cadastra um novo veículo com base nos dados fornecidos.
- `GET`: Lista os veículos cadastrados.
- `PUT`: Atualiza as informações de um veículo existente.
- `DELETE / {id}`: Exclui um veículo com base no seu ID.

## Estrutura do Projeto
A estrutura do projeto segue uma organização padrão do Spring Boot, onde os arquivos Java estão agrupados em pacotes de acordo com sua funcionalidade.

`controller`: Contém os controladores da API responsáveis por receber as requisições e retornar as respostas adequadas.

`endereco`: Contém as classes relacionadas aos dados de endereço.

`ApiApplication.java`: Classe principal responsável por iniciar a aplicação Spring Boot.

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request com melhorias, correções de bugs ou novos recursos.

