---
aliases:
  - Fall
tags:
  - Mechanics
  - Wip
---
When a character falls, they travel downward at a rate of **10m per [[Speed & Resolution|Speed]] step** during the Resolution Phase. Falling [[Damage Types|damage]] bypasses [[Sturdiness]] and is applied directly to [[Blood]].

## Fall [[Damage Types|Damage]]

[[Damage Types|Damage]] is calculated based on total distance fallen.

- Falls of **3m or less** deal no [[Damage Types|damage]].
- For every **6m fallen beyond the first 3m**, the character takes **1d4 Blunt [[Damage Types|damage]]** directly to [[Blood]].
- On landing, the character is knocked **Prone**.

|Total Distance Fallen|Damaging Distance|[[Damage Types|Damage]]|
|---|---|---|
|3m or less|0m|None|
|4–9m|1–6m|1d4|
|10–15m|7–12m|2d4|
|16–21m|13–18m|3d4|
|22–27m|19–24m|4d4|
|28–33m|25–30m|5d4|

Continue the pattern — one additional 1d4 per 6m of damaging distance.

## Catching a Surface

If a climbable or graspable surface is within reach during a fall, the character may attempt to catch it and halt their descent.

Catching a surface is a **Reaction** on the first attempt. Each subsequent attempt costs a **Half [[Actions|Action]]**, allowing up to **6 total attempts** per [[Rounds|round]] across a character's available [[Actions|actions]].

### Catch Test

Roll **2d10 + [[Attributes|Grace]] or [[Attributes|Might]]** against the **Catch DN**.

**Base DN** scales with how many [[Speed & Resolution|Speed]] steps the character has been falling:

|[[Speed & Resolution|Speed]] Steps Fallen|Base DN|
|---|---|
|1|8|
|2|10|
|3|12|
|4|14|
|5+|+2 per additional step|

### Surface Modifier

The surface type modifies the Catch DN.

|Surface Type|DN Modifier|
|---|---|
|Rough natural rock|–3|
|Uneven stone|–2|
|Worked stone|–1|
|Smooth stone|+0|
|Polished stone|+1|
|Fully smooth wall|+3|

### Wetness Modifier

Wet [[Conditions|conditions]] stack with surface type.

|Wetness|DN Modifier|
|---|---|
|Damp|+1|
|Wet|+2|
|Soaking|+3|

> **Example:** A rough natural rock wall that is soaking wet has a net modifier of –3 + 3 = +0. A fully smooth soaking wall is +3 + 3 = +6 added to base DN.

### Failed Catches

Each failed catch attempt reduces the DN by **2** for all subsequent attempts, representing the character scrabbling and slowing their descent slightly even without fully catching.

A failed catch deals **full falling [[Damage Types|damage]] for the total distance fallen so far**, calculated using the formula above.

### Successful Catches

On success, the fall ends immediately. The character is stable and hanging at that surface. No further tests are required to hold on. The character may climb, reposition, or take other [[Actions|actions]] from this position normally.

## Controlled Descent

A character descending under magical or equivalent control — such as a spell that governs fall [[Speed & Resolution|speed]] — negates all falling [[Damage Types|damage]] and allows the character to choose their landing point freely. The specific means of controlled descent defines its own rules.
