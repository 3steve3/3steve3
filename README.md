# Steven Naumov
### Systems Architect & Lead Backend Engineer

I engineer high-performance, backend systems with a focus on data integrity, geospatial telemetry, and mission-critical reliability. My work bridges the gap between high-level business logic and low-level systems performance.

---

## 🛰 Featured Project: HIRTP-Link
**Status:** Open Source / Proof-of-Concept
**Repository:** [github.com/3steve3/HIRTP-Link](https://github.com/3steve3/HIRTP-Link)

HIRTP-Link (High-Integrity Resumable Transfer Protocol) is an application-layer protocol designed for mission-critical data exchange in hostile or unreliable network environments (SatCom, IoT Edge).

### Technical Highlights:
* **Dual-Layer Integrity:** Implements CRC32C transport-layer checksums for packet validation and SHA256 application-layer identity for final end-to-end verification.
* **Stateless Resumption:** Engineered a recovery-oriented state machine that uses identity caching to resume interrupted multi-gigabyte transfers in milliseconds without redundant re-hashing.
* **Cross-Platform Engineering:** Developed a resource-efficient **Rust** client for edge devices and a high-velocity **C# (.NET 10)** base station compiled with **Native AOT** for sub-millisecond startup and minimal memory footprint.
* **Chaos-Ready:** Validated protocol resilience via integrated "Chaos Monkey" simulation to ensure zero data loss during intentional stream severing.

---

## 🛠 Currently Architecting: Bedrock (v15)

**Status:** Proprietary / Commercial OS for Field Services & Logistics  
**Stack:** .NET 10 • PostgreSQL 18 • TimescaleDB • Angular  

Bedrock is a high-integrity, composable commerce operating system designed to track "True Profit" by treating operational friction as first-class data. The architecture is a horizontally scalable modular monolith engineered for forensic data accuracy and auditability.

### Key Architectural Pillars

**Hybridized Vertical Slice Architecture (VSA):**  
A modular monolith design that groups related commands and queries into cohesive feature slices, preventing the complexity of premature microservices while maintaining strict logical boundaries.

**Segregated Transport Layer (CQRS-Lite):**  
- **Commands (Writes):** All state changes are enforced via gRPC for strict contract adherence, high-performance serialization, and transactional rigor.  
- **Queries (Reads):** Data retrieval is exposed via GraphQL, allowing clients to fetch complex, nested projections in a single round-trip without over-fetching.

**Forensic Audit Trail:**  
Leveraging TimescaleDB hypertables to create an immutable, append-only ledger of every system event. We don't just track current state; we track the delta of every business decision.

**Database-Level Multitenancy:**  
Deeply integrated PostgreSQL Row Level Security (RLS) ensures strict tenant isolation at the data layer, preventing application-level leakage.

---

## 🚀 Professional Expertise
* **Languages:** C# (.NET 10), Rust (learning), SQL (Postgres/Timescale), Python
* **Protocols & Integrity:** gRPC (HTTP/2), Protobuf, SHA256, CRC32C, Native AOT Compilation
* **Architectures:** Microservices, Event-Driven Architecture (Transactional Outbox), Vertical Slice, B2B2C Multi-tenancy
* **Infrastructure:** AWS (EC2, S3, RDS), ARM64 (Graviton) Optimization, Docker/Container Orchestration, Linux/Unix Systems

---

## 📬 Contact
[LinkedIn](https://www.linkedin.com/in/steve-naumov/) | [Email](mailto:stevennaumov@outlook.com)
