Login Page Backend API

API REST desenvolvida com Spring Boot responsável por autenticação de usuários, geração de JWT e persistência de dados em PostgreSQL.

Deploy em produção:
https://backend-login-page-abnx.onrender.com

Descrição

Backend responsável por:

Cadastro de usuários

Login com autenticação

Geração e validação de token JWT

Proteção de rotas com Spring Security

Integração com banco PostgreSQL (Supabase)

Endpoints Principais

POST /auth/register
Responsável pelo cadastro de novo usuário.

POST /auth/login
Responsável pela autenticação e geração do token JWT.

GET /health
Endpoint público para verificação de status da aplicação.

Tecnologias Utilizadas

Java

Spring Boot

Spring Security

JWT

PostgreSQL

Supabase

Autenticação

Após login válido, o backend gera um token JWT que deve ser enviado nas requisições protegidas via header Authorization.

Banco de Dados

O banco utilizado é PostgreSQL hospedado no Supabase.

Como rodar localmente

No ambiente de desenvolvimento é utilizado um banco de dados em memória chamado H2. Porém é possível configurar variáveis de ambiente do banco utilizado em produção

Executar:

./mvnw spring-boot:run

A API ficará disponível em:

http://localhost:8080
