---
aliases:
  - Movement
tags:
  - Mechanics/Combat
---
In this system, creatures and characters may have access to various types of movement. Each type represents a different mode of travel with its own mechanical and narrative implications. If a character does not have a value in a movement type, they cannot perform it.

Movement is measured in **squares**. Positions are declared either relatively ("2 squares from this enemy") or absolutely ("this square"). If your movement falls short of your declared destination, you end at the furthest point along your declared path that your movement allows.

## How Movement Works
Every movement type has two values:

- **Initiation [[Ticks, Priority & Resolution|Priority]]** — wPriorityou begin moving, this is your [[Ticks, Priority & Resolution|Priority]] in thPriorityolution order. Higher Initiation [[Ticks, Priority & Resolution|Priority]] meansPrioritystart moving earlier in the [[Rounds|round]].
- **Travel Rate** — how many squares you move per [[Ticks, Priority & Resolution|Priority]] point Priority after initiating. More committed movement types initiate slower but cover ground more efficiently.

Low commitment movement like Walking initiates quickly but travels slowly. High commitment movement like Running initiates slowly but covers ground far more efficiently once underway.

These values are listed as baseline humanoid values. Race or species entries in the relevant module modify Travel Rate to reflect faster or slower creatures.

## Movement Type Table

| Movement Type | Initiation [[Priority & Resolution|SpePriority| Travel Rate Priority                                  | [[Actions|Action]] Cost |
| ------------- | ---------------- | -------------------------------------------------- | ----------- |
| Walk          | 10               | 3 squares per [[Priority & Resolution|PriorityPriority              Priority          | Free        |
| Run           | 8                | 8 squares per [[Priority & Resolution|Priority]Priority              Priority         | Full        |
| Climb         | 5                | 1.5 squares per [[Priority & Resolution|Priority]]Priority              Priority      | Free        |
| Swim          | 4                | 1.5 squares per [[Priority & Resolution|Priority]] Priority              Priority     | Free        |
| Burrow        | 2                | 1 square per [[Priority & Resolution|Priority]]  Priority              Priority       | Free        |
| Fly           | 5                | 5 squares per [[Priority & Resolution|Priority]]   Priority              Priority     | Full        |
| Crawl         | 7                | 1 square per [[Priority & Resolution|Priority]]    Priority              Priority     | Free        |
| Jump          | 8                | 1.5 squares + [[Attributes|Might]] per Instant<br>1 square height | Half        |

## Movement Types

**Walk** Standard movement on flat or gently uneven ground. Quick to initiate but covers ground slowly. Most creatures have a walking distance defined by their species entry in the relevant module.

**Run** An exerted burst of committed movement. Slow to initiate but highly efficient over distance — worth committing to when covering significant ground. Costs a Full [[Actions|Action]].

**Climb** Movement on vertical or difficult surfaces. Requires careful grip and positioning. Interruptions during climbing may require an [[Skills|Athletics]] Test to maintain grip.

**Swim** Movement through water. Difficult to initiate quickly from still water.

**Burrow** Movement through loose earth or similar materials. Very slow to begin. Creatures with Burrow create tunnels that may remain passable for others unless collapsed.

**Fly** Movement through the air. Takes time to launch. Flight may have additional [[Conditions|conditions]] such as requiring hover or avoiding obstacles. Costs a Full [[Actions|Action]].

**Crawl** Slow, deliberate movement while low to the ground or through tight spaces. Initiates quickly — you drop immediately — but covers ground very slowly. May be used for [[Skills|stealth]] or navigating confined areas.

**Jump** A specialised burst movement used to cross gaps or obstacles. Covers its distance instantly at the point of initiation — there is no travel rate. Costs a Half [[Actions|Action]]. Repeating a jump requires re-initiating at [[Ticks, Priority & Resolution|Priority]] 8.

Base jump distance is defined by specPriorityntry. If you have moved at least 3 squares by walking or running immediately before jumping, add your [[Attributes|Might]] in squares to the jump distance.

## Using Movement
- Movement can be taken before, after, or between your Full and Half [[Actions]] each [[Rounds|Round]], allowing flexible tactics.
- Different movement types may be combined within a single [[Rounds|round]], respecting individual distances and [[Actions|Action]] costs.
- You may spend your Reaction during the Resolution Phase to change your movement direction, switch to a different destination, or stop entirely at your current position. See [[Reactions]].

## Difficult Terrain
Difficult terrain — deep water, rubble, dense undergrowth, unstable surfaces — impairs movement. The GM adjudicates the effect based on the environment and the movement type being used. Typical effects include reduced Travel Rate or requiring an [[Skills|Athletics]] Test to move through safely.
