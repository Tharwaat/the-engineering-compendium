# Dev Knowledge Base

> A curated, community-driven collection of high-quality resources for software engineers — articles, open-source repositories, research papers, books, and courses spanning the full spectrum of modern software engineering.

![Resources](https://img.shields.io/badge/resources-770-blue)
![Repos](https://img.shields.io/badge/repositories-72-green)
![Papers](https://img.shields.io/badge/papers-14-orange)
![Articles](https://img.shields.io/badge/articles-651-informational)
![Videos](https://img.shields.io/badge/videos-19-red)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/Tharwaat/the-engineering-compendium.git/pulls)
[![GitHub stars](https://img.shields.io/github/stars/YOUR_USERNAME/YOUR_REPO?style=social)](https://github.com/Tharwaat/the-engineering-compendium.git)

## About

This repository is a living knowledge base assembled from years of reading, bookmarking, and sharing links across backend engineering, distributed systems, databases, cloud infrastructure, and more. Every resource here has been personally selected because it provides genuine, lasting value.

**Who is this for?**  
Backend engineers, system designers, SREs, and anyone who believes that learning is a continuous craft — from junior developers building their first mental model of distributed systems to principal engineers who want a second opinion on a design decision.

**Open for contributions.** If you have a link that made you think differently, taught you something non-obvious, or pointed you to a tool you use every day, open a PR. See [Contributing](#contributing).

## Table of Contents

- [System Design & Architecture](#system-design-architecture) `59`
- [Distributed Systems](#distributed-systems) `18`
- [Databases](#databases) `116`
- [Java & JVM](#java-jvm) `65`
- [Go (Golang)](#go-golang) `10`
- [Rust & Low-Level Programming](#rust-low-level-programming) `6`
- [Algorithms & Data Structures](#algorithms-data-structures) `22`
- [Kafka & Event Streaming](#kafka-event-streaming) `13`
- [Kubernetes & Containers](#kubernetes-containers) `62`
- [Cloud & AWS](#cloud-aws) `7`
- [DevOps & CI/CD](#devops-ci-cd) `8`
- [Operating Systems & Linux](#operating-systems-linux) `10`
- [eBPF & Systems Tracing](#ebpf-systems-tracing) `3`
- [Networking & Protocols](#networking-protocols) `8`
- [Security](#security) `9`
- [Machine Learning & AI](#machine-learning-ai) `18`
- [AI Agents & Claude Code](#ai-agents-claude-code) `8`
- [Monitoring & Observability](#monitoring-observability) `15`
- [Performance & Optimization](#performance-optimization) `7`
- [Data Engineering](#data-engineering) `6`
- [Computer Science Fundamentals](#computer-science-fundamentals) `5`
- [Career & Engineering Growth](#career-engineering-growth) `10`
- [Courses, Books & Learning Paths](#courses-books-learning-paths) `12`
- [Robotics & Embedded Systems](#robotics-embedded-systems) `1`
- [Open Source Tools & Projects](#open-source-tools-projects) `10`
- [Engineering Blogs & General Resources](#engineering-blogs-general-resources) `262`

---

## System Design & Architecture

### Repositories

- [System Design: WhatsApp - DEV Community](https://github.com/karanpratapsingh/system-design#whatsapp)
- [ashishps1/awesome-system-design-resources](https://github.com/ashishps1/awesome-system-design-resources/blob/main/README.md#system-design-interview-problems)
- [microservices-demo/microservices-demo](https://github.com/microservices-demo/microservices-demo)
- [GitHub - systemdesign42/system-design: A resource to help you become good at system design](https://github.com/systemdesign42/system-design)
- [mtdvio/every-programmer-should-know](https://github.com/mtdvio/every-programmer-should-know?utm_source=opensourceprojects.dev&ref=opensourceprojects.dev)
- [GitHub - ddd-by-examples/library: A comprehensive Domain-Driven Design example with problem space strategic analysis and various tactical patterns](https://github.com/ddd-by-examples/library)

### Books & Courses

- [Software Architecture in an AI World – O’Reilly](https://www.oreilly.com/radar/software-architecture-in-an-ai-world/)

### Articles & Tutorials

- [Explicit Architecture 01 Ddd Hexagonal Onion Clean Cqrs How I Put It All Together](https://herbertograca.com/2017/11/16/explicit-architecture-01-ddd-hexagonal-onion-clean-cqrs-how-i-put-it-all-together/)
- [Top 10 Microservices Design Principles |](https://www.developer.com/design/microservices-design-principles/)
- [4 Examples of Microservices Architectures Done Right | Nordic APIs |](https://nordicapis.com/4-examples-of-microservices-architectures-done-right/)
- [Aggregation Pattern (Design Patterns for Microservices)](https://medium.com/geekculture/design-patterns-for-microservices-aggregation-pattern-1b8994516fa2)
- [Pattern: Aggregate](https://microservices.io/patterns/data/aggregate.html)
- [7 Microservice Design Patterns to Use](https://blog.openreplay.com/7-microservice-design-patterns-to-use)
- [Microservices Integration Done Right Using Contract-Driven Development](https://www.infoq.com/articles/contract-driven-development/)
- [System Design Interview Survival Guide (2023): Preparation Strategies and Practical Tips | by Arslan Ahmad | Jan, 2023 | Level Up Coding](https://levelup.gitconnected.com/system-design-interview-survival-guide-2023-preparation-strategies-and-practical-tips-ba9314e6b9e3)
- [Blue Green Deployment Nodejs](https://semaphoreci.com/blog/blue-green-deployment-nodejs)
- [Architecture Notes — System Design & Software Architectures Explained](https://architecturenotes.co/)
- [Building Resilient Payment Systems](https://shopify.engineering/building-resilient-payment-systems)
- [Architecture of a Modern Startup](https://betterprogramming.pub/architecture-of-modern-startup-abaec235c2eb)
- [Microservices Best Practices - Semaphore](https://semaphoreci.com/blog/microservices-best-practices)
- [A Design Analysis of Cloud-based Microservices Architecture at Netflix](https://medium.com/swlh/a-design-analysis-of-cloud-based-microservices-architecture-at-netflix-98836b2da45f)
- [Resiliency in a nutshell. Part: 3 Traditional Engineering—Programming patterns | by Alexander Wichmann Carlsen | Medium | ITNEXT](https://itnext.io/resiliency-in-a-nutshell-part-3-traditional-engineering-programming-patterns-4855242a0f6)
- [Why Clean Architecture Is Great For Complex Projects](https://www.milanjovanovic.tech/blog/why-clean-architecture-is-great-for-complex-projects)
- [The 7 Software Architecture Books Experienced Developers Need to Read | HackerNoon](https://hackernoon.com/the-7-software-architecture-books-experienced-developers-need-to-read)
- [Implementing clean architecture solutions: A practical example | Red Hat Developer](https://developers.redhat.com/articles/2023/08/08/implementing-clean-architecture-solutions-practical-example)
- [Designing APIs for humans: Design patterns - DEV Community](https://dev.to/stripe/designing-apis-for-humans-design-patterns-5847)
- [Top 10 Must-Have Tools for Kubernetes Engineers](https://semaphoreci.com/blog/kubernetes-tools)
- [Building Low Friction gRPC API Gateways](https://kostyay.com/building-low-friction-grpc-api-gateways-bb1afbf233f4)
- [An In Depth Exploration Of Rest Grpc And Graphql I](https://dzone.com/articles/an-in-depth-exploration-of-rest-grpc-and-graphql-i)
- [Understanding Grpc Concepts Best Practices](https://www.infracloud.io/blogs/understanding-grpc-concepts-best-practices/)
- [Designing Scalable Notification System](https://adityagoel123.medium.com/designing-scalable-notification-system-79f83272755e)
- [12 Factor App](https://www.redhat.com/architect/12-factor-app)
- [Backstage on Kubernetes - Piotr's TechBlog](https://piotrminkowski.com/2024/06/28/backstage-on-kubernetes/)
- [Failures and Resilience in Microservices — Mathematical Calculations | by Gul Ershad | Aug, 2024 | ITNEXT](https://itnext.io/mathematical-calculations-for-the-failures-and-resilience-in-microservices-f035437789a9)
- [DevOps Project: CI/CD Pipeline for a Microservices-Based Application on Kubernetes - DEV Community](https://dev.to/prodevopsguytech/devops-project-cicd-pipeline-for-a-microservices-based-application-on-kubernetes-1ba8)
- [Digging Deep to Find the Right Balance Between DDD, Clean and Hexagonal Architectures - DEV Community](https://dev.to/y9vad9/digging-deep-to-find-the-right-balance-between-ddd-clean-and-hexagonal-architectures-4dnn)
- [Hexagonal Architecture. A metapattern. | ITNEXT](https://itnext.io/hexagonal-architecture-fe1250fb52be)
- [10 Scalability Lessons from Zoom's Software Architecture - DEV Community](https://dev.to/somadevtoo/10-scalability-lessons-from-zooms-software-architecture-6g3)
- [Why Microservice Hotel PMS Architecture is the Future](https://www.revfine.com/microservice-hotel-pms-architecture/)
- [System Design Roadmap for Beginners - DEV Community](https://dev.to/hellonehha/system-design-roadmap-for-beginners-nfi)
- [Migrating Java Microservices To Go Guide](https://dzone.com/articles/migrating-java-microservices-to-go-guide)
- [Chaos Engineering For Microservices](https://dzone.com/articles/chaos-engineering-for-microservices?edition=975106)
- [Building TikTok: Video Feed System Design | ITNEXT](https://itnext.io/system-design-building-tiktok-style-video-feed-for-100-million-users-2b3e332678d8)
- [Uber Completes Massive Kubernetes Migration for Microservices and Large-Scale Compute Workloads - InfoQ](https://www.infoq.com/news/2025/05/uber-kubernetes-migration/)
- [Event Driven Microservices Kafka Rabbitmq](https://dzone.com/articles/event-driven-microservices-kafka-rabbitmq)
- [Designing Resilient Event-Driven Systems at Scale - InfoQ](https://www.infoq.com/articles/scalable-resilient-event-systems/)
- [Why We Replaced Kafka with gRPC for Service Communication](https://medium.com/@himanshusingour7/why-we-replaced-kafka-with-grpc-for-service-communication-1c946db514d4)
- [Cell Based Architecture Scalable Resilient Cloud Design](https://dzone.com/articles/cell-based-architecture-scalable-resilient-cloud-design?edition=989314&email_hash=d81f265aee3958897ad13604b99e311b)
- [AntInLoop - Master Algorithms & Data Structures | Learn DSA Online](https://antinloop.com/)
- [How Shopify Handles 30TB of Data Every Minute with a Monolithic Architecture](https://medium.com/@himanshusingour7/how-shopify-handles-30tb-of-data-every-minute-with-a-monolithic-architecture-cad54df86955)
- [Microservices Kubernetes Grpc Circuit Breakers](https://dzone.com/articles/microservices-kubernetes-grpc-circuit-breakers)
- [Understanding the C4 Model: A Clear Path to Documenting Software Architecture](https://alirezafarokhi.medium.com/understanding-the-c4-model-a-clear-path-to-documenting-software-architecture-88c9ee618a08)
- [What are Blocking Queues and Why We Need Them](https://arpitbhayani.me/blogs/blocking-queues/)
- [Monolithic Architecture Guide: Pros, Cons & Evolution Paths](https://strapi.io/blog/monolithic-architecture-pros-cons-evolution-guide)
- [Anton Zhiyanov](https://antonz.org/)
- [system_design_simulator](https://paperdraw.dev/)
- [Codemia | Master System Design Interviews Through Active Practice](https://codemia.io/?via=javarevisited)
- [Start Here](https://highscalability.com/start-here/)
- [Backpressure in System Design: Why It Matters and How to Implement It | by Sushank Hegde | Medium](https://medium.com/@sushankhegde10/backpressure-in-system-design-why-it-matters-and-how-to-implement-it-e3043ba738e6)

---

## Distributed Systems

### Papers & Research

- [Amazon's Dynamo — SOSP 2007 Paper](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)

### Books & Courses

- [Designing Distributed Systems (O'Reilly Book)](https://learning.oreilly.com/library/view/designing-distributed-systems/9781491983638/)

### Articles & Tutorials

- [Understanding Distributed Systems](https://understandingdistributed.systems/)
- [Message Queues In Distributed Systesms](https://www.freecodecamp.org/news/message-queues-in-distributed-systesms/)
- [Concurrent Writes in Distributed Systems](https://medium.com/the-developers-diary/concurrent-writes-in-distributed-systems-601782e4797f)
- [A Distributed Systems Reading List](https://ferd.ca/a-distributed-systems-reading-list.html)
- [How to Minimize Latency and Cost in Distributed Systems - InfoQ](https://www.infoq.com/articles/minimize-latency-cost-distributed-systems/)
- [Building Resilience: Addressing the Challenges of Distributed Microservices | by Gul Ershad | Sep, 2024 | ITNEXT](https://itnext.io/building-resilience-addressing-the-challenges-of-distributed-microservices-93219ddf5d56)
- [Distributed Systems Consistency: Mistake Nobody Warns You About! - CodeOpinion](https://codeopinion.com/distributed-systems-consistency-mistake-nobody-warns-you-about/)
- [Distributed Programming Stalled](https://www.shadaj.me/writing/distributed-programming-stalled)
- [Testing Distributed Systems | Curated list of resources on testing distributed systems](https://asatarin.github.io/testing-distributed-systems/)
- [Building a 100K URLs/Second System with DynamoDB | ITNEXT](https://itnext.io/distributed-tinyurl-architecture-how-to-handle-100k-urls-per-second-54182403117e)
- [Reliability Glossary](https://antithesis.com/resources/reliability_glossary/)
- [Consistency Over Availability: How rqlite handles the CAP Theorem – Vallified](https://philipotoole.com/consistency-over-availability-how-rqlite-handles-the-cap-theorem/)
- [Btree Index Structures In Innodb](https://blog.jcole.us/2013/01/10/btree-index-structures-in-innodb/)
- [The Basics Of The Innodb Undo Logging And History System](https://blog.jcole.us/2014/04/16/the-basics-of-the-innodb-undo-logging-and-history-system/)
- [From Cron to Distributed Schedulers: Scaling Job Execution to Thousands of Jobs per Second](https://itnext.io/from-cron-to-distributed-schedulers-scaling-job-execution-to-thousands-of-jobs-per-second-ef05955bf3d9)
- [The Log: What every software engineer should know about real-time data's unifying abstraction | LinkedIn Engineering](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)

---

## Databases

### Repositories

- [postgres_internals/mvcc at main  Shresth72/postgres_internals](https://github.com/Shresth72/postgres_internals/tree/main/mvcc)
- [GitHub - binhnguyennus/awesome-scalability: The Patterns of Scalable, Reliable, and Performant Large-Scale Systems  GitHub](https://github.com/binhnguyennus/awesome-scalability)
- [GitHub - nextlevelbuilder/ui-ux-pro-max-skill: An AI SKILL that provide design intelligence for building professional UI/UX multiple platforms  GitHub](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)
- [GitHub - VictoriaMetrics/VictoriaLogs: Fast and easy to use database for logs, which can efficiently handle terabytes of logs  GitHub](https://github.com/VictoriaMetrics/VictoriaLogs/)
- [immanuwell/DevOps-interview-questions](https://github.com/immanuwell/DevOps-interview-questions)

### Books & Courses

- [Lets Architect Architecting For Nosql Databases](https://aws.amazon.com/blogs/architecture/lets-architect-architecting-for-nosql-databases/)
- [Core components of Amazon DynamoDB - Amazon DynamoDB](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/HowItWorks.CoreComponents.html)
- [Vector Database Fundamentals](https://www.coursera.org/specializations/vector-database-fundamentals)
- [Performance Engineering of Software Systems | Electrical Engineering and Computer Science | MIT OpenCourseWare](https://ocw.mit.edu/courses/6-172-performance-engineering-of-software-systems-fall-2018/)

### Articles & Tutorials

- [Why Use Mongodb](https://www.mongodb.com/why-use-mongodb#:~:text=Using%20MongoDB%20can%20provide%20many,modern%20databases%20such%20as%20transactions)
- [When To Use Nosql Mongodb](https://www.fivetran.com/blog/when-to-use-nosql-mongodb)
- [MongoDB vs MySQL – Difference Between Them](https://www.guru99.com/mongodb-vs-mysql.html#:~:text=MongoDB%20uses%20JavaScript%20as%20query,need%20a%20traditional%20relational%20database)
- [Mongodb Mysql](https://www.mongodb.com/compare/mongodb-mysql)
- [Beginning Database Design | SpringerLink](https://link.springer.com/book/10.1007/978-1-4302-0366-7)
- [Performance](https://stackexchange.com/performance)
- [How Is Platform Engineering Different From Devops And Sre](https://thenewstack.io/how-is-platform-engineering-different-from-devops-and-sre/)
- [Core Performance Best Practices | Microsoft Learn](https://learn.microsoft.com/en-us/aspnet/core/performance/performance-best-practices)
- [Seeing Through Hardware Counters: A Journey to Threefold Performance Increase](https://netflixtechblog.com/seeing-through-hardware-counters-a-journey-to-threefold-performance-increase-2721924a2822)
- [How to Create NodeJS APIs Using Node.js, Typescript, MongoDB & Express](https://morioh.com/)
- [Comparing Database Types](https://www.prisma.io/dataguide/intro/comparing-database-types)
- [What Is A Query Planner](https://planetscale.com/blog/what-is-a-query-planner)
- [5 Things to Consider When Building a Kubernetes Platform - The New Stack](https://thenewstack.io/5-things-to-consider-when-building-a-kubernetes-platform/)
- [I Struggle to Read and Write 100K Requests in Postgres DB, and My Aggressive Solution with Redis](https://medium.datadriveninvestor.com/i-struggle-to-read-and-write-100k-requests-in-postgres-db-with-my-aggressive-solution-with-redis-91461a8316a1)
- [Improving Search Performance: Travolic's Successful Migration to Elasticsearch](https://medium.com/@mle.mahmoud.yasser/elasticsearch-improving-search-performance-76532630436b)
- [From Postgres To Amazon Dynamodb %Ef%Bf%Bc](https://www.instacart.com/company/how-its-made/from-postgres-to-amazon-dynamodb-%EF%BF%BC/)
- [How to deploy NGINX Ingress Controller on Kubernetes using kubectl - Platform9 Learning](https://platform9.com/learn/v1.0/tutorials/nginix-controller-via-yaml)
- [Java Databases](https://www.marcobehler.com/guides/java-databases)
- [Please stop calling databases CP or AP — Martin Kleppmann’s blog](https://martin.kleppmann.com/2015/05/11/please-stop-calling-databases-cp-or-ap.html)
- [4 Advanced Sharding Techniques Every Software Engineer Must Know | by Arslan Ahmad | Aug, 2023 | Level Up Coding](https://levelup.gitconnected.com/4-advanced-sharding-techniques-every-software-engineer-must-know-b4493dc6ec0f)
- [Relational Databases Explained](https://architecturenotes.co/things-you-should-know-about-databases/)
- [Understanding Java Internals: Speed and Performance](https://www.freecodecamp.org/news/understanding-java-internals-speed-and-performance/)
- [Postgres Full Text Search Engine](https://xata.io/blog/postgres-full-text-search-engine?ref=architecturenotes.co)
- [Postgres Full Text Search Postgres Vs Elasticsearch](https://xata.io/blog/postgres-full-text-search-postgres-vs-elasticsearch)
- [Small Datum: Fixing bug 109595 makes MySQL almost 4X faster on the Insert Benchmark](https://smalldatum.blogspot.com/2023/11/fixing-bug-109595-makes-mysql-almost-4x.html)
- [MySQL 8.2 Introduces Transparent Read/Write Splitting](https://www.infoq.com/news/2023/11/mysql-read-write-splitting/)
- [MongoDB vs. ScyllaDB: A Comparison of Database Architectures - The New Stack](https://thenewstack.io/mongodb-vs-scylladb-a-comparison-of-database-architectures/)
- [PostgreSQL 14 Internals : Postgres Professional](https://postgrespro.com/community/books/internals)
- [11 Database Optimization Techniques](https://danielfoo.medium.com/11-database-optimization-techniques-97fdbed1b627)
- [The Power of Database Indexing Algorithms: B-Tree vs. Hash Indexing](https://dip-mazumder.medium.com/the-power-of-database-indexing-algorithms-b-tree-vs-hash-indexing-6e3a4112a81#:~:text=Hash%20Indexing,-The%20Java%20Trail&text=Database%20indexing%20is%20a,user%20experience%20and%20decreased%20productivity)
- [Moving from DynamoDB to Tiered Storage with MySQL+S3](https://zendesk.engineering/moving-from-dynamodb-to-tiered-storage-with-mysql-s3-cb3dc9bf813a)
- [What Is An Internal Developer Platform](https://internaldeveloperplatform.org/what-is-an-internal-developer-platform/)
- [2017 10 13 Mitigating Replication Lag And Reducing Read Load With Freno](https://github.blog/2017-10-13-mitigating-replication-lag-and-reducing-read-load-with-freno/)
- [Building High-Performing Software Systems: A Guide to Architectural Styles and Techniques](https://romanglushach.medium.com/building-high-performing-software-systems-a-guide-to-architectural-styles-and-techniques-00dc89e08147)
- [From Postgres to ScyllaDB NoSQL, with a 349x Speed Boost - The New Stack](https://thenewstack.io/from-postgres-to-scylladb-nosql-with-a-349x-speed-boost/)
- [iximiuz Labs - Learning-by-Doing Platform to master Cloud Native craft](https://labs.iximiuz.com/)
- [Implement Leaderboard With Redis Sorted Sets](https://implementing.substack.com/p/implement-leaderboard-with-redis-sorted-sets)
- [4000 microservices, 8 million customers, 1 Internal Developer Platform](https://platformengineering.org/events/4000-microservices-8-million-customers-1-internal-developer-platform)
- [The Performance Golden Rule](https://www.stevesouders.com/blog/2012/02/10/the-performance-golden-rule/)
- [How to implement a Distributed Lock using Redis - DEV Community](https://dev.to/ssd/how-to-implement-a-distributed-lock-using-redis-he)
- [How JPA works from your Java code to the Database](https://robertniestroj.hashnode.dev/how-jpa-works-from-your-java-code-to-the-database)
- [How To Run Databases On Kubernetes An 8 Step Guide](https://thenewstack.io/how-to-run-databases-on-kubernetes-an-8-step-guide/)
- [Jvm Performance Tuning For High Throughput And Low Latency](https://dzone.com/articles/jvm-performance-tuning-for-high-throughput-and-low-latency?edition=943903)
- [Modern Hardware for Future Databases](https://transactional.blog/blog/2024-modern-database-hardware)
- [Computer Networking Fundamentals For Developers, DevOps, and Platform Engineers (course) | iximiuz Labs](https://labs.iximiuz.com/courses/computer-networking-fundamentals)
- [Building a Log Analysis Data Pipeline Using Kafka, Elasticsearch, Logstash and Kibana (ELK Stack)](https://towardsdev.com/building-a-log-analysis-data-pipeline-using-kafka-elasticsearch-logstash-and-kibana-elk-stack-8c7c0c034d3f)
- [7 Databases in 7 Weeks for 2025](https://matt.blwt.io/post/7-databases-in-7-weeks-for-2025/)
- [Leaderless Replication For Distributed Data](https://dzone.com/articles/leaderless-replication-for-distributed-data?edition=955907)
- [Practical Protobuf - From Basic to Best Practices](https://victoriametrics.com/blog/go-protobuf-basic/)
- [What I Learned Operating Clickhouse](https://www.tinybird.co/blog-posts/what-i-learned-operating-clickhouse)
- [Sharding with SpringBoot](https://medium.com/@rajkundalia/sharding-with-springboot-c9530e6af929)
- [How Figma's Databases Team Lived to Tell the Scale | Figma Blog](https://www.figma.com/blog/how-figmas-databases-team-lived-to-tell-the-scale/)
- [The Platonic Database](https://tidyfirst.substack.com/p/the-platonic-database?r=4q48ii&triedRedirect=true)
- [Practical Case Study Of Mysql To Postgresql Databa](https://dzone.com/articles/practical-case-study-of-mysql-to-postgresql-databa?edition=980204)
- [Building scalable multi-tenant applications in Go | Atlas | Manage your database schema as code](https://atlasgo.io/blog/2025/05/26/gophercon-scalable-multi-tenant-apps-in-go)
- [ClickStack: A High-Performance OSS Observability Stack on ClickHouse](https://clickhouse.com/blog/clickstack-a-high-performance-oss-observability-stack-on-clickhouse)
- [Database observability: How OpenTelemetry semantic conventions improve consistency across signals | Grafana Labs](https://grafana.com/blog/2025/06/06/database-observability-how-opentelemetry-semantic-conventions-improve-consistency-across-signals/)
- [rgSQL: A test suite for database engines](https://technicaldeft.com/posts/rgsql-a-test-suite-for-database-engines)
- [How to Build a Multi-Tenancy Internal Developer Platform with GitOps and vCluster](https://itnext.io/how-to-build-a-multi-tenancy-internal-developer-platform-with-gitops-and-vcluster-d8f43bfb9c3d)
- [10X Performance Improvement For Expression Evaluation Made Possible By Vectorized Execution](https://www.pingcap.com/blog/10x-performance-improvement-for-expression-evaluation-made-possible-by-vectorized-execution/)
- [Deploying And Managing Redis On Kubernetes](https://collabnix.com/deploying-and-managing-redis-on-kubernetes/)
- [Caching — PlanetScale](https://planetscale.com/blog/caching)
- [Clickhouse Cloud Stateless Compute](https://clickhouse.com/blog/clickhouse-cloud-stateless-compute)
- [Mongodb Change Streams And Go 4J0B](https://dev.to/mongodb/mongodb-change-streams-and-go-4j0b)
- [Cloudflare Chooses PostgreSQL Extension Over Specialized OLAP for 100K Row/Second Analytics - InfoQ](https://www.infoq.com/news/2025/07/cloudflare-timescaledb-olap/)
- [Optimizing Docker Images: Performance, Security, and Efficiency](https://medium.com/@najdmerabet/optimizing-docker-images-performance-security-and-efficiency-947d29908e53)
- [Transformers from Scratch](https://e2eml.school/transformers.html)
- [Making Postgres 42,000x slower because I am unemployed](https://byteofdev.com/posts/making-postgres-slow/)
- [VictoriaLogs Practical Ingestion Guide for Message, Time and Streams](https://victoriametrics.com/blog/victorialogs-concepts-message-time-stream/)
- [Iceberg Topics For Apache Kafka Zero Etl Zero Copy](https://aiven.io/blog/iceberg-topics-for-apache-kafka-zero-etl-zero-copy)
- [Calvin Fast Distributed Transactions For Partitioned Database Systems](https://sayedalesawy.hashnode.dev/calvin-fast-distributed-transactions-for-partitioned-database-systems)
- [Go language previews performance-boosting garbage collector | InfoWorld](https://www.infoworld.com/article/4041753/go-language-previews-performance-boosting-garbage-collector.html)
- [Dor Moshe's Blog](https://dormoshe.io/trending-news/go-logging-best-practices-fast-structured-and-production-ready-87269?utm_source=twitter&utm_campaign=twitter)
- [Grafana's metrics backend for go-mysql-server | DoltHub Blog](https://dolthub.com/blog/2025-09-25-grafana-with-go-mysql-server/)
- [A Beginners Guide To Cdc Change Data Capture](https://vladmihalcea.com/a-beginners-guide-to-cdc-change-data-capture/)
- [Log Sql Spring Boot](https://vladmihalcea.com/log-sql-spring-boot/)
- [Book Review - Troubleshooting Java - Vlad Mihalcea](https://vladmihalcea.com/book-review-troubleshooting-java/)
- [Postgresql Plan Cache Mode](https://vladmihalcea.com/postgresql-plan-cache-mode/)
- [The Complete Guide to Vector Databases for Machine Learning -](https://machinelearningmastery.com/the-complete-guide-to-vector-databases-for-machine-learning/)
- [Testcontainers Database Integration Testing](https://vladmihalcea.com/testcontainers-database-integration-testing/)
- [Build Your Own Database](https://www.nan.fyi/database)
- [Test Data Access Layer](https://vladmihalcea.com/test-data-access-layer/)
- [How To Import Csv Data Into Postgresql](https://vladmihalcea.com/how-to-import-csv-data-into-postgresql/)
- [Relational Database Sql Prepared Statements](https://vladmihalcea.com/relational-database-sql-prepared-statements/)
- [Effective Error Handling: A Uniform Strategy for Heterogeneous Distributed Systems - InfoQ](https://www.infoq.com/podcasts/uniform-strategy-heterogeneous-distributed-systems/)
- [A practical guide to high-performance serverless with GraalVM and Spring | InfoWorld](https://www.infoworld.com/article/4078803/taming-the-java-cold-start-beast-a-practical-guide-to-high-performance-serverless-with-graalvm-and-spring.html)
- [Building a Kubernetes Platform: Think Big, Think in Planes](https://itnext.io/building-a-kubernetes-platform-think-big-think-in-planes-ede8bcba295f)
- [Postgres Pubsub Queue Benchmarks](https://topicpartition.io/blog/postgres-pubsub-queue-benchmarks)
- [Building a Resilient Data Platform with Write-Ahead Log at Netflix](https://netflixtechblog.com/building-a-resilient-data-platform-with-write-ahead-log-at-netflix-127b6712359a)
- [Jdbc Profiling Visualvm](https://vladmihalcea.com/jdbc-profiling-visualvm/)
- [Hibernate Performance Tuning Tips](https://vladmihalcea.com/hibernate-performance-tuning-tips/)
- [PostgreSQL High-Availability Architectures | CYBERTEC PostgreSQL | Services & Support](https://www.cybertec-postgresql.com/en/postgresql-high-availability-architectures/)
- [Go ahead, self-host Postgres | Pierce Freeman](https://pierce.dev/notes/go-ahead-self-host-postgres)
- [How to Build a Database Without a Server - InfoQ](https://www.infoq.com/presentations/arcticdb-db-no-server/)
- [Introducing: Postgres Best Practices](https://supabase.com/blog/postgres-best-practices-for-ai-agents)
- [Startup Perks Database | Free Credits & Discounts for Startups](https://www.startupperks.xyz/?fbclid=IwY2xjawPyJxhleHRuA2FlbQIxMQBzcnRjBmFwcF9pZA80MDk5NjI2MjMwODU2MDkAAR62SXXibjicDmfrlWxmwI4etGN1dPRO5qdRx-BpxETaG_W9c4cqyupJIG7KZA_aem_wWFWr6sQHuehN4eGW9EchA)
- [Build Your Own Key-Value Storage Engine—Week 6: Block-Based SSTables and Indexing](https://read.thecoder.cafe/p/build-your-own-kv-engine-6)
- [Transactions](http://pscale.link/transactions)
- [PostgreSQL triggers and isolation levels - Vlad Mihalcea](https://vladmihalcea.com/postgresql-triggers-isolation-levels/)
- [Netflix Automates RDS PostgreSQL to Aurora PostgreSQL Migration Across 400 Production Clusters - InfoQ](https://www.infoq.com/news/2026/03/netflix-automates-rds-aurora/)
- [Kfc Architecture Blueprint Kafka Flink And Clickhouse](https://bigdataboutique.com/blog/kfc-architecture-blueprint-kafka-flink-and-clickhouse)
- [Inside the JVM: The Engineering Behind Enterprise Performance](https://www.tmdevlab.com/jvm-engineering-enterprise-performance.html)
- [Humanoid Atlas | Humanoid Robot Supply Chain Map & OEM Database](https://www.humanoids.fyi/)
- [Databasemaxxing](https://pthorpe92.dev/databasemaxxing/)
- [Build A Bank Ledger In Go With Postgresql Using The Double Entry Accounting Principle](https://www.freecodecamp.org/news/build-a-bank-ledger-in-go-with-postgresql-using-the-double-entry-accounting-principle/)
- [How TimescaleDB Expands the PostgreSQL IIoT Performance Envelope | Tiger Data](https://www.tigerdata.com/blog/how-timescaledb-expands-postgresql-iiot-performance-envelope)
- [Redis](https://build-your-own.org/redis/)

---

## Java & JVM

### Repositories

- [Forks  airbnb/javascript](https://github.com/airbnb/javascript)
- [sivaprasadreddy/hexagonal-architecture-java-fork](https://github.com/sivaprasadreddy/hexagonal-architecture-java-fork/tree/spring-boot-layered)
- [ionutbalosin/java-application-security-practices](https://github.com/ionutbalosin/java-application-security-practices)

### Papers & Research

- [Loading PDF…](https://courses.csail.mit.edu/6.042/spring18/mcs.pdf)

### Books & Courses

- [Generative Ai For Java And Spring Developers](https://www.coursera.org/specializations/generative-ai-for-java-and-spring-developers)
- [Computation Structures | Electrical Engineering and Computer Science | MIT OpenCourseWare](https://ocw.mit.edu/courses/6-004-computation-structures-spring-2017/)

### Articles & Tutorials

- [Hunting Memory Leaks In Java](https://www.toptal.com/java/hunting-memory-leaks-in-java)
- [Best Way to Master Spring Boot – A Complete Roadmap - GeeksforGeeks](https://www.geeksforgeeks.org/best-way-to-master-spring-boot-a-complete-roadmap/)
- [120+ Core Java Interview Questions and Answers in 2022](https://www.edureka.co/blog/interview-questions/java-interview-questions/)
- [When To Use The Dynamicupdate With Spring Data Jpa](https://dzone.com/articles/when-to-use-the-dynamicupdate-with-spring-data-jpa)
- [Spring Transaction Management Transactional In Depth](https://www.marcobehler.com/guides/spring-transaction-management-transactional-in-depth)
- [inside.java](http://inside.java)
- [50 Microservices Interview Questions for Java Programmers | by Soma | Javarevisited | Jan, 2023 | Medium](https://medium.com/javarevisited/50-microservices-interview-questions-for-java-programmers-70a4a68c4349)
- [The Basics of Java Generics | Baeldung](https://www.baeldung.com/java-generics)
- [Java67: What is CQRS Pattern in Java Microservices? Command Query Responsibility Segregation Example Tutorial](https://www.java67.com/2023/01/what-is-cqrs-command-query.html)
- [Javarevisited: System Design Interview Prep Guide 2023 - Topics, Questions, and Resources](https://javarevisited.blogspot.com/2022/03/how-to-prepare-for-system-design.html)
- [Practical Examples of the Big O Notation | Baeldung on Computer Science](https://www.baeldung.com/cs/big-oh-asymptotic-complexity)
- [Introduction to gRPC with Spring Boot](https://piotrminkowski.com/2023/08/29/introduction-to-grpc-with-spring-boot/)
- [Java Developer](https://career.luxoft.com/job/java-developer/359930/)
- [A categorized list of all Java and JVM features since JDK 8 to 21 - Advanced Web Machinery](https://advancedweb.hu/a-categorized-list-of-all-java-and-jvm-features-since-jdk-8-to-21/)
- [Memory Management in Java: An Introduction](https://foojay.io/today/java-memory-management/)
- [Step-by-Step Guide to Becoming a Java Architect](https://www.analyticsinsight.net/step-by-step-guide-to-becoming-a-java-architect/)
- [Runtime efficiency with Spring (today and tomorrow)](https://spring.io/blog/2023/10/16/runtime-efficiency-with-spring)
- [Spring Boot Multi-tenant Architecture Overview](https://medium.com/@konstde00/spring-boot-multi-tenant-architecture-overview-88198ea3991f)
- [Spring Security](https://www.marcobehler.com/guides/spring-security#_introduction)
- [Spring Data REST: Say Goodbye to Controller and Service](https://medium.com/@mertkagan/spring-data-rest-say-goodbye-to-controller-and-service-1acb6c7437f1)
- [Implement Your Search/Filter Criteria API with Spring Data JPA Specifications](https://blog.stackademic.com/implement-your-search-filter-api-with-spring-data-jpa-specifications-365f2089ef1c)
- [Mastering @Transactional Annotations in Spring Boot](https://medium.com/hprog99/mastering-transactional-annotations-in-spring-boot-eef339543afe)
- [Spring Security — The Security Filter Chain](https://kasunprageethdissanayake.medium.com/spring-security-the-security-filter-chain-2e399a1cb8e3)
- [Navigating Java Developer Interviews: Core Concepts, Spring Insights, Design Patterns, Coding](https://medium.com/javarevisited/navigating-java-developer-interviews-core-concepts-spring-insights-design-patterns-coding-9101ef4f769c)
- [Spring Security Password Handling](https://reflectoring.io/spring-security-password-handling/)
- [Virtual Threads in Spring Boot](https://blog.devgenius.io/virtual-threads-in-spring-boot-f720dcdf018c)
- [Java 11 to 21: A Visual Guide for Seamless Migrati - DZone](https://dzone.com/articles/java-11-to-21-a-visual-guide-for-seamless-migratio)
- [Transitioning from RestTemplate to WebClient in Spring Boot: A Detailed Guide](https://medium.com/hprog99/transitioning-from-resttemplate-to-webclient-in-spring-boot-a-detailed-guide-4febd21063ba)
- [Building Scalable Microservices with gRPC, Spring Boot, and Maven](https://towardsdev.com/building-scalable-microservices-with-grpc-spring-boot-and-maven-fe49c377e450)
- [Java Memory Management and Garbage Collection](https://medium.com/@perspectivementor/java-memory-management-and-garbage-collection-fdf227569a61)
- [Spring Data Jpa Skip Select Insert](https://www.baeldung.com/spring-data-jpa-skip-select-insert?fbclid=IwAR2MOgnkd0da49tkvfBvMOzkJVaZLGAWHRFnKNlZgwQHkaGLKFjlUUg-oT8)
- [Java Concurrency 101: Understanding Multithreading Fundamentals](https://dip-mazumder.medium.com/java-concurrency-101-understanding-multithreading-fundamentals-e5ed48b04ca5)
- [Transactions Caching And Aop Understanding Proxy Usage In Spring](https://spring.io/blog/2012/05/23/transactions-caching-and-aop-understanding-proxy-usage-in-spring)
- [Mastering Design Patterns in Java](https://medium.com/javarevisited/mastering-design-patterns-in-java-1e39194ac480)
- [SOLID Principles Explained in Java](https://medium.com/javarevisited/solid-principles-explained-in-java-5b9fca1f5540)
- [JPA Auditing — Spring Boot & Spring Security](https://medium.com/thefreshwrites/jpa-auditing-spring-boot-spring-security-575c77867570)
- [Build a Shopping Cart Backend with Spring Boot and Spring Security](https://www.freecodecamp.org/news/build-a-shopping-cart-backend-with-spring-boot-and-spring-security/)
- [Java 23 Has Arrived Whats New 9 Minute Read I61](https://dev.to/isaactony/java-23-has-arrived-whats-new-9-minute-read-i61)
- [JVM Anatomy Quarks](https://shipilev.net/jvm/anatomy-quarks/)
- [Java 8 vs Java 11 vs Java 17 vs Java 21: A Comprehensive Comparison](https://medium.com/@a.r.m.monesan_9577/java-8-vs-java-11-vs-java-17-vs-java-21-a-comprehensive-comparison-aa4635f9c3fe)
- [Mastering Task Scheduling: Essential Tricks for Senior Spring Boot Developers](https://levelup.gitconnected.com/mastering-task-scheduling-essential-tricks-for-senior-spring-boot-developers-934f42e0b425)
- [Java Backend Roadmap](https://blog.codewithhamza.dev/java-backend-roadmap)
- [Mastering Event-Driven Microservices with the Command Pattern in Spring Boot & RabbitMQ](https://medium.com/@muhannadalhariri/mastering-event-driven-microservices-with-the-command-pattern-in-spring-boot-rabbitmq-f4b053e31f31)
- [Clean and Modular Java: A Hexagonal Architecture Approach](https://foojay.io/today/clean-and-modular-java-a-hexagonal-architecture-approach/)
- [Essential JVM Heap Settings: What Every Java Developer Should Know | by Abhinav Sonkar | in ITNEXT - Freedium](https://freedium.cfd/https://itnext.io/essential-jvm-heap-settings-what-every-java-developer-should-know-b1e10f70ffd9)
- [How I Optimized a Spring Boot Application to Handle 1M Requests/Second](https://medium.com/javarevisited/how-i-optimized-a-spring-boot-application-to-handle-1m-requests-second-0cbb2f2823ed)
- [From 1K Users to 1B Records: Where Spring Boot Started Breaking | by Pudari Madhavi | Jul, 2025 | Stackademic](https://blog.stackademic.com/from-1k-users-to-1b-records-where-spring-boot-started-breaking-708b17e78351)
- [8+ Years of Java and I Still Missed These Spring Boot Speed Secrets](https://medium.com/@gaddamnaveen192/8-years-of-java-and-i-still-missed-these-spring-boot-speed-secrets-a0e514c48f85)
- [How I document production-ready Spring Boot applications - Wim Deblauwe](https://www.wimdeblauwe.com/blog/2025/09/08/how-i-document-production-ready-spring-boot-applications/)
- [Dev](https://docling-project.github.io/docling-java/dev/)
- [Spring AI tutorial: Get started with Spring AI | InfoWorld](https://www.infoworld.com/article/4091447/spring-ai-tutorial-get-started-with-spring-ai.html)
- [Migrating to Modular Monolith using Spring Modulith and IntelliJ IDEA | The IntelliJ IDEA Blog](https://blog.jetbrains.com/idea/2026/02/migrating-to-modular-monolith-using-spring-modulith-and-intellij-idea/)
- [JVM Internals](http://blog.jamesdbloom.com/JVMInternals.html)
- [You Dont Need Lombok Anymore](https://loiane.com/2026/03/you-dont-need-lombok-anymore/)
- [1. 2. 3. 4. 5](https://systemweakness.com/profiling-allocation-hotspots-in-spring-boot-real-tools-real-fixes-7eed552de171)
- [1. 2. 3. 4. 5](https://piotrminkowski.com/2026/03/24/claude-code-template-for-spring-boot/)
- [AI4JVM — Java & JVM AI Ecosystem Guide: Agent Frameworks, Inference Engines & Tools](https://ai4jvm.com)
- [Course info – Compilers](https://hy-compilers.github.io/spring-2026/)
- [How We Built A Java Ai Agent By Connecting The Dots The Ecosystem Already Had](https://foojay.io/today/how-we-built-a-java-ai-agent-by-connecting-the-dots-the-ecosystem-already-had/)

---

## Go (Golang)

### Repositories

- [dockersamples/go-prometheus-monitoring](https://github.com/dockersamples/go-prometheus-monitoring)
- [iyashjayesh/monigo](https://github.com/iyashjayesh/monigo)
- [GitHub - golang-jwt/jwt: Go implementation of JSON Web Tokens (JWT).  GitHub](https://github.com/golang-jwt/jwt)

### Articles & Tutorials

- [Mastering Real-Time Data Pipelines in Golang with Channels and Worker Pools](https://levelup.gitconnected.com/mastering-real-time-data-pipelines-in-golang-with-channels-and-worker-pools-7eae2f2d662b)
- [How To Process Gigantic Files In Golang Fast And Memory Efficient](https://albertcolom.com/posts/how-to-process-gigantic-files-in-golang-fast-and-memory-efficient/)
- [How to implement the Outbox pattern in Go and Postgres](https://packagemain.tech/p/how-to-implement-the-outbox-pattern-in-golang)
- [HTTP Connection Pooling in Go by David Bacisin](https://davidbacisin.com/writing/golang-http-connection-pools-1)
- [Learning Go in 2026; From Beginner to Senior](https://www.bytesizego.com/blog/learning-golang-2026)
- [Go vs Java: Which One Should You Choose?](https://www.analyticsinsight.net/coding/programming-languages/go-or-java-choosing-the-right-language-for-your-project)
- [Just Fucking Use Go - Blain Smith](https://blainsmith.com/articles/just-fucking-use-go/)

---

## Rust & Low-Level Programming

### Repositories

- [GitHub - gurugio/lowlevelprogramming-university: How to be low-level programmer](https://github.com/gurugio/lowlevelprogramming-university)
- [GitHub - Whitecat18/Rust-for-Malware-Development: This repository contains complete resources and coding practices for malware development using Rust](https://github.com/Whitecat18/Rust-for-Malware-Development)
- [GitHub - DoctorWkt/acwj: A Compiler Writing Journey  GitHub](https://github.com/DoctorWkt/acwj)

### Articles & Tutorials

- [Introduction  Reverse Engineering](https://0xinfection.github.io/reversing/)
- [Memory Allocation Strategies - gingerBill](https://www.gingerbill.org/series/memory-allocation-strategies/)
- [Lets Build Regex](https://kean.blog/post/lets-build-regex)

---

## Algorithms & Data Structures

### Articles & Tutorials

- [sp21.datastructur.es](https://sp21.datastructur.es/)
- [Leetcode Patterns](https://seanprashad.com/leetcode-patterns/)
- [Blind 75 Leetcode Questions](https://leetcode.com/discuss/general-discussion/460599/blind-75-leetcode-questions)
- [Best Practice Questions](https://www.techinterviewhandbook.org/best-practice-questions)
- [Structy | Learn Algorithms, Efficiently.](https://structy.net/)
- [How To Effectively Use Leetcode To Prepare For Interviews](https://leetcode.com/discuss/career/449135/how-to-effectively-use-leetcode-to-prepare-for-interviews)
- [Umpire Interview Strategy](https://guides.codepath.com/compsci/UMPIRE-Interview-Strategy)
- [Leetcode Patterns](https://seanprashad.com/leetcode-patterns/?fbclid=IwAR3YiAD9k0_fqD9HlbH-6abx1g0Ykvdql0CMzSNgWwxzwhBD09jxXW-LKcw)
- [Data Structures And Algorithms Problems](https://www.techiedelight.com/data-structures-and-algorithms-problems)
- [Data Structures Handbook – The Key to Scalable Software](https://www.freecodecamp.org/news/data-structures-the-key-to-scalable-software/)
- [Big O — A Practical Approach. Using code examples to implement Big O… | by Christopher Karg | Jan, 2024 | Towards Data Science](https://towardsdatascience.com/big-o-a-practical-approach-319a6a3c8b27)
- [Linked Lists](https://pressbooks.palni.org/anopenguidetodatastructuresandalgorithms/chapter/linked-lists/)
- [Load Balancing Algorithms Comparison](https://dzone.com/articles/load-balancing-algorithms-comparison?edition=988306&email_hash=d81f265aee3958897ad13604b99e311b)
- [Probabilistic Data Structures: The Clever Tricks Every Engineer Should Know | by Amr Elhewy | in Stackademic - Freedium](https://freedium.cfd/https://medium.com/probabilistic-data-structures-the-clever-tricks-every-engineer-should-know-58552ffda6fd)
- [Associativity](https://en.algorithmica.org/hpc/cpu-cache/associativity/)
- [Big O Doesnt Tell The Whole Story](https://karimshalapy.com/blog/big-o-doesnt-tell-the-whole-story/)
- [Aos Soa](https://en.algorithmica.org/hpc/cpu-cache/aos-soa/)
- [Branching](https://en.algorithmica.org/hpc/pipelining/branching/)
- [RAM & CPU Caches - Algorithmica](https://en.algorithmica.org/hpc/cpu-cache/)
- [Dynamic Programming](https://dp.quantecon.org/)
- [Algorithms for Modern Hardware - Algorithmica](https://en.algorithmica.org/hpc/)
- [Algorithms by Jeff Erickson](https://jeffe.cs.illinois.edu/teaching/algorithms/)

---

## Kafka & Event Streaming

### Repositories

- [GitHub - pmoskovi/kafka-learning-resources: A curated list of Apache Kafka learning resources  GitHub](https://github.com/pmoskovi/kafka-learning-resources)

### Books & Courses

- [Apache Kafka](https://www.udemy.com/course/apache-kafka/)

### Articles & Tutorials

- [An Introduction to Stream Processing - The New Stack](https://thenewstack.io/an-introduction-to-stream-processing-2/)
- [Mastering Kafka — Internals and Implementation](https://towardsdev.com/mastering-kafka-internals-and-implementation-b06d8318f15a)
- [Choosing Between Message Queues and Event Streams - The New Stack](https://thenewstack.io/choosing-between-message-queues-and-event-streams/)
- [How to Build a Reliable Kafka Data Processing Pipeline, Focusing on Contention, Uptime and Latency](https://www.infoq.com/presentations/reliable-kafka-data-processing-pipeline/)
- [Mastering Kafka: A Developer's Production-Ready Checklist](https://medium.com/@sobinsunny/mastering-kafka-a-developers-production-ready-checklist-fdd9702f35cc)
- [Top 10 Tools for Kafka Engineers](https://thenewstack.io/top-10-tools-for-kafka-engineers/)
- [Rabbitmq Vs Kafka Vs Activemq In Fintech A Comparative Guide With Use Cases Challenges And Solutions 2C00](https://dev.to/iamcymentho/rabbitmq-vs-kafka-vs-activemq-in-fintech-a-comparative-guide-with-use-cases-challenges-and-solutions-2c00)
- [Reliably Processing Trillions of Kafka Messages Per Day](https://medium.com/walmartglobaltech/reliably-processing-trillions-of-kafka-messages-per-day-23494f553ef9)
- [Stream All the Things — Patterns of Effective Data Stream Processing](https://www.infoq.com/presentations/streaming-patterns/)
- [What Is Apache Kafka](https://learn.conduktor.io/kafka/what-is-apache-kafka/)
- [Building a Scalable Top-K Using Kafka & Flink](https://medium.com/p/building-a-scalable-top-k-using-kafka-flink-4ac1b61ce5e3?source=social.linkedin&_nonce=41PTHMP7)

---

## Kubernetes & Containers

### Repositories

- [techiescamp/kubernetes-learning-path: A roadmap to learn Kubernetes from scratch (Beginner to Advanced level)](https://github.com/techiescamp/kubernetes-learning-path)
- [GitHub - ghik/kubernetes-the-harder-way: A guide to setting up a production-like Kubernetes cluster on a local machine](https://github.com/ghik/kubernetes-the-harder-way)

### Articles & Tutorials

- [Kubernetes Basics, Core Components & YAML Files](https://medium.com/@fatmaecemozer/kubernetes-basics-core-components-yaml-files-2a11841eb72a)
- [Understanding Kubernetes Autoscaling | Network Computing](https://www.networkcomputing.com/networking/understanding-kubernetes-autoscaling)
- [Docker Networking](https://earthly.dev/blog/docker-networking/#:~:text=Docker%20networking%20is%20primarily%20used,fit%20for%20certain%20use%20cases)
- [Learn Kubernetes Complete Roadmap](https://devopscube.com/learn-kubernetes-complete-roadmap/)
- [Gitops Kubernetes Resources For Absolute Beginners](https://www.weave.works/blog/gitops-kubernetes-resources-for-absolute-beginners)
- [Kubernetes: ClusterIP vs NodePort vs LoadBalancer, Services, and Ingress — an Overview](https://itnext.io/kubernetes-clusterip-vs-nodeport-vs-loadbalancer-services-and-ingress-an-overview-with-722a07f3cfe1)
- [Video Streaming at Scale with Kubernetes and RabbitMQ](https://techblog.skeepers.io/video-streaming-at-scale-with-kubernetes-and-rabbitmq-6e23fd0e75fb)
- [Kubernetes Networking 101 Best Practices And Challenges](https://www.techtarget.com/searchITOperations/tip/Kubernetes-networking-101-Best-practices-and-challenges)
- [Chaos Engineering on Kubernetes: A Beginner's Guide — Revel in Chaos](https://medium.com/@seifeddinerajhi/chaos-engineering-on-kubernetes-a-beginners-guide-revel-in-chaos-0974ae9bee8b)
- [Deciphering the Kubernetes Networking Maze: Navigating Load-Balance, BGP, IPVS and Beyond](https://itnext.io/deciphering-the-kubernetes-networking-maze-navigating-load-balance-bgp-ipvs-and-beyond-7123ef428572)
- [Choosing the Perfect Kubernetes Workload: A Practical Guide for Application Success | by Gulcan Topcu | Jul, 2024](https://itnext.io/choosing-the-perfect-kubernetes-workload-a-practical-guide-for-application-success-fe905c40788a)
- [How to Effectively Utilize Kubernetes Namespaces](https://thekubeguy.com/how-to-effectively-utilize-kubernetes-namespaces-74a612f7f971)
- [Kubernetes: How Traffic Flows from Internet to Container via Istio](https://medium.com/google-cloud/kubernetes-how-traffic-flows-from-internet-to-container-via-istio-9b2958961086/)
- [End-to-End CI/CD Project I. Using Jenkins, SonarQube, Docker… | by Ishaan | Medium](https://medium.com/@fadedstarboy/end-to-end-ci-cd-project-dbc66c00aa3a)
- [The Technical History of Kubernetes | by Brian Grant | ITNEXT](https://itnext.io/the-technical-history-of-kubernetes-2fe1988b522a)
- [kubectl logs Command Reference and Documentation](https://uptrace.dev/blog/kubectl-logs.html)
- [Build a local Kubernetes cluster with free SSL and DNS management | by Nico Singh | Nov, 2024 | ITNEXT](https://itnext.io/build-a-local-kubernetes-cluster-with-free-ssl-and-dns-management-1ee2025b7ae8)
- [I Stopped Using Kubernetes. Our DevOps Team Is Happier Than Ever](https://blog.stackademic.com/i-stopped-using-kubernetes-our-devops-team-is-happier-than-ever-a5519f916ec0)
- [The Kubernetes Introduction I Wish I Had When I Started: A Complete Guide](https://medium.com/@ksaquib/the-kubernetes-introduction-i-wish-i-had-when-i-started-a-complete-guide-f5127f6b5a9f)
- [Mastering Multi Cluster Kubernetes Certificate Management With Cert Manager](https://komodor.com/blog/mastering-multi-cluster-kubernetes-certificate-management-with-cert-manager/)
- [Introduction to Service Mesh - The New Stack](https://thenewstack.io/introduction-to-service-mesh/)
- [Monitoring Go Applications Using Prometheus, Grafana, and Docker - DEV Community](https://dev.to/pradumnasaraf/monitoring-go-applications-using-prometheus-grafana-and-docker-33i5)
- [Kubernetes Containers Linux Processes](https://blog.esc.sh/kubernetes-containers-linux-processes/)
- [Choosing Your Local Kubernetes Companion: A Developer's Guide to Minikube, k0s, k3s, and MicroK8s - DEV Community](https://dev.to/mechcloud_academy/choosing-your-local-kubernetes-companion-a-developers-guide-to-minikube-k0s-k3s-and-microk8s-7g0)
- [Unlocking Lightweight Kubernetes Logging with Loki and Grafana](https://blog.devops.dev/unlocking-lightweight-kubernetes-logging-with-loki-and-grafana-84814c614445)
- [Kubernetes RBAC: A Comprehensive Guide](https://medium.com/@oshratn_61520/kubernetes-rbac-a-comprehensive-guide-6c191671f61e)
- [Setup Kubernetes Cluster Kubeadm](https://devopscube.com/setup-kubernetes-cluster-kubeadm/)
- [Understanding etcd in Kubernetes: A Beginner's Guide](https://medium.com/@__karnati/understanding-etcd-in-kubernetes-a-beginners-guide-743ecf17c361)
- [Welcome - OWASP EKS Goat: AWS EKS Security Masterclass Guide](https://eksgoat.kubernetesvillage.com/)
- [Kubernetes Production Checklist](https://blog.abhimanyu-saharan.com/posts/kubernetes-production-checklist)
- [Helm Chart Explained: Managing Kubernetes Applications with Ease](https://medium.com/@nemagan/helm-chart-explained-managing-kubernetes-applications-with-ease-c2977c05d972)
- [Istio as Rate Limiting and Circuit Breaking with Service Mesh](https://haluan.medium.com/istio-as-rate-limiting-and-circuit-breaker-with-service-mesh-5c9389970fe4)
- [HashiCorp Vault on Kubernetes](https://medium.com/@shashwattripathi11/hashicorp-vault-on-kubernetes-69119921a7e1)
- [Introduction - The Cluster API Book](https://cluster-api.sigs.k8s.io/)
- [Understanding Docker: part 49 – Docker Compose (2025)](https://dev.to/aurelievache/understanding-docker-part-49-docker-compose-2025-5fdd)
- [Warmup Your Pods Using Istio](https://medium.com/blablacar/warmup-your-pods-using-istio-5249ec68f0e9)
- [Container Network Interface (CNI) in Kubernetes: An Introduction](https://itnext.io/container-network-interface-cni-in-kubernetes-an-introduction-6cd453b622bd)
- [KEDA: Kubernetes Event-Driven Autoscaling — A Deep Dive](https://blog.stackademic.com/keda-kubernetes-event-driven-autoscaling-a-deep-dive-53569623b53a)
- [Kubernetes Survival Kit](https://dzone.com/articles/kubernetes-survival-kit)
- [Learning Go Testing From K8S 52Oo](https://dev.to/leapcell/learning-go-testing-from-k8s-52oo)
- [Opa With Kubernetes](https://www.groundcover.com/blog/opa-with-kubernetes)
- [Kubernetes Egress](https://www.solo.io/topics/istio/kubernetes-egress)
- [Securing Kubernetes: Implementing Pod Security Admission (PSA) with Real-World Examples](https://blog-ocampoge.medium.com/securing-kubernetes-implementing-pod-security-admission-psa-with-real-world-examples-94bb9b602ecb)
- [Kubernetes Networking](https://spacelift.io/blog/kubernetes-networking/)
- [All You Need to Know About Kubernetes Namespace](https://blog.devops.dev/all-you-need-to-know-about-kubernetes-namespace-4ee42776f30b)
- [Monitoring Kubernetes Clusters with Prometheus and Grafana: A Comprehensive Guide](https://medium.com/@amadou.diallo_84730/monitoring-kubernetes-clusters-with-prometheus-and-grafana-a-comprehensive-guide-5007cf3088ab)
- [Top Metrics To Watch In Kubernetes](https://dzone.com/articles/top-metrics-to-watch-in-kubernetes)
- [Kubernetes Init Containers](https://devopscube.com/kubernetes-init-containers/)
- [How Container Filesystem Works: Building a Docker-like Container From Scratch](https://labs.iximiuz.com/tutorials/container-filesystem-from-scratch)
- [Kubernetes Services and Traffic Flow Analysis with Kubeshark](https://medium.com/@wangareirungu3/kubernetes-services-and-traffic-flow-analysis-with-kubeshark-736bfb9875a9)
- [eBPF Beginner Skill Path](https://labs.iximiuz.com/skill-paths/ebpf-beginner-skill-path-aa16c6e8)
- [k8s-1m Overview](https://bchess.github.io/k8s-1m/)
- [Canary Deployment in Kubernetes with Zero Downtime](https://medium.com/@anil.goyal0057/canary-deployment-in-kubernetes-with-zero-downtime-15188a296d3c)
- [A Guide To Kubernetes Vpa](https://www.randoli.io/blogs/a-guide-to-kubernetes-vpa)
- [Podman Tutorial Beginners](https://devopscube.com/podman-tutorial-beginners/)
- [Beyond Namespaces Why Kubernetes Needs Real Workload Isolation](https://thenewstack.io/beyond-namespaces-why-kubernetes-needs-real-workload-isolation/)
- [The Hidden Headache Of Kubernetes Rbac](https://www.portainer.io/blog/the-hidden-headache-of-kubernetes-rbac?hss_channel=tw-779234043669774336)
- [Debugging Kubernetes Pods Like A Pro](https://dzone.com/articles/debugging-kubernetes-pods-like-a-pro?email_hash=d81f265aee3958897ad13604b99e311b)
- [Write Ahead Log Wal](https://newsletter.devopscube.com/p/write-ahead-log-wal)
- [Kubernetes Networking From Packets To Pods](https://www.lucavall.in/blog/kubernetes-networking-from-packets-to-pods)

---

## Cloud & AWS

### Repositories

- [GitHub - floci-io/floci: Light, fluffy, and always free - The AWS Local Emulator alternative  GitHub](https://github.com/floci-io/floci)

### Books & Courses

- [Transactional outbox pattern - AWS Prescriptive Guidance](https://docs.aws.amazon.com/prescriptive-guidance/latest/cloud-design-patterns/transactional-outbox.html)

### Articles & Tutorials

- [Paths](https://www.cloudskillsboost.google/paths/)
- [Design Patterns Serverless](https://www.infoq.com/news/2022/09/design-patterns-serverless/)
- [Animations | AWS Fundamentals](https://awsfundamentals.com/animations)
- [Strangler Fig Pattern - Azure Architecture Center | Microsoft Learn](https://learn.microsoft.com/en-us/azure/architecture/patterns/strangler-fig)
- [AWS Workshops](https://workshops.aws/)

---

## DevOps & CI/CD

### Repositories

- [bregman-arie/devops-exercises](https://github.com/bregman-arie/devops-exercises)
- [DevOpsHiveHQ/dynamic-devops-roadmap](https://github.com/DevOpsHiveHQ/dynamic-devops-roadmap/tree/main/projects/hivebox)

### Articles & Tutorials

- [Blue Green Canary Deployment Strategies](https://harness.io/blog/continuous-verification/blue-green-canary-deployment-strategies)
- [Minimum Viable CD ::](https://minimumcd.org/minimumcd/)
- [Engineering Best Practices of CI Pipelines - The New Stack](https://thenewstack.io/engineering-best-practices-of-ci-pipelines/)
- [Understanding the Linux Filesystem: An In-Depth Guide for DevOps Engineers - DEV Community](https://dev.to/prodevopsguytech/understanding-the-linux-filesystem-an-in-depth-guide-for-devops-engineers-ona)
- [The Complete Jenkins DevOps CI/CD Pipeline Bootcamp: Master Continuous Integration and Delivery](https://medium.com/@subhamchand200/the-complete-jenkins-devops-ci-cd-pipeline-bootcamp-master-continuous-integration-and-delivery-a87806c893ea)
- [Jenkins Tutorial](https://spacelift.io/blog/jenkins-tutorial)

---

## Operating Systems & Linux

### Repositories

- [GitHub - imthenachoman/How-To-Secure-A-Linux-Server: An evolving how-to guide for securing a Linux server](https://github.com/imthenachoman/How-To-Secure-A-Linux-Server)

### Articles & Tutorials

- [Operating Systems Notes](https://applied-programming.github.io/Operating-Systems-Notes/)
- [SadServers: Linux, DevOps & SRE Labs | Job Interview Prep](http://sadservers.com)
- [Before Main](https://amit.prasad.me/blog/before-main)
- [Ostep](https://pages.cs.wisc.edu/~remzi/OSTEP/)
- [Demystifying Debuggers, Part 2: The Anatomy Of A Running Program](https://www.rfleury.com/p/demystifying-debuggers-part-2-the#%C2%A7virtual-address-spaces)
- [Introduction to memory management — Memory Management Reference 4.0 documentation](https://www.memorymanagement.org/mmref/index.html#mmref-intro)
- [Internals for Interns](https://internals-for-interns.com/)
- [CS Illustrated: Welcome!](https://people.eecs.berkeley.edu/~ddgarcia/teaching/csillustrated/index.php)
- [Emulsiv](https://eseo-tech.github.io/emulsiV/)

---

## eBPF & Systems Tracing

### Articles & Tutorials

- [An Applied Introduction to eBPF with Go — Ozan Sazak](https://sazak.io/articles/an-applied-introduction-to-ebpf-with-go-2024-06-06)
- [What Is Ebpf](https://ebpf.io/what-is-ebpf/)
- [ebpf.party](https://ebpf.party/)

---

## Networking & Protocols

### Repositories

- [devanshbatham/Everything-About-DNS](https://github.com/devanshbatham/Everything-About-DNS)

### Papers & Research

- [How to Read a Paper (Keshav)](http://ccr.sigcomm.org/online/files/p83-keshavA.pdf)

### Articles & Tutorials

- [What Is Software Complexity](https://carlalexander.ca/what-is-software-complexity/?fbclid=IwAR1FgWDC8sxn_QBGukzSbAJLfrdTG6Nvdea83ehQ1ADbE4-NaqGi2uHlmuU)
- [Mastering NGINX: A Beginner-Friendly Guide to Building a Fast, Secure, and Scalable Web Server](https://medium.com/@nomannayeem/mastering-nginx-a-beginner-friendly-guide-to-building-a-fast-secure-and-scalable-web-server-cb075b423298)
- [If you're not using them already, you need to set up Nginx reverse proxies in your home lab - here's how](https://www.xda-developers.com/how-to-set-up-nginx-reverse-proxies-in-your-home-lab/)
- [HyperText Transfer Protocol (HTTP) explained](https://http.dev/)
- [What Are Namespaces Cgroups How Do They Work](https://blog.nginx.org/blog/what-are-namespaces-cgroups-how-do-they-work)
- [NGINX Architecture – NGINX Community Blog](https://blog.nginx.org/nginx-architecture)

---

## Security

### Repositories

- [GitHub - Z4nzu/hackingtool: ALL IN ONE Hacking Tool For Hackers  GitHub](https://github.com/Z4nzu/hackingtool?fbclid=IwY2xjawRb1S1leHRuA2FlbQIxMQBzcnRjBmFwcF9pZA80MDk5NjI2MjMwODU2MDkAAR6qWi6FPHDP2RxwLk0dM_rNpYPvXJvvFdUTIkcrIcLAlgU1T_TXF1JkApYfjg_aem_W0yr9UaBw9m9mSz7TtGrZA)
- [GitHub - gitleaks/gitleaks at  GitHub](https://github.com/gitleaks/gitleaks?utm_source=opensourceprojects.dev&ref=opensourceprojects.dev)

### Articles & Tutorials

- [Don't Tackle Security Alone: A Beginner's Guide To OWASP - DEV Community](https://blog.gitguardian.com/a-beginners-guide-to-owasp/)
- [OAuth vs OpenID Connect](https://levelup.gitconnected.com/oauth-vs-openid-connect-8c567a017b46)
- [Everything That You Need to Know About OAuth2](https://medium.com/@vikas.taank_40391/everything-that-you-need-to-know-about-oauth2-fb6a29b59e46)
- [How Does OAuth 2.0 Work?](https://medium.com/@techworldwithmilan/how-does-oauth-2-0-work-bea67a760aa5)
- [Resources](https://www.securityjourney.com/resources)
- [./ - Hitchhiker's Guide](https://www.anonymousplanet.org/guide/)
- [Bug Bounty Masterclass | Wiz](https://www.wiz.io/bug-bounty-masterclass)

---

## Machine Learning & AI

### Repositories

- [GitHub - rasbt/LLMs-from-scratch: Implement a ChatGPT-like LLM in PyTorch from scratch, step by step](https://github.com/rasbt/LLMs-from-scratch)
- [QwenLM/Qwen3-VL](https://github.com/QwenLM/Qwen3-VL#cookbooks)
- [GitHub - Infatoshi/all-of-it](https://github.com/Infatoshi/all-of-it)
- [GitHub - mlabonne/llm-course: Course to get into Large Language Models (LLMs) with roadmaps and Colab notebooks](https://github.com/mlabonne/llm-course)
- [GitHub - HenryNdubuaku/maths-cs-ai-compendium: Become a cracked AI/ML Research Engineer  GitHub](https://github.com/HenryNdubuaku/maths-cs-ai-compendium)
- [GitHub - Gitlawb/openclaude: Claude Code opened to any LLM — OpenAI, Gemini, DeepSeek, Ollama, and 200+ models via OpenAI-compatible API shim  GitHub](https://github.com/Gitlawb/openclaude)
- [llm-wiki  GitHub](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f)
- [GitHub - amitshekhariitbhu/llm-internals: Learn LLM internals step by step - from tokenization to attention to inference optimization.  GitHub](https://github.com/amitshekhariitbhu/llm-internals)

### Papers & Research

- [2409.02668](https://arxiv.org/abs/2409.02668)
- [2512.04859v1.pdf](https://arxiv.org/pdf/2512.04859v1)

### Articles & Tutorials

- [Deep Learning Drizzle](https://deep-learning-drizzle.github.io/?fbclid=IwAR0I_rx1toiamVdLpveDSaTOVUrb8zi0RjbBhGcslObwTrflR-ajDtoa7vs)
- [Natural Language Processing Demystified](https://www.nlpdemystified.org/?fbclid=IwAR1McmUU5lQagcLuwZTc3g_OLmQoHKRFA0co1BG62yq005D2z9OixkBufKQ)
- [Chat with Open Large Language Models](https://chat.lmsys.org/)
- [LLMs from Scratch Using Middle School Math | Towards Data Science](https://towardsdatascience.com/understanding-llms-from-scratch-using-middle-school-math-e602d27ec876)
- [Introduction — Machine Learning from Scratch](https://dafriedman97.github.io/mlbook/content/introduction.html)
- [Practical Deep Learning for Coders - Practical Deep Learning](https://course.fast.ai/)
- [The Roadmap of Mathematics for Machine Learning](https://thepalindrome.org/p/the-roadmap-of-mathematics-for-machine-learning)
- [Quantization from the ground up | ngrok blog](https://ngrok.com/blog/quantization)

---

## AI Agents & Claude Code

### Repositories

- [microsoft/mcp-for-beginners](https://github.com/microsoft/mcp-for-beginners)
- [affaan-m/everything-claude-code](https://github.com/affaan-m/everything-claude-code)
- [GitHub - obra/superpowers: An agentic skills framework & software development methodology that works.  GitHub](https://github.com/obra/superpowers)
- [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- [instructkr/claw-code](https://github.com/instructkr/claw-code)
- [kyegomez/OpenMythos](https://github.com/kyegomez/OpenMythos)

### Articles & Tutorials

- [What are MCP Servers?  The Fly Blog](https://fly.io/blog/mcps-everywhere/)
- [The Agent Skills Directory](https://skills.sh/)

---

## Monitoring & Observability

### Repositories

- [GitHub - ccfos/nightingale: Nightingale for monitoring and alerting, just as Grafana for visualization](https://github.com/ccfos/nightingale)
- [GitHub - openreplay/openreplay: Session replay, cobrowsing and product analytics you can self-host. Ideal for reproducing issues and iterating on your product](https://github.com/openreplay/openreplay)
- [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code)
- [GitHub - Tracer-Cloud/opensre: Build your own AI SRE agents. The open source toolkit for the AI era   GitHub](https://github.com/Tracer-Cloud/opensre?twclid=274p4nirdyoa0st0i6laqhcas0)

### Articles & Tutorials

- [What Is Observability Key Components Best Practices](https://www.honeycomb.io/blog/what-is-observability-key-components-best-practices)
- [Modern Load Testing for Engineering Teams with k6 and Grafana | by Prateek Jain | Jun, 2025 | Medium](https://blog.prateekjain.dev/modern-load-testing-for-engineering-teams-with-k6-and-grafana-4214057dff65)
- [Riding the Wave: OTel Experts Share Observability Tips](https://thenewstack.io/riding-the-wave-otel-experts-share-observability-tips/)
- [Books](https://sre.google/books/)
- [Learn Opentelemetry Tracing Through A Grand Strategy Game Introducing Game Of Traces](https://grafana.com/blog/2025/08/11/learn-opentelemetry-tracing-through-a-grand-strategy-game-introducing-game-of-traces/?_bhlid=4734d33bf7644a5c30ee0c2ea8c6d162aaab30a3)
- [Openmetrics Vs Opentelemetry](https://signoz.io/blog/openmetrics-vs-opentelemetry/?_bhlid=108b7386cdea405f86cdb80d28fe181dca8a3cb0)
- [Prometheus Monitoring: Complete Setup & Best Practices](https://medium.com/@rosgluk/prometheus-monitoring-complete-setup-best-practices-9cee2d179038)
- [Build Your Own Key-Value Storage Engine—Week 3: Durability with Write-Ahead Logging](https://read.thecoder.cafe/p/build-your-own-kv-engine-3)
- [A Guide to Safe, Incremental Open Source Observability Migration - The New Stack](https://thenewstack.io/a-guide-to-safe-incremental-open-source-observability-migration/)
- [Explain Plan Visualizer by Datadog](https://explain.datadoghq.com/)
- [Logging Sucks - Your Logs Are Lying To You](https://loggingsucks.com/)

---

## Performance & Optimization

### Papers & Research

- [What Every Programmer Should Know About Memory](https://people.freebsd.org/~lstewart/articles/cpumemory.pdf)

### Articles & Tutorials

- [A Software Engineers Guide To Reading Papers](https://blog.codingconfessions.com/p/a-software-engineers-guide-to-reading-papers)
- [Memory Profiling Part1](https://easyperf.net/blog/2024/02/12/Memory-Profiling-Part1)
- [Bloom Filters](https://samwho.dev/bloom-filters)
- [About Memory Pressure Lock Contention And Data Oriented Design](https://mnt.io/articles/about-memory-pressure-lock-contention-and-data-oriented-design/)
- [Hashing](https://samwho.dev/hashing/)
- [Virtual Memory](https://blog.codingconfessions.com/p/virtual-memory)

---

## Data Engineering

### Repositories

- [GitHub - DataExpert-io/data-engineer-handbook: This is a repo with links to everything you'd ever want to learn about data engineering](https://github.com/DataExpert-io/data-engineer-handbook)
- [GitHub - lynnlangit/learning-data-mesh: Repo with resources for learning Data Mesh  GitHub](https://github.com/lynnlangit/learning-data-mesh)

### Articles & Tutorials

- [A non-beginner Data Engineering Roadmap — 2025 Edition | by Ernani Castro | Feb, 2025 | Data Engineer Things](https://blog.det.life/a-non-beginner-data-engineering-roadmap-2025-edition-2b39d865dd0b)
- [How to Ingest 20-year-stock-trading data REST API with Apache Spark the right way (without Auto Loader)](https://blog.det.life/how-to-ingest-20-year-stock-trading-data-rest-api-with-apache-spark-the-right-way-without-auto-50a1da303077)
- [Tomato Architecture](https://tomato-architecture.netlify.app/)
- [Kubepath](https://hefni-learn.netlify.app/kubepath)

---

## Computer Science Fundamentals

### Repositories

- [GitHub - ossu/computer-science: Path to a free self-taught education in Computer Science!](https://github.com/ossu/computer-science)
- [GitHub - Developer-Y/cs-video-courses: List of Computer Science courses with video lectures](https://github.com/Developer-Y/cs-video-courses)

### Papers & Research

- [Basic Writing and Syntax Book (CMU)](https://www.math.cmu.edu/~jmackey/151_128/bws_book.pdf)

### Articles & Tutorials

- [Agentultra - How I Learned Everything I Know About Programming](https://agentultra.com/blog/how-i-learned-everything-i-know/index.html)
- [Algebrica | A Mathematical Knowledge Base](https://algebrica.org/)

---

## Career & Engineering Growth

### Repositories

- [jordan-cutler/path-to-senior-engineer-handbook](https://github.com/jordan-cutler/path-to-senior-engineer-handbook)
- [Egytech Fyi](https://github.com/egytech-fyi)
- [jorgef/engineeringladders](https://github.com/jorgef/engineeringladders)

### Articles & Tutorials

- [Better Dev Link - Resource around the web on becoming a better programmer](https://betterdev.link/?fbclid=IwAR1CeBlirD7X4ytiXNsMLZjsv-5AsCoaqVu3ZzUC38aLrZ-_LnVzRGtOPxA)
- [Relocation Jobs with Visa Sponsorship | Global Opportunities](https://visajobs.xyz/)
- [Uk Global Talent Visa Work And Live](https://relocateme.substack.com/p/uk-global-talent-visa-work-and-live)
- [The Relocation Friendly Tech Jobs](https://relocateme.substack.com/p/the-relocation-friendly-tech-jobs)
- [Providing Feedback: A Practical Guide](https://ahmd.io/blog/2026/02/11/providing-feedback-a-practical-guide/)
- [Some Things Just Take Time](https://lucumr.pocoo.org/2026/3/20/some-things-just-take-time/)
- [Ludwig - On becoming competitive when joining a new company](https://ludwigabap.com/posts/on-becoming-competitive-when-joining-a-new-company/)

---

## Courses, Books & Learning Paths

### Books & Courses

- [1](https://www.coursera.org/learn/computer-networking/home/week/1)
- [Principles and Patterns for Distributed Application Architecture [Book]](https://learning.oreilly.com/library/view/-/9781098181260/)

### Articles & Tutorials

- [Quiz](https://bigfrontend.dev/quiz)
- [Patterns.dev](https://patterns.dev)
- [Coding Interview Prep For Big Tech](https://www.freecodecamp.org/news/coding-interview-prep-for-big-tech/)
- [What is the Five Layers Model? The Framework of the Internet Explained](https://www.freecodecamp.org/news/the-five-layers-model-explained/)
- [Different Types of APIs – SOAP vs REST vs GraphQL](https://www.freecodecamp.org/news/rest-vs-graphql-apis/)
- [The Ultimate AI/ML Roadmap For Beginners | Towards Data Science](https://contributor.insightmediagroup.io/?p=600052)
- [From Junior to Senior: The Skills Roadmap No One Talks About - DEV Community](https://dev.to/teamcamp/from-junior-to-senior-the-skills-roadmap-no-one-talks-about-18fn)
- [File Systems Architecture Explained](https://www.freecodecamp.org/news/file-systems-architecture-explained/)
- [Keycloak Identity And Access Management](https://www.freecodecamp.org/news/keycloak-identity-and-access-management/)
- [Build Your Own Key-Value Storage Engine—Week 1: In-Memory Store](https://read.thecoder.cafe/p/build-your-own-kv-engine-1)

---

## Robotics & Embedded Systems

### Repositories

- [GitHub - mithi/robotics-coursework:  Places where you can learn robotics (and stuff like that) online   GitHub](https://github.com/mithi/robotics-coursework)

---

## Open Source Tools & Projects

### Repositories

- [gohugoio/hugo](https://github.com/gohugoio/hugo?fbclid=IwAR2ZBPOGQWrgFsO3VRGlc64n6TRsrkvws7ZS71YqpC-mtrcIbGUO5MfJ_VQ)
- [siyuan-note/siyuan](https://github.com/siyuan-note/siyuan)
- [taubyte/tau](https://github.com/taubyte/tau)
- [mikeroyal/Self-Hosting-Guide](https://github.com/mikeroyal/Self-Hosting-Guide)
- [buildermethods/design-os](https://github.com/buildermethods/design-os)
- [GitHub - TryQuiet/quiet at](https://github.com/TryQuiet/quiet)
- [GitHub - dflow-sh/dflow  GitHub](https://github.com/dflow-sh/dflow)
- [GitHub - lucide-icons/lucide: Beautiful & consistent icon toolkit made by the community. Open-source project and a fork of Feather Icons.  GitHub](https://github.com/lucide-icons/lucide)

### Articles & Tutorials

- [How to Use Obsidian for Note-Taking : Beginner’s Guide 2025 - Geeky Gadgets](https://www.geeky-gadgets.com/obsidian-note-taking-app-guide-2025/)
- [OutRay - an open source alternative to ngrok](https://outray.dev/)

---

## Engineering Blogs & General Resources

### Repositories

- [detailyang/awesome-cheatsheet: awesome cheatsheet](https://github.com/detailyang/awesome-cheatsheet)
- [GitHub - kilimchoi/engineering-blogs: A curated list of engineering blogs](https://github.com/kilimchoi/engineering-blogs)
- [poteto/hiring-without-whiteboards](https://github.com/poteto/hiring-without-whiteboards)
- [tarekeldeeb/awesome-islamic-open-source-apps](https://github.com/tarekeldeeb/awesome-islamic-open-source-apps)
- [GitHub - HKUDS/Paper2Slides: "Paper2Slides: From Paper to Presentation in One Click"](https://github.com/HKUDS/Paper2Slides)
- [GitHub - The-Commit-Company/mint: Bank reconciliation made simple for ERPNext](https://github.com/The-Commit-Company/mint)
- [GitHub - ygwyg/MAHORAGA: autonomous trading agent powered by social sentiment analysis and ai that learns, grows, and adapts](https://github.com/ygwyg/MAHORAGA)
- [ai-engineering-field-guide/interview/questions/ at main  alexeygrigorev/ai-engineering-field-guide  GitHub](https://github.com/alexeygrigorev/ai-engineering-field-guide/blob/main/interview/questions/06-home-assignments.md)

### Papers & Research

- [Developer Productivity and Interruptions (Microsoft Research)](https://www.microsoft.com/en-us/research/wp-content/uploads/2019/04/devtime-preprint-TSE19.pdf)
- [Pipelined Replication (Terrace & Freedman, USENIX)](https://www.usenix.org/legacy/event/usenix09/tech/full_papers/terrace/terrace.pdf)
- [Statistics for People Who Hate Statistics (PDF)](https://lib.zu.edu.pk/ebookdata/Media%20Sciences/Statistics%20for%20People%20who%20Hate%20Statistics.pdf)
- [Network Performance Paper (TU Munich 2024)](https://www.net.in.tum.de/fileadmin/TUM/NET/NET-2024-04-1/NET-2024-04-1_16.pdf)
- [Understanding Integer Overflow in C/C++](https://users.cs.utah.edu/~regehr/papers/overflow12.pdf)
- [Cyber-Physical Systems Handbook (Berkeley)](https://brdo.berkeley.edu/sites/default/files/cps_handbook.pdf)
- [Modern C (Jens Gustedt)](https://inria.hal.science/hal-02383654v2/file/modernC.pdf)

### Books & Courses

- [: The Land Trap: A New History of the World's Oldest Asset eBook : Bird, Mike: Kindle Store](https://www.amazon.com/Land-Trap-History-Worlds-Oldest-ebook/dp/B0DN62JHVL)
- [The Little Book of Semaphores – Green Tea Press](https://greenteapress.com/wp/semaphores/)

### Videos

- [OAuth 2.0 and OpenID Connect (in plain English)](https://youtu.be/996OiexHze0)
- [Christopher Okhravi](https://www.youtube.com/c/ChristopherOkhravi)
- [AWS SAA-C02 Full Course in Arabic (Issa Abu Sharif)](https://www.youtube.com/playlist?list=PLOoZRfEtk6kWSM_l9xMjDh-_MJXl03-pf)
- [Watch](https://www.youtube.com/watch?v=veyNxHVfFq8)
- [Watch](https://www.youtube.com/watch?v=S7MNX_UD7vY&list=PLIhvC56v63IJVXv0GJcl9vO5Z6znCVb1P)
- [Watch](https://www.youtube.com/watch?v=ROjZy1WbCIA)
- [What Every Programmer has to know about Database Storage by Alex Petrov](https://youtu.be/e1wbQPbFZdk)
- [@Arabicsoftwarearchtalks](https://www.youtube.com/@arabicsoftwarearchtalks)
- [Test-driven Development Introduction (Arabic)](https://youtube.com/playlist?list=PLZPHP6RGS50NtpHLee-eInDbFqy3P303g)
- [Watch](https://www.youtube.com/watch?v=SzlRJpshKzk&list=PLFGoYjJG_fqoum_IoPpbLN3AwWIWtr6hq&ab_channel=NaveenAutomationLabs)
- [Iwrve Whm84](https://youtu.be/IwrvE-wHm84?si=VtL1VUkdhJ1AwO29)
- [How I add millions of rows to MySQL (for performance testing)](https://youtu.be/ywp9Z0xZPzo?si=X74Fui8ISCw38VBI)
- [Watch](https://youtube.com/watch?v=rJcQqBGEJw4&si=r499UdHjMg1AsVKw)
- [Architecting LARGE software projects.](https://youtu.be/sSpULGNHyoI?si=TdrVE6eBG_Ae02M4)
- [Spring Security Architecture Principles by Daniel Garnier-Moiroux @ Spring I/O 2024](http://youtu.be/HyoLl3VcRFY)
- [Watch](https://youtube.com/watch?v=apREl0KmTdQ&feature=shared)
- [Building Software Systems At Google and Lessons Learned](https://youtu.be/modXC5IWTJI?si=9Gx1WMWcKHdgGWmr)
- [UTF-8, Explained Simply](https://youtu.be/vpSkBV5vydg?si=qTazewa1nBWwsAYy)
- [SentrySearch: A Python CLI that lets you search raw MP4 files in plain English](https://youtube.com/shorts/u1mWMUlzWQk?si=Cr92lOZvnXcOxazi)

### Articles & Tutorials

- [7 Free AWS Practice Labs and AWS Workshops resources](https://medium.com/towards-cloud-computing/7-free-aws-practice-labs-and-aws-workshops-resources-d0a861f05d3)
- [Introduction To Tdd](https://khalilstemmler.com/articles/test-driven-development/introduction-to-tdd/)
- [Notification System Design](https://cloudificationzone.com/2021/08/13/notification-system-design/)
- [L.Php](https://lm.facebook.com/l.php?u=https%3A%2F%2Fmorioh.com%2Fp%2Ff2bd29970df6%3Ff%3D5c21fb01c16e2556b555ab32&h=AT3xq9EJJ25ldVJl-01bfenN-tI2IBqEux1LvocUXdnwDJJ9N8GTdbL3uXNe7ONfpVu2lrgdx8ppF2EHyQhJE7nI60M5-SVy_x1Emr6sm6AMw4x8bY0qI5fArlqnjPgkm1IIcw&s=1)
- [Tech communities you should join! (online and in person) - DEV Community](https://dev.to/juliafmorgado/tech-communities-you-should-join-online-and-in-person-4nba)
- [Application Hosting How Polyhaven Manages 5 Million Page Views And 80Tb Traffic A Month For 400](https://scaleyourapp.com/application-hosting-how-polyhaven-manages-5-million-page-views-and-80tb-traffic-a-month-for-400/)
- [Developer to Architect — Mark Richards](https://www.developertoarchitect.com/)
- [Remote Backend Engineer (~$93k, Remote) at Rift Finance](https://remoteok.com/remote-jobs/remote-backend-engineer-rift-finance-150249)
- [Software Quality](https://jenkov.com/tutorials/dev-essentials/software-quality.html)
- [Intro Data Integration 2](https://dzone.com/articles/intro-data-integration-2)
- [Data Blending What It Is And How To Do It](https://blog.panoply.io/data-blending-what-it-is-and-how-to-do-it)
- [Eligibility Assessment - Office of Immigration Australia](https://www.immigrationsaustralia.com.au/eligibility-assess/)
- [Up For Grabs — Open Source Tasks for New Contributors](https://up-for-grabs.net/#/)
- [Teach Yourself Computer Science](https://teachyourselfcs.com/?fbclid=IwAR2uGdlCw3jz80EvoDua1udtNw-S-zKwqDZsceY-92R-SfAjAtp8Ei9xFHo)
- [Foreword -](https://csdiy.wiki/en/)
- [Query Execution Joins](https://samuelsorial.tech/query-execution-joins)
- [Dual monitor arm pro - FlakeTech](https://flaketech.net/product/dual-monitor-arm-pro-2/)
- [Upload Resume.Php](https://resumeworded.com/upload-resume.php)
- [Jobscan — ATS Resume Checker and Job Search Tools](https://www.jobscan.co)
- [The Art of Writing Amazing REST APIs](https://jkebertz.medium.com/the-art-of-writing-amazing-rest-apis-dc4c4100478d)
- [7 Git articles every open source practitioner should read |](https://opensource.com/article/23/1/git-articles)
- [Historical Source Code That Every Developer Should See | by Shalitha Suranga | Jan, 2023 | Level Up Coding](https://levelup.gitconnected.com/historical-source-code-that-every-developer-should-see-a7e6c6cbd764)
- [soundbetter.cc](https://soundbetter.cc)
- [Www Project Top Ten](https://owasp.org/www-project-top-ten/#)
- [Crafting Interpreters](https://craftinginterpreters.com/)
- [NeetCode](https://neetcode.io/)
- [Quastor — Engineering Newsletter](https://www.quastor.org/?fbclid=IwAR1FPizyZTYAShbJYCU3m7BzmKvy7fiGzO6yr48IVQDyIFK5coEZvXvZ4r4)
- [Uuids Ulids](https://sudhir.io/uuids-ulids)
- [En](https://visualgo.net/en)
- [Jenkov.com — Java & Tech Tutorials](https://jenkov.com/)
- [Hot Take Rest Is A Waste Of Time Just Do Rpc](https://blog.battlefy.com/hot-take-rest-is-a-waste-of-time-just-do-rpc)
- [You're Not a Senior Software Engineer](https://medium.com/vanguards-of-code/youre-not-a-senior-software-engineer-9056ef9ffb96)
- [Image Stacks and iPhone Racks - Building an Internet Scale Meme Search Engine](https://findthatmeme.com/blog/2023/01/08/image-stacks-and-iphone-racks-building-an-internet-scale-meme-search-engine-Qzrz7V6T.html)
- [Tdd](https://www.path-to-programming.tech/posts/tdd/)
- [ProjectLearn - Learn to Code by Creating Projects](https://projectlearn.io/?fbclid=IwAR3DS_Ba_KC6Xk2N43gTxzpZ22k0vPSOxsQQfgWFdDe2V7WZ_bkJyO-Qux4)
- [How Discord Stores Trillions Of Messages](https://discord.com/blog/how-discord-stores-trillions-of-messages)
- [The Law Of Leaky Abstractions](https://www.joelonsoftware.com/2002/11/11/the-law-of-leaky-abstractions/?fbclid=IwAR3cWDo-s07tfL7MntwfuXcscyXkRNAyN03SkpeqzJcFpxPMbMMexJkeCM0)
- [What Is iptables and How to Use It? | by Meysam | SkillUp Ed | Medium](https://medium.com/skilluped/what-is-iptables-and-how-to-use-it-781818422e52)
- [The Stack That Helped Medium Drive 2.6 Millennia of Reading Time](https://medium.engineering/the-stack-that-helped-medium-drive-2-6-millennia-of-reading-time-e56801f7c492)
- [Poe — AI Chat Platform](https://poe.com)
- [Kls5Acbtoyb](https://link.medium.com/Kls5ACbToyb)
- [How to Become a Good Backend Engineer (Fundamentals)](https://medium.com/@hnasr/how-to-become-a-good-backend-engineer-fundamentals-4dcc4a16ce55)
- [Monorepo Dev Practices](https://circleci.com/blog/monorepo-dev-practices/)
- [Most Common Web Vulnerabilities](https://medium.com/p/d9edbd7c500f)
- [Rznl9Gzs7Xb](https://link.medium.com/Rznl9GZs7xb)
- [Reviewer](https://google.github.io/eng-practices/review/reviewer/)
- [Just a moment](https://www.perplexity.ai/)
- [Pg](https://www.interdb.jp/pg)
- [The GPT-3 Architecture, on a Napkin](https://dugas.ch/artificial_curiosity/GPT_architecture.html?fbclid=IwAR1YKnge7zE1HDq9vR2_rgE0oWfSjDWe1dFjSYf4N6Q08IgYSgDUykvnXyI)
- [[Newest] How to Reset Windows 10 Password?](https://www.passfab.net/windows-10/forgot-windows-10-password.html)
- [Refcardz](https://dzone.com/refcardz?filter=popular)
- [Best Books for Software Engineering Leaders | by Matt Bentley | Aug, 2023 | Level Up Coding](https://levelup.gitconnected.com/best-books-for-software-engineering-leaders-221be3d5b2b)
- [Getting Started with Solution Architecture - Dometrain](https://dometrain.com/course/getting-started-solution-architecture/)
- [Web-Pen Testing 101: The Ultimate Starter’s Guide – Codelivly](https://www.codelivly.com/web-pen-testing-101-the-ultimate-starters-guide/)
- [Senior Backend Software Engineer 17](https://remote.co/job/senior-backend-software-engineer-17/)
- [Associate Software Engineer at DISNEY](https://jobs.disneycareers.com/job/burbank/associate-software-engineer/391/53293399328)
- [Software Engineer I (REMOTE) - Technology - Corporate](https://www.dickssportinggoods.jobs/jobs/19067553/software-engineer-i-remote-remote/)
- [“Good Commit” vs “Your Commit”: How to Write a Perfect Git Commit Message | by Victor Timi | Sep, 2023](https://levelup.gitconnected.com/good-commit-vs-your-commit-how-to-write-a-perfect-git-commit-message-6e96ab6357fa)
- [Sweden Companies Visa Sponsorship Jobs 2023](https://opportunitiescorners.com/sweden-companies-visa-sponsorship-jobs-2023/)
- [Async](https://engineering.fb.com/2020/08/17/production-engineering/async/)
- [lensgo.ai](https://lensgo.ai/)
- [CS 124: An Introduction to Computer Science](https://www.cs124.org/)
- [Linkedin S Journey To Java 11](https://engineering.linkedin.com/blog/2022/linkedin-s-journey-to-java-11)
- [Maxjourney Pushing Discords Limits With A Million Plus Online Users In A Single Server](https://discord.com/blog/maxjourney-pushing-discords-limits-with-a-million-plus-online-users-in-a-single-server?utm_source=blog.quastor.org&utm_medium=newsletter&utm_campaign=how-discord-can-serve-millions-of-users-from-a-single-server)
- [JSON is Incredibly Slow: Here's What's Faster!](https://medium.com/data-science-community-srm/json-is-incredibly-slow-heres-what-s-faster-ca35d5aaf9e8)
- [Understanding ReplicaSet vs. StatefulSet vs. DaemonSet vs. Deployments](https://semaphoreci.medium.com/understanding-replicaset-vs-statefulset-vs-daemonset-vs-deployments-9e983766f8d8)
- [Mastering Java Persistence Best Practices For Clou](https://dzone.com/articles/mastering-java-persistence-best-practices-for-clou)
- [A Practical Guide To Writing Technical Specs](https://stackoverflow.blog/2020/04/06/a-practical-guide-to-writing-technical-specs/)
- [Micro Frontends Architecture - DZone](https://dzone.com/articles/micro-frontends-architecture)
- [k6 — Load Testing for Engineering Teams](https://k6.io/)
- [How I learn Software Engineering](https://medium.com/@hnasr/how-i-learn-software-engineering-eae8e25ccac9)
- [Introduction To Snowflake For Junior Software Engi](https://dzone.com/articles/introduction-to-snowflake-for-junior-software-engi?utm_source=Sailthru&utm_medium=email&utm_campaign=DZone_Daily_Digest_12.01.2023&utm_term=dzone-daily-digest-active)
- [Raft Consensus Algorithm](https://raft.github.io/)
- [Amp](https://www-workingsoftware-dev.cdn.ampproject.org/c/s/www.workingsoftware.dev/the-ultimate-list-of-software-architecture-books-in-2024/amp/)
- [Internal Architecture and Working of Apache Tomcat](https://blog.stackademic.com/internal-architecture-and-working-of-apache-tomcat-4a0b1800627d)
- [Reactive Programming in Java — Good Time to Die](https://medium.com/@viraj_63415/reactive-programming-in-java-good-time-to-die-79f243dc1275)
- [Architecture: The Cheat Sheet](https://lab.scub.net/architecture-patterns-the-cheat-sheet-e8b5386f4b4b)
- [V1.0.0](https://www.conventionalcommits.org/en/v1.0.0/?fbclid=IwAR2pcs5YyUcC5awqGy_mH5b-t9n9-RArBh0QaKdXBaiwCz2VggNOxRmC6XA)
- [Inversion of Control and Dependency Injection](https://medium.com/@ali.gelenler/inversion-of-control-and-dependency-injection-047dba4d10dc)
- [Everything I Know About SSDs 2019](https://kcall.co.uk/ssd/index.html)
- [System Design Concepts: Computer Architecture](https://levelup.gitconnected.com/system-design-concepts-computer-architecture-5f2bc395aeb0)
- [System Design — A Deep Dive into the Food Ordering System](https://medium.com/@systemdesignbychk/system-design-a-deep-dive-into-the-food-ordering-system-f84ae6375ce3)
- [API Design 101: From Basics to Best Practices](https://levelup.gitconnected.com/api-design-101-from-basics-to-best-practices-a0261cdf8886)
- [Pagination](https://open.substack.com/pub/francofernando/p/pagination?utm_source=share&utm_medium=android&r=8etn5)
- [Unlocking the Secrets of CAP Theorem: What No One Tells You About Consistency, Availability, and Partition Tolerance](https://levelup.gitconnected.com/unlocking-the-secrets-of-cap-theorem-what-no-one-tells-you-about-consistency-availability-and-cfb5a891442d)
- [1Cgn7De3Pnrnh 4Ba Zrrmlqwz6Kquwud](https://drive.google.com/drive/u/0/mobile/folders/1CgN7DE3pNRNh_4BA_zrrMLqWz6KquwuD)
- [Implementing the Sidecar Pattern in a Microservices Based Application](https://blog.bitsrc.io/implementing-the-sidecar-pattern-in-nodejs-2ec3954fe9b6)
- [Companies](https://workat.tech/problem-solving/practice/companies)
- [The Trap of Learning: FOMO in Software Engineering](https://medium.com/@hnasr/the-trap-of-learning-2b8de2734bf)
- [Intro to Multithreaded JavaScript](https://www.infoworld.com/article/3715643/intro-to-multithreaded-javascript.html)
- [Thinking Like an Architect - InfoQ](https://www.infoq.com/presentations/architect-lessons/)
- [nealford.com • Architectural Katas](https://nealford.com/katas/list.html)
- [Kubetools](https://collabnix.github.io/kubetools/)
- [Under the Hood](https://mohitmishra786.github.io/UnderTheHood/)
- [Pingora Saving Compute 1 Percent At A Time](https://blog.cloudflare.com/pingora-saving-compute-1-percent-at-a-time/)
- [Reactive Programming in Java](https://senoritadeveloper.medium.com/reactive-programming-in-java-a4219a900c80)
- [Comparison Of Service Meshes](https://livewyer.io/blog/2024/05/08/comparison-of-service-meshes/)
- [An Illustrated Proof Of The Cap Theorem](https://mwhittaker.github.io/blog/an_illustrated_proof_of_the_cap_theorem/?utm_source=newsletter.programmingdigest.net&utm_medium=newsletter&utm_campaign=practices-of-reliable-software-design)
- [2024](https://frontendmasters.com/guides/front-end-handbook/2024/)
- [Join Newsletter Li](https://thorben-janssen.com/join-newsletter-li/)
- [A Data-Centric Introduction to Computing](https://dcic-world.org/2023-02-21/index.html)
- [Cs886](https://cs.uwaterloo.ca/~wenhuche/teaching/cs886/)
- [Free for Developers](https://free-for.dev)
- [Intro | Putting the "You" in CPU](https://cpu.land/)
- [If you're a beginner, definitely check this open source guide. I've explained almost everything you need to know. - DEV Community](https://dev.to/anmolbaranwal/if-youre-a-beginner-definitely-check-this-open-source-guide-ive-explained-almost-everything-you-498a)
- [Y Combinator Startup School](https://www.startupschool.org/)
- [Claim your Right for Flight Delay Compensation - Flightright](https://www.flightright.com/)
- [7 things you need in your home lab at any cost](https://www.xda-developers.com/things-you-need-your-home-lab-any-cost/)
- [Learning Journey](https://learn-db.com/learning-journey/)
- [Building A Scalable Reliable And Cost Effective Event Scheduler For Asynchronous Jobs 2Ac3](https://dev.to/joojodontoh/building-a-scalable-reliable-and-cost-effective-event-scheduler-for-asynchronous-jobs-2ac3)
- [In the world of APIs, two technologies have been dominating the conversation: GraphQL and REST](https://dev.to/lovestaco/why-graphql-a-developer-friendly-guide-to-api-evolution-51j5)
- [Complete Guide to Multi-Tenant Architecture](https://medium.com/@seetharamugn/complete-guide-to-multi-tenant-architecture-d69b24b518d6)
- [How To Build A Concurrent Key Value Store In Go 3Pep](https://dev.to/siddheshk02/how-to-build-a-concurrent-key-value-store-in-go-3pep)
- [Master Shell Scripting – Zero to Interview Ready! - DEV Community](https://dev.to/harshit_rwt/master-shell-scripting-zero-to-interview-ready-379e)
- [Public Launch Announcement](https://dagger.io/blog/public-launch-announcement)
- [User Authentication In Go Nm7](https://dev.to/39george/user-authentication-in-go-nm7?utm_source=dormosheio&utm_campaign=dormosheio)
- [Dsatcl](https://jeroenjanssens.com/dsatcl/)
- [Practical Deep Learning for Coders - The book](https://course.fast.ai/Resources/book.html)
- [Book](https://wesmckinney.com/book/)
- [Repository Pattern In Go](https://threedots.tech/post/repository-pattern-in-go/)
- [Vibe Coding 101 With Replit](https://learn.deeplearning.ai/courses/vibe-coding-101-with-replit)
- [Stop Non-Consensual Intimate Image Abuse |](https://stopncii.org/?fbclid=IwY2xjawJoJT1leHRuA2FlbQIxMQABHrDN1uq7eU0dyIKlRHT5eMrJN6Bfti_PhmRvqu-EakpJI1dyn5wxa2Q9X6qs_aem_t850pn97O-EqkcUyFo03PA)
- [My favorite technical blogs](https://eatonphil.com/blogs.html)
- [Books](https://teivah.dev/books/)
- [The Art of Unix Programming](http://www.catb.org/esr/writings/taoup/html/)
- [How To Ask](https://stackoverflow.com/help/how-to-ask)
- [Choosing Message Broker](https://www.infoq.com/articles/choosing-message-broker/)
- [Beyond Code: How to Create Beautiful Documentation That Developers Actually Love (Best Practices) - DEV Community](https://dev.to/therealmrmumba/beyond-code-how-to-create-beautiful-documentation-that-developers-actually-love-best-practices-hc4)
- [Parallel, Concurrent and Distributed Programming — YSC4231 2021](https://ilyasergey.net/YSC4231/)
- [Learn Game Engine Programming](https://engine-programming.github.io/)
- [A Data Scientist’s Guide to Data Streaming - KDnuggets](https://www.kdnuggets.com/2025/05/confluent/a-data-scientists-guide-to-data-streaming)
- [4Dijyve](https://bit.ly/4diJYve)
- [opensource.guide](https://opensource.guide/)
- [MCP: Build Rich-Context AI Apps with Anthropic -](https://www.deeplearning.ai/short-courses/mcp-build-rich-context-ai-apps-with-anthropic/)
- [The Complete Guide to Data Streaming Use Cases](https://www.confluent.io/resources/ebook/streaming-use-case-guide/?utm_campaign=tm.fm-ww_cd.2025-usecase-book-kai-blog&utm_source=blogpost&utm_medium=blogpost)
- [Argo Cd Beginners Guide](https://devtron.ai/blog/argo-cd-beginners-guide/)
- [Writing Load Balancer From Scratch](https://beyondthesyntax.substack.com/p/writing-load-balancer-from-scratch?r=1pyp9s&triedRedirect=true)
- [Modern Go Application Design](https://titpetric.com/2025/06/11/modern-go-application-design/)
- [Implementing Log File Rotation In Go Insights From Logrus Zap And Slog 5B9O](https://dev.to/leapcell/implementing-log-file-rotation-in-go-insights-from-logrus-zap-and-slog-5b9o)
- [Error handling](https://go-monk.beehiiv.com/p/error-handling)
- [Mastering Go Concurrency Patterns: A Comprehensive Guide](https://compositecode.blog/2025/06/22/concurrency-patterns-in-go-a-short-deep-dive-series/)
- [Disk Partition Analyzer In Go](https://rezmoss.com/blog/disk-partition-analyzer-in-go/)
- [Thumbnail Generation - Shared Workflow](https://studio.comfydeploy.com/share/playground/comfy-deploy/thumbnail-generation?fbclid=IwY2xjawLNrJ9leHRuA2FlbQIxMQABHuMUuaktO_JV9VqaBMZIDQJAP7J25YNoUlzJcz_3rgS7oWta8M5hqoD4Xr1h_aem_vbweS4LY7qGmxN0O-8XLRA)
- [Let's Learn MCP | Microsoft Reactor](https://developer.microsoft.com/en-us/reactor/series/s-1562/)
- [Understand Cpu Branch Instructions Better](https://chrisfeilbach.com/2025/07/05/understand-cpu-branch-instructions-better/)
- [Encryption And Decryption In Go A Hands On Guide 3Bcl](https://dev.to/shrsv/encryption-and-decryption-in-go-a-hands-on-guide-3bcl)
- [Graceful Goroutine Shutdowns in Go: A Practical Guide - DEV Community](https://dev.to/jones_charles_ad50858dbc0/graceful-goroutine-shutdowns-in-go-a-practical-guide-2b9a)
- [Why Java Is Still Worth Learning In 2025 A Developers 25 Year Journey](https://empatheticdeveloper.wordpress.com/2025/07/20/why-java-is-still-worth-learning-in-2025-a-developers-25-year-journey/)
- [The Five Orders Of Ignorance](https://www.5oi.org/the-five-orders-of-ignorance)
- [12 Open Source Alternatives to Popular Software (For Developers)](https://dev.to/therealmrmumba/12-open-source-alternatives-to-popular-software-for-developers-1heg)
- [3Tzr13N](https://bit.ly/3TZR13n)
- [Stop Skimming Documentation - DEV Community](https://dev.to/kurealnum/stop-skimming-documentation-mbk)
- [Who S Bug Is It Anyway Aka Handling The On Call Rota 11M6](https://dev.to/jpswade/who-s-bug-is-it-anyway-aka-handling-the-on-call-rota-11m6)
- [Go Concurrency Rocks](https://www.concurrency.rocks/)
- [Immutability from Experience: Part 1](https://medium.com/@whoiskai/immutability-from-experience-part-1-5661fb268c27)
- [Integration Testing For Go Applications Using Test](https://dzone.com/articles/integration-testing-for-go-applications-using-test?email_hash=d81f265aee3958897ad13604b99e311b)
- [Why Llms Cant Build Software](https://zed.dev/blog/why-llms-cant-build-software)
- [DigitalPlat FreeDomain: Free Domain For Everyone. | Open-source Projects | Open-source Projects](https://opensourceprojects.dev/post/1959600649026302372)
- [Dive into Systems](https://diveintosystems.org/)
- [Go'ing Insane Part One: Endless Error Handling – Pursuit Of Laziness – A blog by Jesse Duffield](https://jesseduffield.com/Gos-Shortcomings-1/)
- [Event-Driven Everything: How to Think (and Build) in Events Instead of Requests | by Mike Attara | Aug, 2025 | Medium](https://blog.attara.dev/event-driven-everything-how-to-think-and-build-in-events-instead-of-requests-617f63ca6164)
- [How to Think About GPUs | How To Scale Your Model](https://jax-ml.github.io/scaling-book/gpus/)
- [How to Structure Logs Properly in OpenTelemetry: A Complete Guide](https://oneuptime.com/blog/post/2025-08-28-how-to-structure-logs-properly-in-opentelemetry/view)
- [Building Your First Mcp Server A Beginners Guide 59Ml](https://dev.to/kevin-uehara/building-your-first-mcp-server-a-beginners-guide-59ml)
- [Learn The Go Programming Language Start Here](https://thenewstack.io/learn-the-go-programming-language-start-here/)
- [Mocking Vs Integration Testing](https://www.wiremock.io/post/mocking-vs-integration-testing)
- [Understanding Space-Based Architecture](https://medium.com/the-pragmatic-tech-review/understanding-space-based-architecture-15281953c24c)
- [Cornell Virtual Workshop: Understanding GPU Architecture](https://cvw.cac.cornell.edu/gpu-architecture)
- [Memory Allocation in Go](https://nghiant3223.github.io/2025/06/03/memory_allocation_in_go.html)
- [En](https://www.asyncapi.com/en)
- [Behind The Scenes Of Bun Install](https://bun.com/blog/behind-the-scenes-of-bun-install)
- [Items](https://marketplace.visualstudio.com/items?itemName=vscjava.migrate-java-to-azure)
- [Bw2Jbrm](https://buff.ly/BW2jBrM)
- [Db Tutorial](https://cstack.github.io/db_tutorial/)
- [Preparing For The Systems Design And Coding Interviews](https://blog.pragmaticengineer.com/preparing-for-the-systems-design-and-coding-interviews/)
- [Why Do Cpus Have Multiple Cache Levels](https://fgiesen.wordpress.com/2016/08/07/why-do-cpus-have-multiple-cache-levels/)
- [How Dns Actually Works](https://blog.algomaster.io/p/how-dns-actually-works)
- [Graceful Shutdowns in Go HTTP Servers: Ensuring Zero Downtime for Live Traffic](https://blog.stackademic.com/graceful-shutdowns-in-go-http-servers-ensuring-zero-downtime-for-live-traffic-b8224b28ab4a)
- [Introduction To Keycloak](https://www.mastertheboss.com/keycloak/introduction-to-keycloak/)
- [Go Channels: Understanding Happens-Before for Safe Concurrency - InfoQ](https://www.infoq.com/articles/go-channels-happens-before-concurrency/)
- [Weekend Home Lab Challenges to Level Up Your Skills - Virtualization Howto](https://www.virtualizationhowto.com/2025/10/weekend-home-lab-challenges-to-level-up-your-skills/)
- [Learn Go with Tests | Learn Go with tests](https://quii.gitbook.io/learn-go-with-tests)
- [Flame Graphs](https://www.brendangregg.com/flamegraphs.html)
- [On Learning – avoiding mediocrity | devansh's blog](https://devansh.bearblog.dev/on-learning/)
- [Writing Better Go: Lessons from 10 Code Reviews - Speaker Deck](https://speakerdeck.com/konradreiche/writing-better-go-lessons-from-10-code-reviews)
- [Ionut Balosin – Principal IT Architect, Technical Trainer, Oracle ACE, Java Champion](https://ionutbalosin.com/)
- [Free Labs](https://kodekloud.com/free-labs)
- [Mentorship](https://calcur.tech/mentorship)
- [Organizing Tests](https://rednafi.com/go/organizing-tests/)
- [Visual Guide to Go Maps: Hash Tables — Ozan Sazak](https://sazak.io/articles/visual-guide-to-go-maps-hash-tables-2025-10-26)
- [Idempotency Keys](https://brandur.org/idempotency-keys)
- [The 3-Pass Method: How to Actually Understand That Science Paper (Without Drowning in Jargon) - Paperzilla](https://paperzilla.ai/paper/ee30770b/how-to-read-a-paper)
- [5335234 Latency Reduce Delay Software Systems Pekka Enberg Final](https://sanet.st/books/5335234-latency-reduce-delay-software-systems-pekka-enberg-final)
- [Latency-Sensitive Applications and the Memory Subsystem: Keeping the Data in the Cache - Johnny's Software Lab](https://johnnysswlab.com/latency-sensitive-applications-and-the-memory-subsystem-keeping-the-data-in-the-cache/)
- [Video Encoding 101: A Comprehensive Guide](https://imagekit.io/blog/video-encoding/)
- [(Quite) A Few Words About Async](https://yoric.github.io/post/quite-a-few-words-about-async/)
- [Build to Last — fast.ai](https://www.fast.ai/posts/2025-10-30-build-to-last.html)
- [Domain-Driven Design & Hexagonal Architecture](https://medium.com/@emrbrkg/domain-driven-design-hexagonal-architecture-762f3f67149c)
- [Reduce Container Image Size Case Study](https://sealos.io/blog/reduce-container-image-size-case-study)
- [happyDeliver. Test Your Email Deliverability](https://happydeliver.org/)
- [Inside High-Frequency Trading Systems: The Race to Zero Latency | by Harsh Shukla | Nov, 2025 | Level Up Coding](https://levelup.gitconnected.com/inside-high-frequency-trading-systems-the-race-to-zero-latency-faa638d0c180)
- [DuckDB in Action — Book Preface](https://duckdb.gishub.org/book/preface.html)
- [The Shift Left Architecture From Batch And Lakehouse To Real Time Data Products With Data Streaming](https://www.kai-waehner.de/blog/2024/06/15/the-shift-left-architecture-from-batch-and-lakehouse-to-real-time-data-products-with-data-streaming/)
- [(PDF) Two-Phase Commit](https://www.researchgate.net/publication/275155037_Two-Phase_Commit)
- [Asynchrony is not Concurrency | Loris Cro's Blog](https://kristoff.it/blog/asynchrony-is-not-concurrency/)
- [Vectorization](https://celerdata.com/glossary/vectorization)
- [ML Systems Textbook](https://mlsysbook.ai/contents/core/introduction/introduction.html)
- [mapcn - Beautiful maps made simple](https://mapcn.vercel.app/)
- [Localflare - Local Development Dashboard for Cloudflare Workers](https://localflare.dev/)
- [How Uber Serves Over 150 Million Reads](https://www.uber.com/en-EG/blog/how-uber-serves-over-150-million-reads/?uclick_id=amrdb)
- [MongoBleed explained simply - by Stanislav Kozlovski](https://bigdata.2minutestreaming.com/p/mongobleed-explained-simply)
- [Payment reconciliation: What it is and how it’s done | Stripe](https://stripe.com/resources/more/payment-reconciliation-101)
- [17](https://phrack.org/issues/71/17#article)
- [Codus Operandi](https://www.codusoperandi.com/posts/increasing-your-luck-surface-area)
- [Outcome Engineering](https://o16g.com/)
- [How to build a distributed queue in a single JSON file on object storage](https://turbopuffer.com/blog/object-storage-queue)
- [Heat Graph](https://www.assistant-ui.com/heat-graph)
- [FFmpeg 101](https://blogs.igalia.com/llepage/ffmpeg-101/)
- [Q0473Jss0](https://hubs.la/Q0473JSS0)
- [1. 2. 3. 4. 5](https://hnasr.substack.com/p/how-i-design-software?r=6xhat&utm_medium=ios&triedRedirect=true)
- [CCACHE(1)](https://ccache.dev/manual/4.2.html#_cache_size_management)
- [Enter The Arena Talk](https://www.dgtlgrove.com/p/enter-the-arena-talk)
- [Logo Lattice - Draw logos quickly with snapped square and isometric grids](https://logolattice.com/)

---

## Contributing

Contributions are welcome and encouraged. This is meant to grow into a shared resource pool for the engineering community.

**Guidelines:**

1. **Quality over quantity.** Link to resources that provide depth, not just surface-level introductions.
2. **One resource per PR is fine.** No need for batching.
3. **Use the right section.** If a resource spans multiple topics, pick the primary one.
4. **Use the right sub-section** (`Repositories`, `Papers & Research`, `Books & Courses`, `Videos`, `Articles & Tutorials`).
5. **Add a brief description if the link title isn't self-explanatory.** Format: `- [Title](URL) — short note`.
6. **No paywalled content** unless a free alternative is linked alongside.

To contribute: fork the repo, add your resource to the appropriate section, and open a pull request.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This repository is dedicated to the public domain under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Share freely.
