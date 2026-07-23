---
tags:
  - Mechanics/Combat
---
Blood represents your character's core health and [[Attributes|vitality]] — the life force that keeps them conscious and functioning. It is the pool that determines how much [[Injuries|injury]] your character can sustain before [[Falling|falling]] unconscious or dying.

Unlike [[Sturdiness]], Blood is difficult to restore mid-combat and between encounters. It represents lasting physical harm rather than guard or composure.

## Calculation
**Blood = Base Blood + [[Attributes|Vitality]] + Other Modifiers**
- **Base Blood:** A starting value determined by your species or origin as defined in the relevant module.
- **[[Attributes|Vitality]]:** Your [[Attributes|Vitality]] [[Attributes|Attribute]] added directly, representing physical robustness and [[Skills|endurance]].
- **Other Modifiers:** Bonuses or penalties from abilities, [[Conditions|conditions]], or equipment.

## [[Damage Types|Damage]] Resolution
- When [[Damage Types|damage]] exceeds [[Sturdiness]], the excess reduces Blood.
- If Blood reaches zero, the character falls unconscious. Each [[Rounds|Round]] spent unconscious increases Exhaustion by 1 level.
- If [[Damage Types|damage]] drops Blood below zero, the negative amount converts into Exhaustion levels, then Blood resets to zero.

> **Example:** Blood = 12, [[Sturdiness]] = 4, Incoming [[Damage Types|Damage]] = 14 → 4 absorbed by [[Sturdiness]], remaining 10 reduces Blood to 2.
> **Example:** Blood = 8, [[Sturdiness]] = 2, Incoming [[Damage Types|Damage]] = 12 → 2 absorbed by [[Sturdiness]], remaining 10 reduces Blood to 0 → 2 excess converts into 2 Exhaustion levels.

## Blood Thresholds and Penalties
Even when not fully depleted, low Blood imposes penalties reflecting the strain on the body. Closed [[Injuries|wounds]] may reopen at dangerously low Blood levels.

| Blood Remaining | Effect                                                                        |                                       |
| --------------- | ----------------------------------------------------------------------------- | ------------------------------------- |
| >50%            | No penalty. The character functions normally.                                 |                                       |
| 30–50%          | Gain **Breathless**. Closed [[Injuries\|wounds]] have a 5% chance to reopen.  |
| 10–30%          | Gain **Dazed** and **Disoriented**. [[Evasion]] –2. Closed [[Injuries\|wounds]] have a 10% chance to reopen. |
| <10%            | Severe penalties: –3 to all physical Tests. [[Evasion]] –3. Closed [[Injuries\|wounds]] have a 25% chance to reopen. |
| 0 or below      | All closed [[Injuries\|wounds]] reopen.                      |

> Thresholds are based on your current Blood as a percentage of your maximum, rounded up to the nearest integer. A character with higher maximum Blood is not penalised more heavily than one with lower maximum Blood at the same relative point.

## Blood Dice
Blood Dice represent your body's natural capacity to recover during [[Rest & Recovery|rest]]. They start at **d4** and you gain 1 die every level, settings define how the die value increases. Spent dice are regained on a Long [[Rest & Recovery|Rest]].

## Special Cases
- Some [[Attacks|attacks]] or effects bypass [[Sturdiness]] entirely, directly reducing Blood to represent grievous [[Injuries|wounds]] or powerful strikes.
- Healing or magical effects can restore Blood over time as defined by the relevant module.
