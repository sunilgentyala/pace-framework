# PACE Framework
### Proactive, AI-Driven, Cyber-Physical, Escalation-Aware Defense

> **Author:** Sunil Gentyala · sunil.gentyala@ieee.org · IEEE Member  
> **Status:** Research Preview — v2.0  
> **Citation Style:** Chicago Author-Date

---

## Overview

The **PACE Framework** is a doctrinal architecture for U.S. cyber defense at machine speed. It translates the intent of USCYBERCOM's *Persistent Engagement* concept into four operationally grounded pillars — each closing a distinct structural gap in current doctrine.

```
┌─────────────────────────────────────────────────────────────────┐
│                     THE PACE FRAMEWORK                          │
│                                                                 │
│  P ─ Proactive Threat Hunting & Healing  (ANH Protocol)        │
│  A ─ Adaptive AI Analytics               (SAAP Pipeline)       │
│  C ─ Cyber-Physical CIKR Convergence     (MDI / MRT-C)         │
│  E ─ Escalation-Aware Deterrence         (EADM Matrix)         │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## The Four Pillars

| Pillar | Name | Core Innovation | Gap Addressed |
|--------|------|----------------|---------------|
| **P** | Proactive Threat Hunting & Healing | Automated Network Healing (ANH) with tiered ROEs | Automation Gap |
| **A** | Adaptive AI Analytics | Secure AI Analytics Pipeline (SAAP) — air-gapped LLM | Intelligence Integration Gap |
| **C** | Cyber-Physical CIKR Convergence | CIKR-MRT-C Overlay + Mission Dependency Index (MDI) | Cyber-Physical Convergence Gap |
| **E** | Escalation-Aware Deterrence | Escalation-Aware Deterrence Matrix (EADM) | Escalation Management Gap |

---

## Repository Structure

```
pace-framework-repo/
├── README.md                    ← This file
├── LICENSE                      ← MIT License
├── CITATION.cff                 ← Citation metadata
├── docs/
│   ├── abstract.md              ← Article abstract
│   └── glossary.md              ← Key terms and acronyms
├── framework/
│   ├── pillar-P/
│   │   ├── README.md            ← Proactive Threat Hunting & Healing
│   │   └── ANH_ROE_tiers.md     ← Tiered ROE structure
│   ├── pillar-A/
│   │   ├── README.md            ← Adaptive AI Analytics
│   │   └── SAAP_architecture.md ← Secure AI Analytics Pipeline
│   ├── pillar-C/
│   │   ├── README.md            ← Cyber-Physical Convergence
│   │   └── MDI_methodology.md   ← Mission Dependency Index
│   └── pillar-E/
│       ├── README.md            ← Escalation-Aware Deterrence
│       └── EADM_matrix.md       ← Deterrence matrix categories
├── diagrams/
│   ├── PACE_workflow.svg        ← Full operational workflow diagram
│   └── PACE_architecture.html  ← Interactive architecture diagram
├── policy/
│   └── legal_framework.md      ← Legal authorities and constraints
└── tools/
    └── MDI_calculator.md       ← MDI scoring methodology
```

---

## Key Concepts

### Automated Network Healing (ANH) — Tiered ROE

| Tier | Actions | Authorization | Legal Basis |
|------|---------|--------------|-------------|
| **Tier 1** | Block malicious IP, quarantine endpoint, reroute traffic | **Autonomous** (no sign-off required) | Self-defense reflex; no effects outside defended network |
| **Tier 2** | Segment network, deploy honeypot, isolate OT system | **90-second human window** (defaults to conservative) | Pre-authorized playbook; reversible |
| **Tier 3** | Any effect outside defending network (ACD) | **Explicit human + legal authorization** | Title 10/50; existing offensive cyber authorities |

### Mission Dependency Index (MDI)

```
MDI = f(Node Resilience, Military Dependency, Adversary Intent)
```

Scores civilian CIKR nodes on operational significance to named military operations, bridging CISA's National Critical Functions framework with DoD campaign planning vocabulary.

### Escalation-Aware Deterrence Matrix (EADM)

| Category | Example Actions | Notification |
|----------|----------------|-------------|
| 🟢 Green | Patching, firewall updates | Unit logs only |
| 🟡 Amber | Honeypot deployment, traffic rerouting | NSC crisis repository |
| 🔴 Red | Effects on adversary infrastructure | Human auth + NSC notification |
| ⬛ Black | High-escalation; no pre-auth playbook | Full deliberative process |

---

## Operational Vignette

> A CNMF Cyber Protection Team (CPT) deployed to the Indo-Pacific detects PRC-affiliated pre-positioning in a logistics network adjacent to a high-MDI bulk power node. PACE enables the CPT to:
> 1. **P** — Autonomously quarantine the compromised node (Tier 1) and deploy an adaptive honeypot (Tier 2, 90-sec window)
> 2. **A** — SAAP correlates honeypot behavior with historical PRC tradecraft signatures, elevating attribution confidence
> 3. **C** — CIKR-MRT-C overlay flags power grid as high-MDI; pre-negotiated DSCA template activates CISA coordination
> 4. **E** — Honeypot deployment (amber) logged to NSC crisis repository; adversary escalation risk managed through EADM

---

## Contributing

This is a research framework in active development. Contributions, critiques, and extensions are welcome via Issues and Pull Requests.

**Areas of interest:**
- Legal analysis of ANH Tier 1/2 authorization under international law
- MDI scoring methodology refinement
- ICS/OT protocol coverage for Pillar C
- Wargaming and simulation of EADM deterrence logic

---

## Citation

```bibtex
@misc{gentyala2026pace,
  author = {Gentyala, Sunil},
  title  = {Persistent Engagement at Machine Speed: The {PACE} Framework
            for Proactive, {AI}-Driven Cyber-Physical Defense in Gray-Zone Conflict},
  year   = {2026},
  note   = {Preprint, v2.0},
  email  = {sunil.gentyala@ieee.org},
  url    = {https://github.com/sunilgentyala/pace-framework}
}
```

---

## License

MIT License — see [LICENSE](LICENSE) for details.

> **Disclaimer:** The views expressed in this work are those of the author and do not reflect the official policy or position of the Institute of Electrical and Electronics Engineers, the U.S. Government, or any subdivisions thereof.
