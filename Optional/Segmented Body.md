---
tags:
  - Mechanics/Combat
  - Optional
---
## Core Compatibility Note
This optional rule **deviates from Core's Damage Types Damage Resolution Order**. Core requires the sequence Armour DR → Sturdiness → Blood to remain intact, with additional layers sitting _within_ the Blood step rather than interrupting it. This rule instead merges Sturdiness and Blood into a single pool **per body segment**. A setting using this rule is explicitly forking from Core on this point, and should say so in its own documentation rather than claiming full Core compatibility.

Everything else in Core (dying state, Exhaustion accumulation, death at Exhaustion 10, once-only resurrection, Injuries framework) is preserved and adapted below — this rule does not touch those beyond what's explicitly stated.

## Overview
Rather than tracking Sturdiness and Blood as two separate pools across the whole body, each character's body is divided into **segments**, each with its own single pool: **Segment Health**.

**Segment Health = ⌈(Sturdiness + Blood) × Segment Multiplier⌉**

Sturdiness and Blood are calculated as normal per Core, summed into one base value, then multiplied per segment then apply the ceiling function (round up).

## Segments and Multipliers

|Segment|Multiplier|Notes|
|---|---|---|
|Torso|×0.5|Default target, largest and most trained-for.|
|Head|×0.2|Small pool — a handful of good hits is lethal.|
|Arm (each)|×0.15|Disables that arm at 0.|
|Leg (each)|×0.15|Disables that leg at 0.|

Values are illustrative starting points — a module should tune multipliers to its own lethality target, but Torso should remain the largest single segment and Head the smallest of the "vital" segments.

> **Example:** A character with Sturdiness 6 and Blood 10 has a combined base of 16. Torso Health = 8, Head Health = 3.2 → 4, each Arm = 2.4 → 3, each Leg = 2.4 → 3.

## Damage Resolution (Segmented)
1. Determine which segment is hit (see Hit Location, below).
2. Apply Armour DR — universal, segmented, or both (see Armour DR, below).
3. Remaining damage reduces that segment's Health pool directly. There is no separate Sturdiness-then-Blood split within a segment — this rule replaces both.
4. If a segment reaches 0, apply its **Segment Failure** effect (below).

Damage to one segment does **not** carry over to another segment or to a shared pool. A depleted Arm doesn't spill into Torso.

## Segment Failure

|Segment|At 0 Health|
|---|---|
|Torso|Character enters the **dying state** (per Core Death rules) — falls unconscious, gains 1 Exhaustion per Round.|
|Head|Character enters the **dying state**, as above.|
|Arm|Arm becomes **Disabled** — cannot be used to wield weapons, hold items, or provide two-handed bonuses. Does not trigger dying or Exhaustion.|
|Leg|Leg becomes **Disabled** — Movement Distance halved per disabled leg; both legs disabled reduces the character to Prone and unable to stand without assistance. Does not trigger dying or Exhaustion.|

Only Torso and Head feed into the dying state and Exhaustion — this preserves Core's death sequence rather than replacing it. Excess damage that would reduce a Torso or Head pool below 0 converts to Exhaustion levels exactly as Core's Blood overflow rule describes.

Disabled limbs remain Disabled until treated — cross-reference with Injuries below.

## Hit Location
**Default target: Torso.** Any attack that doesn't specify otherwise resolves against Torso Health.

**Called Shots:** An attacker may target a specific segment (Head, Arm, Leg) by declaring it before the attack roll. Called shots suffer a penalty for difficulty of that target:

| Segment | Called Shot Penalty    |
| ------- | ---------------------- |
| Head    | 2 sets of Disadvantage |
| Arm     | Disadvantage           |
| Leg     | Disadvantage           |

A module should pick either the Disadvantage die mechanic or a flat numeric penalty and apply it consistently — don't mix both for the same segment.

**Critical Success alternative:** A module may instead (or additionally) allow a Critical Success on an untargeted attack to let the attacker choose the segment struck after the fact, representing a lucky, precise hit rather than a deliberately aimed one.

## Armour DR
This rule explicitly supports three configurations, and a module may use any single one or combine them:

- **Universal DR** — a flat DR value applies to all segments equally (e.g. force fields, environmental hazard suits).
- **Segmented DR** — different DR per segment (e.g. plate cuirass on Torso, helmet on Head, vambraces on Arms), with unarmoured segments having 0 DR.
- **Layered (Universal + Segmented)** — both apply simultaneously and stack, e.g. a subdermal armour augment (universal) plus a plate vest (Torso-only segmented). Resolve Universal DR first, then Segmented DR, before damage reaches the segment's Health pool.

A module using this rule **must state explicitly** which of the three configurations it's using and, if segmented or layered, list DR per segment on each armour entry.

## Injuries Interaction
Segment Failure on a limb functions similarly to a permanent Injury, but is not automatically one:
- A **Disabled** limb at 0 Health can be stabilised/closed via a Medicine Test as normal for wounds, restoring some function once the segment's Health is restored above 0.
- If a **Critical Success** reduces a segment to 0 or below (Torso, Head, or limb), it instead inflicts a **permanent Injury** per Core's Injuries rules, using the existing Permanent Injury List (Lost Arm, Lost Leg, Damaged Eye, etc.) — matched to whichever segment failed.

## Recovery
Segment Health recovers using the same sources as Sturdiness/Blood recovery in Core. Instead you add together the recovery and you can spend them as points where ever needed.