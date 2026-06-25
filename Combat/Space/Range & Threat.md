---
aliases:
  - Range
---
# Range & Threat
Your **Melee Threat Range** determines how far from your token you can make melee **[[Attacks]]** and apply defensive [[reactions]] such as **[[Parry]]** or **[[Block]]**
### Melee Threat Range Formula
`Melee Threat = Natural Range + Weapon Range`
- **Natural Range (NR):**  
    The [[Movement Types|distance]] your body can threaten without a weapon.  
    **Default for humanoids: 1.0 m**  
    Larger or smaller creatures may have different NR values.
- **Weapon Range (WR):**  
    A value listed on the weapon as **+Xm**, representing the extension provided by the weapon.

**Example:**  
A [[human]] (NR 1.0 m) using a spear (WR +1.5 m):
`Melee Threat = 1.0 m + 1.5 m = 2.5 m`
### Engagement States
These distances matter for **control and leverage**, not just whether you _can_ hit.

|Relationship|Meaning|Mechanical Result|
|---|---|---|
|**Both combatants are within each other’s Natural Range**|Close Engagement|Neutral — neither gains special bonuses from weapon length alone.|
|**You are inside their NR but they are _not_ inside yours**|You are _inside their guard_|Short [[weapons]] gain benefit (e.g., **[[Close-Quarters]]**); long [[weapons]] may suffer penalties (e.g., **Reach: Close-In Weakness**).|
|**Neither combatant is within the other’s Threat Range**|Out of range|No melee [[attacks]] possible.|

### Positioning Example
- Dagger user (NR 1.0 + WR 0.35 = **1.35 m**)
- Spear user (NR 1.0 + WR 1.5 = **2.5 m**)

| [[Movement Types\|Distance]] | Outcome                                                                                                                                                                             |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **2.5 m**                    | Spear can [[Attacks\|attack]], dagger cannot.                                                                                                                                       |
| **1.2 m**                    | Both can [[Attacks\|attack]] normally.                                                                                                                                              |
| **0.5 m**                    | Dagger is inside spear’s **Natural Range** → dagger gains advantage (if using **[[Close-Quarters]]** [[weapons]]), spear suffers **Close-In Weakness** (if using **Reach** weapon). |