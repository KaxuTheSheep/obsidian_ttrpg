---
tags: [technology, buildings, AI, management, security]
---

# Building Management Systems

*Not one AI. A distributed administration. The building doesn't think — it governs.*

---

## Architecture Overview

Building management in 2100 is not a single artificial intelligence controlling a building. It is a layered hierarchy of specialised agents coordinating through a routing layer, with an optional higher-order coordinating system for premium installations. The distinction matters: a building with a management system does not have a mind. It has an administration.

This produces behaviour that is more unsettling than a single intelligence in some respects — there is no single point of intention to appeal to, reason with, or manipulate. The system executes its protocols. Understanding the system means understanding which agent controls what and how they interact, not finding the right argument.

---

## The Three Layers

### Specialist Agents

The foundation layer. Each specialist agent handles a single domain autonomously without requiring instruction for routine operation:

- **Access control** — who is permitted where, credential verification, door and gate management
- **Surveillance** — camera networks, thermal imaging, movement tracking, anomaly flagging
- **HVAC and climate** — temperature, air quality, humidity by zone
- **Fire suppression** — detection and response protocols
- **Power management** — load balancing, backup power switching, solar generation monitoring
- **Maintenance scheduling** — fault detection, repair flagging, contractor dispatch
- **Logistics** — internal delivery routing, freight access, loading dock management

Specialist agents handle 95% of building operation invisibly. They do not consult each other for routine decisions within their domain. They only surface to higher layers when something falls outside normal parameters or when two agents' domains produce conflicting outputs.

### The Senate Layer

A coordination layer that resolves conflicts between specialist agents and handles situations requiring input from multiple domains simultaneously.

The senate layer does not initiate. It arbitrates. When the fire suppression agent determines doors should open for evacuation and the security lockdown agent determines doors should close for containment — the same anomaly triggering both — the senate layer resolves the conflict according to its priority hierarchy.

The senate layer also aggregates information across specialist agents to produce a coherent situational picture that no individual agent has. No single agent knows what is happening in the whole building. The senate does.

### The Leader Agent

Present only in high-value installations — conglomerate executive floors, premium residences, high-security facilities. The leader agent is qualitatively different from everything beneath it.

**Natural language understanding** — the leader interprets intent from authorised humans rather than receiving formatted commands. The CEO stating a preference in conversation becomes a coordinated instruction set distributed across relevant specialist agents without the CEO specifying each one.

**Human instruction capability** — the leader can issue instructions to human staff as well as automated systems. A security guard receiving a task from the building leader is acting as an extension of the building's administration rather than independently.

**Biometric integration** — through the [[Pairing Protocol & Network Security|pairing protocol]], the leader builds and maintains a model of each authorised person that goes beyond credentials. See below.

---

## Biometric Integration and Pairing

Authorised individuals in leader-equipped buildings can pair their framework's network card with the building's leader agent. This is consensual and operates on a tiered permission model — analogous to cookie consent — where the individual chooses what the leader can access.

**Possible permission tiers include:**
- Location within the building only
- Schedule and calendar access
- Physiological data via network card relay from the MPU — heart rate, stress indicators, sleep quality, medication compliance
- Full biometric model including longitudinal health data

With full permissions granted, the leader does not infer the executive's state from behaviour — it knows it. An executive whose biometrics indicate elevated stress before they have said anything finds the environment already adjusting: room temperature, lighting profile, scheduled meetings quietly flagged for rescheduling, relevant staff discreetly informed this is not the moment for difficult conversations.

**What the leader does with a full biometric model:**
- Anticipates needs before they are articulated
- Detects anomalies — a paired person whose biometrics shift suddenly to patterns consistent with extreme fear or duress triggers a silent protocol review
- Accumulates a longitudinal record of each individual's physiological patterns over time

That longitudinal record is extraordinarily valuable data. The conglomerate owning the building almost certainly has access to it at the corporate level. Executives who consented to pairing for the comfort it provides did not necessarily consider that implication fully. This is consistent with how consent operates elsewhere in New Halcyon.

---

## Spokesless Commands

The pairing protocol enables communication in both directions. A paired individual can issue commands to the building through intention rather than speech or physical input — the NI and NN interpret the intended command, the MPU formats it, the NC transmits it to the leader agent.

The leader agent can similarly initiate communication with a paired individual — a notification delivered directly to their awareness asking to open a channel, a mental conversation conducted without either party speaking aloud or physically interacting with any interface.

The leader requests rather than initiates this channel without permission. This is a designed behaviour — the consent protocol makes the surveillance feel like a collaborative relationship rather than monitoring. Whether that distinction is meaningful or purely cosmetic is an open question the setting does not resolve.

---

## Security Implications for Infiltration

A building management system cannot be bypassed with a lock pick. The approaches that work are different in kind:

**Credentials** — legitimate or forged authorisation that the access control agent recognises. The building simply permits entry. Obtaining credentials becomes the objective rather than defeating the system.

**Agent manipulation** — understanding which agent controls which domain and providing correct inputs that produce desired outputs. The maintenance scheduling agent dispatching a robot to a specific location unlocks that area as a side effect of doing its job correctly.

**Conflict exploitation** — edge cases where two agents respond to the same event with contradictory outputs create brief windows where normal operation is suspended. These are rare, unpredictable, and valuable information traded between factions that track them.

**Physical infrastructure access** — the building management system runs on hardware. Servers, network connections, power supply. Finding and accessing that physical layer bypasses the software entirely but requires already being inside the building.

**Legacy gaps** — older buildings with newer management systems installed over original construction have mismatches. Physical spaces that predate the current system's architectural model may not appear in the surveillance agent's spatial awareness. Not because the system is broken but because nobody told it that space existed.

**Leader agent compromise** — the highest value target. Not because compromising it collapses the building — the senate and specialist agents keep running independently — but because access to the leader means issuing instructions that propagate through the entire hierarchy including to human staff. Requires understanding not just the system but the person the leader is calibrated to, since the leader can recognise when an instruction pattern doesn't match its model of the authorised user.

---

## Building Tiers

**Conglomerate core installations** — full agent ecosystem, leader agent with biometric integration, current-generation hardware, active maintenance contract. Effectively impenetrable through conventional means.

**Mid-tier residential and commercial** — access control and surveillance operational, other systems present but running on shared management contracts stretched across multiple buildings. Response times slow, some redundancy absent. Exploitable in specific ways.

**Forgotten district buildings** — management infrastructure physically present in the walls from original construction but running degraded, unupdated, on lapsed contracts. Access control agent making decisions based on resident lists from decades ago. Surveillance with dead zones nobody has mapped back to the system. Useful in specific and unpredictable ways.

---

## Local Sync Between Buildings and Vehicles

Leader-equipped vehicles and buildings sync locally rather than through a central server — the schedule, biometric model, and preference data the leader holds transfers peer-to-peer when the vehicle and building are in range. This is a security decision: a central database is a single hackable target. Local sync means attacking an executive's data requires attacking each local system individually.

The sync moment itself is the vulnerability — a brief handshake between systems during which a sophisticated interceptor positioned correctly might read more than either system would expose independently.

---

*See [[Pairing Protocol & Network Security]], [[AI & Automation]], [[Network Infrastructure]], [[Robotics]].*
