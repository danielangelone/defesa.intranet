Projeto de Intranet com Spring

Este é um projeto de Intranet desenvolvido em Java com o framework Spring. A aplicação utiliza o Spring Boot para facilitar a configuração e o desenvolvimento.


Visão Geral

A aplicação de Intranet é destinada a oferecer recursos de segurança, gerenciamento de usuários e funcionalidades web para uso interno de uma organização. Ela utiliza as seguintes tecnologias e bibliotecas principais:


Spring Boot v2.5.2 para simplificar a configuração do projeto.

Spring Security v5.5.1 para controle de acesso e autenticação.

Thymeleaf v3.1.0.RELEASE como mecanismo de template para a criação de páginas web.

PostgreSQL (ou outro banco de dados compatível) para armazenamento de dados.

Pré-requisitos

Java 17

PostgreSQL (ou outro banco de dados compatível)

Maven

Configuração

Certifique-se de configurar um banco de dados PostgreSQL e ajustar as configurações de conexão no arquivo application.properties.

spring.datasource.url=jdbc:postgresql://localhost:5432/seubanco

spring.datasource.username=seuusuario

spring.datasource.password=suasenha


Executando a Aplicação

Para executar a aplicação, utilize o seguinte comando Maven:

mvn spring-boot:run


Acesse a aplicação em http://localhost:8080 no seu navegador.


Testes

A aplicação inclui testes unitários e de integração. Para executar os testes, utilize o seguinte comando:

mvn test


Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) e enviar pull requests para melhorar este projeto.


Licença

Este projeto é licenciado sob a MIT License.

