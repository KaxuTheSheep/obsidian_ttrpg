---
tags:
  - Mechanics
  - Religion
  - Lore
---
Divinity is the expression of a Deity's power through a Follower's soul. Where [[Magic]] is a mage shaping [[mana]] with their own understanding and control, Divinity is a Deity acting through the persistent resonant link formed when a Follower's soul-current synchronises with the Deity's mana construct — see [[Soul]] for the underlying mechanism. The soul remains the Follower's own. The Deity runs alongside it, not through it.

Divinity is only accessible to Followers — characters who have invested all 9 [[Faith]] Points in a single Deity and completed that Deity's personal quest, unlocking the 10th point. See [[Faith]] and [[Blessings]] for how a Follower's passive Blessings work. This document covers the active side of that relationship: **Incantations**.

## Divinity vs Magic
A mage builds a spell through [[Spell Construction]] or learns one institutionally — either way, the framework is theirs, reverse-engineered or absorbed from someone else's understanding of [[mana]]. An Incantation is never built or learned in that sense. It is **given** — granted directly through the Follower Discipline tree as a personal gift from the Deity, representing that Deity's own understanding of their domain made available to someone they have chosen to work through. A Follower does not research an Incantation into existence. They are entrusted with one.

This distinction matters mechanically, not just narratively. Incantations do not fail the way spells do, do not scale the way spells scale, and cannot be taught, copied, or reverse-engineered between characters — not even between two Followers of the same Deity. Two Followers of the Ashen Crown might each hold an Incantation that calls on Glory, but the two are not interchangeable, and neither can hand theirs to the other.

Nothing prevents a Follower from also training as a mage. Incantations and spells are entirely separate systems that a character may draw on independently, side by side, without either interfering with the other.

## Casting an Incantation
Every Incantation is cast the same way:

> **Roll 2d10 + [[Attributes|Resolve]]**, compared against the Incantation's **DN**.

Resolve is the fixed casting Attribute for every Incantation — unlike Flux Casting, there is no choice of Insight, Resolve, or Presence per cast. Divinity is a matter of conviction, not technique.

There is no Control/Manifest split. An Incantation either succeeds outright or it does not. There is no partial success, no Backlash, and no [[Sanity]] cost — the power was never the Follower's own to strain against. What Incantations cost instead is **use**.

### Uses per Rest
Each Incantation has its own charge pool, refreshing on a Rest as defined by the Incantation itself (typically a Short Rest, at GM discretion per Incantation):

> **Uses per Rest = Resolve + N** (minimum 1)

**N** is a flat value set individually for that Incantation when it is created — some Incantations are demanding enough that N is negative, others generous enough that N is a healthy positive number. This mirrors how certain Racial Web abilities scale charges off an Attribute (see the Cindral's *Sustained Burn* for a comparable precedent).

**Every cast consumes one use, whether it succeeds or fails.** This is the entire risk profile of an Incantation: they are safe — no Backlash, no lasting harm, no destabilised soul — but rigid and limited. A Follower who casts carelessly simply runs out. There is nothing to recover mid-Rest and no way to push past the limit; when the charges are spent, the Deity has nothing left to give until the Follower rests.

### Incantations vs Spells at a Glance

| Property | Spells (Flux/Weave) | Incantations |
|---|---|---|
| **Origin** | Researched, taught, or institutionally learned | Granted through the Follower Discipline tree |
| **Casting Attribute** | Insight, Resolve, or Presence (chosen per cast) | Resolve (always) |
| **Resolution** | Control DN / Manifest DN, partial success possible | Single DN, succeed or fail |
| **Cost** | [[Sanity]], scaling with enhancement invested | One use from the Incantation's own charge pool |
| **Failure Consequence** | Backlash — a real, physically unstable magical effect | The charge is spent; nothing else happens |
| **Transferable?** | Yes — taught, copied, reverse-engineered | No — personal to the Follower who was granted it |
| **Preparation** | None (Flux) to full pre-combat setup (Woven) | None |

## Acquiring Incantations
Incantations are Discipline nodes, available only within a Deity's Follower Discipline tree (see [[wip]] for the planned "one branch per Deity" structure), and only once Follower status is reached. A Major-devotion believer sitting at 7–9 Faith Points has no access to Incantations at all, regardless of how strong their Blessing is — Incantations are strictly Follower-gated, in the same way the Blessings document treats Divinity access as a Follower-exclusive unlock.

Because Incantations are granted rather than built, a GM introducing a new one for their table is effectively deciding what that Deity has chosen to entrust, not designing a spell for a player to discover. The Incantation Blueprint Template below exists to keep that decision consistent across Deities, the same way the Spell Blueprint Template in [[Spell Construction]] keeps spells consistent across mages.

## Radiant and Umbral Damage
[[Magic]] is explicit that Radiant and Umbral damage cannot be produced by trained mages regardless of skill, understanding, or mana supply — these forces originate exclusively from Deities and can only be channelled through Followers. In practice, this means any Incantation dealing damage as a core effect will typically deal Radiant or Umbral damage, depending on the Deity's nature, rather than a conventional [[Damage Types|damage type]].

## Spells That Imitate Incantations
A sufficiently determined mage can build a spell that mimics the *utility* of a specific Incantation — a light-suppression spell that behaves something like a Hollow Shade concealment Incantation, for instance. What a mage's spell can never do is reproduce the Incantation's actual mechanics or its Radiant/Umbral output. An imitation spell is still a spell in every respect that matters: it still resolves through Control DN and Manifest DN, still costs Sanity, still risks Backlash on failure, and can still be taught or reverse-engineered by anyone with the aptitude. It simply happens to look similar from the outside. The two systems never merge, no matter how close the flavour gets.

# Incantation Blueprint Template
A template for building a new Incantation. Not every field needs to be filled in for every Incantation — some are simpler than others.

## Incantation Name
**Name:** [Incantation Name]
**Deity:** [Granting Deity]
**Domain Expression:** [Which of the Deity's domains this reflects]
**Type:** [Attack / Utility / Control / Ritual / etc.]

## Core Concept
A short description of what the Incantation *is* — how this expresses the Deity's will through the Follower, not a "natural process being accelerated" the way a spell would be.

## Casting
**DN:** X
**Uses per Short Rest:** Resolve + N *(state N per specific spell)*
**Casting Attribute:** Resolve *(always)*

## Effect
What happens on success.
- Primary effect
- Target rules
- Damage type, if any (Radiant/Umbral as applicable)
- Secondary or lingering effects, if any

## Failure
By default, failure simply consumes the use and nothing else happens. Only deviate from this if the specific Incantation calls for a distinct thematic consequence — and if so, state it here explicitly, since it is *not* the default assumption for Incantations the way Backlash is for Flux spells.

## Notes
Any Deity-specific flavour, restrictions, or narrative conditions tied to this Incantation (e.g. requiring line of sight to a shrine, only functioning at night, requiring the Follower to speak a specific vow aloud).
