# Standard Project Path

## When This Path Applies

- Private sector projects
- Non-UK government public sector
- No AI/ML components
- No specific compliance framework requirements

## Phased Command Sequence

### Phase 1: Foundation (Mandatory)

| # | Command | Rationale | Artifacts |
|---|---------|-----------|-----------|
| 1 | `/skill:arckit-principles` | Governance foundation — 21 downstream commands depend on this | ARC-000-PRIN-v1.0.md |
| 2 | `/skill:arckit-stakeholders` | Identify who cares and what they need — drives everything downstream | ARC-{PID}-STKE-v1.0.md |
| 3 | `/skill:arckit-risk` | Identify what could go wrong before committing resources | ARC-{PID}-RISK-v1.0.md |

### Phase 2: Business Justification

| # | Command | Rationale | Artifacts |
|---|---------|-----------|-----------|
| 4 | `/skill:arckit-sobc` | Justify the investment before detailed technical work | ARC-{PID}-SOBC-v1.0.md |
| 5 | `/skill:arckit-requirements` | Central artifact — 38 commands depend on this | ARC-{PID}-REQ-v1.0.md |

### Phase 3: Design and Analysis

| # | Command | Rationale | Artifacts |
|---|---------|-----------|-----------|
| 6 | `/skill:arckit-data-model` | Define data structures from DR-xxx requirements | ARC-{PID}-DMOD-v1.0.md |
| 7 | `/skill:arckit-research` | Technology options, build vs buy, vendor landscape | ARC-{PID}-RES-v1.0.md |
| 8 | `/skill:arckit-wardley` | Strategic positioning and evolution analysis | ARC-{PID}-WARD-001-v1.0.md |
| 9 | `/skill:arckit-roadmap` | Multi-year timeline from strategy analysis | ARC-{PID}-ROAD-v1.0.md |
| 10 | `/skill:arckit-diagram` | Architecture diagrams (C4, DFD, sequence) | ARC-{PID}-DIAG-001-v1.0.md |

### Phase 4: Procurement (If Applicable)

| # | Command | Rationale | Artifacts |
|---|---------|-----------|-----------|
| 11 | `/skill:arckit-sow` | Statement of work / RFP for vendors | ARC-{PID}-SOW-v1.0.md |
| 12 | `/skill:arckit-evaluate` | Vendor evaluation framework and scoring | ARC-{PID}-EVAL-v1.0.md |

### Phase 5: Design Reviews

| # | Command | Rationale | Artifacts |
|---|---------|-----------|-----------|
| 13 | `/skill:arckit-hld-review` | Validate high-level design against requirements | ARC-{PID}-HLDR-v1.0.md |
| 14 | `/skill:arckit-dld-review` | Validate detailed design | ARC-{PID}-DLDR-v1.0.md |
| 15 | `/skill:arckit-adr` | Record key architecture decisions | ARC-{PID}-ADR-001-v1.0.md |

### Phase 6: Implementation

| # | Command | Rationale | Artifacts |
|---|---------|-----------|-----------|
| 16 | `/skill:arckit-backlog` | Product backlog from requirements and design | ARC-{PID}-BKLG-v1.0.md |
| 17 | `/skill:arckit-trello` | Export backlog to Trello (optional) | Trello board |

### Phase 7: Operations and Quality

| # | Command | Rationale | Artifacts |
|---|---------|-----------|-----------|
| 18 | `/skill:arckit-devops` | CI/CD, IaC, container orchestration strategy | ARC-{PID}-DVOP-v1.0.md |
| 19 | `/skill:arckit-operationalize` | Operational readiness, SRE, runbooks | ARC-{PID}-OPS-v1.0.md |
| 20 | `/skill:arckit-traceability` | End-to-end traceability matrix | ARC-{PID}-TRACE-v1.0.md |
| 21 | `/skill:arckit-principles-compliance` | Principles adherence assessment | ARC-{PID}-PCOMP-v1.0.md |
| 22 | `/skill:arckit-conformance` | ADR conformance checking | ARC-{PID}-CONF-v1.0.md |
| 23 | `/skill:arckit-analyze` | Deep governance analysis | ARC-{PID}-ANAL-v1.0.md |

### Phase 8: Reporting

| # | Command | Rationale | Artifacts |
|---|---------|-----------|-----------|
| 24 | `/skill:arckit-story` | Comprehensive project narrative | ARC-{PID}-STORY-v1.0.md |
| 25 | `/skill:arckit-pages` | GitHub Pages documentation site | docs/index.html |

## Optional Commands

These can be added at the appropriate phase if needed:

| Command | When to Add | Phase |
|---------|-------------|-------|
| `/skill:arckit-strategy` | Executive strategy synthesis needed | After Phase 3 |
| `/skill:arckit-platform-design` | Multi-sided platform or marketplace | Phase 3 |
| `/skill:arckit-datascout` | External data sources needed | Phase 3, before data-model |
| `/skill:arckit-dpia` | Personal data is processed | Phase 3, after data-model |
| `/skill:arckit-finops` | Cloud cost management needed | Phase 7 |
| `/skill:arckit-servicenow` | ServiceNow CMDB integration | Phase 7 |
| `/skill:arckit-presentation` | Governance board slide deck | Phase 8 |

## Minimum Viable Path

For quick prototype documentation or proof of concept:

1. `/skill:arckit-principles`
2. `/skill:arckit-stakeholders`
3. `/skill:arckit-requirements`
4. `/skill:arckit-research`
5. `/skill:arckit-diagram`

## Duration

- **Full path**: 4-8 months
- **Minimum viable**: 1-2 weeks
