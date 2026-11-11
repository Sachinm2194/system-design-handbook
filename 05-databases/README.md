
# Phase 5: Databases

This phase covers database fundamentals, data models, storage engines, indexing, transactions, replication, and scaling strategies. It explores how databases store, retrieve, and manage data while maintaining performance, consistency, and reliability.

The goal is to understand how to choose, design, and scale databases based on application requirements and system design trade-offs.

---

## Topics Covered

### 1. Database Fundamentals
- What is a database?
- Database management systems (DBMS)
- Relational vs non-relational databases
- Structured, semi-structured, and unstructured data
- Database schemas and data models
- Primary keys and foreign keys
- Constraints and relationships
- Normalization: 1NF, 2NF, 3NF, BCNF
- Denormalization and its trade-offs
- OLTP vs OLAP
- ACID properties

### 2. SQL Databases
- Relational database fundamentals
- Tables, rows, and columns
- SQL query fundamentals
- Joins: INNER, LEFT, RIGHT, FULL
- Aggregations and GROUP BY
- Subqueries and common table expressions
- Transactions in SQL
- Stored procedures and triggers
- Connection pooling
- PostgreSQL and MySQL architecture
- When to choose relational databases

### 3. NoSQL Databases
- Why NoSQL databases exist
- Relational vs NoSQL trade-offs
- Key-value databases
- Document databases
- Wide-column databases
- Graph databases
- Data modeling in NoSQL
- Denormalization in NoSQL systems
- Query patterns and access-driven modeling
- Choosing the right NoSQL database

### 4. Database Indexing
- Why indexes are needed
- Primary and secondary indexes
- Clustered and non-clustered indexes
- B-tree and B+ tree indexes
- Hash indexes
- Composite indexes
- Covering indexes
- Unique indexes
- Full-text indexes
- Index selectivity and cardinality
- Index maintenance and write overhead
- Query execution plans
- Query optimization and EXPLAIN

### 5. Transactions and Concurrency Control
- Transaction lifecycle
- ACID properties in practice
- Isolation levels:
  - Read Uncommitted
  - Read Committed
  - Repeatable Read
  - Serializable
- Dirty reads
- Non-repeatable reads
- Phantom reads
- Lost updates
- Optimistic concurrency control
- Pessimistic concurrency control
- Multi-Version Concurrency Control (MVCC)
- Locks and lock granularity
- Deadlocks and deadlock prevention
- Write-ahead logging (WAL)

### 6. Replication and High Availability
- Why database replication is needed
- Primary-replica architecture
- Synchronous replication
- Asynchronous replication
- Semi-synchronous replication
- Replication lag
- Read replicas and read scaling
- Failover and leader election
- Automatic failover
- Split-brain scenarios
- Multi-primary replication
- Conflict resolution
- High availability and disaster recovery

### 7. Sharding and Partitioning
- Why database sharding is needed
- Horizontal vs vertical partitioning
- Range-based sharding
- Hash-based sharding
- Directory-based sharding
- Consistent hashing for shard distribution
- Choosing a shard key
- Hot partitions and hotspots
- Cross-shard queries
- Cross-shard transactions
- Rebalancing and shard migration
- Sharding vs partitioning

### 8. Database Storage Engines
- What is a storage engine?
- Row-oriented vs column-oriented storage
- Page-based storage
- Buffer pool and page cache
- Write-ahead log (WAL)
- B-tree storage engines
- LSM-tree storage engines
- Compaction and garbage collection
- Read and write amplification
- Storage engine trade-offs
- InnoDB architecture
- RocksDB fundamentals

### 9. Distributed Databases and NewSQL
- Distributed database fundamentals
- Shared-nothing architecture
- Distributed transactions
- Two-Phase Commit (2PC)
- Consensus in database systems
- Strong consistency vs eventual consistency
- Distributed SQL databases
- NewSQL architecture
- CockroachDB fundamentals
- Google Spanner architecture
- Distributed database trade-offs

### 10. OLAP and Analytical Databases
- OLTP vs OLAP
- Row stores vs column stores
- Columnar storage
- Data warehouses
- Analytical query execution
- Aggregations and large-scale scans
- Materialized views
- Data cubes and dimensional modeling
- Star and snowflake schemas
- ClickHouse fundamentals
- When to use analytical databases

---

## Topic Files

| # | Topic | File |
|---|---|---|
| 01 | Database Fundamentals | `01-database-fundamentals.md` |
| 02 | SQL Databases | `02-sql-databases.md` |
| 03 | NoSQL Databases | `03-nosql-databases.md` |
| 04 | Database Indexing | `04-database-indexing.md` |
| 05 | Transactions and Concurrency Control | `05-transactions-and-concurrency-control.md` |
| 06 | Replication and High Availability | `06-replication-and-high-availability.md` |
| 07 | Sharding and Partitioning | `07-sharding-and-partitioning.md` |
| 08 | Database Storage Engines | `08-database-storage-engines.md` |
| 09 | Distributed Databases and NewSQL | `09-distributed-databases-and-newsql.md` |
| 10 | OLAP and Analytical Databases | `10-olap-and-analytical-databases.md` |

---

## Folder Structure

\`\`\`text
05-databases/
│
├── README.md
├── 01-database-fundamentals.md
├── 02-sql-databases.md
├── 03-nosql-databases.md
├── 04-database-indexing.md
├── 05-transactions-and-concurrency-control.md
├── 06-replication-and-high-availability.md
├── 07-sharding-and-partitioning.md
├── 08-database-storage-engines.md
├── 09-distributed-databases-and-newsql.md
└── 10-olap-and-analytical-databases.md
\`\`\`
