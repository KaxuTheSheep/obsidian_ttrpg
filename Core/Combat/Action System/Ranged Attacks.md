---
tags:
  - Mechanics/Combat
---
Ranged [[attacks]] allow characters to strike targets at a distance using bows, thrown weapons, firearms, or similar arms. They follow the same core [[Attacks|attack]] resolution as melee but interact differently with [[Movement Types|movement]], cover, and spatial timing.

## [[Attacks|Attack]] Roll
Roll **2d10 + [[Attributes|Grace]]** and compare to the target's [[Evasion]].

## Projectile Types
Ranged weapons [[Falling|fall]] into two categories based on how their projectiles are tracked.

### Tracked Projectiles
Bows, crossbows, thrown weapons, and similar arms use tracked projectile [[Movement Types|movement]]. The projectile travels through space during the Resolution Phase and can interact with anything in its path.

### Instant Projectiles
Firearms [[Attributes|resolve]] instantly at the [[Ticks, Priority & Resolution|Priority]] they are fired. Bullet travel time is irrelevant at encounter scale — the projectile arrives in the same [[Ticks, Priority & Resolution|Priority]] step it is launched. No path tracking occurs. The [[Attacks|attack]] simply resolves against the declared target at Initiation [[Ticks, Priority & Resolution|Priority]].

## Tracked Projectile Resolution
Tracked projectiles move through space in **path segments** during the Resolution Phase.

- At **Initiation [[Ticks, Priority & Resolution|Priority]] X** the projectile leaves the [[weapon]] at position Y.
- At **[[Ticks, Priority & Resolution|Priority]] X–1** it has travelled one Travel Rate worth of meters, reaching position Z.
- **Any creature in the direct path between Y and Z** at that [[Ticks, Priority & Resolution|Priority]] step is a valid hit candidate.
- The projectile checks the closest creature to Y first.
- **Non-piercing projectiles** stop at the first creature hit within a segment. Tracking ends.
- **Piercing projectiles** continue through targets. How many they can pierce is defined by the [[weapon]] (e.g. a heavy crossbow may pierce 1 additional target; a high-powered piercing [[weapon]] may pierce many).

If a creature **moves into the projectile's path** at their own [[Ticks, Priority & Resolution|Priority]] step, their updated position is used at that step. If the projectile has already passed that position in a prior segment, they are unaffected.

**Friendly fire applies.** If an ally moves into the projectile's path between segments, they are a valid hit candidate the same as an enemy. Intent does not redirect physics.

### Travel Rate
Travel Rate is expressed in **meters per [[Ticks, Priority & Resolution|Priority]] step**. This is listed on the [[weapon]].

### Example
A shortbow is fired at **Initiation [[Ticks, Priority & Resolution|Priority]] 16** with a Travel Rate of **15 meters per [[Ticks, Priority & Resolution|Priority]] step**.
- [[Ticks, Priority & Resolution|Priority]] 16 → Arrow leaves bow at position Y.
- [[Ticks, Priority & Resolution|Priority]] 15 → Arrow has travelled 15 meters, reaching position Z. Any creature in the Y–Z path is checked, closest first.
- [[Ticks, Priority & Resolution|Priority]] 14 → Arrow continues another 15 meters. New segment checked.
- This continues until the arrow hits a target or reaches maximum [[Range & Threat|range]].

## Firearms
Firearms [[Attributes|resolve]] instantly — no path tracking. The [[Attacks|attack]] resolves at Initiation [[Ticks, Priority & Resolution|Priority]] against the declared target. Initiation [[Ticks, Priority & Resolution|Priority]] represents handling characteristics (aim time, draw, cycling) rather than projectile [[Ticks, Priority & Resolution|Priority]].

**General firearm characteristics:**
- **Pistols / SMGs** — high Initiation [[Ticks, Priority & Resolution|Priority]], lower [[Damage Types|damage]], short–medium optimal [[Range & Threat|range]]
- **Rifles** — moderate Initiation [[Ticks, Priority & Resolution|Priority]], high [[Damage Types|damage]], long optimal [[Range & Threat|range]]
- **Sniper rifles** — low Initiation [[Ticks, Priority & Resolution|Priority]] (significant aim time), very high [[Damage Types|damage]], extreme [[Range & Threat|range]], high pierce count
- **Shotguns** — moderate Initiation [[Ticks, Priority & Resolution|Priority]], hits a **cone** rather than a line (width defined by [[Weapon|weapon]]), no pierce, effective at short [[Range & Threat|range]] only

Specific stats are defined in the relevant module's [[Weapon|weapon]] list.

## [[Range & Threat|Range]]
Each ranged [[Weapon|weapon]] has an optimal [[Range & Threat|range]] in meters.
- Within optimal [[Range & Threat|range]]: no penalty.
- Beyond optimal [[Range & Threat|range]]: **–1 to [[Attacks|Attack]] and [[Damage Types|Damage]] per 20 meters beyond optimal [[Range & Threat|range]]**.

There is no cap on [[Range & Threat|range]] penalties.

## Minimum [[Range & Threat|Range]]
If a target is within minimum [[Range & Threat|range]]:
- [[Attacks|Attack]] rolls are made at **Disadvantage**.

This represents awkward handling at extreme close [[Range & Threat|range]].

## Cover

| Cover | Effect |
|---|---|
| Partial (25–50%) | –2 to [[Attacks|Attack]] |
| Significant (75%) | –4 to [[Attacks|Attack]] |
| Full (100%) | [[Attacks|Attack]] automatically fails |

On a Critical Success against Full Cover, the shot may find a gap or ricochet at GM discretion.

## [[Facing]]
- Attacking from the rear arc grants **Advantage**.
- [[Parry]] does not apply to ranged [[Attacks|attacks]].
- [[Block]] only applies if a shield is actively [[Facing|facing]] the attacker.
- [[Dodge]] applies normally.

## [[Reactions]] and Cover
A character may use a Reaction during the Resolution Phase to move into cover. Whether they reach cover before impact depends on their [[Movement Types|movement]] [[Ticks, Priority & Resolution|Priority]] steps relative to the projectile's travel [[Ticks, Priority & Resolution|Priority]] steps (for tracked projectiles) or the firing [[Ticks, Priority & Resolution|Priority]] (for instant projectiles).
