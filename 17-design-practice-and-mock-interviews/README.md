
# Phase 17: Design Practice and Mock Interviews

This phase focuses on applying system design concepts to practical problems and interview scenarios. It provides a structured progression from basic component design to complex distributed systems, helping develop the ability to gather requirements, estimate scale, design architectures, and explain trade-offs.

The goal is to build confidence in solving open-ended system design problems, communicate architectural decisions clearly, and develop a repeatable approach to system design interviews.

---

## Topics Covered

### 1. System Design Interview Fundamentals
- What is a system design interview?
- High-Level Design (HLD) vs Low-Level Design (LLD)
- Functional requirements
- Non-functional requirements
- Clarifying questions
- Identifying constraints and assumptions
- Defining system boundaries
- API design and data modeling
- Architecture diagrams
- Identifying bottlenecks and failure points
- Discussing trade-offs
- Communicating design decisions

### 2. Requirement Gathering and Estimation
- Functional and non-functional requirement gathering
- Identifying users and core use cases
- Traffic estimation
- Requests per second (RPS)
- Daily active users (DAU) and monthly active users (MAU)
- Read-to-write ratio
- Storage estimation
- Bandwidth estimation
- Memory and cache estimation
- Capacity planning
- Peak traffic estimation
- Back-of-the-envelope calculations
- Making and validating assumptions

### 3. Design Problem Solving Framework
- Step 1: Clarify requirements
- Step 2: Define functional and non-functional requirements
- Step 3: Estimate scale and capacity
- Step 4: Define APIs and data models
- Step 5: Draw the high-level architecture
- Step 6: Deep dive into critical components
- Step 7: Identify bottlenecks and failure scenarios
- Step 8: Discuss scalability and reliability
- Step 9: Evaluate trade-offs
- Step 10: Summarize the design

### 4. Level 1: Foundational Design Problems
Focus: Core components, APIs, data models, and basic architecture.

- Design a URL Shortener
- Design a Rate Limiter
- Design a Notification Service
- Design a File Upload Service
- Design a Key-Value Store
- Design a Distributed Cache
- Design a Unique ID Generator
- Design a Web Crawler

### 5. Level 2: Intermediate Design Problems
Focus: Scaling, caching, databases, messaging, and distributed communication.

- Design a Pastebin
- Design a News Feed
- Design a Chat Application
- Design a Social Media Following System
- Design a Search Autocomplete System
- Design a Video Upload and Processing Platform
- Design a Ride-Hailing Location Service
- Design a Distributed Job Scheduler

### 6. Level 3: Advanced Design Problems
Focus: High availability, consistency, distributed transactions, and large-scale architecture.

- Design WhatsApp
- Design Twitter/X
- Design YouTube
- Design Netflix
- Design Instagram
- Design Uber
- Design Google Maps
- Design Google Drive
- Design Google Docs
- Design a Payment System
- Design an E-Commerce Platform
- Design a Ticket Booking System

### 7. Level 4: Staff-Level and Complex Design Problems
Focus: Multi-region architecture, massive scale, fault isolation, cost optimization, and organizational constraints.

- Design a Global Distributed Database
- Design a Multi-Region Messaging Platform
- Design a Global Content Delivery Network
- Design a Multi-Tenant SaaS Platform
- Design a Large-Scale Event Streaming Platform
- Design a Global Search Infrastructure
- Design a Real-Time Analytics Platform
- Design a Multi-Region Payment Infrastructure
- Design a Large-Scale Data Platform
- Design a Globally Distributed Collaboration System

### 8. Architecture Deep-Dive Exercises
- Identify the system's critical path
- Find single points of failure
- Analyze database bottlenecks
- Identify hot keys and hot partitions
- Evaluate caching strategies
- Choose partition and shard keys
- Analyze consistency requirements
- Design retry and failure handling
- Evaluate replication strategies
- Plan for regional outages
- Estimate infrastructure costs
- Optimize latency and throughput
- Compare alternative architectures

### 9. Mock Interview Practice
- 30-minute system design interview
- 45-minute system design interview
- 60-minute system design interview
- Requirement gathering exercises
- Architecture diagram exercises
- API and data model exercises
- Deep-dive discussion exercises
- Trade-off explanation exercises
- Interviewer-led and candidate-led sessions
- Peer mock interviews
- Self-review and feedback
- Time management and communication

### 10. Design Review and Evaluation
- Requirement coverage
- Functional correctness
- Architecture clarity
- API design quality
- Data model quality
- Scalability
- Availability and reliability
- Consistency choices
- Fault tolerance
- Security considerations
- Performance and latency
- Cost efficiency
- Trade-off reasoning
- Communication and presentation

---

## Topic Files

| # | Topic | File |
|---|---|---|
| 01 | System Design Interview Fundamentals | `01-system-design-interview-fundamentals.md` |
| 02 | Requirement Gathering and Estimation | `02-requirement-gathering-and-estimation.md` |
| 03 | Design Problem Solving Framework | `03-design-problem-solving-framework.md` |
| 04 | Level 1: Foundational Design Problems | `04-level-1-foundational-design-problems.md` |
| 05 | Level 2: Intermediate Design Problems | `05-level-2-intermediate-design-problems.md` |
| 06 | Level 3: Advanced Design Problems | `06-level-3-advanced-design-problems.md` |
| 07 | Level 4: Staff-Level Design Problems | `07-level-4-staff-level-design-problems.md` |
| 08 | Architecture Deep-Dive Exercises | `08-architecture-deep-dive-exercises.md` |
| 09 | Mock Interview Practice | `09-mock-interview-practice.md` |
| 10 | Design Review and Evaluation | `10-design-review-and-evaluation.md` |

---

## Folder Structure

\`\`\`text
17-design-practice-and-mock-interviews/
│
├── README.md
├── 01-system-design-interview-fundamentals.md
├── 02-requirement-gathering-and-estimation.md
├── 03-design-problem-solving-framework.md
├── 04-level-1-foundational-design-problems.md
├── 05-level-2-intermediate-design-problems.md
├── 06-level-3-advanced-design-problems.md
├── 07-level-4-staff-level-design-problems.md
├── 08-architecture-deep-dive-exercises.md
├── 09-mock-interview-practice.md
└── 10-design-review-and-evaluation.md
\`\`\`
