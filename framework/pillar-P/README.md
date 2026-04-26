# Pillar P — Proactive Threat Hunting and Healing

**Core Innovation:** Automated Network Healing (ANH) Protocol  
**Gap Addressed:** The Automation Gap — human-speed ROEs on machine-speed threats

## Overview

The P pillar reconceptualizes defensive cyber operations from static monitoring to
continuous, autonomous network healing. Rather than waiting for analyst-driven detection
and response cycles, ANH executes pre-authorized defensive actions within legally validated
bounds — enabling Cyber Protection Teams to contest adversaries at the speed of the attack.

## The Three-Tier ROE Structure

See [ANH_ROE_tiers.md](ANH_ROE_tiers.md) for full detail.

| Tier | Trigger | Response | Authorization |
|------|---------|----------|--------------|
| 1 | Known malicious IP / compromised endpoint / suspicious routing | Block / Quarantine / Reroute | **Autonomous** |
| 2 | Network segmentation needed / honeypot opportunity / OT isolation | Deploy / Segment / Isolate | **90-second human window** |
| 3 | Effect outside defending network required | Active cyber defense | **Explicit Title 10/50 auth** |

## Decoy Technology

Adaptive honeypot environments mimic the defended network's actual architecture,
calibrated to the adversary's observed reconnaissance behavior. When an adversary
transitions from reconnaissance to exploitation, the honeypot:

1. Absorbs the attack vector
2. Generates high-fidelity adversary tradecraft telemetry for Pillar II (SAAP)
3. Buys time for Tier 3 human authorization if warranted
4. Triggers EADM amber-category notification (Pillar IV)

## Legal Architecture

Three binding conditions on all ANH actions:
- **Proportionality** — action must be proportionate to the observed threat
- **Scope** — action must be confined to U.S. government or authorized partner networks
- **Reversibility** — action must be reversible unless threat severity exceeds defined threshold
