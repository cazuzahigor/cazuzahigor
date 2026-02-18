<div align="center">

```
╔══════════════════════════════════════════════════════════╗
║          HIGOR CAZUZA — SOFTWARE ENGINEER                ║
║          Java Platform & Backend Systems                 ║
╚══════════════════════════════════════════════════════════╝
```

[![Java](https://img.shields.io/badge/Java_21|25-ED8B00?style=flat-square&logo=openjdk&logoColor=white)](https://openjdk.org/)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot_3.x-6DB33F?style=flat-square&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)](https://www.kernel.org/)

</div>

---

## `$ whoami`

Backend Software Engineer with a focus on the **Java platform**: from language semantics and runtime behavior to the design of robust and high throughput systems.

My foundation is in **software engineering fundamentals**: algorithms, data structures, and computational complexity. I apply these not as academic exercises, but as tools for making deliberate design decisions. Choosing the right abstraction, the right data structure, the right concurrency model for the problem at hand.

I follow the Java platform closely, particularly the evolution brought by **Java 21 through 25**: structured concurrency, value types, and the ongoing refinement of the type system via pattern matching and sealed hierarchies.

> _"Understanding the machine makes you a better engineer. Understanding the problem makes you an effective one."_

---

## Core Competencies

### Java Platform

| Area | Detail |
|---|---|
| **Language & Type System** | Sealed classes, records, pattern matching for switch, exhaustive type hierarchies |
| **Concurrency** | Virtual Threads (Project Loom), Structured Concurrency, thread per request versus reactive trade offs |
| **Java 25 Preview Features** | Value classes (Project Valhalla), string templates, unnamed patterns and variables |
| **JVM Internals** | Memory model, garbage collection strategies (G1, ZGC), just in time compilation basics |
| **API Design** | Effective use of the Collections framework, Stream API, Optional, and functional interfaces |

### Algorithms & Data Structures

| Area | Detail |
|---|---|
| **Core Structures** | Arrays, linked lists, trees (BST, AVL), hash tables, heaps, graphs |
| **Algorithm Design** | Divide and conquer, dynamic programming, greedy strategies, backtracking |
| **Complexity Analysis** | Time and space complexity reasoning applied to real implementation decisions |
| **Sorting & Search** | Comparative and non comparative sorting, binary search and its variants |

### Backend & Persistence

| Area | Detail |
|---|---|
| **Spring Boot 3.x** | Application architecture, dependency injection, transaction management |
| **Spring Data JPA** | Repository patterns, query derivation, N+1 awareness, fetch strategies |
| **PostgreSQL** | Relational modeling, query optimization, indexing, ACID guarantees |
| **API Design** | RESTful conventions, error handling contracts, versioning strategies |

---

## Selected Projects

### High Concurrency Service with Java 21 Virtual Threads

**Context:** Redesigning the concurrency model of an I/O bound backend service.

**Engineering decisions:**

Adopted **Virtual Threads** to handle high request concurrency without the memory and scheduling overhead of platform threads, trading thread per request simplicity for genuine scalability. Applied **Structured Concurrency** to scope and manage concurrent subtasks with clear lifecycle boundaries, avoiding patterns that introduce resource leaks. Benchmarked with **JMH** to validate throughput gains and confirm latency reduction under load.

**Outcome:** Significant improvement in concurrent request handling and a simpler concurrency model compared to reactive alternatives, without sacrificing readability.

---

### Data Centric API with Spring Boot 3 + PostgreSQL

**Context:** Designing a persistence layer that remains correct and performant under real load.

**Engineering decisions:**

Modeled the domain carefully to avoid anemic entity design and ensure transactional boundaries aligned with business invariants. Identified and resolved **N+1 query patterns** through fetch strategy tuning and query consolidation. Applied indexing and query analysis to ensure predictable performance as data volume grew.

**Outcome:** A maintainable, consistent data layer with predictable behavior under concurrent access and load.

---

## Technology Radar

```
Adopted        →  Java 21+, Spring Boot 3, PostgreSQL, Git, Docker
Experimenting  →  Java 25 preview features (Valhalla), Testcontainers, Structured Concurrency APIs
Watching       →  GraalVM Native Image, Project Panama, OpenTelemetry for JVM
```

---

## Connect

<div align="center">

| | |
|---|---|
| 💼 LinkedIn | [linkedin.com/in/higorcazuza](https://linkedin.com/in/higorcazuza) |
| ✍️ Technical Writing | _Java internals and backend engineering, coming soon_ |
| 📬 Email | [higorcazuza@protonmail.com](mailto:higorcazuza@protonmail.com) |

_Available for backend engineering roles with meaningful technical challenges in the Java ecosystem._

</div>

---

<div align="center">
<sub>Engineered with intent. Refined over time.</sub>
</div>
