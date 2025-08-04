# 🧱 Clean Architecture Template (.NET 9)

A pragmatic and extensible Clean Architecture solution template for building robust .NET applications using **Domain-Driven Design (DDD)** principles.

---

## 🧩 What's Included?

### 📦 SharedKernel Project
- Common **DDD abstractions**
- Reusable **value objects**, **base entities**, and **interfaces**

### 🏛 Domain Layer
- Rich **domain model** with sample entities
- Focus on **business logic** and **ubiquitous language**

### 📚 Application Layer
- **CQRS** with MediatR-style requests
- Example **use cases**
- **Cross-cutting concerns**:
  - Logging
  - Validation (using FluentValidation)

### 🏗 Infrastructure Layer
- **Authentication** and **Authorization**
  - Role-based and Permission-based strategies
- **EF Core** with **PostgreSQL** support
- **Logging**:
  - Structured logging via **Serilog**
  - Integrated with **Seq** for log visualization

> 🔍 Seq is available at [http://localhost:8081](http://localhost:8081) by default.

### 🧪 Testing Projects
- ✅ Unit Testing
- ✅ Functional Testing
- ✅ Integration Testing
- ✅ Architecture Testing (e.g., validate dependency rules)

---

## 🚀 Advanced Features & Roadmap

This template is built with best practices in mind and is designed to grow with your project. It includes or supports:

- ✅ Domain-Driven Design (DDD)
- ✅ Role-based Authorization
- ✅ Permission-based Authorization
- ✅ Distributed Caching with Redis
- ✅ OpenTelemetry for distributed tracing
- ✅ Outbox Pattern for reliable event publishing
- ✅ API Versioning
- ✅ Unit Testing
- ✅ Functional Testing
- ✅ Integration Testing

---

## 📥 Getting Started

```bash
git clone https://github.com/your-org/clean-architecture-template.git
cd clean-architecture-template
docker-compose up -d
```bash

Then open http://localhost:8081 to explore structured logs via Seq.
