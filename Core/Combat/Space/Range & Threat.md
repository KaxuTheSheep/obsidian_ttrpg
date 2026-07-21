---
aliases:
  - Range
---
# Range & Threat
Your **Melee Threat Range** determines how far from your weapon can make a melee **[[Attacks]]** and apply defensive [[Reactions|reactions]] such as **[[Parry]]** or **[[Block]]**.

### Melee Threat Range Formula
`Melee Threat = Natural Range + Weapon Range`
- **Natural Range (NR):**
	  -The distance your body can threaten without a [[Weapon|weapon]].
	- **Default for humanoids: 1 meter**
	- Larger or smaller creatures may have different NR values defined in their entry.
- **[[Weapon]] Range (WR):**
	- A value listed on the [[Weapon|weapon]] as **+X meters**, representing  the extension provided by the [[Weapon|weapon]].

**Example:**
A humanoid (NR 1 meter) using a spear (WR +1 meter):
`Melee  Threat = 1 + 1 = 2 meters`

### Engagement States
These distances matter for **control and leverage**, not just whether you _can_ hit.

| Relationship | Meaning | Mechanical Result |
|---|---|---|
| **Both combatants are within each other's Natural Range** | Close Engagement | Neutral — neither gains special bonuses from [[Weapon\|weapon]] length alone. |
| **You are inside their NR but they are _not_ inside yours** | You are _inside their guard_ | Short weapons gain benefit (e.g., **[[Close-Quarters]]**); long weapons may suffer penalties (e.g., **Reach: Close-In Weakness**). |
| **Neither combatant is within the other's Threat Range** | Out of range | No melee [[Attacks\|attacks]] possible. |

### Positioning Example
- Dagger user (NR 1 + WR 0 = **1 square**)
- Spear user (NR 1 + WR 1 = **2 squares**)

| Distance                  | Outcome                                                                                                                                                                                            |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **2 meters**              | Spear can [[Attacks                                                                                       \| attack]], dagger cannot.                                                              |
| **1 meter**               | Both can [[Attacks                                                                                        \| attack]] normally.                                                                    |
| **0 meters (same meter)** | Dagger is inside spear's Natural Range → dagger gains advantage (if using **[[Close-Quarters]]** [[Weapon \| weapon]]), spear suffers Close-In Weakness (if using **Reach** [[Weapon \| weapon]]). |