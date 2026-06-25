# backend-infrastructure-projects

A central hub for low-level backend systems I built from scratch to deepen my understanding of network protocols, memory management, and distributed architecture.

## The Projects

* **[HTTP/1.1 Server](https://github.com/huboleo/http-server)**
  A custom server built on raw TCP sockets that handles HTTP request parsing, routing, and concurrent client connections. 

* **[In-Memory Key-Value Database](https://github.com/huboleo/in-memory-database)**
  A thread-safe, Redis-style data store utilizing locks/mutexes for high-speed concurrent access with O(1) time complexity. 

* **[Message Queue](https://github.com/huboleo/message-queue)**
  A Kafka-like, log-based message broker built to manage asynchronous communication, persist event data, and safely route it between producers and consumers.

* **[API Rate Limiter](https://github.com/huboleo/rate-limiter)**
  A network traffic controller using the Token Bucket algorithm to manage API quotas, ensure fair usage, and prevent server overload.

* **[ETL Data Pipeline](https://github.com/huboleo/etl-data-pipeline)**
  A simple etl data pipeline that ingests the transactions data, transforms it and loads everything into an SQL db
