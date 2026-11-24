# MyBar

Sistema Web para gerenciamento de contas de bares e restaurantes: abertura e fechamento de contas, lançamentos de itens, pagamentos e controle de cozinha e entregas.

## Funcionalidades

- Gestão de contas (abrir, lançar, fechar com gorjeta e ingresso)
- Cadastro de itens no cardápio e tipos de itens
- Controle de cozinha e de entregas
- Relatório de contas por período

## Tecnologias

Java 21, Spring Boot, Spring Data JPA (Hibernate), MySQL, HTML, CSS e Javascript

## Como executar

1. Instale o [JDK 21](http://oracle.com/java/technologies/javase/jdk21-archive-downloads.html) e o [MySQL](https://www.mysql.com/downloads/).

2. Crie o banco:
    ```sql
    CREATE DATABASE mybar CHARACTER SET utf8mb4;
    ```

3. Ajuste usuário e senha em `src/main/resources/application.properties`.

4. Execute `./mvnw spring-boot:run`

5. Acesse `http://localhost:8080/html/contas/index.html`

## Estrutura do projeto

- `docs/`: especificação de requisitos funcionais
- `src/main/java`: código-fonte (model, DAO, service, controller)
- `src/main/resources/static`: CSS, JavaScript, telas HTML e imagens

## Autores
Gustavo Alves de Araujo & Kauan Soares da Costa.

Disciplina de Programação Orientada à Objetos (POO) do Curso de Ciência da Computação da Universidade Federal do Piauí, 2026.2.