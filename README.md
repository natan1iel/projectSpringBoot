# 📝 ToDoList API

![Java](https://img.shields.io/badge/Java-17+-red?style=for-the-badge)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen?style=for-the-badge)
![Maven](https://img.shields.io/badge/Maven-4.0.0-blue?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-ready-2496ED?style=for-the-badge)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow?style=for-the-badge)

> Projeto desenvolvido durante um **minicurso da Rocketseat**, com o objetivo de criar uma **API REST para gerenciamento de tarefas (To-Do List)** utilizando **Java e Spring Boot**.

---

## 🚀 Tecnologias utilizadas
- **Java 17+**
- **Spring Boot**
- **Spring Web**
- **Spring Data JPA**
- **H2 Database** (ou outro configurado em `application.properties`)
- **Maven**
- **Docker**

---

## ⚙️ Funcionalidades
✅ Cadastro e autenticação de usuários  
✅ Criação, atualização, listagem e exclusão de tarefas  
✅ Filtro de autenticação para proteger rotas  
✅ Tratamento centralizado de erros  
✅ Estrutura modular e organizada  

---

## 📁 Estrutura do projeto
src/
├─ main/java/br/com/nataniel/todolist
│ ├─ user/ → Controle e persistência de usuários
│ ├─ task/ → CRUD de tarefas
│ ├─ filter/ → Filtros de autenticação
│ ├─ errors/ → Manipulação de exceções
│ ├─ utils/ → Funções auxiliares
│ └─ TodolistApplication.java
└─ resources/
└─ application.properties


---

## 🧩 Endpoints principais
| Método | Endpoint | Descrição |
|:-------:|:----------|:-----------|
| `POST` | `/users` | Cadastra um novo usuário |
| `POST` | `/tasks` | Cria uma nova tarefa |
| `GET`  | `/tasks` | Lista todas as tarefas do usuário |
| `PUT`  | `/tasks/{id}` | Atualiza uma tarefa existente |
| `DELETE` | `/tasks/{id}` | Remove uma tarefa |

---

## 🐳 Docker
Para executar o projeto via Docker:

```bash
# Build da imagem
docker build -t todolist-api .

# Execução do container
docker run -p 8080:8080 todolist-api

📚 Origem

Este projeto foi desenvolvido durante um minicurso da Rocketseat, com o intuito de praticar conceitos fundamentais de APIs REST com Spring Boot, autenticação, e boas práticas de organização de código.

👨‍💻 Autor
Nataniel Oliveira
📧 Contato: onataniel@ymail.com
🌐 GitHub: https://github.com/natan1iel
