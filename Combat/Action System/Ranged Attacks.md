---
tags:
  - Mechanics/Combat
---
Ranged [[attacks]] allow characters to strike targets at a [[Movement Types|distance]] using bows, thrown [[weapons]], or similar arms. They follow the same core [[Attacks|attack]] resolution as melee but interact differently with movement, cover, and spatial timing.

## Attack Roll
Roll **2d10 + Grace** and compare to the target’s [[Evasion]].

## Arrow Travel
Ranged weapons use two timing values:
- **Initiation [[Speed & Resolution|Speed]]** — when the attack is launched in the Resolution Phase.
- **Travel Rate** — how far the projectile moves per [[Speed & Resolution|Speed]] step (metres per step).

Projectiles move continuously through the Speed timeline after being launched.

## Projectile Resolution
All ranged projectiles (arrows, bolts, thrown weapons, and spell projectiles) move through space during the Resolution Phase.

- Projectiles advance along their path by their **Travel Rate each Speed step** after initiation.
- At each Speed step, the projectile’s position is checked against all valid targets.
- If a projectile enters a target’s occupied space at any Speed step, the attack resolves immediately.
- If a target moves into or out of that space at their own Speed steps, the check uses their updated position at that step.

> A target is considered hit if the projectile passes through their occupied space (typically a 1–2m radius unless otherwise defined).

Projectiles travel in a straight line from origin to declared target unless stated otherwise.

## Example
A shortbow is fired at **Initiation Speed 16** with a Travel Rate of **15m per Speed step**.
- Speed 16 → Arrow is released.
- Speed 15 → 15m travelled.
- Speed 14 → 30m travelled.
- Speed 13 → 45m travelled.
- Speed 12 → 60m travelled → target is present → attack resolves.

A second creature begins moving at Speed 10, but the projectile has already passed their position before they enter it, so they are unaffected.

## Range
Each ranged weapon has an optimal [[Range & Threat|range]].
- Within optimal range: no penalty.
- Beyond optimal range: **-1 to Attack and Damage per 20m beyond optimal range**.

There is no cap on range penalties.

## Minimum Range
If a target is within minimum [[Range & Threat|range]]:
- Attack rolls are made at **Disadvantage**.
This represents awkward handling at extreme close range.

## Cover
Cover represents physical obstruction between attacker and target.

|Cover|Effect|
|---|---|
|Partial (25–50%)|–2 to Attack|
|Significant (75%)|–4 to Attack|
|Full (100%)|Attack automatically fails|

On a Critical Success against Full Cover, the shot may find a gap or ricochet at GM discretion.

## Facing
- Attacking from the rear arc grants **Advantage**.
- [[Parry]] does not apply to ranged attacks.
- [[Block]] only applies if a shield is actively facing the attacker.
- [[Dodge]] applies normally.

## Reactions and Cover
A character may use a Reaction during the Resolution Phase to move into cover.

Whether they reach cover before impact depends on their **movement Speed steps relative to the projectile’s travel Speed steps**.