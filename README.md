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
| [`01_Three_Layer_Framework.md`](docs/01_Three_Layer_Framework.md) | **Three-Layer Framework**: Architecture overview across Public, Business, and Core function boundaries. |
| [`02_Technical_Architecture.md`](docs/02_Technical_Architecture.md) | **Technical Architecture**: Data models, cryptographic attestation, and interaction lifecycles. |
| [`03_Certification_&_Defense.md`](docs/03_Certification_&_Defense.md) | **Certification & Defense**: Phase 1–3 criteria and economic anti-troll / Sybil-dampening mechanisms. |
| [`04_Roadmap.md`](docs/04_Roadmap.md) | **Implementation Roadmap**: Modular plug-in strategy from concept freeze to municipal sandboxes. |
| [`05_AI_Agent_Safety_Gateway.md`](docs/05_AI_Agent_Safety_Gateway.md) | **AI Agent Safety Gateway**: Autonomous execution controls, rate limiters, and social return invariants. |
| [`06_Compatibility_Matrix_&_Integration.md`](docs/06_Compatibility_Matrix_&_Integration.md) | **Compatibility Matrix**: Interoperability mapping (W3C DID, ROS 2, DePIN, ISO safety standards). |
| [`07_Stewardship_Model.md`](docs/07_Stewardship_Model.md) | **Stewardship Model**: Human-in-the-Loop oversight, multi-sig governance, and commons administration. |
| [`08_Yield_Protocol_&_Vibes_Telemetry.md`](docs/08_Yield_Protocol_&_Vibes_Telemetry.md) | **Yield Protocol & Vibes Telemetry**: Pedestrian precedence rules, service animal buffers, and stress indices. |
| [`09_Incident_Logging_&_Audit_Trail.md`](docs/09_Incident_Logging_&_Audit_Trail.md) | **Incident Logging & Audit Trail**: Near-miss classification, verifiable provenance, and data sanitization. |

---

## 3. Guiding Principles

1. **Plug-in Over Monopoly**: Avoid redundant infrastructure; provide lightweight software adapters linking robots directly to public commons.
2. **Accountability Over Surveillance**: Reject raw biometric or video capture. Quantize spatial friction to preserve privacy while maintaining mathematical proof of safe operation.
3. **Care Beyond Utility**: Physical AI units share shared environments with biological life; courteous yielding and baseline social returns are immutable protocol invariants.

---

## License

This project is licensed under the [Apache License 2.0](LICENSE).
