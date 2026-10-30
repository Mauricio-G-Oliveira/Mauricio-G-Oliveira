<div align="center">

# Olá, sou Maurício Oliveira 👋
### **Senior Software Engineer & Java Software Architect**
*Especialista em Sistemas Financeiros Transacionais, Arquitetura Distribuída, Alta Concorrência, Clean Architecture e DDD*

[![Java 21](https://img.shields.io/badge/Java-21_LTS-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://openjdk.org/)
[![Spring Boot 3](https://img.shields.io/badge/Spring_Boot-3.3.4-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)](https://spring.io/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![React](https://img.shields.io/badge/React-18_%2F_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)

<br/>

> *"Em sistemas de missão crítica, a integridade matemática dos dados, a idempotência e a ausência de deadlocks não são detalhes de implementação: são os alicerces fundamentais da arquitetura de software."*

</div>

---

## 🏛️ Sobre Mim & Perfil de Engenharia

Engenheiro de Software com forte atuação no ecossistema **Java Enterprise (Java 21 + Spring Boot 3)** e arquitetura de microsserviços. Construo soluções voltadas para alta vazão, conformidade regulatória, integridade contábil e resiliência:

* 🛡️ **Concorrência de Baixo Nível & Bancos de Dados:** Isolamento transacional ACID, eliminação de deadlocks via ordenação determinística de travas pessimistas (`SELECT FOR UPDATE`), controle de concorrência otimista (`@Version`) e bancos de alta escala (**PostgreSQL 16** com **Flyway**).
* ⚡ **Core Banking & Engenharia Financeira:** Domínio estrito de **Partidas Dobradas (Double-Entry Bookkeeping)**, garantia do invariante contábil ($\sum \text{Débitos} = \sum \text{Créditos}$) e execução única (**Idempotência com chaves UUIDv7**).
* 📐 **Arquitetura Limpa & DDD:** Modelagem orientada a domínio puro (**Domain-Driven Design**), Arquitetura Hexagonal (Ports & Adapters) e enforcement arquitetural automatizado com **ArchUnit**.
* 🧪 **Qualidade Industrial:** Testes de integração de alta fidelidade com **Testcontainers** simulando concorrência real e contêineres efêmeros.

---

## 🌟 Projetos em Destaque (Featured Engineering Showcase)

<div align="center">

### 1. 🏦 [Fintech Core Ledger & Instant Payment Engine](https://github.com/Mauricio-G-Oliveira/fintech-core-ledger)
**Motor de Liquidação Financeira Instantânea, Conciliação e Ledger Imutável por Partidas Dobradas**

[![Live Demo](https://img.shields.io/badge/Aplicação_Online-Acessar_Simulador_Live-10B981?style=for-the-badge&logo=github&logoColor=white)](https://mauricio-g-oliveira.github.io/fintech-core-ledger/)
[![GitHub Repo](https://img.shields.io/badge/Repositório-Ver_Código_Fonte-black?style=for-the-badge&logo=github)](https://github.com/Mauricio-G-Oliveira/fintech-core-ledger)
[![PRs Merged](https://img.shields.io/badge/Gitflow-4_PRs_Merged-8957E5?style=for-the-badge&logo=git&logoColor=white)](https://github.com/Mauricio-G-Oliveira/fintech-core-ledger/pulls?q=is%3Apr)

</div>

* **Arquitetura Limpa & DDD:** Domínio contábil puro isolado de dependências externas (`Money`, `Account`, `LedgerTransaction`, `LedgerEntry`).
* **Double-Entry Bookkeeping:** Nenhuma conta sofre mutação direta; toda transação gera pernas imutáveis onde $\sum \text{DR} = \sum \text{CR}$ ($\Delta = \text{R\$} \, 0{,}00$).
* **Deadlock-Free Locking:** Ordenação determinística de contas antes do bloqueio pessimista (`SELECT FOR UPDATE`), eliminando colisões de concorrência cruzada.
* **Garantia de Idempotência:** Interceptor com chave `X-Idempotency-Key` (UUIDv7) para anular retentativas duplicadas de gateways.
* **Simulador Live no GitHub Pages:** Interface interativa com teste de colisão em tempo real (5 requisições concorrentes simultâneas).
* **Tech Stack:** Java 21 LTS, Spring Boot 3.3.4, PostgreSQL 16, Flyway, Testcontainers, ArchUnit, React, Vite, Tailwind CSS.

---

<div align="center">

### 2. 🎛️ [StageFlow Platform • Ecosystem Full-Stack Cloud](https://github.com/Mauricio-G-Oliveira/stageflow)
**Plataforma Completa na Nuvem para Gestão de Palco, Músicos, Repertório e Contratos**

[![Live Demo](https://img.shields.io/badge/Aplicação_Online-Acessar_PWA_Cloud-5A0FC8?style=for-the-badge&logo=github&logoColor=white)](https://mauricio-g-oliveira.github.io/stageflow/)
[![Frontend Repo](https://img.shields.io/badge/Frontend-React_19_TypeScript-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://github.com/Mauricio-G-Oliveira/stageflow)
[![Backend Repo](https://img.shields.io/badge/Backend-Java_21_Spring_Boot_3-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://github.com/Mauricio-G-Oliveira/stageflow-backend)

</div>

* **Sistema 100% Completo & Deploy em Nuvem:** Ecossistema desacoplado operando em produção com comunicação via API RESTful segura.
* **Backend Enterprise:** Java 21 LTS, Spring Boot 3.3.4, Spring Security com autenticação JWT sem estado, PostgreSQL e Docker.
* **Frontend Moderno:** React 19.2, TypeScript 6, Tailwind CSS v4 e PWA instalável com suporte offline e responsividade total.
* **Destaques:** Gestão de cachês, geração automática de propostas comerciais em PDF, controle de setlist em tempo real e sincronização de eventos.

---

<div align="center">

### 3. 💎 [MakerPixel Gestão Financeira, Inteligência Fiscal & PWA](https://github.com/Mauricio-G-Oliveira/makerpixel-gestao)
**Plataforma Corporativa de Gestão Financeira, Conciliação Multi-Extrato & Compliance Tributário**

[![Live Demo](https://img.shields.io/badge/Aplicação_Online-Acessar_Demonstração-00E5FF?style=for-the-badge&logo=github&logoColor=black)](https://mauricio-g-oliveira.github.io/makerpixel-gestao/)
[![GitHub Repo](https://img.shields.io/badge/Repositório-Ver_Código_Fonte-black?style=for-the-badge&logo=github)](https://github.com/Mauricio-G-Oliveira/makerpixel-gestao)
[![Tests Passing](https://img.shields.io/badge/Tests-226_Passing_(100%25)-10B981?style=for-the-badge&logo=node.js&logoColor=white)](https://github.com/Mauricio-G-Oliveira/makerpixel-gestao)

</div>

* **Conciliação Bancária Multi-Extrato:** Parser inteligente de arquivos OFX e extratos em lote com conciliação automática de lançamentos.
* **Inteligência Fiscal & Tributária:** Conformidade com ICMS e adaptação para a **Reforma Tributária (LC 214/2025)**.
* **Integração Oficial com ERP Contábil:** Exportação compatível com o sistema contábil **SCI Único**.
* **Segurança e Privacidade:** Criptografia client-side com PBKDF2 (100k iterações) e total aderência à LGPD.

---

## 🛠️ Competências & Arsenal Tecnológico

| Categoria | Tecnologias & Práticas de Engenharia |
| :--- | :--- |
| **Linguagens & Runtimes** | Java 21 LTS (Virtual Threads, Records, Sealed Classes, Pattern Matching), TypeScript, SQL ANSI |
| **Frameworks & Core** | Spring Boot 3.3, Spring Data JPA, Spring Security, Spring Validation, Actuator, Hibernate 6 |
| **Concorrência & Transações** | Pessimistic Lock (`SELECT FOR UPDATE`), Optimistic Lock (`@Version`), Double-Entry Bookkeeping, Idempotência (UUIDv7) |
| **Bancos de Dados & Cache** | PostgreSQL 16, Flyway Migrations, Redis (Distributed Locks), HikariCP (Connection Pool) |
| **Mensageria & Streaming** | Apache Kafka, Event-Driven Architecture, Outbox Pattern |
| **Qualidade & Testes** | Testcontainers (Real Container Testing), ArchUnit (Architectural Rules), JUnit 5, Mockito |
| **DevOps & Cloud** | Docker, Docker Compose, Gitflow (Feature Branches & PRs), GitHub Actions CI/CD |
| **Frontend & Mobile Web** | React 18 / 19, TypeScript, Vite, Tailwind CSS (v3 e v4), Progressive Web Apps (PWA) |

---

## 📊 Estatísticas do GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Mauricio-G-Oliveira&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0b0f19&title_color=10b981&text_color=94a3b8&icon_color=06b6d4" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mauricio-G-Oliveira&layout=compact&theme=tokyonight&hide_border=true&bg_color=0b0f19&title_color=10b981&text_color=94a3b8" alt="Top Languages" width="45%" />
</div>

---

<div align="center">
  <p>💼 Aberto a oportunidades de alto impacto como <strong>Senior Software Engineer</strong> e <strong>Java Software Architect / Tech Lead</strong>.</p>
</div>
