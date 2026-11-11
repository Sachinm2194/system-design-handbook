
# Phase 7: Messaging and Streaming

This phase covers asynchronous communication, message queues, event-driven architecture, distributed messaging systems, and real-time data streaming. It explores how services communicate reliably without being tightly coupled and how large volumes of events are processed at scale.

The goal is to understand how to design scalable messaging and streaming architectures, handle message delivery guarantees, and build reliable event-driven systems.

---

## Topics Covered

### 1. Messaging Fundamentals
- Synchronous vs asynchronous communication
- What is message-based communication?
- Message queues and message brokers
- Producer and consumer architecture
- Point-to-point messaging
- Publish-Subscribe (Pub/Sub) pattern
- Event-driven architecture
- Commands vs events
- Message routing and delivery
- Message ordering
- Message acknowledgements
- Message persistence
- Queue durability
- Backpressure and flow control

### 2. Message Queues
- Queue architecture and components
- Work queues and task queues
- Competing consumers
- Consumer groups
- Message visibility timeout
- Message acknowledgement and rejection
- Dead Letter Queues (DLQ)
- Delayed and scheduled messages
- Priority queues
- Message retries
- Poison messages
- Queue scaling and partitioning
- RabbitMQ architecture and exchanges
- Direct, fanout, topic, and headers exchanges

### 3. Apache Kafka Fundamentals
- What is Apache Kafka?
- Kafka architecture and components
- Brokers, topics, and partitions
- Producers and consumers
- Consumer groups
- Offsets and consumer positions
- Replication factor
- Leader and follower replicas
- Partition leadership and reassignment
- Kafka message format
- Log-based storage
- Retention policies
- Log compaction
- Kafka architecture and scalability

### 4. Message Delivery Semantics
- At-most-once delivery
- At-least-once delivery
- Exactly-once processing
- Message duplication
- Idempotent consumers
- Message deduplication
- Producer acknowledgements
- Consumer acknowledgements and offset commits
- Automatic vs manual offset commits
- Retry strategies
- Ordering guarantees
- Transactional messaging
- Delivery guarantees vs processing guarantees

### 5. Kafka Advanced Concepts
- Kafka producer internals
- Batching and compression
- Producer idempotence
- Kafka transactions
- Consumer rebalancing
- Partition assignment strategies
- Consumer lag
- Replication and in-sync replicas (ISR)
- Leader election
- Unclean leader election
- Kafka Connect
- Change Data Capture (CDC)
- Kafka Streams
- Kafka cluster operations and monitoring

### 6. Stream Processing
- Batch processing vs stream processing
- Stream processing fundamentals
- Event time vs processing time
- Windows and windowing operations
- Tumbling, sliding, and session windows
- Stateful vs stateless processing
- Event-time ordering
- Late-arriving events
- Watermarks
- Stream joins
- Aggregations and transformations
- Checkpointing and fault tolerance
- Exactly-once stream processing
- Apache Flink architecture
- Kafka Streams vs Apache Flink

### 7. Workflow Engines and Orchestration
- Workflow orchestration fundamentals
- Workflow vs message queue
- Task scheduling and execution
- Workflow state management
- Durable execution
- Retries and failure recovery
- Timeouts and compensation
- Long-running workflows
- Workflow versioning
- Distributed workflow execution
- Temporal architecture and fundamentals
- Workflow engines vs traditional job schedulers

### 8. Event-Driven System Design
- Event-driven architecture patterns
- Event notification
- Event-carried state transfer
- Event sourcing fundamentals
- Transactional Outbox pattern
- Inbox pattern
- Saga pattern overview
- Event choreography vs orchestration
- Schema evolution and compatibility
- Event versioning
- Event replay
- Handling duplicate and out-of-order events
- Designing reliable event-driven systems

---

## Topic Files

| # | Topic | File |
|---|---|---|
| 01 | Messaging Fundamentals | `01-messaging-fundamentals.md` |
| 02 | Message Queues | `02-message-queues.md` |
| 03 | Apache Kafka Fundamentals | `03-apache-kafka-fundamentals.md` |
| 04 | Message Delivery Semantics | `04-message-delivery-semantics.md` |
| 05 | Kafka Advanced Concepts | `05-kafka-advanced-concepts.md` |
| 06 | Stream Processing | `06-stream-processing.md` |
| 07 | Workflow Engines and Orchestration | `07-workflow-engines-and-orchestration.md` |
| 08 | Event-Driven System Design | `08-event-driven-system-design.md` |

---

## Folder Structure

\`\`\`text
07-messaging-and-streaming/
│
├── README.md
├── 01-messaging-fundamentals.md
├── 02-message-queues.md
├── 03-apache-kafka-fundamentals.md
├── 04-message-delivery-semantics.md
├── 05-kafka-advanced-concepts.md
├── 06-stream-processing.md
├── 07-workflow-engines-and-orchestration.md
└── 08-event-driven-system-design.md
\`\`\`
