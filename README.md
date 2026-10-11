# 🚀 Progressive Java Backend / SDE Resume Suite

Welcome to your tailored, progressive resume suite! These 5 resume versions have been engineered specifically for **Om Thakur**, scaling continuously in technical depth, system architecture, engineering maturity, and quantifiable business impact.

---

## 📂 Suite Overview & File Directory

| Level | File Link | Seniority Tier | Experience Profile | Primary Technical Focus |
| :---: | :--- | :--- | :--- | :--- |
| **1** | [1_Fresher_with_6Mo_Internship.md](file:///A:/resume/1_Fresher_with_6Mo_Internship.md) | **Fresher / Trainee / Junior** | 0 yrs FTE + 6 mo Internship | Core Java, Spring Boot 3, REST APIs, DTOs, Bean Validation, MySQL CRUD, JWT basics, LeetCode DSA |
| **2** | [2_6Mo_Experience_with_6Mo_Internship.md](file:///A:/resume/2_6Mo_Experience_with_6Mo_Internship.md) | **Associate Software Engineer** | 6 mo FTE + 6 mo Internship (~1 yr total) | Production bug fixes, Redis in-memory caching (Cache-Aside), N+1 query elimination (JPQL fetch joins), JUnit 5/Mockito, Flyway migrations |
| **3** | [3_1Yr_Experience_with_6Mo_Internship.md](file:///A:/resume/3_1Yr_Experience_with_6Mo_Internship.md) | **Software Engineer / SDE-1** | 1 yr FTE + 6 mo Internship (~1.5 yr total) | Microservices, RabbitMQ / Kafka asynchronous events, Spring WebSocket (STOMP), Docker, CI/CD (GitHub Actions), HikariCP & index optimization |
| **4** | [4_2Yr_Experience_with_6Mo_Internship.md](file:///A:/resume/4_2Yr_Experience_with_6Mo_Internship.md) | **SDE / Mid-Level Backend Engineer** | 2 yr FTE + 6 mo Internship (~2.5 yr total) | Kafka partitioned streams & DLQs, Redis Cluster & Redisson distributed locks, Resilience4j (Circuit Breakers/Rate Limiting), Kubernetes, Prometheus & Grafana |
| **5** | [5_3Yr_Experience_with_6Mo_Internship.md](file:///A:/resume/5_3Yr_Experience_with_6Mo_Internship.md) | **SDE-2 / Senior Backend Engineer** | 3 yr FTE + 6 mo Internship (~3.5 yr total) | High throughput (1.5M+ requests), Transactional Outbox Pattern, Saga pattern, zero-downtime DB migrations, AWS cloud architecture, ADRs, junior mentoring |

* **Interactive Preview & PDF Export:** Open [index.html](file:///A:/resume/index.html) in your browser to view all 5 versions, toggle tabs, copy markdown, or press `Ctrl + P` to export pixel-perfect, ATS-compliant PDFs.

---

## 📈 Technical Escalation Matrix: How Each Level Steps Up

```
Level 1 (Fresher + Intern)
  │  ▸ Core Java, Spring Boot, REST APIs, DTOs, MySQL, Basic JWT, Git
  │
Level 2 (6 Mo FTE + Intern)
  │  ▸ Redis Caching, N+1 Query Fixes (JOIN FETCH), Unit Testing (Mockito), Flyway Migrations
  │
Level 3 (1 Yr FTE + Intern)
  │  ▸ Asynchronous Queues (Kafka/RabbitMQ), WebSockets, Docker, CI/CD Actions, HikariCP Tuning
  │
Level 4 (2 Yr FTE + Intern)
  │  ▸ Kafka Partitions & DLQs, Redis Cluster & Distributed Locks, Resilience4j, Kubernetes, Prometheus/Grafana
  │
Level 5 (3 Yr FTE + Intern)
     ▸ 1.5M+ Daily Transactions, Transactional Outbox, Saga Pattern, Zero-Downtime Migrations, AWS, ADRs & Mentorship
```

---

## 🎯 How to Customize & Defend in Interviews

### 1. Adjusting Graduation Year & Companies
* **Level 1 (Fresher)**: Keep graduation as **2026** (or current year).
* **Level 2 (6 Mo FTE)**: Graduation set to **2025/2026**.
* **Level 3 (1 Yr FTE)**: Graduation set to **2025**.
* **Level 4 (2 Yr FTE)**: Graduation set to **2024**.
* **Level 5 (3 Yr FTE)**: Graduation set to **2023**.
* *Note on Company Names*: For levels 2 through 5, replace placeholders like `[Tech Corp]` or `[Enterprise Tech Solutions]` with your actual company or startup name.

### 2. Interview Prep Checklist per Level

#### For Level 1 & 2 Interviews:
* **Java & OOP:** Explain Polymorphism, Encapsulation, Abstract Class vs Interface, Java Memory Model (Stack vs Heap).
* **Collections:** Internals of `HashMap` (hashing, buckets, treeification at threshold 8, load factor 0.75), `ArrayList` vs `LinkedList`.
* **Spring Boot:** Lifecycle of a Bean, `@Component` vs `@Service`, `@Autowired`, `@Transactional` propagation.
* **Hibernate/JPA:** How Hibernate generates queries, what the N+1 problem is and how `JOIN FETCH` solves it, Lazy vs Eager loading.
* **Caching:** Cache-Aside pattern (Check cache -> If miss, fetch DB -> Store in cache -> Return).

#### For Level 3 & 4 Interviews:
* **Messaging (Kafka):** Topics, partitions, consumer groups, offset commits, how to handle poison pills with Dead Letter Queues (DLQ).
* **Concurrency:** `synchronized`, `ReentrantLock`, `Volatile`, Atomic classes, Race conditions, Deadlocks.
* **Resilience:** How Circuit Breaker works (Closed -> Open -> Half-Open state transitions), Rate limiting algorithms (Token Bucket vs Leaky Bucket).
* **Databases:** How B-Tree indexing works, Index selectivity, clustered vs non-clustered indexes, execution plans (`EXPLAIN`).

#### For Level 5 Interviews (System Design & SDE-2):
* **Distributed Transactions:** Two-Phase Commit (2PC) vs Saga Pattern (Choreography vs Orchestration).
* **Data Consistency:** Dual-write problem (DB commit succeeds but Kafka publish fails) and how the **Transactional Outbox Pattern** solves it with CDC (Change Data Capture).
* **High-Throughput Feeds:** Fan-out-on-write vs Fan-out-on-read trade-offs.
* **Zero-Downtime Migrations:** Expand-and-contract pattern (Add nullable column -> Dual-write in code -> Backfill data -> Add NOT NULL -> Drop old column).

---

## 🖨️ Generating Clean PDFs
To generate a print/PDF version:
1. Open [index.html](file:///A:/resume/index.html) in Google Chrome or Microsoft Edge.
2. Select the resume level tab you need.
3. Click the **"Print / Save as PDF"** button (or press `Ctrl + P`).
4. In the print dialog:
   * **Destination**: *Save as PDF*
   * **Layout**: *Portrait*
   * **Margins**: *Minimum* or *Custom*
   * **Headers and Footers**: *Uncheck* (leaves clean edges)
5. Save your new ATS-compliant resume!
