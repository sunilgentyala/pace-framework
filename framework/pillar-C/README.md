# Pillar C — Cyber-Physical Convergence for Critical Infrastructure

**Core Innovation:** CIKR-MRT-C Overlay + Mission Dependency Index (MDI)  
**Gap Addressed:** The Cyber-Physical Convergence Gap — no doctrine linking civilian ICS to military readiness

## Overview

The C pillar establishes a standardized mapping methodology that links the resilience
of civilian Critical Infrastructure and Key Resources (CIKR) — specifically industrial
control systems (ICS) — to military operational readiness metrics. It enables combatant
command planners to articulate the military significance of civilian infrastructure in
campaign planning documents, closing the planning gap that adversaries like Volt Typhoon
have already operationalized.

## Mission Dependency Index (MDI)

See [MDI_methodology.md](MDI_methodology.md) for full scoring methodology.

```
MDI Score = weighted_average(
    Node_Resilience_Score,      ← from CISA National Critical Functions framework
    Military_Dependency_Score,  ← operational chain analysis
    Adversary_Targeting_Score   ← all-source intelligence assessment
)

Score range: 0.0 (negligible) → 1.0 (mission-critical)
Threshold for pre-crisis DSCA planning: MDI ≥ 0.65
```

## CIKR-MRT-C Overlay

A planning layer overlaid on existing MRT-C products that:
1. Identifies CIKR nodes within the geographic area of operations
2. Assigns MDI scores to each node
3. Prioritizes nodes for pre-crisis coordination with CISA and sector risk management agencies
4. Integrates with DSCA pre-authorization templates

## DSCA Pre-Negotiation Template

Rather than negotiating military cyber assistance authority during a crisis, PACE
requires pre-crisis DSCA templates that define:
- Scope of authorized military cyber assistance
- Information sharing triggers and channels
- CISA/SRMA coordination contacts and protocols
- Legal limits and Posse Comitatus compliance measures
