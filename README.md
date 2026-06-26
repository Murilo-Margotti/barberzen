# BarberZen

BarberZen é um sistema de gerenciamento para barbearias desenvolvido em Java 21.

O projeto nasceu com dois objetivos principais:

* Resolver um problema real de agendamento e gestão de clientes para pequenas barbearias.
* Servir como projeto de estudo e portfólio durante minha jornada para me tornar desenvolvedor Back-end.

Ao invés de depender de frameworks desde o início, o foco deste projeto é aprender e aplicar fundamentos sólidos de desenvolvimento de software, construindo a aplicação de forma evolutiva.

---

## Objetivos do Projeto

* Praticar programação orientada a objetos (POO)
* Aplicar boas práticas de desenvolvimento
* Trabalhar com persistência de dados
* Desenvolver uma arquitetura organizada e escalável
* Evoluir gradualmente para tecnologias utilizadas no mercado

Este projeto será desenvolvido em etapas, permitindo acompanhar a evolução da aplicação desde uma versão simples em console até uma API completa.

---

## Tecnologias

### Versão Atual

* Java 21
* Maven
* Git
* GitHub
* Jackson (JSON)

### Tecnologias Planejadas

* PostgreSQL
* JDBC
* Spring Boot
* Docker

---

## Funcionalidades Planejadas

### Clientes

* Cadastro de clientes
* Consulta de clientes
* Atualização de cadastro
* Exclusão de clientes

### Agendamentos

* Criação de agendamentos
* Cancelamento de agendamentos
* Consulta da agenda
* Controle de horários disponíveis

### Regras de Negócio

* Impedir horários duplicados
* Validar clientes cadastrados
* Impedir agendamentos em datas passadas
* Respeitar horário de funcionamento

---

## Roadmap

### Fase 1 - Aplicação Console

* Estrutura do projeto
* Modelagem das entidades
* Persistência em arquivos JSON
* Serviços e regras de negócio
* Menu interativo via terminal

### Fase 2 - Banco de Dados

* Integração com PostgreSQL
* Persistência utilizando JDBC
* Refatoração da camada de dados

### Fase 3 - API REST

* Migração para Spring Boot
* Endpoints REST
* Validações e tratamento de erros

### Fase 4 - Deploy e Containerização

* Docker
* Banco de dados containerizado
* Preparação para ambiente de produção

---

## Estrutura Inicial

```text
src
└── main
    └── java
        └── com.barberzen
            ├── model
            ├── repository
            ├── service
            ├── util
            └── app
```

---

## Status

🚧 Em desenvolvimento

Primeira versão sendo construída com foco em aprendizado, organização de código e evolução contínua.

---

## Autor

Murilo Margotti

Estudante de Engenharia de Software com foco em desenvolvimento Back-end Java.
