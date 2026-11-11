
# Phase 18: Staff-Level System Design

This phase focuses on the architectural thinking, technical leadership, and decision-making skills expected of senior and staff-level engineers. It explores how to design systems across teams and business domains, evaluate long-term trade-offs, manage migrations, optimize costs, and communicate technical strategy.

The goal is to develop the ability to make high-impact architecture decisions, influence engineering direction, and lead complex technical initiatives across an organization.

---

## Topics Covered

### 1. Architecture and Technical Strategy
- Defining technical vision and architecture principles
- Aligning architecture with business goals
- Translating business requirements into technical strategy
- Evaluating build vs buy decisions
- Architecture evolution and long-term planning
- Identifying architectural risks
- Managing technical debt
- Balancing short-term delivery and long-term quality
- Architecture decision records (ADRs)
- Architecture governance
- Establishing engineering standards
- Measuring architecture effectiveness

### 2. Large-Scale System Design Decisions
- Designing systems across multiple teams
- Defining service and domain boundaries
- Choosing between monoliths and microservices
- Database technology selection
- Consistency and availability trade-offs
- Synchronous vs asynchronous communication
- Event-driven architecture decisions
- Multi-region architecture
- Data ownership and service boundaries
- Shared infrastructure vs independent platforms
- Managing cross-service dependencies
- Evaluating architectural alternatives

### 3. Scalability, Reliability, and Resilience Strategy
- Capacity planning at organizational scale
- Horizontal and vertical scaling trade-offs
- Global traffic management
- Multi-region availability strategies
- Fault isolation and blast-radius reduction
- Reliability targets and error budgets
- SLO-driven architecture
- Disaster recovery planning
- Failure mode analysis
- Resilience testing
- Reliability investment prioritization
- Balancing reliability and infrastructure cost

### 4. Cost Optimization and FinOps
- Infrastructure cost fundamentals
- Compute, storage, and network cost analysis
- Cloud cost allocation
- Cost per request and cost per customer
- Resource utilization optimization
- Capacity planning and overprovisioning
- Autoscaling and rightsizing
- Storage tiering and lifecycle policies
- Caching and data transfer cost optimization
- Multi-region cost trade-offs
- Cost-aware architecture decisions
- FinOps principles
- Measuring cost efficiency

### 5. System Migrations and Modernization
- Legacy system modernization
- Monolith to microservices migration
- Strangler Fig pattern
- Database migration strategies
- Schema evolution and compatibility
- Zero-downtime migrations
- Data backfill and reconciliation
- Dual writes and their risks
- Shadow traffic and traffic mirroring
- Incremental migration strategies
- Rollback and recovery planning
- Migration risk management
- Measuring migration success

### 6. Platform Engineering and Developer Productivity
- Platform engineering fundamentals
- Internal Developer Platforms (IDPs)
- Self-service infrastructure
- Golden paths and paved roads
- Developer experience (DevEx)
- Infrastructure abstraction
- Service templates and scaffolding
- CI/CD platform design
- Developer tooling and automation
- Platform reliability and ownership
- Platform adoption and feedback
- Measuring developer productivity

### 7. Technical Leadership and Cross-Team Collaboration
- Technical leadership without direct authority
- Influencing engineering decisions
- Cross-team architecture alignment
- Managing technical disagreements
- Driving technical initiatives
- Mentoring senior engineers
- Building engineering consensus
- Delegation and ownership
- Managing dependencies between teams
- Communicating technical trade-offs
- Working with product and business stakeholders
- Creating a culture of technical excellence

### 8. Design Documents and Technical Communication
- Writing architecture design documents
- Problem statements and context
- Requirements and constraints
- Architecture diagrams
- API and data model documentation
- Evaluating design alternatives
- Documenting trade-offs and risks
- Architecture Decision Records (ADRs)
- Technical proposals and RFCs
- Design reviews
- Presenting architecture to leadership
- Communicating complex systems clearly

### 9. Organizational Design and Engineering Processes
- Team topology and ownership boundaries
- Conway's Law
- Team APIs and service ownership
- Platform teams vs product teams
- Centralized vs decentralized architecture decisions
- Engineering governance
- Technical standards and consistency
- Incident ownership and escalation
- Cross-team planning
- Managing architectural dependencies
- Balancing autonomy and alignment
- Organizational scalability

### 10. Staff-Level System Design Scenarios
- Designing a global multi-region platform
- Modernizing a large legacy architecture
- Migrating a monolith with zero downtime
- Reducing infrastructure costs at scale
- Improving reliability across critical services
- Designing a shared internal platform
- Splitting a large service into independent domains
- Handling organization-wide data consistency
- Building a platform for multiple engineering teams
- Managing a high-risk architecture migration
- Evaluating competing long-term architecture strategies
- Defending architecture decisions with business and technical reasoning

---

## Topic Files

| # | Topic | File |
|---|---|---|
| 01 | Architecture and Technical Strategy | `01-architecture-and-technical-strategy.md` |
| 02 | Large-Scale System Design Decisions | `02-large-scale-system-design-decisions.md` |
| 03 | Scalability, Reliability, and Resilience Strategy | `03-scalability-reliability-and-resilience-strategy.md` |
| 04 | Cost Optimization and FinOps | `04-cost-optimization-and-finops.md` |
| 05 | System Migrations and Modernization | `05-system-migrations-and-modernization.md` |
| 06 | Platform Engineering and Developer Productivity | `06-platform-engineering-and-developer-productivity.md` |
| 07 | Technical Leadership and Cross-Team Collaboration | `07-technical-leadership-and-cross-team-collaboration.md` |
| 08 | Design Documents and Technical Communication | `08-design-documents-and-technical-communication.md` |
| 09 | Organizational Design and Engineering Processes | `09-organizational-design-and-engineering-processes.md` |
| 10 | Staff-Level System Design Scenarios | `10-staff-level-system-design-scenarios.md` |

---

## Folder Structure

\`\`\`text
18-staff-level-system-design/
│
├── README.md
├── 01-architecture-and-technical-strategy.md
├── 02-large-scale-system-design-decisions.md
├── 03-scalability-reliability-and-resilience-strategy.md
├── 04-cost-optimization-and-finops.md
├── 05-system-migrations-and-modernization.md
├── 06-platform-engineering-and-developer-productivity.md
├── 07-technical-leadership-and-cross-team-collaboration.md
├── 08-design-documents-and-technical-communication.md
├── 09-organizational-design-and-engineering-processes.md
└── 10-staff-level-system-design-scenarios.md
\`\`\`
