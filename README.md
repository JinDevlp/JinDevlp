# Hi, I'm Jin

**Java Software Engineer · Spring Boot · AWS · Multi-tenant SaaS**

I'm a Java software engineer (backend and full stack) in Dallas–Fort Worth, with 3.5+ years of Java and Spring Boot. I was a founding engineer on **Basil POS**, a multi-tenant point-of-sale SaaS platform serving hundreds of businesses. From its 2023 launch I built features across ordering and menus, reporting, labor, merchant operations and payments, including about 120 of its roughly 500 REST endpoints.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/devjinchoi/)

### What I worked on

- **Multi-tenant platform:** a database-per-tenant backend (merchant onboarding and schema, JWT-based tenant routing with Spring's `AbstractRoutingDataSource`), role-based permissions, and CloudWatch alarms. I led the Spring Boot 4.1 / Java 25 upgrade through dev and staging and wrote an AWS modernization plan (Aurora MySQL, consolidated connection pooling, ECS Fargate).
- **Ordering and menus:** menu, category and modifier management with menu schedules and QR menus, online ordering with customer accounts and order history, dine-in tables, kitchen re-fire and receipt printing.
- **Integrations:** Uber Eats, DoorDash and Grubhub orders through OrderOut (26 endpoints), card terminals on two Dejavoo APIs (sales, tip adjusts, voids, refunds, settlement) and Authorize.Net for online payments.
- **Reporting and background jobs:** sales, tax, labor and settlement reports delivered as scheduled HTML emails, and event-driven jobs on EventBridge Scheduler and SQS, such as automatic clock-out with a fallback for failed messages.
- **Full stack:** built the first Android POS screens (Java), and created the React + TypeScript back office and the Mission Control operations console used to manage merchants.
- **Reliability:** fixed a time-zone and daylight-saving bug that made a nightly job run twice or skip a day, and traced false failures to a vendor timeout.
- **Team:** code reviews in Agile sprints, mentoring a new backend developer, and AI-assisted development checked with tests that reproduce each issue.

### Currently building

**[payments-platform](https://github.com/JinDevlp/payments-platform)**: event-driven Java microservices with idempotent REST APIs, a transactional outbox to Kafka, a consumer that skips duplicate events, and Testcontainers integration tests. Kubernetes, Terraform on AWS, monitoring and load testing are on the roadmap.

### Tech

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white) ![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logoColor=white) ![JUnit5](https://img.shields.io/badge/JUnit_5-25A162?style=for-the-badge&logo=junit5&logoColor=white) ![Mockito](https://img.shields.io/badge/Mockito-78A641?style=for-the-badge&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

**Learning now, in payments-platform:**

![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)

AWS Certified Cloud Practitioner · Bilingual in English and Korean · Open to Java developer and software engineer roles (backend or full stack) in Dallas–Fort Worth or remote, available immediately
