# 🧪 API REST com Spring Boot

Este projeto é uma API REST simples feita com Spring Boot que gerencia usuários (User) em memória. A API permite criar, listar, atualizar e remover usuários via requisições HTTP.

---

## ✅ Tecnologias utilizadas

- Java
- Spring Boot
- Spring Web (starter)
- Postman (para testes)

---

## 🚀 Como rodar o projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/NicolleMP/RestAPI-SpringBoot.git
   cd RestAPI-SpringBoot
2. Abra o projeto e executa a classe:
    ```bash
   DemonApplication.java
3. API disponível em:
   ```bash
   hhtp://localhost:8080

 ---

 ## 📦 Endpoints da API

 - GET/users - Lista todos os usuários.
 - POST/users - Cria um novo usuário.
 - PUT/users/{id} - Atualiza um usuário que já existe.
 - DELETE/users/{id} - Remove um usuário pelo ID.

   * Os IDs são gerados automaticamente

 ---

 ## 🔍 Testes com Postman

1. Abra o Postman.
2. Crie uma nova requisição com o método que deseja.
3. Use a URL http://localhost:8080/users.
4. Selecione a opção body > raw > JSON.
5. Realize os testes.

 
