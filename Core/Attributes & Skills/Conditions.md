---
aliases:
  - Condition
tags:
  - Mechanics/Combat
---
Conditions represent temporary states aside from Exhaustion that impair a character's senses, [[Movement Types|movement]], awareness, or ability to act.

### Blinded
You cannot see.
- Automatically fail any **Tests** requiring sight.
- **[[Attacks|Attack]]** Tests you make are at **Disadvantage**.
- **[[Attacks|Attack]]** Tests made against you are at **Disadvantage**.
- **[[Skills|Perception]]** Tests involving sight are at **Disadvantage**.

### Breathless
Your breath is restricted.
- **[[Attributes|Might]]** and **[[Attributes|Vitality]]** **Tests** are at **Disadvantage**.

### Bound
Your [[weapon]] arm is locked by an opponent's [[weapon]]. See [[Weapon Traits#Weapon Bind|Weapon Bind]] for how Bound is applied.
- You cannot use your bound [[weapon]] in any way — no [[attacks]], [[Parry]], or [[Block]] with it.
- Your [[Movement Types|movement]] is unaffected.
- You may attempt to escape as a **Full [[Actions|Action]]**: opposed [[Attributes|Might]] or [[Attributes|Grace]] vs the initiator's [[Attributes|Might]] or [[Attributes|Grace]]. On success, Bound ends.
- Bound ends if the initiator drops the Bind voluntarily or is incapacitated.

### Deafened
You cannot hear.
- Automatically fail any **Tests** requiring hearing.

### Dazed
Your focus is unstable.
- The **first Test** you make each [[Rounds|round]] is at **Disadvantage**.

### Disoriented
Your coordination breaks for a moment.
- You **lose your Half [[Actions|Action]]** on your next [[Rounds|round]].

### Exhaustion (1–10)
Exhaustion represents the gradual wearing down of the body and mind through strain, [[Injuries|injury]], stress, and [[Skills|survival]] pressure. It is measured in **levels from 0 to 10**.  
At **10**, the character **dies**.

Exhaustion does **not** reduce [[Damage Types|damage]], [[Blood]], or [[Attributes]].  
Instead, it affects **[[Ticks, Priority & Resolution|Priority]]** and **[[Actions|Action]] availability**.

#### Effects by Level

| Exhaustion Level | Effect                                                                                                                                  |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| **1–2**          | No mechanical penalty. Fatigue is felt but does not impair [[Skills\|performance]].                                                     |
| **3–4**          | **–1 to all [[Actions\|Action]] [[Ticks, Priority & Resolution\|Priority]] values.**                                                    |
| **5–6**          | **–2 to all [[Actions\|Action]] [[Ticks, Priority & Resolution\|Priority]] values.**                                                    |
| **7–8**          | **Lose 1 Full [[Actions\|Action]]** each [[Rounds\|round]].                                                                             |
| **9**            | **Lose 1 Full [[Actions\|Action]]** each [[Rounds\|round]], and your **[[Ticks, Priority & Resolution\|Priority]] penalty becomes –3.** |
| **10**           | **[[Death]].** The body or mind cannot continue.                                                                                        |

### Frightened
An overwhelming sense of fear or dread toward a specific source.
- Disadvantage on [[Attacks|Attack]] Tests against the source of your fear.
- Disadvantage on all Tests made while within sight of the source.
- On gaining Frightened, immediately lose [[Sanity]] based on the source:

| Source | [[Sanity]] Loss |
|---|---|
| Mundane (pain, [[Skills\|intimidation]]) | 5 [[Sanity]] |
| Supernatural (monsters, forbidden entities, overwhelming [[Attributes\|presence]]) | 10 [[Sanity]] |

[[Sanity]] loss from Frightened feeds into your existing [[Sanity]] thresholds. Repeated or sustained exposure to fear pushes characters toward [[Afflictions]] naturally.

#### Ending Frightened
Frightened ends when:
- The duration expires.
- The source is no longer visible.
- You make a [[Attributes|Resolve]] Test at the start of your turn (DN set by the source). On success, Frightened ends immediately.

### Grappled
Your body is physically restrained by another creature. See [[Core/Combat/Action System/Grapple]] for full rules on how Grappled is applied and maintained.
- Your **[[Movement Types|movement]] distance becomes 0**.
- You can still take [[Actions]].
- You may attempt to escape as a **Full [[Actions|Action]]**: opposed [[Attributes|Might]] or [[Attributes|Grace]] vs the initiator's [[Attributes|Might]] or [[Attributes|Grace]]. On success, Grappled ends and the initiator's Grappling state ends.

### Immobilised
You cannot move from your space.
- You may still take [[Actions]] normally.

### Prone
You are low to the ground.
- Melee **[[Attacks|Attack]]** Tests against you are at **Advantage**.
- Ranged **[[Attacks|Attack]]** Tests against you are at **Disadvantage**.
- Standing requires **half** your **Walking Distance**.

### Paralysed
You are completely immobilised.  
You suffer all effects of **Stunned**, and additionally:
- You **cannot move** or speak.
- Any **melee [[Attacks|attack]]** that hits you is treated as a **Critical Success**.
- Your **[[Evasion]] is 0**, and cannot be raised.

### Slowed
Your [[Movement Types|movement]] is impaired.
- Your **[[Movement Types|movement]] distances** from [[Movement Types]] are **halved**.
- [[Movement Types|Movement]]-based **[[Ticks, Priority & Resolution|Priority]]** values suffer **–1**.

### Stunned
Your mind or body is overwhelmed.
- You **cannot take [[Actions]] or [[Reactions]]**.
- You may still move up to **half** your **Walking Distance**, but cannot use that [[Movement Types|movement]] to [[Attacks|Attack]] or Defend.
- **[[Attacks|Attack]]** Tests against you are at **Disadvantage**.
- Your **[[Sturdiness]]** is ignored; your effective **[[Evasion]] becomes Base [[Evasion]]**.

### Unconscious
- You are treated as **Paralysed**.
- You **drop Prone** automatically.
- **[[Attacks|Attack]]** Tests against you have **Advantage**; melee hits are **Critical Success**.

### Vulnerable
Your defences are compromised.
- You **take double [[Damage Types|damage]]** from all sources.
- **[[Sturdiness]]** is reduced by **3** while Vulnerable is active.
