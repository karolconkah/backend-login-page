Sistema de Autenticação Full Stack

Aplicação Full Stack composta por frontend em Angular 17 e backend em Spring Boot (Java), implementando autenticação baseada em JWT e comunicação via API REST.

Visão Geral

O projeto consiste em uma aplicação de autenticação com separação clara entre frontend e backend, utilizando arquitetura REST, validação de dados e controle de acesso baseado em token.

A aplicação foi desenvolvida com foco em organização modular, boas práticas e estrutura em camadas.

Tecnologias Utilizadas
Frontend

Angular 17

TypeScript

Reactive Forms

Componentes Standalone

Consumo de API via HTTP Client

Gerenciamento de dependências com npm

Backend

Java

Spring Boot

Spring Security

JWT (JSON Web Token)

JPA

H2 Database (em memória)

Funcionalidades
Backend

API REST para autenticação

Geração e validação de token JWT

Controle de acesso com Spring Security

Configuração de CORS

Estrutura em camadas (Controller, Service, Repository)

Uso de DTOs para transferência de dados

Persistência utilizando H2 em memória

Frontend

Tela de login com validação utilizando Reactive Forms

Integração com API backend

Tratamento de erros de autenticação

Organização modular com componentes standalone

Segurança

A autenticação foi implementada utilizando JWT, com geração de token no login e validação para acesso às rotas protegidas. O modelo adotado é stateless.

Banco de Dados

Foi utilizado H2 Database em memória para persistência durante o desenvolvimento, permitindo testes rápidos sem necessidade de instalação de banco externo.

Objetivo do Projeto

Prática de desenvolvimento Full Stack com foco em:

Integração frontend e backend

Segurança com autenticação baseada em token

Estruturação profissional de projetos

Aplicação de conceitos REST

Organização modular no Angular

Como Executar
Backend (Spring Boot)
cd backend
mvn spring-boot:run

A aplicação iniciará em:

http://localhost:8080

Frontend (Angular 17)
cd frontend
npm install
ng serve

A aplicação estará disponível em:

http://localhost:4200

Observação

O backend deve estar rodando antes de iniciar o frontend.

O banco utilizado é H2 em memória (não requer instalação).

Este projeto backend em Spring e Java foi integrado com o frontend disponível como login-page
