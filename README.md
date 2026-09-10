# Hi, I'm Patrick 👋

I'm a Computer Science student at the University of Florida, with a previous background in technical program and project management at MongoDB and Yext.

I enjoy building backend systems, full-stack applications, and performance-focused software. I'm especially interested in problems involving distributed systems, scalability, and backend engineering.

Currently seeking a Software Engineering internship for Summer 2027.

## Featured Projects

### High-Performance Link Shortener

`Python` · `FastAPI` · `PostgreSQL` · `Redis` · `Docker` · `AWS EKS`

A performance-focused URL shortener built to explore how backend architecture changes as traffic scales.

* Built REST APIs for link creation and low-latency redirects
* Used PostgreSQL as the durable data store with Redis LFU caching for hot links
* Optimized the redirect path with indexed queries, SQLAlchemy Core, and connection-pool tuning
* Containerized the service and scaled across multiple replicas on AWS EKS
* Seeded 1M links and load tested with k6
* Scaled throughput from **~40 RPS → 10,045 RPS**, maintaining **68.1 ms p95 latency** and a **91.8% cache hit rate**

[View repository →](https://github.com/pattyolowry/link-shortener)

---

### [CinemaTreasures.club](https://cinematreasures.club/)

`TypeScript` · `React` · `Node.js` · `Express` · `MongoDB` · `AWS`

A production full-stack application I built for my film club to track watched movies, member ratings, rankings, annual awards, and club artifacts.

* Designed a TypeScript/Express REST API with JWT authentication, role-based access, request validation, and MongoDB persistence
* Built a React + TypeScript frontend using Vite and TanStack Query
* Added event-driven background processing with Amazon SQS + Lambda for movie metadata enrichment and notifications
* Implemented image uploads using Amazon S3
* Added production observability with Prometheus metrics, Grafana alerts, and structured logging
* Built automated CI/CD workflows and reduced backend hosting costs by 77% through an infrastructure migration

[View repository →](https://github.com/pattyolowry/cinema-treasures)

---

### Six Degrees of Kevin Bacon

`Python` · `Graph Algorithms` · `BFS`

A graph traversal project for finding the shortest connection between actors through shared movie appearances.

* Built graph data structures from a large movie and actor dataset
* Implemented traversal logic for shortest-path search
* Added a CLI for interactive actor-to-actor searches
* Compared traditional BFS against bidirectional BFS to study search-space and runtime improvements

[View repository →](https://github.com/pattyolowry/bacon-number)

## Technologies

|                                    |                                                                        |
| ---------------------------------- | ---------------------------------------------------------------------- |
| **Languages**                      | `Python` · `TypeScript` · `JavaScript` · `C++` · `SQL`                 |
| **Backend & Data**                 | `FastAPI` · `Node.js` · `Express` · `PostgreSQL` · `MongoDB` · `Redis` |
| **Infrastructure & Observability** | `Docker` · `AWS` · `Grafana` · `Prometheus`                            |


## Previous Experience

Before transitioning into software engineering, I spent several years working alongside engineering teams on large-scale technical systems.

At **MongoDB**, I supported Observability engineering teams by leading cross-team programs, improving planning and operating processes, and helping the organization adopt more agile ways of working. I also built internal tools using Python and Flask to streamline workflows and reduce manual effort.

At **Yext**, I managed the company's Google Business Profile integration supporting 1.5M+ business locations, working closely with engineering teams on API integrations and platform changes.

My previous experiences have shaped how I approach software engineering today: I care not only about writing code, but also about understanding customer needs, making thoughtful system tradeoffs, building reliable software, and considering how systems perform and operate in production.

## Education

**University of Florida**  
B.S. Computer Science — Expected December 2027  

**California Polytechnic State University, San Luis Obispo**  
B.S. Mechanical Engineering  

## Connect

[LinkedIn](https://www.linkedin.com/in/pattyolowry/)
