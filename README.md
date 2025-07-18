🩺 Voll.med API - Sistema de Gestão para Clínicas Médicas
Este projeto é uma API REST desenvolvida em Java com Spring Boot para gerenciar os recursos de uma clínica médica. Ele faz parte de um estudo prático voltado para o domínio de desenvolvimento backend com foco em boas práticas como arquitetura limpa, MVC, e uso de padrões do Spring.

⚙️ Tecnologias Utilizadas
Java 17+

Spring Boot

Spring Data JPA

Hibernate

H2 (ou PostgreSQL, dependendo do ambiente)

Maven

Lombok

Swagger/OpenAPI (para documentação da API)

Testes com JUnit

🧱 Estrutura do Projeto
O projeto segue a arquitetura MVC:

rust
Copiar
Editar
src/
├── controller     -> Camada responsável pelos endpoints REST
├── service        -> Camada de regras de negócio
├── repository     -> Acesso a dados (JPA)
├── domain/model   -> Entidades do banco
├── dto            -> Objetos de transferência de dados
├── config         -> Configurações do projeto (ex: Swagger)
└── exception      -> Tratamento de erros e exceções personalizadas

📌 Funcionalidades da API
 Cadastro de médicos

 Atualização de dados de médicos

 Listagem paginada de médicos ativos

 Inativação de médicos (delete lógico)

 Cadastro de pacientes

 Agendamento de consultas

 Cancelamento de consultas

 Autenticação com Spring Security

 Upload de documentos médicos (em desenvolvimento)

 🙋‍♂️ Autor
João Lopes – @seu-linkedin
Desenvolvedor backend apaixonado por boas práticas de código e sistemas limpos.
