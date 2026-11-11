
# Phase 4: APIs and Communication

This phase covers how services communicate with clients and with other services. It focuses on API design, communication protocols, real-time communication, request safety, rate limiting, and data serialization.

The goal is to understand how to design reliable, scalable, and efficient communication interfaces in distributed systems.

---

## Topics Covered

### 1. API Design Fundamentals
- What is an API?
- API contracts and interface design
- API endpoints and resources
- Request and response structure
- API versioning strategies
- Backward and forward compatibility
- Pagination: offset-based and cursor-based
- Filtering, sorting, and searching
- API documentation and specifications
- OpenAPI and Swagger

### 2. REST APIs
- REST architectural constraints
- Resources and resource-oriented design
- HTTP methods: GET, POST, PUT, PATCH, DELETE
- HTTP status codes
- Idempotent and non-idempotent operations
- Safe methods and idempotency
- Stateless communication
- REST API best practices
- Error handling and response formats
- REST API limitations

### 3. gRPC
- What is gRPC?
- Remote Procedure Call (RPC) fundamentals
- gRPC architecture and request lifecycle
- Protocol Buffers (Protobuf)
- Service and message definitions
- Unary RPC
- Server streaming
- Client streaming
- Bidirectional streaming
- Deadlines, timeouts, and cancellation
- Error handling and status codes
- gRPC vs REST
- Service-to-service communication use cases

### 4. GraphQL
- What is GraphQL?
- GraphQL architecture
- Schema Definition Language (SDL)
- Queries, mutations, and subscriptions
- Types, fields, and resolvers
- Nested queries and relationships
- Pagination in GraphQL
- N+1 query problem
- DataLoader and batching
- GraphQL vs REST
- Caching considerations
- When to use GraphQL

### 5. WebSockets and Real-Time Communication
- Real-time communication fundamentals
- HTTP polling
- Long polling
- Server-Sent Events (SSE)
- WebSockets
- WebSocket handshake and connection lifecycle
- Full-duplex communication
- Connection management
- Heartbeats and connection timeouts
- Reconnection strategies
- Message delivery and ordering
- Scaling WebSocket connections
- Pub/Sub integration for real-time systems
- WebSockets vs SSE vs polling

### 6. Idempotency and Request Reliability
- What is idempotency?
- Idempotent vs non-idempotent operations
- Idempotency keys
- Request deduplication
- Duplicate request handling
- Retry mechanisms
- Exponential backoff and jitter
- Timeout handling
- At-most-once and at-least-once request behavior
- Idempotency in payment and order APIs

### 7. Rate Limiting and Throttling
- Why rate limiting is needed
- Rate limiting vs throttling
- Fixed window counter
- Sliding window log
- Sliding window counter
- Token bucket algorithm
- Leaky bucket algorithm
- Distributed rate limiting
- Per-user, per-IP, and per-API limits
- Rate limiting with Redis
- Handling rate limit errors
- HTTP 429 and retry guidance

### 8. Data Serialization and Communication Formats
- What is serialization and deserialization?
- JSON
- XML
- Protocol Buffers
- Apache Avro
- MessagePack
- Binary vs text-based formats
- Schema evolution
- Backward and forward compatibility
- Serialization performance and payload size
- Choosing the right serialization format

---

## Topic Files

| # | Topic | File |
|---|---|---|
| 01 | API Design Fundamentals | `01-api-design-fundamentals.md` |
| 02 | REST APIs | `02-rest-apis.md` |
| 03 | gRPC | `03-grpc.md` |
| 04 | GraphQL | `04-graphql.md` |
| 05 | WebSockets and Real-Time Communication | `05-websockets-and-realtime-communication.md` |
| 06 | Idempotency and Request Reliability | `06-idempotency-and-request-reliability.md` |
| 07 | Rate Limiting and Throttling | `07-rate-limiting-and-throttling.md` |
| 08 | Data Serialization and Communication Formats | `08-data-serialization-and-communication-formats.md` |

---

## Folder Structure

\`\`\`text
04-apis-and-communication/
│
├── README.md
├── 01-api-design-fundamentals.md
├── 02-rest-apis.md
├── 03-grpc.md
├── 04-graphql.md
├── 05-websockets-and-realtime-communication.md
├── 06-idempotency-and-request-reliability.md
├── 07-rate-limiting-and-throttling.md
└── 08-data-serialization-and-communication-formats.md
\`\`\`
