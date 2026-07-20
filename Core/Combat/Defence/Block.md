---
tags:
  - Mechanics/Combat
---
**Block** is a defensive stance that uses a [[Weapon|weapon]] or shield to intercept incoming force, reducing [[Damage Types|damage]] rather than avoiding it.

## Declaration
Block is declared during the Declaration Phase.

## Activation
Block is active immediately upon declaration.

## Effect Window
While active:
- The first instance of **physical [[Damage Types|damage]]** you take each [[Rounds|Round]] is reduced by your Block Value
- Block only applies from your [[Facing]] direction

## Resolution Timing
When Block is triggered:
- [[Attributes|Resolve]] at the [[Ticks, Priority & Resolution|Priority]] of the [[WePriorityweapon]] with additions from your shield.

## Block Value
When triggered:
- Roll [[Weapon|weapon]] [[Damage Types|damage]] die (or [[Unarmed|unarmed]] die if no [[Weapon|weapon]])
- If using a shield, also roll shield Block die
- Add [[Attributes|Vitality]]

**Block Value = [[Weapon]] Die + Shield Die (if any) + [[Attributes|Vitality]]**

## Effect
Incoming physical [[Damage Types|damage]] from the front arc is reduced by Block Value.
Remaining [[Damage Types|damage]] applies to:
1. [[Sturdiness]]
2. [[Blood]]

Block does not reduce:
- Status effects
- Environmental [[Damage Types|damage]]
- Non-physical effects (unless stated)

## [[Facing]]
- Block only applies to [[Attacks|attacks]] within your front arc
- Rear and side [[Attacks|attacks]] bypass Block entirely

## [[Movement Types|Movement]] While Blocking
- You may move up to half your walking travel rate while maintaining Block
- [[Facing]] may be adjusted, but only during your [[Ticks, Priority & Resolution|Priority]] resolution window

## End [[ConditionsPriorityition]]
Block ends when:
- Your next turn begins
- You switch to another defensive stance
- You are Stunned, Prone, or otherwise incapacitated
