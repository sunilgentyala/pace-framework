# Escalation-Aware Deterrence Matrix (EADM)

## Category Definitions and Protocols

### 🟢 GREEN — Routine Defensive Operations

**Definition:** Standard defensive maintenance with no meaningful adversary-signaling value.
Actions in this category produce no observable indicators that adversary intelligence
collection would distinguish from routine network operations.

**Examples:**
- Endpoint patching and software updates
- Firewall rule updates (non-emergency)
- Anomaly detection threshold calibration
- Log review and archiving
- Routine vulnerability scanning (scheduled)

**Notification:** Unit operations log only. No escalation required.

---

### 🟡 AMBER — Observable Defensive Actions

**Definition:** Defensive measures that an adversary with active intelligence collection
on the defended network might observe and potentially interpret as preparation for
escalatory action.

**Examples:**
- Adaptive honeypot deployment (Pillar I, Tier 2)
- Network traffic rerouting
- Network segmentation
- OT system isolation from control network
- Enhanced monitoring activation on high-value targets

**Notification protocol:**
1. Automated log entry to NSC crisis communications repository (timestamp, action, trigger, authority)
2. Notification to theater J2 and J3
3. CPT commander acknowledgment
4. If action taken during elevated tension period: additional NSC-level notification

**Rationale:** Pre-creating a documented record of amber actions enables rapid, accurate
response if adversary raises the action through diplomatic channels — reducing the
probability that an adversary misinterpretation escalates before the U.S. can clarify.

---

### 🔴 RED — Engagement Actions

**Definition:** Defensive actions that, while protective in intent, produce observable
effects on adversary-controlled infrastructure or capabilities.

**Examples:**
- Active cyber defense (ACD) measures affecting adversary command-and-control
- Disruption of adversary pre-positioned access
- Hunt Forward operations generating observable adversary-side tradecraft
- Actions degrading adversary reconnaissance or staging capability

**Authorization requirements:**
1. CPT commander recommendation with SAAP intelligence assessment
2. Legal review (Title 10/50 authorities, applicable PPDs)
3. Authorization at appropriate command level
4. NSC-level notification prior to execution
5. Post-action assessment and EADM review

---

### ⬛ BLACK — Extreme Actions

**Definition:** Actions with high escalation potential for which no pre-authorized
playbook exists and which may approach or cross the threshold of armed attack.

**Process:** Full deliberative process — outside ANH protocol entirely.
Treated as offensive cyber operations subject to all applicable legal and policy constraints.

---

## Deterrence Communication Channels

| Channel | Use Case | Authority Level |
|---------|---------|----------------|
| Public doctrine statements | Establish general deterrence parameters | OSD/USCYBERCOM public affairs |
| Back-channel diplomatic signaling | De-escalate specific incidents | NSC/State Department |
| Third-country intermediaries | Communication with non-dialog adversaries | NSC/State |
| Crisis hotlines | Prevent real-time miscalculation during incidents | POTUS-level |
| UN Security Council | Formal attribution and condemnation | State Department |
