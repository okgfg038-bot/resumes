# OM THAKUR
**Software Development Engineer (Backend) | SDE**
Indore, Madhya Pradesh, India | +91-9302975212 | omsinghthakur930@gmail.com  
[LinkedIn](https://linkedin.com/in/om-thakur) | [GitHub](https://github.com/Omsingh1912) | [LeetCode](https://leetcode.com/u/Omsingh1912)

---

## PROFESSIONAL SUMMARY
Performance-driven **Software Development Engineer with 2.5 years of experience** (2 years full-time + 6 months internship) designing, scaling, and maintaining distributed microservices and event-driven architectures using **Java 17/21, Spring Boot 3, Apache Kafka, Redis Cluster, and PostgreSQL/MySQL**. Proven expertise in building fault-tolerant architectures utilizing **Resilience4j**, designing high-throughput messaging pipelines, and containerizing workloads across **Docker and Kubernetes/AWS**. Deep knowledge of database query optimization, distributed caching strategies, concurrency control, and production observability with **Prometheus & Grafana**.

---

## TECHNICAL SKILLS
* **Languages:** Java (17/21), SQL, JavaScript, Bash
* **Frameworks & Microservices:** Spring Boot 3, Spring Cloud (Gateway, Eureka/Consul), Spring Data JPA, Hibernate, RESTful APIs, gRPC (basics)
* **Distributed Systems & Messaging:** Apache Kafka (Partitions, Consumer Groups, DLQ), RabbitMQ, Distributed Locks (Redisson), WebSockets (STOMP)
* **Databases & Caching:** PostgreSQL, MySQL, Redis Cluster (Cache-Aside, Write-Through, Invalidation, Pub/Sub), HikariCP, Flyway
* **Resilience & Fault Tolerance:** Resilience4j (Circuit Breaker, Rate Limiter, Retry, Bulkhead), Idempotency Keys, Optimistic Locking (`@Version`)
* **DevOps, Cloud & Containers:** Docker, Kubernetes (Deployments, Services, ConfigMaps), AWS (EC2, S3, RDS, CloudWatch), GitHub Actions, CI/CD
* **Observability & Testing:** Prometheus, Grafana, OpenTelemetry, Micrometer, JUnit 5, Mockito, Testcontainers, SonarQube

---

## PROFESSIONAL EXPERIENCE

### **Software Development Engineer (Backend)** | CloudTech Solutions *(or Product Scale-up)*  
*October 2024 – Present* *(2 Years Full-Time)*

* Architected and maintained 4 core distributed microservices handling **250,000+ daily transactions** across mission-critical commerce and feed pipelines with **99.95% uptime**.
* Implemented an event-driven architecture using **Apache Kafka**, establishing dedicated topics, partitioned consumer groups, and **Dead Letter Queues (DLQ)** for asynchronous order processing and audit events, reducing end-to-end processing latency by **40%**.
* Designed a multi-layer distributed caching strategy using **Redis Cluster**, implementing Cache-Aside with probabilistic early expiration, which reduced database read loads by **65%** and brought P99 response times down from **450ms to 65ms**.
* Implemented resilience patterns across inter-service REST communications using **Resilience4j (Circuit Breakers, Timeouts, and Rate Limiters)**, preventing cascading failures and ensuring graceful degradation during third-party downstream outages.
* Prevented concurrent race conditions on critical transactions by implementing **distributed locking with Redis/Redisson** and database-level **optimistic locking (`@Version`)**, achieving zero double-spending or duplicate writes.
* Refactored legacy PostgreSQL queries by introducing composite B-Tree indexes, analyzing query plans via `EXPLAIN ANALYZE`, and restructuring schema partitions, yielding a **4x improvement in complex analytical query throughput**.
* Established end-to-end observability across all microservices using **Spring Boot Actuator, Micrometer, Prometheus, and Grafana dashboards**, shrinking Mean Time to Detect (MTTD) production issues by **50%**.
* Streamlined release lifecycles by building multi-stage **Docker builds and CI/CD pipelines in GitHub Actions**, deploying containerized services directly to Kubernetes clusters.

### **Java Developer Intern** | Dollop Infotech, Indore  
*April 2024 – September 2024* *(6 Months Internship)*

* Built and optimized 15+ secure RESTful endpoints for enterprise applications using Spring Boot 3, Spring Security, and Spring Data JPA.
* Configured stateless JWT authentication and role-based access control (RBAC), securing sensitive administrative endpoints.
* Designed normalized relational database schemas in MySQL, managed schema evolution via Flyway, and eliminated N+1 query overheads using JPQL fetch joins.
* Maintained 80%+ unit test code coverage using JUnit 5 and Mockito, actively participating in Agile sprints and peer code reviews.

---

## ARCHITECTURAL PROJECTS

### **High-Scale Social Media & Feed Engine (Instagram Distributed Architecture)**  
*Tech Stack: Java 21, Spring Boot 3, Kafka, Redis, WebSockets, PostgreSQL, Docker, Kubernetes*  
* [GitHub Repository](https://github.com/Omsingh1912/Instagram-clone)
* Architected a distributed social platform backend capable of supporting real-time media ingestion, feed generation, and high-frequency search indexing.
* Implemented real-time push notifications and bidirectional chat feeds using **Spring WebSocket (STOMP)** backed by a Redis Pub/Sub message broker for multi-instance horizontal scaling.
* Decoupled notification generation and analytics telemetry into background Kafka consumers, shielding customer-facing API threads from processing spikes.
* Deployed containerized microservices to local Kubernetes clusters with health probes, ingress routing, and config maps.

### **Enterprise Sales Pipeline & Financial Reporting Service**  
*Tech Stack: Java 17, Spring Boot, Spring Security, Redis, MySQL, Flyway, Docker Compose*  
* Developed an enterprise sales lifecycle engine tracking lead attribution, deal forecasting, and sales quotas.
* Implemented asynchronous multi-parameter search utilizing JPA Criteria API and Redis caching, cutting reporting wait times by 70%.
* Enforced automated schema migrations across development and staging environments using **Flyway**.

---

## PROBLEM SOLVING & COMPUTER SCIENCE FUNDAMENTALS
* **LeetCode (200+ Problems Solved):** Strong expertise in Data Structures, Graph Algorithms (BFS/DFS, Dijkstra), Dynamic Programming, Tree Traversals, and Concurrency.
* **System Design Knowledge:** High-Level Design (HLD) & Low-Level Design (LLD), CAP Theorem, Load Balancing, Consistent Hashing, Database Sharding.

---

## EDUCATION

### **Bachelor of Technology (B.Tech) – Information Technology**  
Sushila Devi Bansal College of Technology (SDBC), Indore  
*Graduation: 2024* | **CGPA: 6.9 / 10**
