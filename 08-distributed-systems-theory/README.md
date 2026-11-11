
# Phase 8: Distributed Systems Theory

This phase covers the fundamental concepts, algorithms, and trade-offs behind distributed systems. It explores how multiple independent nodes coordinate, maintain consistency, handle failures, and operate reliably across networks.

The goal is to understand the theoretical foundations of distributed systems and apply them to real-world system design decisions.

---

## Topics Covered

### 1. Distributed Systems Fundamentals
- What is a distributed system?
- Characteristics of distributed systems
- Distributed system architecture
- Network communication and partial failures
- Fault tolerance and failure handling
- Failure models: crash, omission, and Byzantine failures
- Node failures and network partitions
- Timeouts, retries, and failure detection
- Availability and reliability
- Horizontal scaling and decentralization
- Challenges in distributed computing

### 2. CAP Theorem and PACELC
- What is the CAP theorem?
- Consistency, Availability, and Partition Tolerance
- Network partitions
- CP vs AP systems
- Why CA is not achievable during a network partition
- CAP theorem trade-offs in practice
- Strong consistency vs eventual consistency
- PACELC theorem
- Latency vs consistency trade-offs
- CAP and PACELC examples in real systems

### 3. Consistency Models
- What is consistency in distributed systems?
- Strong consistency
- Linearizability
- Sequential consistency
- Causal consistency
- Eventual consistency
- Read-your-writes consistency
- Monotonic reads
- Monotonic writes
- Consistent prefix reads
- Quorum-based consistency
- Consistency vs availability
- Choosing consistency models for applications

### 4. Consensus Algorithms
- What is consensus?
- Why consensus is difficult in distributed systems
- Leader election
- Distributed coordination
- Paxos fundamentals
- Basic Paxos and Multi-Paxos
- Raft consensus algorithm
- Raft roles and states
- Leader election in Raft
- Log replication
- Safety and liveness
- Membership changes
- Consensus vs atomic broadcast
- Practical uses of consensus algorithms

### 5. Distributed Time and Ordering
- Physical clocks and clock synchronization
- Clock drift and clock skew
- NTP fundamentals
- Logical clocks
- Lamport timestamps
- Vector clocks
- Happens-before relationship
- Event ordering
- Total ordering vs partial ordering
- Hybrid Logical Clocks (HLC)
- Distributed timestamps
- Last-write-wins and its limitations

### 6. Distributed Transactions and Sagas
- Distributed transaction fundamentals
- Challenges of transactions across services
- Two-Phase Commit (2PC)
- Coordinator and participant roles
- Blocking and failure scenarios in 2PC
- Three-Phase Commit (3PC) overview
- Distributed transaction limitations
- Saga pattern
- Choreography vs orchestration
- Compensating transactions
- Retry and recovery strategies
- Eventual consistency in distributed workflows
- Choosing between 2PC and Saga

### 7. Conflict-Free Replicated Data Types (CRDTs)
- What are CRDTs?
- Strong Eventual Consistency
- State-based CRDTs
- Operation-based CRDTs
- Grow-only counters
- Positive-Negative counters
- Grow-only sets
- Two-phase sets
- Last-Write-Wins registers
- Observed-Remove Sets (OR-Set)
- Conflict resolution
- CRDT limitations and trade-offs
- CRDT use cases in collaborative systems

### 8. Quorums and Replication
- Distributed replication fundamentals
- Leader-based replication
- Leaderless replication
- Read and write quorums
- Quorum intersection
- R + W > N rule
- Tunable consistency
- Sloppy quorums
- Hinted handoff
- Read repair
- Anti-entropy mechanisms
- Merkle trees for replica synchronization
- Replication conflicts and resolution

### 9. Distributed Coordination and Membership
- Service discovery
- Node membership and failure detection
- Heartbeats and gossip protocols
- Distributed locks
- Lease-based coordination
- Fencing tokens
- Leader election mechanisms
- Coordination services
- ZooKeeper fundamentals
- etcd fundamentals
- Distributed configuration management
- Split-brain prevention
- Coordination trade-offs

---

## Topic Files

| # | Topic | File |
|---|---|---|
| 01 | Distributed Systems Fundamentals | `01-distributed-systems-fundamentals.md` |
| 02 | CAP Theorem and PACELC | `02-cap-theorem-and-pacelc.md` |
| 03 | Consistency Models | `03-consistency-models.md` |
| 04 | Consensus Algorithms | `04-consensus-algorithms.md` |
| 05 | Distributed Time and Ordering | `05-distributed-time-and-ordering.md` |
| 06 | Distributed Transactions and Sagas | `06-distributed-transactions-and-sagas.md` |
| 07 | Conflict-Free Replicated Data Types | `07-conflict-free-replicated-data-types.md` |
| 08 | Quorums and Replication | `08-quorums-and-replication.md` |
| 09 | Distributed Coordination and Membership | `09-distributed-coordination-and-membership.md` |

---

## Folder Structure

\`\`\`text
08-distributed-systems-theory/
│
├── README.md
├── 01-distributed-systems-fundamentals.md
├── 02-cap-theorem-and-pacelc.md
├── 03-consistency-models.md
├── 04-consensus-algorithms.md
├── 05-distributed-time-and-ordering.md
├── 06-distributed-transactions-and-sagas.md
├── 07-conflict-free-replicated-data-types.md
├── 08-quorums-and-replication.md
└── 09-distributed-coordination-and-membership.md
\`\`\`
