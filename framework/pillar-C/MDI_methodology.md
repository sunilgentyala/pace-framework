# Mission Dependency Index (MDI) — Scoring Methodology

## Purpose

The MDI translates the operational significance of civilian infrastructure nodes into
a quantifiable metric that can be embedded in military campaign planning documents,
intelligence products, and pre-crisis coordination materials.

## Input Variables

### 1. Node Resilience Score (NRS)
**Source:** CISA National Critical Functions (NCF) framework assessment
**Range:** 0.0 (no resilience measures) → 1.0 (fully hardened with redundancy)
**Inversion:** Lower resilience = Higher vulnerability contribution to MDI

### 2. Military Dependency Score (MDS)
**Source:** Theater logistics and operational chain analysis
**Factors:**
- Does denial/degradation of this node interrupt a named military operation?
- What is the timeline to operational impact (hours/days/weeks)?
- Are alternative pathways available? At what cost?
**Range:** 0.0 (no dependency) → 1.0 (sole-source, time-critical dependency)

### 3. Adversary Targeting Score (ATS)
**Source:** All-source intelligence assessment
**Factors:**
- Adversary assessed capability to target this specific node type
- Historical adversary behavior (pre-positioning, reconnaissance)
- Node's prominence in adversary targeting doctrine/planning
**Range:** 0.0 (no assessed interest) → 1.0 (active pre-positioning detected)

## Composite MDI Formula

```
MDI = (0.30 × NRS_inverted) + (0.45 × MDS) + (0.25 × ATS)
```

Weights reflect the primacy of military dependency in the operational context.
Weights should be reviewed annually and may be adjusted by theater combatant command
based on specific operational environment assessments.

## MDI Thresholds and Actions

| MDI Score | Category | Required Action |
|-----------|----------|----------------|
| 0.80 – 1.00 | Critical | Pre-crisis DSCA template + CISA MOU + quarterly CPT coordination |
| 0.65 – 0.79 | High | Pre-crisis DSCA template + annual coordination |
| 0.45 – 0.64 | Medium | Information sharing agreement + bi-annual review |
| 0.00 – 0.44 | Low | Monitoring only; no pre-crisis coordination required |
