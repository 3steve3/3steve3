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

## 🛠 Currently Architecting: V15 Composable Commerce OS
**Status:** Proprietary / Closed Source (Commercial Potential)
**Architectural Specification:** [View the Public Architecture & Schema Docs](https://github.com/3steve3/v15_architecture_spec/tree/main)

V15 is a headless, multi-tenant, composable operating system designed for high-integrity verticals like field services, automotive, and warehouse management. The architecture is engineered for sub-millisecond transactional latency and zero-copy data ingestion pipelines.

### Key Architectural Pillars:
* **Database-Level Security:** Enforcing multi-tenancy and data segregation via PostgreSQL Row Level Security (RLS).
* **Immutable Auditing:** Leveraging TimescaleDB hypertables for an append-only, tamper-proof audit trail of every state change.
* **Data-Oriented Performance:** Utilizing .NET 10/C# 14 structs and devirtualized logic to maximize CPU cache locality and minimize GC pressure.
* **Hybrid API Gateway:** Combining the strict performance of internal gRPC services with a flexible, public-facing GraphQL API for client applications.

---

## 🚀 Professional Expertise
* **Languages:** C# (.NET 10), Rust (learning), SQL (Postgres/Timescale), Python
* **Protocols & Integrity:** gRPC (HTTP/2), Protobuf, SHA256, CRC32C, Native AOT Compilation
* **Architectures:** Microservices, Event-Driven Architecture (Transactional Outbox), Vertical Slice, B2B2C Multi-tenancy
* **Infrastructure:** AWS (EC2, S3, RDS), ARM64 (Graviton) Optimization, Docker/Container Orchestration, Linux/Unix Systems

---

## 📬 Contact
[LinkedIn](https://www.linkedin.com/in/steve-naumov/) | [Email](mailto:stevennaumov@outlook.com)
