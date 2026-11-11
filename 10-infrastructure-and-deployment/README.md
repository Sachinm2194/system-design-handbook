
# Phase 10: Infrastructure and Deployment

This phase covers the infrastructure, deployment practices, and platform technologies used to run modern distributed systems. It explores containers, orchestration, infrastructure automation, CI/CD pipelines, cloud platforms, and multi-region deployments.

The goal is to understand how applications are packaged, deployed, scaled, and operated reliably across infrastructure environments.

---

## Topics Covered

### 1. Infrastructure Fundamentals
- What is infrastructure in software systems?
- Compute, storage, and networking resources
- Bare-metal servers vs virtual machines
- Virtualization and hypervisors
- Public, private, and hybrid cloud
- Infrastructure as a Service (IaaS)
- Platform as a Service (PaaS)
- Software as a Service (SaaS)
- Cloud regions and availability zones
- Infrastructure scalability and elasticity
- Infrastructure provisioning and capacity planning

### 2. Containers and Docker
- What are containers?
- Containers vs virtual machines
- Container architecture
- Namespaces and cgroups
- Docker architecture
- Docker images and layers
- Docker containers and lifecycle
- Dockerfile fundamentals
- Image building and optimization
- Container networking
- Container volumes and persistent storage
- Container registries
- Multi-stage builds
- Container security fundamentals

### 3. Kubernetes Fundamentals
- What is Kubernetes?
- Kubernetes architecture
- Control plane and worker nodes
- API server, scheduler, and controller manager
- etcd in Kubernetes
- Pods and containers
- Deployments and ReplicaSets
- StatefulSets and DaemonSets
- Services and service discovery
- ConfigMaps and Secrets
- Namespaces
- Labels and selectors
- Persistent Volumes and Persistent Volume Claims
- Ingress and Gateway API fundamentals
- Kubernetes resource requests and limits

### 4. Kubernetes Advanced Concepts
- Pod scheduling and placement
- Node selectors and affinity
- Taints and tolerations
- Horizontal Pod Autoscaler (HPA)
- Vertical Pod Autoscaler (VPA)
- Cluster autoscaling
- Liveness, readiness, and startup probes
- Rolling updates and rollbacks
- Blue-green deployments
- Canary deployments
- Jobs and CronJobs
- Pod disruption budgets
- Network policies
- Helm charts
- Kubernetes operators
- Kubernetes failure handling and troubleshooting

### 5. Infrastructure as Code (IaC)
- What is Infrastructure as Code?
- Declarative vs imperative infrastructure
- Infrastructure provisioning
- Configuration management
- Terraform fundamentals
- Terraform providers and resources
- Terraform state management
- Modules and reusable infrastructure
- State locking and remote backends
- Infrastructure drift detection
- Ansible fundamentals
- Immutable infrastructure
- IaC testing and security
- Infrastructure automation best practices

### 6. CI/CD and Deployment Strategies
- Continuous Integration (CI)
- Continuous Delivery vs Continuous Deployment
- Build, test, and deployment pipelines
- Pipeline stages and artifacts
- Automated testing in CI/CD
- Build automation
- Artifact repositories
- Deployment automation
- Rolling deployments
- Blue-green deployments
- Canary releases
- Feature flags
- Rollbacks and release management
- Database migration strategies
- GitOps fundamentals
- Argo CD and Flux fundamentals

### 7. Cloud Infrastructure
- Cloud computing fundamentals
- Compute services and virtual machines
- Object, block, and file storage
- Virtual private clouds and networking
- Load balancing services
- Managed databases
- Managed messaging services
- Serverless computing
- Functions as a Service (FaaS)
- Auto Scaling
- Identity and Access Management (IAM)
- Cloud monitoring and logging
- AWS, Azure, and Google Cloud fundamentals
- Managed services vs self-hosted infrastructure
- Cloud cost optimization

### 8. Multi-Region and Global Deployment
- Single-region vs multi-region architecture
- Availability zones and regional failures
- Active-active architecture
- Active-passive architecture
- Global load balancing
- Geo-routing and traffic management
- Cross-region replication
- Data consistency across regions
- Regional failover and failback
- Disaster recovery planning
- Backup and restore strategies
- Recovery Time Objective (RTO)
- Recovery Point Objective (RPO)
- Data residency and regional compliance
- Multi-region deployment trade-offs

### 9. Service Mesh and Infrastructure Networking
- What is a service mesh?
- Control plane and data plane
- Sidecar proxy architecture
- Service-to-service communication
- Traffic routing and load balancing
- Service discovery
- Mutual TLS (mTLS)
- Retries, timeouts, and circuit breaking
- Traffic splitting and canary releases
- Observability in service meshes
- Istio and Linkerd fundamentals
- Service mesh vs API Gateway

---

## Topic Files

| # | Topic | File |
|---|---|---|
| 01 | Infrastructure Fundamentals | `01-infrastructure-fundamentals.md` |
| 02 | Containers and Docker | `02-containers-and-docker.md` |
| 03 | Kubernetes Fundamentals | `03-kubernetes-fundamentals.md` |
| 04 | Kubernetes Advanced Concepts | `04-kubernetes-advanced-concepts.md` |
| 05 | Infrastructure as Code | `05-infrastructure-as-code.md` |
| 06 | CI/CD and Deployment Strategies | `06-cicd-and-deployment-strategies.md` |
| 07 | Cloud Infrastructure | `07-cloud-infrastructure.md` |
| 08 | Multi-Region and Global Deployment | `08-multi-region-and-global-deployment.md` |
| 09 | Service Mesh and Infrastructure Networking | `09-service-mesh-and-infrastructure-networking.md` |

---

## Folder Structure

\`\`\`text
10-infrastructure-and-deployment/
│
├── README.md
├── 01-infrastructure-fundamentals.md
├── 02-containers-and-docker.md
├── 03-kubernetes-fundamentals.md
├── 04-kubernetes-advanced-concepts.md
├── 05-infrastructure-as-code.md
├── 06-cicd-and-deployment-strategies.md
├── 07-cloud-infrastructure.md
├── 08-multi-region-and-global-deployment.md
└── 09-service-mesh-and-infrastructure-networking.md
\`\`\`
