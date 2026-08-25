<<<<<<< HEAD
# Skeleton

Projeto baseado no roadmap. TODOs apenas.
=======
# 🏥 Medical Scheduling System

Um sistema de agendamento de consultas médicas desenvolvido em **Go (Golang)**, seguindo princípios de Clean Architecture e boas práticas de desenvolvimento backend.

> Este projeto está sendo desenvolvido para fins de estudo e portfólio, simulando um sistema utilizado por clínicas médicas para gerenciamento de pacientes, médicos, consultas e prontuários eletrônicos.

---

## 🚀 Tecnologias

- Go
- PostgreSQL
- Chi Router
- JWT
- SQLC / PGX
- Docker
- Docker Compose
- Golang Migrate
- Testify
- Swagger (OpenAPI)

---

## 📁 Arquitetura

```
cmd/
internal/
 ├── domain/
 ├── repository/
 ├── service/
 ├── handler/
 ├── middleware/
 ├── config/
 └── routes/
migrations/
pkg/
```

O projeto segue uma arquitetura em camadas:

```
HTTP
   │
Handler
   │
Service
   │
Repository
   │
PostgreSQL
```

Cada camada possui responsabilidade única, facilitando manutenção, testes e evolução da aplicação.

---

# Funcionalidades

## 👤 Pacientes

- Cadastro
- Atualização
- Exclusão
- Histórico

## 👨‍⚕️ Médicos

- Cadastro
- Especialidades
- Disponibilidade

## 📅 Consultas

- Agendamento
- Remarcação
- Cancelamento
- Controle de status
- Validação de conflitos de horário

## 📄 Prontuário

- Registro clínico
- Diagnóstico
- Prescrição
- Histórico por paciente

## 🔐 Autenticação

- Login JWT
- Controle de acesso por perfil
- Admin
- Médico
- Recepção

---

## Roadmap

- [x] Estrutura inicial
- [ ] CRUD de Pacientes
- [ ] CRUD de Médicos
- [ ] Disponibilidade
- [ ] Agendamento
- [ ] Prontuário
- [ ] Autenticação
- [ ] Testes
- [ ] Documentação Swagger

---

## Objetivo

O principal objetivo deste projeto é aprofundar conhecimentos em:

- Go
- APIs REST
- Arquitetura em Camadas
- Clean Architecture
- PostgreSQL
- Docker
- Testes
- SQL

---

## Status

🚧 Em desenvolvimento.

Este repositório está sendo utilizado como projeto de estudos e portfólio.
>>>>>>> c698dc3fbb3c0730deaeade40b03a0553f0fab32
