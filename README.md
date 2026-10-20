# Hi, I'm Ashraful 👋

### Backend Engineer | Java • Spring Boot • Microservices • Kafka • AWS

I'm a Software Engineer focused on building scalable backend systems, distributed applications, and production-grade SaaS platforms.

I have 3.5+ years of professional software engineering experience, primarily building production systems with TypeScript, Node.js, React, databases, cloud infrastructure, and event-driven architectures.

I'm currently expanding my backend engineering career into **Java and Spring Boot**, with a strong foundation in **Core Java, OOP, data structures, system design, and enterprise application development**.

My goal is to build reliable, scalable backend systems and grow deeper into **distributed systems, cloud engineering, and enterprise software architecture**.

---

## 🚀 About Me

- 💻 Software Engineer with 3.5+ years of professional experience
- ☕ Currently focusing on **Java & Spring Boot backend engineering**
- 🏗️ Interested in **system design, distributed systems, and backend architecture**
- 🔄 Experienced with **microservices and event-driven systems**
- 📨 Working with asynchronous processing and queue-based workflows
- ☁️ Exploring and building with **AWS and cloud infrastructure**
- 🐳 Experienced with Docker and production deployments
- 🗄️ Comfortable with PostgreSQL, MongoDB, and Redis
- 🤖 Experienced with LLM APIs, RAG, vector search, and AI agent workflows
- 👨‍💻 Strong production background with Node.js and TypeScript
- 📍 Based in Dhaka, Bangladesh

---

## 🧠 Current Engineering Focus

My current learning and engineering path is focused on:

```text
Core Java
    ↓
Object-Oriented Programming
    ↓
Data Structures & Algorithms
    ↓
Spring Boot
    ↓
Spring Security
    ↓
JPA / Hibernate
    ↓
PostgreSQL
    ↓
Redis
    ↓
Kafka
    ↓
Microservices
    ↓
Distributed Systems
    ↓
AWS & Cloud Engineering
```

I'm particularly interested in understanding not only how to build applications, but also how backend systems behave under:

- High concurrency
- Distributed workloads
- Network failures
- Partial failures
- Large volumes of data
- Asynchronous processing
- Traffic spikes
- Database contention
- Service-to-service communication

---

# 🚀 Production Systems I've Built

Most of my professional production work is under private repositories.

The following projects represent the type of systems I've worked on and the engineering problems I've solved.

---

## ⚡ Real-Time Trading SaaS Platform

### `cefi.kvants.ai`

**Node.js · Express.js · React · MongoDB · Redis · WebSockets · Stripe**

A real-time copy-trading platform serving web and mobile clients.

### Key Engineering Work

- Built backend APIs for trading and account management
- Implemented real-time trade mirroring using WebSockets
- Supported sub-second propagation between trader and follower accounts
- Implemented idempotent order execution
- Built portfolio synchronization workflows
- Used Redis for high-speed data and workflow operations
- Integrated exchange APIs
- Implemented subscription billing using Stripe
- Implemented role-based access control
- Worked across shared APIs and business logic for multiple clients

---

# ☕ CommerceFlow

### Distributed Order Processing Platform

**Java · Spring Boot · PostgreSQL · Redis · Kafka · Docker · AWS**

CommerceFlow is a personal backend engineering project designed around microservices and event-driven architecture.

The project focuses on building a production-style distributed order processing system using Java and Spring Boot.

### Architecture

```text
                    ┌─────────────────┐
                    │    API Client   │
                    └────────┬────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │   API Gateway   │
                    └────────┬────────┘
                             │
              ┌──────────────┼──────────────┐
              │              │              │
              ▼              ▼              ▼
        ┌──────────┐   ┌──────────┐   ┌──────────┐
        │   User   │   │  Order   │   │ Payment  │
        │ Service  │   │ Service  │   │ Service  │
        └──────────┘   └─────┬────┘   └─────┬────┘
                             │              │
                             └──────┬───────┘
                                    ▼
                              ┌───────────┐
                              │   Kafka   │
                              └─────┬─────┘
                                    │
                    ┌───────────────┼───────────────┐
                    ▼               ▼               ▼
             ┌──────────┐   ┌────────────┐   ┌──────────┐
             │ Payment  │   │Notification│   │  Other   │
             │ Workflow │   │  Service   │   │Consumers │
             └──────────┘   └────────────┘   └──────────┘
```

