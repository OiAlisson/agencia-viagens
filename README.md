# API Agência de Viagens

API RESTful desenvolvida com Spring Boot, PostgreSQL, Spring Data JPA e Spring Security.

## Configuração e Execução
1. Instale o Java e o banco de dados PostgreSQL.
2. Crie um banco de dados chamado `agencia_viagens` no PostgreSQL.
3. Ajuste as credenciais (`username` e `password`) no arquivo `application.properties`.
4. Execute a aplicação.

## Usuários de Teste (Cadastrar no banco após a execução)
- Perfil Administrador: `username: admin`, `role: ADMIN`
- Perfil Usuário: `username: user`, `role: USER`

## Regras de Acesso
- `GET /destinos`: Acesso público.
- `POST, PUT, DELETE /destinos`: Restrito ao perfil ADMIN.
