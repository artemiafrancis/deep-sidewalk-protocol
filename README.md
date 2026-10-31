# DeEP Sidewalk Protocol (DSP)

**Public-Space Physical AI Alignment, Verifiable Telemetry, and Social Return Infrastructure.**

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Specifications](https://img.shields.io/badge/Specs-v0.2_Draft-orange.svg)](docs)
[![Schemas](https://img.shields.io/badge/JSON_Schema-Draft--07-green.svg)](schemas)

> **Status**: Draft specification — not an implemented protocol.

---

## Overview

The **DeEP Sidewalk Protocol (DSP)**—operating alongside the **Decentralized Electronic Passport (DeEP)** framework—defines an open, modular standard for Physical AI and autonomous mobility units (e.g., guide robots, delivery AMRs, assistive micro-mobility) operating within shared pedestrian spaces.

Rather than enforcing closed monopolies or surveillance-heavy tracking, DSP provides a **decentralized electronic vessel** that separates mechanical compliance, spatial friction telemetry, yield auditing, and automated social return.

> **Official Portal & Philosophy**: [https://www.lead-project.xyz/](https://www.lead-project.xyz/)
> *The high-level philosophy and project manifesto are published on the official portal. This repository hosts the technical RFCs, schemas, and implementation drafts.*

---

## Repository Structure

```text
deep-sidewalk-protocol/
├── docs/       # Technical RFCs and operational architecture specifications
└── schemas/    # Formal JSON Schema definitions (Draft-07)
```

## 1. Core Data Schemas (`schemas/`)

The protocol architecture is anchored by four primary data schemas supporting machine identity, environmental difficulty reporting, safe contribution proofs, and value settlement:

| Schema File | Name & Purpose |
| :--- | :--- |
| [`dsp-passport-credential.schema.json`](schemas/dsp-passport-credential.schema.json) | **DSP-Passport Credential**: W3C VC-based passport defining clearance phases, operator liability, insurance binding, and active care slots. |
| [`dsp-difficulty-patch.schema.json`](schemas/dsp-difficulty-patch.schema.json) | **DSP-Difficulty Patch**: Privacy-preserving, non-personal traversal friction and biological coexistence stress mapped to spatial indexing grids (e.g., H3). |
| [`dsp-contribution-receipt.schema.json`](schemas/dsp-contribution-receipt.schema.json) | **DSP-Contribution Receipt**: Cryptographic proof of safe transit, adherence to pedestrian precedence (Yield Protocol), and difficulty-adjusted utility. |
| [`dsp-value-transaction.schema.json`](schemas/dsp-value-transaction.schema.json) | **DSP-Value Transaction**: Settlement ledger enforcing automated allocation splits and programmatic routing to public welfare (e.g., Dog Pension). |

---

## 2. Technical Documentation (`docs/`)

| Document | Focus Area |
| :--- | :--- |
| [`01_three_layer_framework.md`](docs/01_three_layer_framework.md) | **Three-Layer Framework**: Architecture overview across Public, Business, and Core function boundaries. |
| [`02_technical_architecture.md`](docs/02_technical_architecture.md) | **Technical Architecture**: Data models, cryptographic attestation, and interaction lifecycles. |
| [`03_certification_&_defense.md`](docs/03_certification_&_defense.md) | **Certification & Defense**: Phase 1–3 criteria and economic anti-troll / Sybil-dampening mechanisms. |
| [`04_roadmap.md`](docs/04_roadmap.md) | **Implementation Roadmap**: Modular plug-in strategy from concept freeze to municipal sandboxes. |
| [`05_ai_agent_safety_gateway.md`](docs/05_ai_agent_safety_gateway.md) | **AI Agent Safety Gateway**: Autonomous execution controls, rate limiters, and social return invariants. |
| [`06_compatibility_matrix_&_integration.md`](docs/06_compatibility_matrix_&_integration.md) | **Compatibility Matrix**: Interoperability mapping (W3C DID, ROS 2, DePIN, ISO safety standards). |
| [`07_stewardship_model.md`](docs/07_stewardship_model.md) | **Stewardship Model**: Human-in-the-Loop oversight, multi-sig governance, and commons administration. |
| [`08_yield_protocol_&_vibes_telemetry.md`](docs/08_yield_protocol_&_vibes_telemetry.md) | **Yield Protocol & Vibes Telemetry**: Pedestrian precedence rules, service animal buffers, and stress indices. |
| [`09_incident_logging_&_audit_trail.md`](docs/09_incident_logging_&_audit_trail.md) | **Incident Logging & Audit Trail**: Near-miss classification, verifiable provenance, and data sanitization. |

---

## 3. Guiding Principles

1. **Plug-in Over Monopoly**: Avoid redundant infrastructure; provide lightweight software adapters linking robots directly to public commons.
2. **Accountability Over Surveillance**: Reject raw biometric or video capture. Quantize spatial friction to preserve privacy while maintaining mathematical proof of safe operation.
3. **Care Beyond Utility**: Physical AI units share shared environments with biological life; courteous yielding and baseline social returns are immutable protocol invariants.

---

## License

This project is licensed under the [Apache License 2.0](LICENSE).
