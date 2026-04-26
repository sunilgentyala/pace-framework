# ANH Protocol — Tiered ROE Detail

## Tier 1: Autonomous Defensive Reflexes

**Legal basis:** Analogous to self-defense. No effects outside the defended network.
These actions require no deliberation beyond the automated detection trigger.

**Authorized actions:**
- Block inbound/outbound traffic from known malicious IP addresses
- Quarantine compromised endpoints from the network segment
- Reroute traffic away from compromised network nodes
- Kill unauthorized processes on monitored endpoints
- Reset session tokens on compromised accounts

**Audit requirement:** All Tier 1 actions logged with timestamp, trigger signature,
affected asset, and action taken. Log retained for 365 days minimum.

---

## Tier 2: Human-Window Actions

**Legal basis:** Pre-authorized playbook; reversible; confined to defended network.
**Authorization window:** 90 seconds from machine-initiated alert.
**Default:** If no human action taken within 90 seconds, system executes the more
conservative option (e.g., partial isolation rather than full segmentation).

**Authorized actions:**
- Sever a network segment from the larger enterprise
- Deploy an adaptive honeypot environment mimicking defended architecture
- Isolate an OT system from its industrial control network
- Activate out-of-band communication pathways
- Enable enhanced logging on high-value targets

**Notification requirements:**
- Immediate alert to CPT commander
- EADM category assessment (see Pillar E)
- Log entry to unit operations center

---

## Tier 3: Human-Authorized Actions

**Legal basis:** Requires Title 10 and/or Title 50 authority; NSC notification required.
Actions that produce any effect outside the defending network fall into this tier.

**Process:**
1. CPT generates Tier 3 recommendation with supporting intelligence (SAAP output)
2. Legal review against applicable ROEs and Presidential Policy Directives
3. Commander authorization at appropriate level
4. NSC notification per PPD requirements
5. Action execution with full audit trail
6. EADM red-category post-action assessment

**Examples:**
- Active cyber defense measures affecting adversary infrastructure
- Hunt Forward operations generating observable adversary-side tradecraft
- Any action degrading adversary offensive capability
