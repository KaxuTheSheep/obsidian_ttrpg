# Module Design Guide

This document defines the contract between the core system and any module built on top of it. Each module exists in its own vault alongside its world lore. This file is self-contained — no cross-vault links are assumed.

---

## What the Core Guarantees

These mechanics are fixed. A module must not override or contradict them.

**Resolution**

- All tests use 2d10 plus relevant modifiers compared to a Difficulty Number.
- Advantage and Disadvantage use 4d10, dropping the two lowest or two highest respectively.
- Critical Success is double 10s. Critical Failure is double 1s.
- Die steps follow the sequence: d2 → d4 → d6 → d8 → d10 → d12 → d14... d2 is the floor.

**Combat flow**

- Combat is divided into Rounds consisting of a Declaration Phase and a Resolution Phase.
- Actions resolve in descending Speed order. Ties resolve by Grace, then GM discretion.
- Each character receives 2.5 Actions and 1 Reaction per Round. Unused actions do not carry over.
- Action types are Full Action, Half Action, and Reaction as defined in the core.

**Damage resolution order**

- All damage resolves in this fixed sequence: Armour DR → Sturdiness → Blood.
- This order cannot be changed by a module. Additional layers (e.g. segmented Blood pools) must sit within or replace the Blood step, not interrupt the sequence upstream.

**Health framework**

- Sturdiness is a recoverable buffer representing posture and guard. It is restored more easily than Blood.
- Blood is lasting physical harm and is harder to restore.
- When Blood reaches zero the character enters the dying state, gaining 1 Exhaustion per Round.
- At Exhaustion 10 the character dies permanently.

**Injury framework**

- Critical Successes on attacks can cause wounds imposing –1 to Physical Tests each.
- Critical Successes that reduce Blood to zero or below cause permanent injuries rather than wounds.
- The permanent injury table in the core is the default. Modules may extend it but not remove the framework.

**Resurrection**

- A character may only be resurrected once across their entire life regardless of setting.
- This is a narrative design rule, not a world-specific one. Modules define the fiction of how resurrection occurs, or whether it is accessible at all, but cannot remove the once-only limitation.

**Sanity framework**

- Sanity represents mental resilience. It depletes under fear, trauma, and psychological strain.
- Sanity thresholds and the Affliction framework apply in all settings unless a module explicitly opts out and replaces them with an equivalent system.
- The Affliction examples in the core are illustrative, not exhaustive. See the section on module-defined content below.

**Vision and senses**

- The light scale (0–5) and three-zone visibility model (Clear, Blurry, Black) are core mechanics.
- Mechanical effects of each zone are fixed. Modules define what light sources exist and at what level they sit on the scale.

---

## What a Module Must Define

A module is not functional without these. They have no core default beyond the framework.

**Armour DR**

- The core defines that Armour DR exists as a flat damage reduction applied before Sturdiness.
- The module defines: what armour exists, how it is acquired, what DR values it provides, and any secondary mechanical effects such as movement penalties or attribute restrictions.
- DR values should be defined on a consistent internal scale. Cross-module comparisons are not guaranteed to be meaningful.

**Injury restoration**

- The core defines that permanent injuries persist until treated by advanced means.
- The module defines what those means are. Examples: magical regrowth, surgical reconstruction, prosthetic replacement.
- Modules involving augmentation or cybernetics should define how destroyed augmented body parts interact with the permanent injury table.

**Resurrection fiction**

- If resurrection is possible in the world, the module defines the method, cost, and accessibility.
- If resurrection is not possible, the module states this explicitly.

**Afflictions**

- The core provides an Affliction framework and examples. The module may use those examples, extend them, or replace them entirely with setting-appropriate alternatives.
- Any module-defined Affliction must follow the same three-tier structure (Minor, Moderate, Severe) and must specify trigger, mechanical effect, and recovery condition at each tier.

**Light sources**

- The module defines what light sources exist in the setting and what level on the 0–5 scale they occupy.
- The core examples (dying embers, torches, direct sunlight) are illustrative and fantasy-adjacent. Modules should replace them with setting-appropriate equivalents.

**Skills**

- The core skill list is the baseline. Modules may add setting-specific skills following the same format: skill name, linked attribute, and description.
- Modules should not remove core skills but may make some irrelevant by context.

---

## What a Module May Override

These are core defaults that a module can replace if the setting requires it.

**Blood model**

- The core treats Blood as a single unified pool.
- A module may replace this with a segmented model (e.g. one pool per body segment) provided the following are preserved:
    - The dying state triggers when the relevant pool or pools reach zero.
    - The Exhaustion accumulation and death at Exhaustion 10 rules remain unchanged.
    - Wound and injury rules are adapted to function within the new model.

**Blood and Sturdiness scaling**

- Base values and scaling rates are defined per module to suit the setting's lethality and power level.

**Conditions**

- Core conditions are the default set. A module may add setting-specific conditions following the same format: name, effect, and end condition.
- Core conditions should not be removed, but a module may note that certain conditions are rarely or never encountered in its context.

**Sanity system**

- A module may opt out of the Sanity system entirely if the setting does not support it, provided it either replaces it with an equivalent mental resilience mechanic or explicitly states that no such system applies.

---

## Compatibility Rules

Any module claiming compatibility with this core must:

1. Not alter the 2d10 resolution mechanic or the Advantage/Disadvantage system.
2. Not alter the Speed-based resolution order or the Action economy.
3. Preserve the damage resolution sequence: Armour DR → Sturdiness → Blood (or Blood equivalent).
4. Preserve the dying state and death rules.
5. Preserve the once-only resurrection limit.
6. Define all items listed under _What a Module Must Define_.

A module that changes any item in the fixed list is no longer a module — it is a fork of the core system.