---
tags:
  - Mechanics/Combat
---

# Segmented Body System

*[[Damage Types|Damage]] in New Halcyon is not abstract. It lands somewhere specific and what it hits determines what happens next.*

---

## Overview

Rather than a single unified health pool, the body is divided into segments each with their own Integrity pool. Global [[Sturdiness]] remains as a first layer buffer representing posture, guard, and the ability to roll with a hit. Once Sturdiness is exhausted, [[Damage Types|damage]] becomes localised and anatomical.

---

## Segments

| Segment | Notes |
|---|---|
| Head | Includes neck. Small pool, most dangerous to cripple. |
| Upper Torso | Vital organs, heart, lungs. |
| Lower Torso | Abdomen. Crippling triggers bleed out rather than immediate dying. |
| Left Arm | Includes hand. |
| Right Arm | Includes hand. |
| Left Leg | Includes foot. |
| Right Leg | Includes foot. |

---

## Integrity Pools

Integrity represents the localised health of each segment. It is derived from the character's core **Blood** stat using the following formula:

**Segment Integrity = Blood × 5 × Segment Multiplier**

| Segment | Multiplier | Example — Blood 10 |
|---|---|---|
| Head | 0.15 | 7 |
| Upper Torso | 0.25 | 12 |
| Lower Torso | 0.20 | 10 |
| Each Arm | 0.10 | 5 |
| Each Leg | 0.10 | 5 |

Total Integrity across all segments equals Blood × 5. Blood itself remains the core stat from which everything is derived. Integrity is the segmented expression of it.

[[Rounds|Round]] all values down to the nearest whole number.

---

## [[Damage Types|Damage]] Resolution Order

When a character takes [[Damage Types|damage]] resolve in this sequence:

1. **Armour DR** reduces incoming [[Damage Types|damage]] for the targeted segment — see [[Cyberpunk Armour]]
2. **Sturdiness** absorbs remaining [[Damage Types|damage]] from its global pool
3. If Sturdiness is at 0, remaining [[Damage Types|damage]] reduces **Integrity** of the targeted segment
4. If Integrity reaches 0 the segment is **crippled**

---

## Normal Hits and Critical Hits

**Normal hits** represent grazes, partial impacts, and [[Rounds|rounds]] that connect but do not land cleanly. Sturdiness absorbs them as normal.

**Critical hits** represent direct, clean impacts. A critical hit **bypasses Sturdiness entirely** and applies [[Damage Types|damage]] straight to the targeted segment's Integrity pool. This is the primary mechanical reward of a critical success — not increased [[Damage Types|damage]] numbers but guaranteed anatomical impact.

A called shot that also scores a critical is the most dangerous combination — correct location, direct hit, full Integrity [[Damage Types|damage]] with no Sturdiness buffer.

---

## Called Shots

By default [[Attacks|attacks]] target the Upper or Lower Torso. An attacker may declare a specific segment or target before rolling. This reduces the [[Attacks|attack]] roll by a flat value relative to the torso baseline.

| Target | Roll Reduction |
|---|---|
| Upper Torso | 0 |
| Lower Torso | 0 |
| Arms | −3 |
| Legs | −3 |
| Head | −5 |
| Specific target within segment* | Additional −5 |

*Specific targets within a segment include eyes, heart, lungs, joints, hands, and equivalent precise locations. These stack on top of the segment reduction.

> **Example:** Targeting the left eye is a head shot (−5) plus specific target (−5) for a total roll reduction of −10.

Called shots do not bypass Sturdiness on their own. Only a critical hit does that. A called shot that scores a critical hit combines both effects.

Disciplines, [[Weapon|weapon]] types, and traits may reduce these penalties for specific builds. See relevant discipline files.

---

## Crippling

When a segment's Integrity reaches 0 it becomes **crippled**. Two things happen simultaneously:

- A **permanent injury** is applied to that segment
- An **immediate effect** triggers based on which segment was crippled

| Segment | Permanent Injury | Immediate Effect |
|---|---|---|
| Head | Brain [[Damage Types|damage]], fractured skull, lost eye | Enter **dying state** |
| Upper Torso | Punctured lung, heart [[Damage Types|damage]], shattered clavicle | Enter **dying state** |
| Lower Torso | Organ [[Damage Types|damage]], spinal injury | **Bleed out** begins — see below |
| Arm | Lost arm, mangled hand, destroyed joint | Drop held item in that arm. Relevant augments in that segment become non-functional. |
| Leg | Lost leg, shattered knee | Fall **prone**. [[Movement Types|Movement]] halved until treated. Relevant augments in that segment become non-functional. |

Permanent injuries persist beyond the encounter. See [[Injuries]] for full consequences of each injury type.

---

## Lower Torso Bleed Out

When the Lower Torso is crippled the character does not immediately enter the dying state. Instead a bleed out effect begins.

Each [[Rounds|round]], Integrity drains from both **Upper Torso** and **Head** simultaneously at a fixed rate of **[PLACEHOLDER — requires balancing]** per [[Rounds|round]].

At the start of each [[Rounds|round]] the affected character may make a **Vitality Test DN [PLACEHOLDER]** to suppress the drain for that [[Rounds|round]].

An ally may attempt to stabilise the wound with a **[[Skills|Medicine]] Test DN 14** as a Full [[Actions|Action]]. On success the drain stops. The crippled segment and permanent injury remain.

If either Upper Torso or Head Integrity reaches 0 as a result of bleed out, the character enters the dying state normally.

---

## Augmented Segments

Augments installed in a segment replace or supplement the biological tissue of that segment. When a segment's Integrity reaches 0 the following applies regardless of augmentation level:

- Augments in that segment become **non-functional**
- The permanent injury applies to whatever biological tissue remains
- For fully augmented segments with no biological tissue, the permanent injury reflects hardware destruction rather than biological trauma

This keeps parity between augmented and unaugmented characters. Both lose segment function at 0 Integrity through different fictional mechanisms.

Augment repair requires a **fitter**. Biological injury treatment follows standard [[Injuries]] rules.

---

## Dying State

A character enters the dying state when Head or Upper Torso Integrity reaches 0, or when bleed out drains either of those segments to 0.

While dying the character gains 1 level of Exhaustion per [[Rounds|Round]]. At Exhaustion 10 the character dies. See [[Death]] for full rules.

---

*See [[Cyberpunk Armour]], [[Firearms]], [[Injuries]], [[Death]], [[Sturdiness]].*
