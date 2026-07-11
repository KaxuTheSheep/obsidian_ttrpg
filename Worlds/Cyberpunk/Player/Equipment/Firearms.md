---
tags:
  - Mechanics/Combat
---

# Firearms

*Point and shoot at close range. Everything else is skill, patience, and knowing your [[Weapon|weapon]].*

---

## Overview

Firearms [[Attributes|resolve]] differently depending on [[Range & Threat|range]]. At close ranges the bullet arrives effectively instantly — no travel tracking, no path calculation. At long and extreme ranges the physics of the shot matter and the core [[Ranged Attacks]] projectile rules engage.

---

## [[Attacks|Attack]] Roll

Roll **2d10 + [[Attributes|Grace]]** and compare to the target's Evasion.

Called shots reduce the [[Attacks|attack]] roll before comparison. See [[Segmented Body]] for called shot values.

---

## [[Weapon]] Categories

Each category has a distinct mechanical identity, CQC classification, and [[Range & Threat|range]] band profile.

### CQC Classification

| Classification | Effect |
|---|---|
| CQC Optimised | No penalty at point blank. Certain builds may gain advantage in close quarters. |
| Neutral | No mechanical penalty at point blank. Fiction implies awkwardness but rules do not govern it. |
| CQC Penalised | Disadvantage on [[Attacks|attack]] rolls at point blank [[Range & Threat|range]]. |

### Categories

**Pistol**
- CQC: Optimised
- Identity: Precision, stealth, quickdraw. The headshot [[Weapon|weapon]]. Discipline investment centres on called shots and close engagements.
- Fire: Single shot

**SMG**
- CQC: Optimised  
- Identity: Volume of fire at close [[Range & Threat|range]], suppressive pressure in tight spaces.
- Fire: Burst

**Assault Rifle**
- CQC: Neutral
- Identity: Flexible general purpose [[Weapon|weapon]]. Effective across most ranges.
- Fire: Single or burst

**Shotgun**
- CQC: Optimised
- Identity: Cone [[Damage Types|damage]], close [[Range & Threat|range]] dominance, hard [[Range & Threat|range]] cutoff.
- Fire: See Cone Rules below

**Sniper Rifle**
- CQC: Penalised
- Identity: Extreme [[Range & Threat|range]] precision. Full projectile tracking rules always apply.
- Fire: Single shot, slow

**LMG**
- CQC: Penalised
- Identity: Sustained suppressive fire, high ammunition consumption, area control.
- Fire: Burst, heavy

---

## [[Range & Threat|Range]] Bands

[[Range & Threat|Range]] determines which rules govern the shot. Squares are approximately 1.5 metres each.

| Category | Point Blank | Close | Medium | Long | Extreme |
|---|---|---|---|---|---|
| Pistol | 0–2sq | 3–8sq | 9–20sq | 21–40sq | 41sq+ |
| SMG | 0–2sq | 3–10sq | 11–25sq | 26–50sq | 51sq+ |
| Assault Rifle | 0–2sq | 3–15sq | 16–40sq | 41–80sq | 81sq+ |
| Shotgun | 0–2sq | 3–6sq | 7–12sq | 13sq+ | — |
| Sniper Rifle | 0–5sq | 6–20sq | 21–60sq | 61–150sq | 151sq+ |
| LMG | 0–2sq | 3–12sq | 13–35sq | 36–70sq | 71sq+ |

### [[Range & Threat|Range]] Rules by Band

**Point Blank** — CQC classification applies. See above.

**Close and Medium** — Shot resolves instantly. No projectile travel tracking. Standard [[Attacks|attack]] roll vs Evasion.

**Long** — Core [[Ranged Attacks]] projectile tracking rules engage. [[Movement Types|Movement]] and positioning matter.

**Extreme** — Full projectile tracking with significant penalties. Sniper territory. Wind and distance compound.

**Shotgun beyond Medium** — No [[Attacks|attack]] roll. Effective [[Range & Threat|range]] ends at medium. The spread is too wide to reliably hit a target beyond that distance.

