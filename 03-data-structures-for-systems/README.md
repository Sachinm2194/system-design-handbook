
# Phase 3: Data Structures and Algorithms for Systems

<sub>Duration: Weeks 5–6</sub>

## Overview

Understand the data structures and algorithms used internally by databases, distributed systems, storage engines, and large-scale applications. Focus on how these structures improve search performance, optimize storage, distribute data, and handle large-scale workloads efficiently.

---

## Topics Covered

### 1. Hashing Fundamentals
- Hash functions and their properties
- Hash collisions
- Collision resolution techniques
- Separate chaining
- Open addressing
- Hash tables
- Load factor and resizing
- Cryptographic vs non-cryptographic hashing
- Consistent and uniform hash distribution

### 2. B-Trees and B+ Trees
- Tree data structure fundamentals
- B-Tree structure and properties
- B+ Tree structure and properties
- Node splitting and merging
- Insertion and deletion
- Range queries
- Disk-based indexing
- B-Tree vs B+ Tree
- Usage in database indexes and file systems

### 3. Log-Structured Merge Trees (LSM)
- LSM Tree fundamentals
- Memtables and immutable memtables
- SSTables (Sorted String Tables)
- Write-ahead logs (WAL)
- Flush and compaction
- Leveled and tiered compaction
- Read and write amplification
- Tombstones
- LSM Tree vs B-Tree
- Usage in RocksDB, LevelDB and Cassandra

### 4. Bloom Filters
- Probabilistic data structures
- Bloom Filter fundamentals
- Bit arrays and hash functions
- False positive probability
- False negatives
- Optimal number of hash functions
- Space efficiency
- Counting Bloom Filters
- Scalable Bloom Filters
- Usage in databases and distributed storage

### 5. Consistent Hashing
- Consistent hashing fundamentals
- Hash rings
- Virtual nodes
- Node addition and removal
- Data redistribution
- Load distribution
- Hot partitions and hotspots
- Replication with consistent hashing
- Consistent hashing vs traditional hashing
- Usage in distributed caches and databases

### 6. Rendezvous Hashing
- Rendezvous hashing fundamentals
- Highest Random Weight (HRW) hashing
- Node selection
- Node addition and removal
- Load distribution
- Rendezvous hashing vs consistent hashing
- Practical use cases

### 7. Geohash
- Geospatial indexing fundamentals
- Latitude and longitude
- Geohash encoding and decoding
- Binary subdivision of geographic regions
- Geohash precision
- Neighboring geohash cells
- Range queries
- Proximity search
- Geohash limitations and boundary problems
- Usage in location-based services

### 8. Skip Lists and Merkle Trees
- Skip List fundamentals
- Multi-level linked lists
- Search, insertion and deletion
- Time complexity
- Merkle Tree fundamentals
- Hash trees
- Parent and leaf hashes
- Data integrity verification
- Merkle proofs
- Usage in distributed storage and synchronization

---

## Topic Files

| # | Topic | File |
|---|---|---|
| 01 | Hashing Fundamentals | `01-hashing-fundamentals.md` |
| 02 | B-Trees and B+ Trees | `02-b-trees-and-b-plus-trees.md` |
| 03 | LSM Trees | `03-lsm-trees.md` |
| 04 | Bloom Filters | `04-bloom-filters.md` |
| 05 | Consistent Hashing | `05-consistent-hashing.md` |
| 06 | Rendezvous Hashing | `06-rendezvous-hashing.md` |
| 07 | Geohash | `07-geohash.md` |
| 08 | Skip Lists and Merkle Trees | `08-skip-lists-and-merkle-trees.md` |