### Engineering Features

- Designed microservice-based architecture
- Created dedicated Order, Payment, User and Notification services
- Built REST APIs using Spring Boot
- Implemented event-driven communication using Kafka
- Implemented asynchronous order and payment workflows
- Implemented Spring Security
- Added JWT-based authentication
- Added role-based authorization
- Implemented Redis caching
- Used PostgreSQL for transactional persistence
- Implemented database transactions
- Added optimistic locking for concurrent updates
- Implemented idempotency for reliable request processing
- Containerized services using Docker
- Deployed the application on AWS
- Added unit and integration testing
- Used JUnit, Mockito and Testcontainers

### Key Engineering Concepts

```text
Microservices
Event-Driven Architecture
REST APIs
Authentication & Authorization
Distributed Transactions
Idempotency
Optimistic Locking
Caching
Asynchronous Processing
Containerization
Cloud Deployment
Automated Testing
```

---

# 🤖 AI & Automation Systems

I've also worked on backend systems that integrate modern AI capabilities with production workflows.

### Technologies & Concepts

- LLM API Integration
- OpenAI
- Claude
- Gemini
- Retrieval-Augmented Generation (RAG)
- Vector Search
- Embeddings
- AI Agents
- Agentic Workflows
- Tool Use
- AI-Assisted Development

### Areas of Application

- Market analysis
- Internal automation
- Content generation
- Automated decision pipelines
- Data processing
- Intelligent backend workflows

---

# 🛒 Full-Stack E-Commerce Platform

### `sundarbanhoneybd.com`

**Next.js · TypeScript · Node.js · MongoDB**

A complete e-commerce platform consisting of a customer storefront and self-service administrative back office.

### Key Features

- Customer storefront
- Administrative dashboard
- Product catalogue management
- Order management
- Inventory workflows
- Checkout
- Payment gateway integration
- Role-based access control
- Sales and fulfilment workflows
- REST APIs

### Performance

- Served 1,000+ active users
- Optimized database aggregation queries
- Optimized image delivery
- Focused on fast page loading over mobile networks

---

# 💼 Professional Experience

## Software Engineer — Core Devs Ltd.

**Jul 2024 – Present**

Working across backend systems, SaaS platforms, real-time systems, AI-powered automation, and production applications.

### Responsibilities

- Own features and systems end-to-end
- Perform technical research
- Design application architecture
- Design service boundaries
- Design data models and integrations
- Build production APIs
- Develop WebSocket-based systems
- Develop queue-backed workflows
- Work with long-running background jobs
- Integrate AI and LLM APIs
- Build RAG and agent workflows
- Review code
- Mentor engineers
- Support production systems

### Technologies

```text
TypeScript
Node.js
Express.js
React
Next.js
WebSockets
Queues
Redis
MongoDB
PostgreSQL
AWS
Docker
LLM APIs
RAG
AI Agents
```

---

# 💼 Full Stack Developer — Mitali International

**Feb 2023 – Jul 2024**

Built and maintained production e-commerce platforms and business applications.

### Responsibilities

- Developed customer-facing applications
- Built backend APIs
- Developed administrative systems
- Implemented payment workflows
- Led migration of the company website to Next.js
- Improved application performance
- Improved SEO and maintainability
- Worked directly with business stakeholders
- Resolved production issues
- Supported applications after deployment

---

# 🧰 Tech Stack

## Languages

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

---

## Backend

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

```text
Java
Spring Boot
Spring Security
Node.js
Express.js
Nest.js
REST APIs
JWT
```

---

## Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)

```text
React
Next.js
Redux Toolkit
Tailwind CSS
```

---

## Databases

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

```text
PostgreSQL
MongoDB
Redis
```

---

## Messaging & Distributed Systems

![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)

```text
Apache Kafka
Event-Driven Architecture
Message-Based Processing
Asynchronous Workflows
Distributed Systems
```

---

## Cloud & DevOps

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

```text
AWS
IAM
EC2
S3
Docker
Nginx
GitHub Actions
CI/CD
```

