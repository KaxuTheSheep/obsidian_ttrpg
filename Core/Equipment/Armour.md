---
tags:
  - Mechanics/Combat
  - Item
---
Armour Damage Resistance (DR) is a Core mechanic: a flat reduction applied to incoming [[Damage Types|damage]] **before** it reaches [[Sturdiness]] (see [[Damage Types#Damage Resolution Order]]). What Core does *not* define is where DR comes from, how much of it a given source grants, or whether it covers the whole body or only part of it. That's left to the setting — this document lays out the shapes that source can take, for a module to pick from or combine.

## Sources of DR
A creature's total DR may come from one or more of the following, defined per module:

- **Worn Armour** — external equipment (plate, leather, padded cloth) put on and removed like any other item. This is the default assumption in most fantasy or grounded settings.
- **Natural Armour** — DR intrinsic to the creature's own body (scales, hide, chitin, bark). Doesn't occupy an equipment slot and isn't subject to equipment loss, though a module may still allow it to be damaged or degraded narratively.
- **Augmented Armour** — DR from cybernetics, implants, or magical alteration to the body itself. Functionally similar to Natural Armour for DR purposes, but typically interacts with [[Injuries|Injury]] and repair rules differently (see the Module Responsibility note in [[Setting Mechanic Creation]] regarding destroyed augmented body parts).

Where more than one source applies to a creature simultaneously, the module should state whether DR stacks, whether only the highest applies, or whether they layer against different damage types.

## Full-Body vs Segmented DR
Core assumes, by default, a **single DR value** applied uniformly regardless of where a hit lands — this keeps the damage resolution order (Armour DR → Sturdiness → Blood) simple and fast at the table.

A module may instead adopt **Segmented DR**, where different body locations (head, torso, limbs) carry different DR values. This is a legitimate optional layer, but it is not free — a module doing this must additionally define:

- **How hit location is determined.** Core has no hit-location subsystem. A module must add one (e.g. a location table rolled alongside the attack, a called-shot mechanic, or a Facing-derived arc-to-location mapping) or Segmented DR has nothing to resolve against.
- **How partial coverage interacts with an uncovered location.** If a creature wears a breastplate with no matching greaves, a hit resolved to the legs should use whatever DR (if any) applies there — typically 0, or a lower Natural/Augmented value if applicable.
- **That the fixed resolution order is preserved per hit.** Segmentation changes *which* DR value is looked up, not the sequence itself — Armour DR (segment-appropriate) → Sturdiness → Blood remains fixed, per [[Setting Mechanic Creation]].

Segmented DR adds tactical granularity (called shots, targeting gaps in armour) at the cost of table speed. Full-body DR is faster and is the recommended default unless the setting's combat identity specifically wants called-shot play.

## What a Module Must Still Define
- The actual DR values granted by each piece of worn armour, and any Weight Class or [[Movement Types|movement]] penalties attached to it.
- Whether Natural or Augmented armour exists in the setting at all, and its values.
- If adopting Segmented DR: the hit-location method and the DR table per segment.
