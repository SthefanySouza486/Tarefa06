# 📝 Lista de Tarefas 06 (Full Stack)
Projeto full-stack de um sistema simples de "Lista de Tarefas" (To-Do List), utilizando Spring Boot no backend e Vue.js no frontend.

Este projeto implementa um CRUD (Create, Read, Update, Delete) completo para gerenciar tarefas, com o frontend consumindo a API REST criada no backend. A comunicação é habilitada via CORS.


## 🚀 Tecnologias Utilizadas
Este projeto é dividido em duas partes principais:

**Backend (API)**
- Java 17
- Spring Boot 3
- Spring Web: Para criação de controladores REST.
- Spring Data JPA: Para persistência de dados.
- H2 Database: Banco de dados em memória para desenvolvimento.
- Maven: Gerenciador de dependências.

**Frontend**
- Vue.js: Framework JavaScript progressivo.
- JavaScript (ES6+)
- HTML5 / CSS3
- Axios: (Implícito pelo tarefaService.js) Para realizar chamadas HTTP à API.


## ✨ Funcionalidades Principais
- Listar: Visualizar todas as tarefas cadastradas.
- Criar: Adicionar uma nova tarefa à lista.
- Marcar como Concluída: Atualizar o status de uma tarefa para "concluída".
- Excluir: Remover uma tarefa da lista.


## ⚙️ Como Executar o Projeto
Você precisará de dois terminais abertos para executar o backend e o frontend separadamente.

**Pré-requisitos:**
- JDK 17 (ou superior)
- Maven
- Node.js e npm
-
**1.** Executando o Backend (API)

      1. Navegue até a raiz do projeto (onde está o pom.xml).
      
      2. Instale as dependências e inicie o servidor Spring Boot:
      
      ```bash
      ./mvnw spring-boot:run
      ```
      
      3. O backend estará em execução na porta http://localhost:8080.

      
**2.** Executando o Frontend (Vue.js)

     1. Abra um novo terminal.
     
     2. Navegue até a pasta do frontend:
     
     ```bash
     cd frontend/app-tarefas
     ```
     
     3. Instale o http-server (se ainda não o tiver) e inicie-o:
     
     ```bash
     # Instala o servidor (apenas na primeira vez)
     npm install -g http-server

     # Inicia o servidor na porta 8081
     http-server -p 8081
     ```
  
      4. Acesse a aplicação no seu navegador:http://localhost:8081
  

## 📋 Endpoints da API (Backend)

<img width="595" height="184" alt="image" src="https://github.com/user-attachments/assets/00bb9bb3-1421-4282-b993-0dc3dfff7973" />


## 👤 Autor
- Sthefany Souza
- GitHub: https://github.com/SthefanySouza486
