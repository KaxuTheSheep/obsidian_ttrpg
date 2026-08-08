---
tags:
  - Mechanics/Combat
  - Item
---
Equipment Quality represents the material and craftsmanship of a specific item, independent of what category it is. It applies universally across weapons, armour, and shields — the same five usable tiers plus Broken, expressed through whichever stats that equipment type actually cares about.

**Standard** is the baseline. Every weapon, armour, and shield statted by a module should be written at Standard quality. Nothing about their existing entries changes — Quality is a modifier layered on top, not a rewrite.

This document is the setting-agnostic core of the system. A module adopting it need only supply its own price multipliers (if it uses currency at all) and its own fictional framing for acquisition and degradation triggers — see the notes marked **Module-defined** below.

## Broken
A **Broken** item is treated as though it does not exist for mechanical purposes — it cannot be used for its function at all, regardless of what it is. A Broken weapon deals no damage and cannot be used to Attack, Parry, or Block. Broken armour provides no DR and no Evasion Modifier. A Broken shield provides no Block Die and no Parry Adjustment.

It still physically occupies inventory space and can still be carried, sold as scrap, or restored — it is not destroyed, only unusable until repaired back into a functioning tier through [[Skills|Crafting]] or the relevant restoration process below.

## Weapons

| Tier | Attack / Parry Roll | [[Ticks, Priority & Resolution\|Priority]] | Damage |
|---|---|---|---|
| Broken | — | — | Cannot be used |
| Shoddy | –1 | –2 | Reliable trait lost, if present |
| Worn | +0 | –1 | — |
| Standard | +0 | +0 | As written |
| Fine | +1 | +1 | — |
| Masterwork | +1 | +2 | +1 die step |

Heavy-class weapons gain only **half** the listed Priority bonus at Fine and Masterwork, rounded down — their identity is built on being slow but devastating, and full application would let a Masterwork heavy weapon out-pace a Standard light or standard weapon.

[[Range & Threat|Range]] is never modified by Quality at any tier. Range is geometric, not a property of material.

## Shields

| Tier | [[Parry]] Adjustment | [[Ticks, Priority & Resolution\|Priority]] | [[Block]] Die |
|---|---|---|---|
| Broken | — | — | Cannot be used |
| Shoddy | –1 | –2 | Step down |
| Worn | +0 | –1 | — |
| Standard | +0 | +0 | As written |
| Fine | +1 | +1 | Step up |
| Masterwork | +1 | +2 | Step up twice |

Block Die steps follow the standard die step sequence (d2 → d4 → d6 → d8 → d10 → d12 → d14), per [[The Core Dice]].

## Armour

| Tier | Evasion Modifier | DR |
|---|---|---|
| Broken | — | Cannot be used |
| Shoddy | –1 | –2 |
| Worn | +0 | –1 |
| Standard | As written | As written |
| Fine | +0 | +1 |
| Masterwork | +1 | +2 |

DR changes by 1 per tier moved away from Standard in either direction. Masterwork armour's +1 Evasion Modifier represents genuinely superior fit and balance, not just protection.

## Acquiring Quality Items
*(Module-defined)* Quality above Standard is not usually something a starting character buys off a shelf casually — Fine and Masterwork items should generally be GM-gated behind commission, reputation, quest reward, or setting-specific recovery rather than sitting in a general price list outright. Shoddy and Worn items, by contrast, are exactly what a scavenged black market or a desperate sale would produce, and can reasonably be available from character creation. The specific markets, factions, or locations that produce each tier are for the module to define.

## Degradation
Equipment does not degrade from ordinary use, ordinary combat, or the simple passing of time. It degrades when the GM calls for it, following a **meaningful narrative event** — this is a storytelling tool, not a tracked resource with pips or a wear counter.

### Trigger Categories
A piece of equipment drops **one full Quality Tier** when the GM determines one of the following has genuinely occurred. The specific in-fiction examples are *(Module-defined)*; the categories themselves are universal:

- **Environmental exposure** — corrosive or extreme conditions the item wasn't built to withstand.
- **Improper use** — equipment used outside its intended purpose or design conditions.
- **Extended neglect** — multiple missed Rest Activities where Repair Gear was available but skipped.
- **A specific story beat** — deliberate sabotage, a duel fought to visible ruin, an item the GM has flagged as narratively significant taking a symbolic blow.

Degradation always moves exactly one tier per triggering event, never further, regardless of how severe the moment was. If the GM wants something to go straight to ruined, that's a Broken item created directly through fiction (shattered, snapped, crushed), not a Quality Tier drop.

### Restoration
- **One tier of restoration** can be recovered through the **Repair Gear** [[Rest & Recovery|Rest Activity]], provided the character has appropriate materials — attempting it with nothing to repair with does not restore Quality even if it removes minor wear as normally written.
- **Full restoration to Standard** in a single sitting is available through a successful [[Skills|Crafting]] Test during a Short or Long Rest, DN set by the GM based on how far degraded the item is and what materials are available.
- **A Broken item** cannot be restored through Repair Gear at all — it requires a full Crafting Test (or equivalent commission) to bring it back to Shoddy, and further restoration from there follows the normal Crafting rules above.
- **GM override:** some damage is too severe for restoration to make narrative sense — an item destroyed in a way the fiction demands stay destroyed can be ruled permanently unrestorable. This should be rare and telegraphed, not applied retroactively as a surprise.

