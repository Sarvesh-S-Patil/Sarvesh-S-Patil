### Hi, I'm Sarvesh 👋

I'm a **Java backend developer**. I work mostly with Spring Boot, and lately I've been building distributed systems with Kafka, Oracle and Angular. I also do machine learning in Python.

- 🔭 Currently building **[PayFlow](https://github.com/Sarvesh-S-Patil/PayFlow-Demo)**, an internet banking payments platform made of microservices
- 🌱 Learning: event-driven architecture, concurrency, Spring Batch

---

### ⭐ Featured project: PayFlow

**Four Spring Boot microservices and an Angular UI that model an internet banking payment flow.** A maker creates a payment, a different checker approves it, and a mock bank posts it over the IFT or NEFT rails.

<a href="https://github.com/Sarvesh-S-Patil/PayFlow-Demo">
  <img src="https://raw.githubusercontent.com/Sarvesh-S-Patil/PayFlow-Demo/main/screenshots/demo.gif?v=2" alt="PayFlow demo: maker creates a payment, checker approves it, the bank posts it" width="720">
</a>

- **Maker-checker approval**, enforced in the service layer and again by a database `CHECK` constraint
- **Transactional outbox**, so a crash can't lose an event between Oracle and Kafka
- **Idempotency at every hop** (`Idempotency-Key` header, idempotent ledger and bank)
- **Concurrency-safe posting:** ordered row locks with no deadlocks, and a balance that can never go negative
- **Bulk CSV payments** of up to 1,000 rows, validated all-or-nothing
- Kafka dead-letter topic, with replay from the admin UI

`Java 17` `Spring Boot 3.3` `Spring Kafka` `Oracle 23ai` `Flyway` `Angular 20` `Testcontainers` `Docker Compose`

➡️ [Architecture, screenshots and design notes](https://github.com/Sarvesh-S-Patil/PayFlow-Demo)

---

### 🛠️ Projects

| Project | What it is | Stack |
|---|---|---|
| [**PayFlow**](https://github.com/Sarvesh-S-Patil/PayFlow-Demo) | Internet banking payments platform: maker-checker, outbox, Kafka, mock bank | Spring Boot · Kafka · Oracle · Angular |
| [**Library Management System**](https://github.com/Sarvesh-S-Patil/LibraryManagementSystem) | REST API for books, students, library cards, issue/return, and overdue fines | Spring Boot · JPA/Hibernate · MySQL |
| [**URL Shortener**](https://github.com/Sarvesh-S-Patil/URL-Shortener) | Turns long URLs into short codes (ID encoded in base 26) and redirects with HTTP 302 | Spring Boot · JPA · MySQL |
| [**Bank Application**](https://github.com/Sarvesh-S-Patil/BankApplication) | Web banking app with admin and customer portals, transactions and a passbook | Java Servlets · JSP · JDBC · MySQL |
| [**ML Projects**](https://github.com/Sarvesh-S-Patil/AIMLProjects) | Churn prediction, sales forecasting, a movie recommender and more | Python · scikit-learn · pandas |
| [**Spring Assignments**](https://github.com/Sarvesh-S-Patil/Apro-Spring-Assignments) | 17 Spring apps: JPA mappings, JWT security, Spring Batch, email, cloud | Spring Boot · Spring Security · Spring Batch |

---

### 🧰 Tech stack

**Backend:**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**Data:**
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Frontend:**
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Testing & DevOps:**
![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**ML:**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
