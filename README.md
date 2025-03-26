# Back-end do Jarvis

[![Java](https://img.shields.io/badge/Java-17-blue)](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.5.4-brightgreen)](https://spring.io/projects/spring-boot)
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

## Descrição

Este projeto é um sistema de gerenciamento de tarefas pensado especialmente para indivídups neurodivergente. O sistema permite aos usuários criar, editar e excluir tarefas, objetivos e etiquetas. Além disso, oferece funcionalidades de lembretes com notificações via SMS (WhatsApp) e Amazon Alexa, integrando-se a serviços externos para envio dessas notificações.

## Funcionalidades

- **Gerenciamento de Tarefas:** Criação, edição, visualização e exclusão de tarefas.
- **Subtarefas:** Associação de subtarefas a tarefas principais.
- **Objetivos (Goals):** Definição e acompanhamento de objetivos relacionados às tarefas.
- **Etiquetas (Labels):** Categorização de tarefas por meio de etiquetas personalizadas.
- **Lembretes (Reminders):** Agendamento de lembretes com notificações via WhatsApp e Amazon Alexa.
- **Autenticação e Autorização:** Sistema de login seguro utilizando JWT.
- **Integrações:** Configuração de integrações com serviços externos como WhatsApp e Amazon Alexa.

## Tecnologias Utilizadas

- **Java 17**
- **Spring Boot 2.5.4**
- **Banco de Dados:** SQL Server
- **APIs Externas:** Integração com APIs do WhatsApp e Amazon Alexa para envio de notificações.

## Pré-requisitos

Antes de iniciar, certifique-se de que possui os seguintes requisitos instalados:

- [Java 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html) ou superior.
- [Docker](https://www.docker.com/get-started) (opcional, para execução do banco de dados em contêiner).
- IDE de sua preferência (recomendado: [IntelliJ IDEA](https://www.jetbrains.com/idea/download/)).