---

## Ammunition and Magazines

Every firearm tracks ammunition as a percentage of magazine capacity. Each [[Attacks|attack]] consumes a fixed percentage based on fire mode.

| Fire Mode | Magazine Consumption per Trigger Pull |
|---|---|
| Single shot | 10% |
| Burst | 25% |
| Heavy burst — LMG | 35% |

### Magazine States

Track current magazine percentage during play.

| Percentage | State | Effect |
|---|---|---|
| 100–26% | Loaded | No effect |
| 25–1% | Low | Player is aware the magazine is nearly empty |
| 0% | Empty | Must reload before firing |

### Reload

Default reload cost is a **Half [[Actions|Action]]**.

Some weapons deviate from this default:

| [[Weapon]] | Reload Cost |
|---|---|
| Pistol | Half [[Actions|Action]] |
| SMG | Half [[Actions|Action]] |
| Assault Rifle | Half [[Actions|Action]] |
| Shotgun | Full [[Actions|Action]] |
| Sniper Rifle | Full [[Actions|Action]] |
| LMG | Full [[Actions|Action]] + |

### Reloading with an Occupied Offhand

If the offhand holds another firearm or a similarly sized object that does not impede manual dexterity, reloading remains a Half [[Actions|Action]] but requires a **[[Attributes|Grace]] Test DN 12–14**.

- **Success** — reload completes as a Half [[Actions|Action]]
- **Failure** — reload takes a Full [[Actions|Action]] instead

If the offhand holds something that meaningfully blocks manual dexterity — a shield, a large object, anything requiring grip — the character must drop or stow it before reloading.

Traits and disciplines may remove the need for this test entirely. See relevant discipline files.

### Magazine Extensions

Magazine extensions reduce the percentage consumed per trigger pull rather than increasing the pool size. Extensions are additive when stacked.

Each [[Weapon|weapon]] has a single magazine extension slot. Only one extension type may be installed at a time. Extensions are [[Weapon|weapon]] modifications — see [[Weapon Modifications]].

> **Example:** An assault rifle base burst costs 25% per trigger pull. A standard extended magazine reduces consumption by 5%, bringing it to 20% per burst. A high capacity magazine reduces by 10%, bringing it to 15% per burst.

---

## Shotgun Cone Rules

Shotguns do not make standard single target [[Attacks|attack]] rolls at close and medium [[Range & Threat|range]]. Instead they project a cone.

**Cone dimensions:**
- Width: 3 squares at maximum [[Range & Threat|range]] of the band
- Originates from the shooter's square

**[[Damage Types|Damage]] by position:**
- First square of cone — full [[Damage Types|damage]]
- Second square onward — quarter [[Damage Types|damage]]

**Penetration:**
- The first creature in any column of the cone stops penetration for that column
- Creatures directly behind another creature in the same column are not hit

**To hit:** Each creature in the cone makes an Evasion check against the shooter's [[Attacks|attack]] roll. The shooter rolls once and compares to each target individually.

Shotguns have no Extreme [[Range & Threat|range]] band. Beyond Medium the spread renders the [[Weapon|weapon]] ineffective.

---

## Networked vs Non-Networked Firearms

Firearms with a network card integrate with the shooter's augment ecosystem through the [[Pairing Protocol]]. This enables augmented eye targeting assistance and [[Weapon|weapon]] status feedback.

**Networked weapons** are subject to injection [[Attacks|attacks]] and remote interference through the pairing protocol. A [[Weapon|weapon]] that will not fire when needed is a lethal liability.

**Non-networked weapons** are deliberately dumb. No network card, no electronic firing mechanism beyond basic function. They cannot be interfered with remotely. Experienced operators often pay a premium for this property.

See [[Pairing Protocol & Network Security]] for full hacking and injection rules.

---

*See [[Segmented Body]], [[Ranged Attacks]], [[Weapon Modifications]], [[Pairing Protocol & Network Security]], [[Cyberpunk Armour]].*
