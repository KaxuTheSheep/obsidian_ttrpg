---
tags:
  - Mechanics/Combat
---
Ranged [[attacks]] allow characters to strike targets at a distance using bows, thrown weapons, firearms, or similar arms. They follow the same core [[Attacks|attack]] resolution as melee but interact differently with [[Movement Types|movement]], cover, and spatial timing.

## [[Attacks|Attack]] Roll
Roll **2d10 + [[Attributes|Grace]]** and compare to the target's [[Evasion]].

## Projectile Types
Ranged weapons [[Falling|fall]] into two categories based on how their projectiles are tracked.

## Tracked Projectile Resolution
Tracked projectiles move through space in **path segments** during the Resolution Phase.

- At **Initiation [[Ticks, Priority & Resolution|Priority]] X** the projectile leaves the [[weapon]] and move one Travel Rate worth of meters in **[[Ticks, Priority & Resolution|Tick]] X**, at position Y.
- At **[[Ticks, Priority & Resolution|Tick]] X–1** it has travelled another one Travel Rate worth of meters, reaching position Z, this continues every Tick.
- If at any point there is a target at the correct **Tick** between the old position and new position, then that's a valid target and you roll attack roll against them.
- If it doesn't this represents the shot being off target and their minor movements to be enough to essential pass through them and continues.
- If it hits against the target, take the damage as they normally would.
- **Non-piercing projectiles** stop at the first creature hit within a segment. Tracking ends.
- **Piercing projectiles** continue through targets. How many they can pierce is defined by the [[weapon]] (e.g. a heavy crossbow may pierce 1 additional target; a high-powered piercing [[weapon]] may pierce many).

If a creature **moves into the projectile's path** at their own [[Ticks, Priority & Resolution|Priority]] step, their updated position is used at that step. If the projectile has already passed that position in a prior segment, they are unaffected.

**Friendly fire applies.** If an ally moves into the projectile's path between segments, they are a valid hit candidate the same as an enemy. Intent does not redirect physics.

### Travel Rate
Travel Rate is expressed in **meters per [[Ticks, Priority & Resolution|Tick]] step**. This is listed on the weapon.

### Example for a Fantasy setting
A shortbow is fired at **Initiation [[Ticks, Priority & Resolution|Priority]] 16** with a Travel Rate of **15 meters per [[Ticks, Priority & Resolution|Tick]] step**.
- [[Ticks, Priority & Resolution|Tick]] 16 → Arrow leaves bow at position Y.
- [[Ticks, Priority & Resolution|Tick]] 15 → Arrow has travelled 15 meters, reaching position Z. Any creature in the Y–Z path is checked, closest first.
- [[Ticks, Priority & Resolution|Tick]] 14 → Arrow continues another 15 meters. New segment checked.
- This continues until the arrow hits a target or is no longer needed to be tracked for whatever other reason.

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

| Cover             | Effect                                              |
| ----------------- | --------------------------------------------------- |
| Partial (25–50%)  | 1 instance of disadvantage to [[Attacks\|Attack]]   |
| Significant (75%) | 2 instances of disadvantage to [[Attacks \|Attack]] |
| Full (100%)       | [[Attacks\|Attack]] automatically fails             |

On a Critical Success against Full Cover, the shot may find a gap or ricochet at GM discretion.

## [[Facing]]
- Attacking from the rear arc grants **Advantage**.
- [[Parry]] does not apply to ranged [[Attacks|attacks]].
- [[Block]] only applies if a shield is actively [[Facing|facing]] the attacker.
- [[Dodge]] applies normally.

## [[Reactions]] and Cover
A character may use a Reaction during the Resolution Phase to move into cover. Whether they reach cover before impact depends on their [[Movement Types|movement]] [[Ticks, Priority & Resolution|Priority]] steps relative to the projectile's travel [[Ticks, Priority & Resolution|Priority]] steps (for tracked projectiles) or the firing [[Ticks, Priority & Resolution|Priority]] (for instant projectiles).