---

## Architecture & Engineering

```text
System Design
Microservices
Distributed Systems
Event-Driven Architecture
REST APIs
Real-Time Systems
Concurrency
Idempotency
Caching
Database Transactions
Optimistic Locking
API Security
```

---

## AI / Machine Learning

```text
LLM API Integration
RAG
Vector Search
Embeddings
AI Agents
Agentic Workflows
Tool Use
AI-Assisted Development
```

---

# 🔐 Security

I'm interested in building secure backend systems using:

- Spring Security
- JWT Authentication
- Role-Based Access Control
- API Authorization
- Secure REST APIs
- Token-based authentication
- Service-level security

---

# 🧪 Testing

Testing technologies and practices I work with:

```text
JUnit
Mockito
Testcontainers
Jest
Unit Testing
Integration Testing
API Testing
```

---

# 🏗️ Engineering Principles

I try to approach backend engineering around a few core principles:

### Reliability

Systems should behave predictably even when components fail.

### Scalability

Architecture should allow services to scale independently when required.

### Maintainability

Code should be understandable and easy for other engineers to extend.

### Security

Authentication, authorization and data protection should be considered from the beginning.

### Observability

Production systems should provide enough information to understand failures and performance problems.

### Simplicity

Distributed architecture should only be introduced when the problem actually requires it.

---

# 📚 Currently Learning

## Java

- Core Java
- OOP
- Collections
- Generics
- Streams
- Multithreading
- Concurrency
- JVM fundamentals
- Exception handling
- Memory management

## Spring

- Spring Boot
- Spring MVC
- Spring Security
- Spring Data JPA
- Hibernate
- REST API development
- Dependency Injection
- Transaction management

## Distributed Systems

- Microservices
- Kafka
- Event-driven architecture
- Distributed transactions
- Idempotency
- Concurrency
- Caching
- Fault tolerance
- Service communication

## Cloud

- AWS
- Docker
- CI/CD
- Infrastructure fundamentals
- Production deployment

---

# 🎯 Career Direction

My current career direction is focused on becoming a strong backend and distributed-systems engineer.

I'm particularly interested in roles involving:

- Java Backend Engineering
- Spring Boot
- Enterprise Software
- Microservices
- Distributed Systems
- Cloud Engineering
- System Design
- High-scale Backend Systems

---

# 📊 GitHub Stats

<p align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=smashraful&show_icons=true&theme=github_dark&hide_border=true"
    alt="Ashraful's GitHub Stats"
  />
</p>

<p align="center">
  <img
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=smashraful&layout=compact&theme=github_dark&hide_border=true"
    alt="Ashraful's Top Languages"
  />
</p>

---

# 📈 GitHub Streak

<p align="center">
  <img
    src="https://github-readme-streak-stats.herokuapp.com/?user=smashraful&theme=github-dark-blue&hide_border=true"
    alt="GitHub Streak"
  />
</p>

---

# 🤝 Let's Connect

I'm interested in connecting with engineers, developers, founders, and teams working on backend systems, distributed architectures, cloud platforms, enterprise software, and AI-powered products.

### LinkedIn

[linkedin.com/in/smashraful](https://linkedin.com/in/smashraful)

### Portfolio

[theashlab.com](https://theashlab.com)

### GitHub

[github.com/smashraful](https://github.com/smashraful)

### Email

[smashraful.dev@gmail.com](mailto:smashraful.dev@gmail.com)

---

# ⚡ A Little More About Me

I started my professional journey as a full-stack developer, working heavily with JavaScript, TypeScript, React, and Node.js.

Over time, my interest shifted toward the engineering problems behind the applications:

```text
How do systems scale?
How do services communicate?
How do we handle concurrency?
How do we guarantee reliable processing?
How do distributed systems recover from failures?
How should databases be designed?
How do we build systems that remain maintainable as they grow?
```

That led me deeper into backend engineering, system design, distributed systems, cloud infrastructure, and now Java/Spring Boot.

I'm currently building projects that help me bridge my existing production experience with enterprise backend engineering.

---

<p align="center">

### 🚀 Build systems. Understand the fundamentals. Keep learning.

</p>
