
# LLD-B: Design Patterns

This phase covers commonly used object-oriented design patterns that help solve recurring software design problems. It explores creational, structural, and behavioral patterns, along with dependency injection and common anti-patterns.

The goal is to understand when and why to apply design patterns, how they improve code flexibility and maintainability, and how to implement them in practical low-level design problems.

---

## Topics Covered

### 1. Design Pattern Fundamentals
- What are design patterns?
- Why design patterns are needed
- Design pattern terminology
- Pattern structure: intent, problem, solution, and consequences
- Gang of Four (GoF) design patterns
- Creational, structural, and behavioral patterns
- Composition vs inheritance in pattern design
- Programming to interfaces
- Choosing the right design pattern
- Avoiding overengineering and unnecessary patterns

### 2. Creational Design Patterns
- What are creational patterns?
- Singleton Pattern
- Factory Method Pattern
- Abstract Factory Pattern
- Builder Pattern
- Prototype Pattern
- Object creation and lifecycle management
- Lazy initialization
- Thread-safe Singleton implementation
- Factory vs Abstract Factory
- Factory vs Builder
- Practical use cases and trade-offs

### 3. Structural Design Patterns
- What are structural patterns?
- Adapter Pattern
- Bridge Pattern
- Composite Pattern
- Decorator Pattern
- Facade Pattern
- Flyweight Pattern
- Proxy Pattern
- Static vs dynamic proxies
- Object composition and delegation
- Adapter vs Decorator
- Decorator vs Proxy
- Practical use cases and trade-offs

### 4. Behavioral Design Patterns
- What are behavioral patterns?
- Strategy Pattern
- Observer Pattern
- Command Pattern
- State Pattern
- Chain of Responsibility Pattern
- Template Method Pattern
- Iterator Pattern
- Mediator Pattern
- Memento Pattern
- Visitor Pattern
- Interpreter Pattern
- Strategy vs State
- Observer vs Mediator
- Command vs Strategy
- Practical use cases and trade-offs

### 5. Dependency Injection and Inversion of Control
- What is Dependency Injection (DI)?
- What is Inversion of Control (IoC)?
- Constructor injection
- Setter injection
- Interface injection
- Dependency injection containers
- Dependency inversion vs dependency injection
- Manual dependency injection
- Managing object lifecycles
- Loose coupling through dependency injection
- Dependency injection in testing
- Common dependency injection mistakes

### 6. Enterprise and Application Design Patterns
- Repository Pattern
- Unit of Work Pattern
- Data Mapper Pattern
- Active Record Pattern
- Service Layer Pattern
- Specification Pattern
- DTO (Data Transfer Object) Pattern
- MVC (Model-View-Controller)
- MVP (Model-View-Presenter)
- MVVM (Model-View-ViewModel)
- Front Controller Pattern
- Dependency injection in layered applications
- Choosing application-level patterns

### 7. Concurrency and Thread-Safe Design Patterns
- Thread-safe Singleton
- Producer-Consumer Pattern
- Thread Pool Pattern
- Read-Write Lock Pattern
- Immutable Object Pattern
- Guarded Suspension Pattern
- Active Object Pattern
- Double-Checked Locking
- Synchronization and shared state
- Thread-safe object design
- Concurrency-related design trade-offs

### 8. Design Pattern Selection and Anti-Patterns
- Identifying recurring design problems
- Mapping problems to appropriate patterns
- Combining multiple design patterns
- Pattern trade-offs and complexity
- Common design pattern misuse
- Singleton overuse
- God object anti-pattern
- Service locator anti-pattern
- Anemic domain model
- Over-abstraction
- Premature optimization
- Refactoring toward better design
- Evaluating maintainability and extensibility

---

## Topic Files

| # | Topic | File |
|---|---|---|
| 01 | Design Pattern Fundamentals | `01-design-pattern-fundamentals.md` |
| 02 | Creational Design Patterns | `02-creational-design-patterns.md` |
| 03 | Structural Design Patterns | `03-structural-design-patterns.md` |
| 04 | Behavioral Design Patterns | `04-behavioral-design-patterns.md` |
| 05 | Dependency Injection and Inversion of Control | `05-dependency-injection-and-inversion-of-control.md` |
| 06 | Enterprise and Application Design Patterns | `06-enterprise-and-application-design-patterns.md` |
| 07 | Concurrency and Thread-Safe Design Patterns | `07-concurrency-and-thread-safe-design-patterns.md` |
| 08 | Design Pattern Selection and Anti-Patterns | `08-design-pattern-selection-and-anti-patterns.md` |

---

## Folder Structure

\`\`\`text
LLD-B-design-patterns/
│
├── README.md
├── 01-design-pattern-fundamentals.md
├── 02-creational-design-patterns.md
├── 03-structural-design-patterns.md
├── 04-behavioral-design-patterns.md
├── 05-dependency-injection-and-inversion-of-control.md
├── 06-enterprise-and-application-design-patterns.md
├── 07-concurrency-and-thread-safe-design-patterns.md
└── 08-design-pattern-selection-and-anti-patterns.md
\`\`\`
