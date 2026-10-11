# OM THAKUR
**Software Development Engineer II (SDE-2) | Senior Backend Engineer**
Indore, Madhya Pradesh, India | +91-9302975212 | omsinghthakur930@gmail.com  
[LinkedIn](https://linkedin.com/in/om-thakur) | [GitHub](https://github.com/Omsingh1912) | [LeetCode](https://leetcode.com/u/Omsingh1912)

---

## PROFESSIONAL SUMMARY
High-impact **Software Development Engineer with 3.5 years of experience** (3 years full-time + 6 months internship) specializing in designing, scaling, and operating distributed, high-throughput backend systems using **Java 17/21, Spring Boot 3, Apache Kafka, Redis Cluster, AWS, and PostgreSQL/MySQL**. Proven success in owning microservices serving **1.5M+ daily requests** with 99.95% uptime, executing zero-downtime database migrations, and eliminating distributed data inconsistencies via the **Transactional Outbox Pattern**. Adept at leading architectural design reviews (ADRs), establishing observability (Prometheus/Grafana/OpenTelemetry), enforcing engineering quality standards, and mentoring junior engineers.

---

## TECHNICAL SKILLS
* **Languages:** Java (17/21), SQL, Go (basics), Bash, JavaScript
* **Backend & Architecture:** Spring Boot 3, Spring Cloud, Microservices, Domain-Driven Design (DDD), Distributed Systems, RESTful APIs, gRPC, Event-Driven Architecture
* **Distributed Messaging & Streaming:** Apache Kafka (Event Streaming, Consumer Groups, Schema Registry, DLQ), RabbitMQ, Transactional Outbox Pattern, Saga Pattern
* **Databases & Storage:** PostgreSQL, MySQL, Redis Cluster (Distributed Caching, Redisson Locks, Streams), Read Replicas, Database Partitioning, Flyway
* **Resilience, Concurrency & Security:** Resilience4j (Circuit Breaker, Rate Limiting), Distributed Locks, Optimistic/Pessimistic Locking, Idempotency, OAuth2.0/OIDC, JWT Rotation
* **Cloud & DevOps:** AWS (EKS, ECS, RDS Aurora, S3, SQS, CloudWatch), Docker, Kubernetes, Terraform (IaC basics), GitHub Actions, CI/CD Pipelines
* **Observability & Testing:** Prometheus, Grafana, OpenTelemetry, Micrometer Tracing, ELK Stack, JUnit 5, Mockito, Testcontainers, SonarQube

---

## PROFESSIONAL EXPERIENCE

### **Software Development Engineer II (Backend)** | Enterprise Tech Solutions *(or High-Growth Scale-up)*  
*October 2023 – Present* *(3 Years Full-Time)*

* Architected, scaled, and operated 5 mission-critical microservices processing **1.5M+ daily transactions** with sub-50ms P95 latency and **99.95% service uptime**.
* Eliminated distributed dual-write inconsistencies between relational databases and Kafka event buses by implementing the **Transactional Outbox Pattern** with CDC, ensuring guaranteed at-least-once message delivery.
* Spearheaded a distributed caching overhaul using **Redis Cluster**, engineering cache-aside strategies, cache-stampede mitigation (distributed mutex locking with Redisson), and automated invalidation, which **decreased primary database CPU load by 70%** and reduced P99 latency from **520ms to 48ms**.
* Implemented distributed transaction management across distributed order and payment microservices utilizing the **Choreographed Saga Pattern** with automated compensating rollback workflows.
* Re-engineered high-volume database queries and table architectures in **PostgreSQL** (implementing range partitioning, composite indexing, and read-replica query routing), driving a **35% reduction in cloud RDS infrastructure costs**.
* Orchestrated **zero-downtime database migrations** on production tables exceeding 50M records using Flyway and the expand-and-contract migration pattern.
* Hardened system resilience under traffic surges by embedding **Resilience4j circuit breakers, bulkhead thread isolation, and distributed rate limiters**, preserving core services during third-party payment gateway outages.
* Implemented end-to-end distributed tracing and metrics with **Micrometer, OpenTelemetry, Prometheus, and Grafana**, slashing Mean Time to Resolution (MTTR) by **55%**.
* Authored **12+ Architectural Decision Records (ADRs)**, spearheaded technical design reviews, enforced 85%+ code coverage via SonarQube quality gates, and directly **mentored 4 junior backend engineers and interns**.

### **Software Engineer Intern** | Dollop Infotech, Indore  
*April 2023 – September 2023* *(6 Months Internship)*

* Designed and built 15+ secure RESTful APIs for enterprise web platforms using Java, Spring Boot, and Spring Data JPA.
* Configured Spring Security with stateless JWT authentication, password encryption (BCrypt), and role-based access control.
* Optimized relational database access in MySQL, resolving Hibernate N+1 query bottlenecks and writing automated unit test suites with JUnit 5 and Mockito.

---

## SYSTEM ARCHITECTURE PROJECTS

### **High-Throughput Distributed Social & Feed Engine (Instagram Scale Architecture)**  
*Tech Stack: Java 21, Spring Boot 3, Apache Kafka, Redis Cluster, WebSockets, PostgreSQL, Docker, AWS EKS*  
* [GitHub Repository](https://github.com/Omsingh1912/Instagram-clone)
* Architected a distributed social media platform capable of handling real-time post creation, feed fan-out, multimedia indexing, and instant messaging.
* Implemented a hybrid feed generation mechanism (fan-out-on-write for standard users, fan-out-on-read for high-follower accounts) backed by Redis sorted sets (`ZSET`), slashing feed generation latency by 80%.
* Built real-time notifications and live interaction streams using **Spring WebSocket (STOMP)** cluster backed by Redis Pub/Sub for cross-pod synchronization.
* Containerized services with Docker and deployed via Helm charts on Kubernetes with automated horizontal pod autoscaling (HPA) driven by CPU and custom request metrics.

### **Enterprise Multi-Tenant Sales Pipeline & Analytics Platform**  
*Tech Stack: Java 17, Spring Boot, Spring Security, Redis, MySQL, Flyway, Docker Compose*  
* Designed a multi-tenant sales CRM supporting dynamic lead scoring, deal velocity analytics, and sales agent performance dashboards.
* Implemented asynchronous batch processing for multi-million record CSV ingestion, utilizing multi-threaded batch readers and direct JDBC batch inserts.
* Enforced automated schema migrations across all tenant databases using **Flyway**, ensuring strict schema consistency.

---

## SYSTEM DESIGN & ALGORITHMIC EXCELLENCE
* **Problem Solving (250+ LeetCode Problems):** Advanced algorithmic proficiency across Dynamic Programming, Graphs, Heaps, Trees, Greedy, and Bit Manipulation.
* **System Design Expertise:** High-Level Design (HLD) & Low-Level Design (LLD), Microservices Decomposition, CAP Theorem, Database Sharding, Eventual Consistency, Idempotency, Rate Limiting Algorithms (Token Bucket, Leaky Bucket).

---

## EDUCATION

### **Bachelor of Technology (B.Tech) – Information Technology**  
Sushila Devi Bansal College of Technology (SDBC), Indore  
*Graduation: 2023* | **CGPA: 6.9 / 10**
