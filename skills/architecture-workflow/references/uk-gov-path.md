# UK Government Project Path

## When This Path Applies

- UK Government civilian departments (non-MOD)
- Projects subject to GDS Service Standard
- Projects subject to Technology Code of Practice (TCoP)
- NCSC Cyber Assessment Framework applies
- G-Cloud or Digital Outcomes procurement likely

## Compliance Frameworks

- GDS Service Standard (14 points)
- Technology Code of Practice (TCoP)
- NCSC Cyber Assessment Framework (CAF)
- Secure by Design (civilian)
- Green Book / Orange Book (HM Treasury)

## Phased Command Sequence

### Phase 1: Foundation (Mandatory)

| # | Command | Rationale | Artifacts |
|---|---------|-----------|-----------|
| 1 | `/skill:arckit-principles` | Governance foundation — must align with GDS and TCoP | ARC-000-PRIN-v1.0.md |
| 2 | `/skill:arckit-stakeholders` | Map DDaT roles, SROs, policy owners | ARC-{PID}-STKE-v1.0.md |
| 3 | `/skill:arckit-risk` | HMG Orange Book risk methodology | ARC-{PID}-RISK-v1.0.md |

### Phase 2: Business Justification

| # | Command | Rationale | Artifacts |
|---|---------|-----------|-----------|
| 4 | `/skill:arckit-sobc` | HM Treasury Green Book SOBC with 5-case model | ARC-{PID}-SOBC-v1.0.md |
| 5 | `/skill:arckit-requirements` | Requirements aligned to GDS service standard | ARC-{PID}-REQ-v1.0.md |

### Phase 3: Design and Analysis

| # | Command | Rationale | Artifacts |
|---|---------|-----------|-----------|
| 6 | `/skill:arckit-datascout` | Discover UK Gov open data sources (TCoP Point 10) | ARC-{PID}-DSCT-v1.0.md |
| 7 | `/skill:arckit-data-model` | Data architecture with GDPR/DPA considerations | ARC-{PID}-DMOD-v1.0.md |
| 8 | `/skill:arckit-dpia` | Data Protection Impact Assessment (mandatory for personal data) | ARC-{PID}-DPIA-v1.0.md |
| 9 | `/skill:arckit-research` | Technology research with Crown Commercial focus | ARC-{PID}-RES-v1.0.md |
| 10 | `/skill:arckit-wardley` | Strategic positioning for GaaP components | ARC-{PID}-WARD-001-v1.0.md |
| 11 | `/skill:arckit-roadmap` | Roadmap aligned to spending review cycles | ARC-{PID}-ROAD-v1.0.md |
| 12 | `/skill:arckit-diagram` | Architecture diagrams (C4, sequence, DFD) | ARC-{PID}-DIAG-001-v1.0.md |

### Phase 4: Procurement (G-Cloud / DOS)

| # | Command | Rationale | Artifacts |
|---|---------|-----------|-----------|
| 13 | `/skill:arckit-gcloud-search` | Search Digital Marketplace for G-Cloud services | Console output |
| 14 | `/skill:arckit-gcloud-clarify` | Generate clarification questions for shortlisted services | ARC-{PID}-GCLR-v1.0.md |
| 15 | `/skill:arckit-sow` | Statement of work for procurement | ARC-{PID}-SOW-v1.0.md |
| 16 | `/skill:arckit-evaluate` | Vendor evaluation with value-for-money assessment | ARC-{PID}-EVAL-v1.0.md |

### Phase 5: Design Reviews

| # | Command | Rationale | Artifacts |
|---|---------|-----------|-----------|
| 17 | `/skill:arckit-hld-review` | HLD review against GDS patterns | ARC-{PID}-HLDR-v1.0.md |
| 18 | `/skill:arckit-dld-review` | DLD review for security and performance | ARC-{PID}-DLDR-v1.0.md |
| 19 | `/skill:arckit-adr` | Architecture Decision Records | ARC-{PID}-ADR-001-v1.0.md |

### Phase 6: Implementation

| # | Command | Rationale | Artifacts |
|---|---------|-----------|-----------|
| 20 | `/skill:arckit-backlog` | Product backlog from requirements and design | ARC-{PID}-BKLG-v1.0.md |

### Phase 7: Operations and Quality

| # | Command | Rationale | Artifacts |
|---|---------|-----------|-----------|
| 21 | `/skill:arckit-devops` | CI/CD aligned to GDS technology standards | ARC-{PID}-DVOP-v1.0.md |
| 22 | `/skill:arckit-operationalize` | Operational readiness, service desk integration | ARC-{PID}-OPS-v1.0.md |
| 23 | `/skill:arckit-traceability` | End-to-end traceability matrix | ARC-{PID}-TRACE-v1.0.md |

### Phase 8: Compliance (UK Government Specific)

| # | Command | Rationale | Artifacts |
|---|---------|-----------|-----------|
| 24 | `/skill:arckit-tcop` | Technology Code of Practice assessment | ARC-{PID}-TCOP-v1.0.md |
| 25 | `/skill:arckit-secure` | Secure by Design assessment (NCSC CAF) | ARC-{PID}-SEC-v1.0.md |
| 26 | `/skill:arckit-principles-compliance` | Principles adherence | ARC-{PID}-PCOMP-v1.0.md |
| 27 | `/skill:arckit-conformance` | ADR conformance checking | ARC-{PID}-CONF-v1.0.md |
| 28 | `/skill:arckit-analyze` | Deep governance analysis | ARC-{PID}-ANAL-v1.0.md |
| 29 | `/skill:arckit-service-assessment` | GDS Service Assessment readiness | ARC-{PID}-SA-v1.0.md |

### Phase 9: Reporting

| # | Command | Rationale | Artifacts |
|---|---------|-----------|-----------|
| 30 | `/skill:arckit-story` | Project narrative for governance boards | ARC-{PID}-STORY-v1.0.md |
| 31 | `/skill:arckit-pages` | GitHub Pages documentation site | docs/index.html |

## Optional Commands

These can be added at the appropriate phase if needed:

| Command | When to Add | Phase |
|---------|-------------|-------|
| `/skill:arckit-strategy` | Executive strategy synthesis needed | After Phase 3 |
| `/skill:arckit-platform-design` | Government as a Platform (GaaP) service | Phase 3 |
| `/skill:arckit-data-mesh-contract` | Federated data products | Phase 3, after data-model |
| `/skill:arckit-dos` | Digital Outcomes and Specialists procurement | Phase 4 (alternative to G-Cloud) |
| `/skill:arckit-finops` | Cloud cost management | Phase 7 |
| `/skill:arckit-servicenow` | ServiceNow CMDB integration | Phase 7 |
| `/skill:arckit-presentation` | Governance board slide deck | Phase 9 |

## Minimum Viable Path

For Alpha assessment preparation:

1. `/skill:arckit-principles`
2. `/skill:arckit-stakeholders`
3. `/skill:arckit-requirements`
4. `/skill:arckit-research`
5. `/skill:arckit-tcop`
6. `/skill:arckit-secure`

## Duration

- **Full path**: 6-12 months
- **Minimum viable**: 2-4 weeks
