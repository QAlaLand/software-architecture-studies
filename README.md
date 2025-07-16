# QA Studies: Software Architecture and Testing Strategies

This repository gathers materials, notes, and practical examples on essential topics for QA professionals focusing on automation, software architecture, and advanced testing strategies.

---

## 🧱 Software Architecture Topics 

### 1. Types of Software Architecture
- **Monolithic**  
  Understanding how to test applications with high coupling and the challenges of integrated testing.

- **Microservices**  
  Communication via REST, gRPC, and messaging systems (Kafka, RabbitMQ). Strategies for distributed and independent testing.

- **Event-driven**  
  Testing asynchronous systems, ensuring idempotency and event traceability.

- **Serverless**  
  Limitations and testing strategies for isolated functions in environments like AWS Lambda and Azure Functions.

- **Clean Architecture / Hexagonal Architecture**  
  Clear separation of concerns and identifying ideal points for mocks and unit/integration tests.

---

### 2. Design Patterns Relevant for Testing
- **Dependency Injection**  
  Facilitates creation of mocks and stubs for isolated tests.

- **Factory / Builder**  
  Helps in creating complex test data.

- **Observer / Event Publisher-Subscriber**  
  Used in reactive and event-driven systems to facilitate event testing.

- **Adapter / Facade**  
  Helps isolate external dependencies during testing.

---

### 3. Testability in Architecture
- Applying **Inversion of Control** to create decoupled, easily testable components.  
- Clear separation between business logic and I/O operations.  
- Best practices for logging to improve traceability and debugging.  
- Implementing tests within CI/CD pipelines for automated testing of independent services.

---

### 4. Testing Strategies in Architecture
- **Test Pyramid**: Prioritize unit tests, then integration tests, followed by end-to-end (E2E) tests.  
- Testing in isolated environments versus production monitoring (observability testing).  
- **Contract Testing** with Pact to ensure reliable service integrations.  
- **Consumer-driven Contracts**, especially useful in microservices.  
- Resilience testing and controlled failure introduction through **Chaos Engineering** (Chaos Monkey, Gremlin).

---

## 📚 Contents
This repository includes:
- Theoretical summaries  
- Links to practical automation and testing examples  
- Scripts and templates for contract testing  
- Exercises for implementing chaos engineering strategies  
- Tool recommendations and bibliography


