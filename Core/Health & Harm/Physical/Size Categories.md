---
aliases:
  - Size
  - Size Category
  - Tiny
  - Small
  - Large
  - Huge
  - Gargantuan
tags:
  - Mechanics
  - Mechanics/Combat
---
Every creature belongs to a Size Category. Size is a physical fact about a creature's body — how much space it occupies, how far it can naturally reach, how hard it is to spot or pin down, and how much punishment its frame can absorb before the life goes out of it. Size does not represent toughness or armour; a creature's [[Sturdiness]] and Damage Resistance are governed entirely by its own stat block, race, and equipment, not by its Size Category.

Medium is the baseline. All modifiers below are stated relative to it.

## The Size Table

| Category   | Natural Range | Space    | Carry Capacity (INT) | Evasion Mod (INT) | Opposed [[Attributes\|Might]] (INT) | Opposed [[Attributes\|Grace]] (INT) | Natural UNARMED Die | Stealth DN Mod (INT) | Detection Range | Fall/Collision Damage (INT) | [[Blood]] Multiplier |
| ---------- | ------------- | -------- | -------------------- | ----------------- | ----------------------------------- | ----------------------------------- | ------------------- | -------------------- | --------------- | --------------------------- | -------------------- |
| Tiny       | 0.25m         | 0.3m     | ×1 (min 3)           | +4                | −6                                  | +4                                  | 0 (Only Might)      | +4                   | ×0.5            | −1 die step                 | ×0.5                 |
| Small      | 0.5m          | 0.5m     | ×2                   | +2                | −3                                  | +2                                  | 1d2                 | +2                   | ×0.75           | −1 die step                 | ×0.75                |
| **Medium** | **1m**        | **0.6m** | **×3**               | **+0**            | **+0**                              | **+0**                              | **1d4**             | **+0**               | **×1**          | **as written**              | **×1**               |
| Large      | 1.5m          | 1.2m     | ×5                   | −2                | +3                                  | −1                                  | 1d6                 | −2                   | ×1.5            | +1 die step                 | ×1.5                 |
| Huge       | 2m            | 2.4m     | ×8                   | −4                | +6                                  | −2                                  | 1d8                 | −4                   | ×2              | +2 die steps                | ×2                   |
| Gargantuan | 3m            | 3.6m     | ×12                  | −6                | +9                                  | −3                                  | 1d10                | −6                   | ×3              | +3 die steps                | ×2.5                 |

## How Each Column Works

### Natural Range
Replaces the default 1m Natural Range in the [[Range & Threat]] formula for that creature. [[Weapon]] Range still adds on top as normal.

> **Melee Threat = Size Natural Range + Weapon Range**

### Space
The creature's footprint diameter on the map, using the standard ~0.6m-per-percentile baseline. This is the number that drives the Close-Quarters interaction below — reach alone does not determine whether a creature is "inside the guard" of another; physical bulk does.

### Carry Capacity
Multiplies the creature's normal [[Carrying Limits|Carrying Capacity]] result (`6 + Might × 3`) rather than replacing it, so a large but weak creature and a large but powerful one still land in sensible places relative to each other.

### Evasion Mod
Applied directly to [[Evasion]]. This is passive — it represents how large a target the creature presents and applies whether or not the creature is aware, moving, or actively defending.

### Opposed Might / Opposed Grace
Applied as a flat modifier whenever the creature's **Might** or **Grace** is used in an opposed roll — [[Core/Combat/Action System/Grapple|Grapple]] initiation and escape, Weapon Bind Disarm Attempts, forced-movement resistance, Sundering-adjacent Might Tests, and Grace used defensively via **[[Dodge]]** (declared or reactive) or **[[Parry]]**.

The two columns deliberately move in opposite directions. A larger creature is much harder to physically overpower (**Might**) but no more nimble for its size, and often less so (**Grace**). A smaller creature is trivial to muscle around but correspondingly hard to actually catch or land a decisive blow on — this is why the Grace bonus is **not** folded into Evasion Mod: Evasion Mod represents passive target size, while the Opposed Grace modifier represents active agility, and a small, evasive creature legitimately benefits from both stacking together when it chooses to actively Dodge or Parry.

### Natural Weapon Die
The baseline damage die for that creature's natural weapons (bite, claw, unarmed strike, and similar) before adding any Attribute, in the same slot the core [[Unarmed]] rules use 1d4 for Medium creatures. A creature's own stat block may override this where its natural weapon is thematically sharper or duller than its size alone would suggest — this is a floor to build from, not a hard override of existing Bestiary entries.

### Stealth DN Mod
A modifier to the creature's own [[Skills|Stealth]] Test results. Smaller creatures are inherently easier to conceal; larger ones essentially cannot hide their presence, only their intent (see [[Disguise]]).

### Detection Range
A multiplier applied to any ability or trait that grants detection over a flat distance in meters — Predator's Scent, Vibration Sense, and similar. Apply after all other modifiers to that range.

### Fall / Collision Damage
A die step adjustment (per [[The Core Dice#Die Steps|Die Steps]]) applied to [[Falling]] damage they take.

### Blood Multiplier
Applied to the creature's base [[Blood]]. This exists specifically to reflect that a Size Category shift changes the sheer physical mass of life force present — it is separate from, and stacks with, whatever a creature's race or Vitality investment already contributes. Note that this is the **only** place raw survivability is affected by size; [[Sturdiness]] and Damage Resistance remain entirely independent of Size Category by design.

## Size Category 
Some Settings may allow for size category changes from the default Medium.

**Full Category Shift** — the player moves one full Size Category (up or down). Apply every column of the destination row as a complete package: Natural Range, Space, Carry Capacity, Evasion Mod, both Opposed modifiers, Natural Weapon Die, Stealth DN Mod, Detection Range, Fall/Collision Damage, and the Blood Multiplier all move together. 

**Half-Step** — the recipient gains a partial physical change, you take a median of the 2 values which your size category is in between, rounding for values which need to be an integer which have a (INT) in the header and for dice you take the dice value in the direction of which size you are heading. You get called a Smaller or Larger Version of whatever size category you were before. If you become Smaller or Larger again you go to a normal category size accordingly.

**Cosmetic** — the physical change has no meaningful mechanical footprint (a visual difference only). Do not invent fractional modifiers for this; describe the change narratively and leave every column untouched.
