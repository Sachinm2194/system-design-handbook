
# LLD-D: Machine Coding and Practical Design Problems

This phase focuses on implementing complete, working applications from real-world problem statements. It combines object-oriented design, SOLID principles, design patterns, domain modeling, and clean code practices through hands-on machine coding exercises.

The goal is to develop the ability to translate requirements into working software, design extensible class structures, handle edge cases, write testable code, and implement solutions within practical time constraints.

---

## Topics Covered

### 1. Machine Coding Fundamentals
- What is a machine coding round?
- Machine coding vs LLD interviews
- Understanding problem statements
- Requirement clarification
- Functional and non-functional requirements
- Identifying entities and responsibilities
- Defining class and interface boundaries
- Designing APIs and method contracts
- Class diagrams and object relationships
- Implementation planning
- Handling edge cases
- Writing clean and maintainable code
- Time management during machine coding rounds

### 2. Implementation and Code Organization
- Project structure and package organization
- Separation of concerns
- Layered application design
- Domain, service, and repository layers
- Interface-based design
- Dependency injection
- In-memory data storage
- Input validation
- Exception handling
- Logging and debugging
- Unit testing
- Extensibility and maintainability
- Writing executable applications

### 3. Parking Lot System
- Vehicle types and parking spot types
- Parking lot and floor management
- Vehicle entry and exit
- Parking spot allocation
- Ticket generation
- Parking fee calculation
- Payment handling
- Spot availability
- Multiple floors
- Different allocation strategies
- Extending the system for new vehicle types

### 4. LRU Cache
- Cache interface design
- Key-value storage
- HashMap implementation
- Doubly linked list
- Get and put operations
- Least Recently Used eviction
- Capacity management
- Time complexity analysis
- Thread-safe LRU cache
- Extending the cache with TTL
- Cache eviction strategy abstraction

### 5. BookMyShow / Movie Ticket Booking
- Movie and theatre management
- Screen and show management
- Seat categories
- Seat availability
- Seat locking and temporary reservations
- Booking lifecycle
- Concurrent booking requests
- Double-booking prevention
- Payment integration
- Booking confirmation and cancellation
- Booking expiration
- Refund handling

### 6. Elevator System
- Elevator and floor modeling
- Request and command handling
- Internal and external requests
- Elevator scheduling
- Direction management
- Elevator states
- Multiple elevator coordination
- Scheduling strategies
- Door and safety management
- Handling simultaneous requests
- Extending the system for multiple buildings

### 7. Splitwise / Expense Sharing System
- User and group management
- Expense creation
- Equal expense splitting
- Exact amount splitting
- Percentage-based splitting
- Balance calculation
- Debt tracking
- Simplifying debts
- Settlement operations
- Expense history
- Notifications
- Extensible splitting strategies

### 8. Food Ordering System
- Restaurant and menu management
- Customer and delivery partner modeling
- Cart management
- Order creation
- Order lifecycle and state transitions
- Restaurant order acceptance
- Inventory and item availability
- Pricing and discounts
- Payment processing
- Delivery assignment
- Order tracking
- Cancellation and refund handling

### 9. Ride-Hailing System
- Rider and driver management
- Vehicle modeling
- Ride request creation
- Driver matching
- Location and distance calculation
- Fare calculation
- Surge pricing
- Ride lifecycle
- Ride acceptance and cancellation
- Payment processing
- Driver availability
- Extensible matching strategies

### 10. Inventory Management System
- Product and SKU management
- Warehouse management
- Stock tracking
- Inventory reservation
- Stock allocation
- Replenishment
- Purchase orders
- Stock movement
- Concurrent inventory updates
- Low-stock alerts
- Inventory adjustment
- Audit history

### 11. Logging Framework
- Logger and log level design
- Log message formatting
- Multiple output destinations
- Console and file appenders
- Configurable log levels
- Logging filters
- Asynchronous logging
- Thread safety
- Log rotation
- Extensible appender architecture

