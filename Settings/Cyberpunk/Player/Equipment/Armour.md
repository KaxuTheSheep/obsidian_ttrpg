---
tags:
  - Mechanics/Combat
---

# Armour

*In a city where augments are the default protection, wearing armour on the outside says something about who you are and what you can afford.*

---

## Overview

External armour provides flat damage reduction to covered segments. It is the primary defensive option for unaugmented characters and a supplementary layer for partially augmented builds. Fully augmented characters rely on subdermal augment plating rather than external armour — the protection is worn inside the body.

Armour degrades under sustained damage. It does not self repair. Repair requires a fitter or a repair pack.

---

## How Armour Works

Each armour set covers specific segments. When a covered segment takes damage, the armour's **DR value** reduces that damage before Sturdiness and Integrity are affected.

**Damage resolution with armour:**
1. Incoming damage to a covered segment is reduced by the armour's DR
2. Remaining damage reduces global Sturdiness
3. If Sturdiness is 0, remaining damage reduces that segment's Integrity

Armour only reduces damage to segments it covers. Uncovered segments receive no DR benefit.

---

## Armour Integrity and Degradation

Each armour piece has its own Integrity pool separate from the body's segment Integrity. This represents the physical condition of the armour itself.

As armour absorbs hits its Integrity degrades. When armour Integrity drops to or below **30% of its maximum**, the DR value **halves, rounding down**.

> **Example:** Armour with DR 4 and Integrity 20 takes repeated hits. When Integrity falls to 6 or below, DR drops to 2. If DR were 3 it would drop to 1. DR 1 drops to 0.

Armour at 0 Integrity provides no DR. It is effectively destroyed.

---

## Repair

Armour Integrity does not recover through rest. It must be repaired.

**Repair Pack** — a consumable that restores a fixed amount of armour Integrity in the field. Not widely available. Useful for extending armour life during extended operations without access to a fitter.

**Fitter repair** — full Integrity restoration. Requires visiting a fitter with the appropriate equipment. Cost varies by armour quality and damage sustained.

---

## Armour Sets

Armour is purchased as sets covering specific segment combinations. Helmets and leg guards are modular additions that stack onto any base set.

### Base Sets

| Set | Coverage | DR | Notes |
|---|---|---|---|
| Full Body Suit | All segments | Low | Primary augmentless option. Thin protection everywhere. |
| Tactical Vest | Upper Torso, Lower Torso | High | Vital protection only. Limbs and head exposed. |
| Combat Suit | Upper Torso, Lower Torso, Arms | Medium | Balanced coverage. Popular with partial augment builds. |

### Modular Additions

| Piece | Coverage | DR | Notes |
|---|---|---|---|
| Helmet | Head | Medium | Stacks onto any base set. |
| Leg Guards | Legs | Low–Medium | Stacks onto any base set. |

### DR Values

Specific DR values are **[PLACEHOLDER — requires balancing]**. General principle: external armour has lower DR than high end subdermal augment plating but is accessible without augmentation, fitters, or framework installation.

High end external armour approaches the DR of low end augment plating. The crossover point is intentional — a heavily armoured unaugmented character and a lightly augmented character occupy similar defensive tiers early in the game.

---

## Armour and Augments

Augmented characters with subdermal plating in a segment already have DR on that segment from the augment itself. External armour and augment plating **do not stack** — use whichever is higher for that segment.

This means:
- Fully augmented characters gain little from external armour
- Partially augmented characters benefit from armour on their unaugmented segments
- Unaugmented characters rely entirely on external armour for any DR

Subdermal augment plating follows the same 30% degradation threshold rule as external armour, tied to the segment's own Integrity rather than a separate pool. When the segment drops to 30% Integrity, the augment plating DR halves.

See [[Slot Categories]] for subdermal augment plating options.

---

## Why Armour Exists in New Halcyon

Augments are the dominant form of protection for anyone with the means and the framework to install them. External armour exists for three reasons:

**Augmentless characters** have no subdermal protection and no augmented limb integrity. Armour is their only mechanical DR option. A fully armoured unaugmented character can be genuinely resilient — they simply wear their protection on the outside.

**Partial builds** have unprotected segments alongside augmented ones. Armour fills those gaps cheaply without requiring additional augment installation and fitter fees.

**Framework rejection or avoidance** — characters who refuse augmentation for philosophical, political, or practical reasons still need to survive a city with no public safety infrastructure. Armour is the answer that requires no corporate dependency, no subscription, and no vulnerability to injection attacks.

---

*See [[Segmented Body]], [[Slot Categories]], [[Firearms]], [[Injuries]].*
