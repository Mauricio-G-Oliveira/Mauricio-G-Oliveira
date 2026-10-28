<div align="center">

# Olá, sou Maurício Oliveira 👋
### **Senior Software Engineer & Java Software Architect**
*Especialista em Sistemas Financeiros Transacionais, Motores de Liquidação de Alta Concorrência, Clean Architecture e DDD*

[![Java 21](https://img.shields.io/badge/Java-21_LTS-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://openjdk.org/)
[![Spring Boot 3](https://img.shields.io/badge/Spring_Boot-3.3.4-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)](https://spring.io/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Kafka](https://img.shields.io/badge/Apache_Kafka-Event--Driven-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)](https://kafka.apache.org/)
[![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)

<br/>

> *"Em sistemas financeiros e de missão crítica, a corretude matemática, a idempotência e a ausência de deadlocks não são opcionais: são os alicerces fundamentais da arquitetura."*

</div>

---

## 🏛️ Sobre Mim & Perfil de Engenharia

Engenheiro de Software Sênior com sólida vivência no ecossistema **Java Enterprise (Java 21 + Spring Boot 3)**, focado na concepção e sustentação de backends transacionais de alta vazão, integridade contábil e resiliência:

* 🛡️ **Engenharia de Concorrência & Dados:** Experiência prática com isolamento de transações ACID, estratégias anti-deadlock via ordenação determinística de locks pessimistas (`SELECT FOR UPDATE`), concorrência otimista (`@Version`) e bancos relacionais em grande escala (**PostgreSQL 16** com migrações **Flyway**).
* ⚡ **Sistemas Financeiros & Core Ledger:** Domínio profundo de **Partidas Dobradas (Double-Entry Bookkeeping)**, conformidade com regras contábeis bancárias (invariante contábil estrita $\sum \text{Débitos} = \sum \text{Créditos}$), pipelines de conciliação e garantia de execução única (**Idempotência com chaves UUIDv7**).
* 📐 **Design de Software Limpo:** Aplicação rigorosa de **Domain-Driven Design (DDD)**, **Clean Architecture / Arquitetura Hexagonal** e enforcement contínuo de barreiras de domínio via **ArchUnit**.
* 🧪 **Qualidade Industrial:** Testes de integração de alta fidelidade simulando concorrência real e contenção de banco com **Testcontainers**.

---

## 🌟 Projeto Destaque (Flagship Architecture)

### 🏦 [Fintech Core Ledger & Instant Payment Engine](https://github.com/Mauricio-G-Oliveira/fintech-core-ledger)
> **Motor de Liquidação Financeira Instantânea, Conciliação e Ledger Imutável por Partidas Dobradas**

[![Live Demo](https://img.shields.io/badge/Aplicação_Online-Acessar_Simulador_Live-10B981?style=for-the-badge&logo=github&logoColor=white)](https://mauricio-g-oliveira.github.io/fintech-core-ledger/)
[![GitHub Repo](https://img.shields.io/badge/Repositório-Ver_Código_Fonte-black?style=for-the-badge&logo=github)](https://github.com/Mauricio-G-Oliveira/fintech-core-ledger)

* **Arquitetura Limpa:** Desacoplamento estrito entre Domínio Contábil puro, Casos de Uso, Infraestrutura e Controladores REST.
* **Double-Entry Bookkeeping:** Nenhuma mutação de saldo sem pernas balanceadas de Débito (DR) e Crédito (CR).
* **Deadlock-Free Locking:** Ordenação lexicográfica de contas no banco para mitigar 100% de deadlocks em transferências concorrentes cruzadas ($A \to B$ e $B \to A$).
* **Filtro de Idempotência:** Interceptor de requisições com cache transacional para anular impactos de timeouts e retentativas de rede.
* **Simulador Interativo Live:** Interface completa em React + Tailwind com estresse de 5 chamadas simultâneas publicado no GitHub Pages.

---

## 🛠️ Competências & Arsenal Tecnológico

| Área | Tecnologias & Práticas |
| :--- | :--- |
| **Linguagens & Runtimes** | Java 21 LTS (Virtual Threads, Records, Sealed Classes), SQL ANSI |
| **Frameworks & Core** | Spring Boot 3.3, Spring Data JPA, Spring Security, Spring Validation, Actuator |
| **Bancos de Dados & Cache** | PostgreSQL 16, Flyway Migrations, Redis (Distributed Locking), HikariCP |
| **Mensageria & Streaming** | Apache Kafka, Event-Driven Architecture, Outbox Pattern |
| **Qualidade & Testes** | Testcontainers, ArchUnit, JUnit 5, Mockito, Testes de Carga Concorrente |
| **DevOps & Infra** | Docker, Docker Compose, Gitflow (Feature Branches & PRs), GitHub Actions CI/CD |
| **Frontend de Apoio** | React 18, TypeScript, Vite, Tailwind CSS, REST APIs |

---

## 📊 Estatísticas do GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Mauricio-G-Oliveira&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0b0f19&title_color=10b981&text_color=94a3b8&icon_color=06b6d4" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mauricio-G-Oliveira&layout=compact&theme=tokyonight&hide_border=true&bg_color=0b0f19&title_color=10b981&text_color=94a3b8" alt="Top Languages" width="45%" />
</div>

---

<div align="center">
  <p>💼 Aberto a oportunidades de alto impacto como <strong>Engenheiro de Software Java Sênior</strong> e <strong>Tech Lead</strong>.</p>
</div>