### 12. Rate Limiter
- Rate limiter interface
- Fixed window counter
- Sliding window log
- Sliding window counter
- Token bucket
- Leaky bucket
- Per-user and per-client limits
- Time-based window management
- Concurrent request handling
- Distributed rate limiter extension

### 13. Task Scheduler
- Task and scheduler modeling
- One-time and recurring tasks
- Task priorities
- Task execution
- Scheduling strategies
- Delayed execution
- Retry and failure handling
- Task cancellation
- Concurrent execution
- Worker pool management
- Task status tracking

### 14. Additional Machine Coding Problems
- Design a Vending Machine
- Design a Library Management System
- Design a Hotel Booking System
- Design a Chess Game
- Design a Snake and Ladder Game
- Design a Tic-Tac-Toe Game
- Design an ATM
- Design a Car Rental System
- Design an Online Auction System
- Design a Notification Service
- Design a File System
- Design a Meeting Room Scheduler
- Design a Shopping Cart
- Design a Digital Wallet

### 15. HLD and LLD Bridging Exercises
- Translate high-level components into classes
- Identify service boundaries and domain objects
- Convert APIs into method contracts
- Model database entities and relationships
- Implement core business logic
- Apply design patterns to real problems
- Handle concurrency and consistency
- Identify in-memory vs persistent storage responsibilities
- Connect multiple modules
- Design extensible application workflows
- Evaluate code-level and system-level trade-offs

### 16. Machine Coding Evaluation and Practice
- Requirement coverage
- Correctness and edge-case handling
- Object-oriented design quality
- SOLID principle application
- Appropriate design pattern usage
- Code readability and organization
- Extensibility and maintainability
- Testability and unit test coverage
- Time and complexity analysis
- Concurrency handling
- Handling changing requirements
- Explaining design decisions
- Refactoring and improving solutions

---

## Topic Files

| # | Topic | File |
|---|---|---|
| 01 | Machine Coding Fundamentals | `01-machine-coding-fundamentals.md` |
| 02 | Implementation and Code Organization | `02-implementation-and-code-organization.md` |
| 03 | Parking Lot System | `03-parking-lot-system.md` |
| 04 | LRU Cache | `04-lru-cache.md` |
| 05 | BookMyShow / Movie Ticket Booking | `05-movie-ticket-booking-system.md` |
| 06 | Elevator System | `06-elevator-system.md` |
| 07 | Splitwise / Expense Sharing System | `07-expense-sharing-system.md` |
| 08 | Food Ordering System | `08-food-ordering-system.md` |
| 09 | Ride-Hailing System | `09-ride-hailing-system.md` |
| 10 | Inventory Management System | `10-inventory-management-system.md` |
| 11 | Logging Framework | `11-logging-framework.md` |
| 12 | Rate Limiter | `12-rate-limiter.md` |
| 13 | Task Scheduler | `13-task-scheduler.md` |
| 14 | Additional Machine Coding Problems | `14-additional-machine-coding-problems.md` |
| 15 | HLD and LLD Bridging Exercises | `15-hld-and-lld-bridging-exercises.md` |
| 16 | Machine Coding Evaluation and Practice | `16-machine-coding-evaluation-and-practice.md` |

---

## Folder Structure

\`\`\`text
LLD-D-machine-coding/
│
├── README.md
├── 01-machine-coding-fundamentals.md
├── 02-implementation-and-code-organization.md
├── 03-parking-lot-system.md
├── 04-lru-cache.md
├── 05-movie-ticket-booking-system.md
├── 06-elevator-system.md
├── 07-expense-sharing-system.md
├── 08-food-ordering-system.md
├── 09-ride-hailing-system.md
├── 10-inventory-management-system.md
├── 11-logging-framework.md
├── 12-rate-limiter.md
├── 13-task-scheduler.md
├── 14-additional-machine-coding-problems.md
├── 15-hld-and-lld-bridging-exercises.md
└── 16-machine-coding-evaluation-and-practice.md
\`\`\`
