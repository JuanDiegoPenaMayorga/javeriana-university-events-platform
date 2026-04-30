# 🎓 Javeriana Academic Events Platform

![Status](https://img.shields.io/badge/Status-Work_In_Progress-orange.svg)
![Architecture Focus](https://img.shields.io/badge/Architecture-Observability_%26_Audit-blue)
![Delivery](https://img.shields.io/badge/Phase-System_Requirements-success)

An enterprise-grade, scalable event management system specifically engineered for Universidad Javeriana. This platform centralizes event creation, tackles massive concurrency workflows, and provides strict data traceability for institutional decision-making.

---

## 🎯 Architecture Driver: Observability & Compliance
While resolving highly concurrent workflows (e.g., ticket scalping/bottlenecks during high-demand events), this system architecture revolves around deep system transparency:

* 🔎 **End-to-End Traceability (Observability):** Comprehensive tracing spanning frontend clicks to backend queues, allowing IT teams to detect latency issues or failed integrations (e.g., delayed payments) proactively.
* ⚖️ **Immutable Audit Trails:** Deep operational security aligned with local regulations (Ley 1581 - Colombian Data Protection). Tracks precisely "who created an event, when they updated the budget, and who approved the venue".
* 📊 **Real-time Institutional Reporting:** Advanced multitenancy event streaming decoupled from the transactional DB to build live monitoring dashboards for Faculty Heads and Event Coordinators.

## 🏗️ Repository Structure (In Progress)

Documentation and logical modeling will be located in our specific folders as we fulfill our iterative software architecture cycles.

```text
/
├── docs/                       
│   ├── adrs/                   # Architecture Decision Records (e.g., 001-centralized-logging.md)
│   ├── architecture/           # C4 Models (Context, Container, Component Views)
│   └── deliverable_SRS/        # Requirements Document (IEEE 29148 Standard)
├── src/                        # Functional Microservices & Platform Modules
└── tests/                      # Workload Simulations (JMeter) & Telemetry testing
