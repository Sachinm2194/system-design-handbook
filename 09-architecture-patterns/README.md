
# Phase 9: Architecture Patterns

This phase covers the architectural patterns and design approaches used to structure large-scale software systems. It explores how to organize services, manage business complexity, separate responsibilities, and build systems that are scalable, maintainable, and independently deployable.

The goal is to understand common architecture patterns, their trade-offs, and when to apply them in real-world system design.

---

## Topics Covered

### 1. Monolithic and Microservices Architecture
- What is monolithic architecture?
- Modular monoliths
- What are microservices?
- Microservices architecture principles
- Monolith vs microservices
- Service boundaries and decomposition
- Domain-based service decomposition
- Database per service pattern
- Independent deployment and scaling
- Inter-service communication
- Microservices challenges and trade-offs
- When to choose monoliths vs microservices

### 2. Service-Oriented Architecture (SOA)
- What is Service-Oriented Architecture?
- SOA principles and characteristics
- Services and service contracts
- Enterprise Service Bus (ESB)
- Service orchestration
- Service choreography
- SOA vs microservices
- SOA use cases and limitations

### 3. Domain-Driven Design (DDD)
- What is Domain-Driven Design?
- Strategic vs tactical DDD
- Domain, subdomain, and core domain
- Supporting and generic subdomains
- Ubiquitous language
- Bounded contexts
- Context mapping
- Shared kernel
- Anti-corruption layer
- Domain events
- Aggregates and aggregate roots
- Entities and value objects
- Repositories and domain services
- Applying DDD to microservices

### 4. Layered and Hexagonal Architecture
- Layered architecture
- Presentation, application, domain, and infrastructure layers
- Separation of concerns
- Dependency direction
- Clean Architecture
- Hexagonal Architecture (Ports and Adapters)
- Primary and secondary adapters
- Dependency inversion
- Onion Architecture
- Comparing Clean, Hexagonal, and Onion architectures
- Testability and maintainability trade-offs

### 5. CQRS and Event Sourcing
- Command Query Responsibility Segregation (CQRS)
- Commands and queries
- Read and write model separation
- CQRS architecture
- Command and query handlers
- Event Sourcing fundamentals
- Events as the source of truth
- Event store
- Event replay
- Snapshots
- Projections and read models
- Event versioning
- CQRS vs traditional CRUD
- CQRS and Event Sourcing together
- Eventual consistency and operational trade-offs

### 6. Multi-Tenant Architecture
- What is multi-tenancy?
- Single-tenant vs multi-tenant systems
- Shared database and shared schema
- Shared database with separate schemas
- Separate database per tenant
- Tenant identification and isolation
- Data isolation and access control
- Tenant-aware caching
- Tenant-aware rate limiting
- Resource quotas and noisy-neighbor problems
- Tenant provisioning and lifecycle management
- Multi-tenant scaling strategies
- Security and compliance considerations

### 7. Cell-Based Architecture
- What is cell-based architecture?
- Cells and cell boundaries
- Isolating failures within cells
- Cell routing and tenant placement
- Cell-level data ownership
- Cell provisioning and scaling
- Handling overloaded cells
- Cell migration and rebalancing
- Cell-based vs multi-region architecture
- Fault isolation and blast-radius reduction
- Cell-based architecture use cases

### 8. Event-Driven Architecture
- Event-driven architecture fundamentals
- Event producers and consumers
- Event notification
- Event-carried state transfer
- Event choreography
- Event orchestration
- Event contracts and schemas
- Event versioning and compatibility
- Event-driven microservices
- Eventual consistency
- Transactional Outbox and Inbox patterns
- Event replay and recovery
- Event-driven architecture trade-offs

### 9. Backend for Frontend and API Gateway Patterns
- API Gateway pattern
- Backend for Frontend (BFF)
- Request routing and aggregation
- Authentication and authorization at the gateway
- Rate limiting and throttling
- Response transformation
- API composition
- Gateway vs service mesh
- BFF per client type
- Gateway bottlenecks and failure handling
- Choosing between API Gateway and BFF

---

## Topic Files

| # | Topic | File |
|---|---|---|
| 01 | Monolithic and Microservices Architecture | `01-monolithic-and-microservices-architecture.md` |
| 02 | Service-Oriented Architecture | `02-service-oriented-architecture.md` |
| 03 | Domain-Driven Design | `03-domain-driven-design.md` |
| 04 | Layered and Hexagonal Architecture | `04-layered-and-hexagonal-architecture.md` |
| 05 | CQRS and Event Sourcing | `05-cqrs-and-event-sourcing.md` |
| 06 | Multi-Tenant Architecture | `06-multi-tenant-architecture.md` |
| 07 | Cell-Based Architecture | `07-cell-based-architecture.md` |
| 08 | Event-Driven Architecture | `08-event-driven-architecture.md` |
| 09 | Backend for Frontend and API Gateway Patterns | `09-backend-for-frontend-and-api-gateway.md` |

---

## Folder Structure

\`\`\`text
09-architecture-patterns/
│
├── README.md
├── 01-monolithic-and-microservices-architecture.md
├── 02-service-oriented-architecture.md
├── 03-domain-driven-design.md
├── 04-layered-and-hexagonal-architecture.md
├── 05-cqrs-and-event-sourcing.md
├── 06-multi-tenant-architecture.md
├── 07-cell-based-architecture.md
├── 08-event-driven-architecture.md
└── 09-backend-for-frontend-and-api-gateway.md
\`\`\`
