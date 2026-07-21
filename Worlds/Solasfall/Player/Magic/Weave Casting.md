---
tags:
  - Mechanics
  - Magic
  - Draft
---
Weave Casting is the construction of a magical circle that resolves [[mana]] through fixed geometry rather than live control. Where Flux Casting is shaped moment to moment, a Weave is *drawn* — and however well or badly it is drawn is how it will always behave. There is no partial success band and no Backlash. The risk is not that the spell misfires violently; it is that the spell is permanently, quietly wrong in some way, forever.

## Two Modes

### Woven (Prepared)
A Woven circle is drawn entirely outside combat, using the rules below with no external interference possible. No Reaction-based interruption exists. The only risk is the caster's own skill at the moment of drawing.

### Drawn Weave (Mid-Combat)
A Drawn Weave uses the same construction rules, but under pressure. Every time the caster is successfully attacked while mid-draw:
1. Immediately make a **Defect Test** (see below), even if the draw isn't finished.
2. Add **+1 Tick step** to remaining draw time.

This is the entire risk/reward trade against Flux Casting: no Backlash, ever — but time, exposure, and the compounding chance of a permanent flaw instead.

## Core Values
Every Weave circle is defined by the same two values used in Flux Casting, reinterpreted for Weave's purposes:

- **Control DN** — governs **Time**. How many Priority steps the draw takes to complete.
- **Manifest DN** — governs **Defects**. The target number for the Defect Test.

## Draw Time
Drawing starts at **Priority 16** each round it is worked on.

- **Draw Duration (in Priority steps) = Control DN.**
- If Control l DN ≤ 16, the draw completes within the round, resolving at Priority `16 − Control DN`.
- If Control DN > 16, the caster spends the entire round drawing without finishing. Carry the excess (`Control DN − 16`) into the next round as a fresh countdown starting again from Priority 16. Repeat until fully paid off.

Higher Control DN means a longer, more exposed draw. Complex, powerful circles are safer once activated but dangerous while still being drawn — this is the core tension of Drawn Weave specifically. Woven circles, drawn outside combat, don't feel this tension at all; Time still applies, but nothing can interrupt it.

## Defect Test
**Roll:** `2d10 + Insight + Grace` vs **Manifest DN**.

Insight and Grace here are flat modifiers only — Insight does not govern enhancement precision the way it does in Flux Casting, and no Attribute currently offsets or caps how much Manifest DN climbs with Enhancement investment. More power always means a harder Defect Test, full stop.

| Margin vs Manifest DN | Severity |
|---|---|
| Meets or exceeds by 5+ | None — the circle performs exactly as designed. |
| Meets exactly | Minor — a cosmetic or flavour-only defect. |
| 1–4 below | Moderate — a persistent mechanical flaw. |
| 5+ below | Severe — a significant, potentially dangerous flaw. |

The Defect Test is rolled once on completion for a Woven circle or an uninterrupted Drawn Weave. For an interrupted Drawn Weave, it is **re-rolled on every interruption**, and the **worst result stands** — each reroll also carries its own +1 Priority step penalty on top of whatever was already accrued.

## Defects Are Permanent
Once a defect is determined for a specific drawn circle, it is fixed. It is not rerolled on future activations of the same Woven item, and it is not "typical" of that spell in general — two mages who each draw the same spell can end up with entirely different, individually flawed versions. A defect is a property of *that one drawing*, not of the spell as a concept.

Defects should be **spell-specific and thematically consistent** — the same instruction that governs Backlash tables in Flux Casting. A Fireball's defects should look like fireball problems: curving trajectories, mistimed detonation, inverted heat. A Weave with no plausible "gone wrong" version for a given defect type shouldn't be forced into one.

### Suggested Defect Examples
*(Illustrative only — defects should be built per-spell, the same way Backlash examples are per-spell in Spell Construction.)*

- **Minor:** the projectile curves slightly on release; the light is a faintly wrong hue; a soft audible hum on activation that defeats Silent-equivalent uses.
- **Moderate:** effective range reduced by a fixed amount; one variable is locked slightly off from the intended value; a short, fixed delay between trigger and effect.
- **Severe:** the effect triggers centred on the caster instead of the target; the damage type partially inverts; the area or radius only partially completes, leaving an inconsistent gap.

## Enhancement
Each Enhancement Point invested in a Weave circle:

- **+1 to Control DN** — slower draw, more exposure to interruption.
- **+2 to Manifest DN** — harder Defect Test, greater likelihood of a flaw.

This is numerically identical to Flux Casting's Enhancement scaling — the same +1/+2 relationship — reinterpreted here as Time and Defect risk rather than Stability and Completion. There is no upper limit on investment, only compounding time cost and compounding defect risk.

## Cost
Weave Casting has no [[Sanity]] cost. Its only costs are:

- **Time** (Control DN, expressed as Priority steps)
- **Risk of a permanent Defect** (Manifest DN, tested via the Defect Test)

This distinguishes it from Flux Casting, whose primary drawback is Backlash, and from Incantations, whose cost is limited uses per Rest.

## Weave Blueprint Fields
When designing a new Weave circle, use the standard Spell Blueprint Template from Spell Construction, replacing the Flux-specific Base Stats block with:

```
## Weave Casting Data
**Control DN:** X   (governs draw time — Priority steps to complete)
**Manifest DN:** X  (Defect Test target: 2d10 + Insight + Grace)
**Enhancement:** Each point invested adds +1 Control DN and +2 Manifest DN.
**Suggested Defects:**
  - Minor: ...
  - Moderate: ...
  - Severe: ...
```