---
aliases:
  - Movement
tags:
  - Mechanics/Combat
---
In this system, creatures and characters may have access to various types of movement. Each type represents a different mode of travel with its own mechanical and narrative implications. If a character does not have a value in a movement type, they cannot perform it.

Movement is measured in **meters**. Positions are declared either relatively ("2 meters from this enemy") or absolutely ("this meter"). If your movement falls short of your declared destination, you end at the furthest point along your declared path that your movement allows.

## How Movement Works
Every movement type has two values:

- **Initiation [[Ticks, Priority & Resolution|Priority]]** — when you begin moving, this is your [[Ticks, Priority & Resolution|Priority]] in tick order. Higher Initiation [[Ticks, Priority & Resolution|Priority]] means the moving earlier in the [[Rounds|round]].
- **Travel Rate** — how many meters you move per [[Ticks, Priority & Resolution|Tick]] in time after initiating. More committed movement types initiate slower but cover ground more efficiently.

Low commitment movement like Walking initiates quickly but travels slowly. High commitment movement like Running initiates slowly but covers ground far more efficiently once underway.

These values are listed as baseline humanoid values. Race or species entries in the relevant module modify Travel Rate to reflect faster or slower creatures.

## Movement Type Table

| Movement Type | Initiation [[Ticks, Priority & Resolution\|Priority]]**\| | Travel Rate [[Ticks, Priority & Resolution\|Tick]]                 | [[Actions\|Action]] Cost |
| ------------- | --------------------------------------------------------- | ------------------------------------------------------------------ | ------------------------ |
| Walk          | 10                                                        | 3 meters per [[Ticks, Priority & Resolution\|Tick]]               | Free                     |
| Run           | 8                                                         | 8 meters per [[Ticks, Priority & Resolution\|Tick]]               | Full                     |
| Climb         | 5                                                         | 1.5 meters per [[Ticks, Priority & Resolution\|Tick]]             | Free                     |
| Swim          | 4                                                         | 1.5 meters per [[Ticks, Priority & Resolution\|Tick]]             | Free                     |
| Burrow        | 2                                                         | 1 meter per [[Ticks, Priority & Resolution\|Tick]]                | Free                     |
| Fly           | 5                                                         | 5 meters per [[Ticks, Priority & Resolution\|Tick]]               | Full                     |
| Crawl         | 7                                                         | 1 meter per [[Ticks, Priority & Resolution\|Tick]]                | Free                     |
| Jump          | 8                                                         | 1.5 meters + [[Attributes\|Might]] per Instant<br>1 meter height | Half                     |

## Movement Types

**Walk** Standard movement on flat or gently uneven ground. Quick to initiate but covers ground slowly. Most creatures have a walking distance defined by their species entry in the relevant module.

**Run** An exerted burst of committed movement. Slow to initiate but highly efficient over distance — worth committing to when covering significant ground. Costs a Full [[Actions|Action]].

**Climb** Movement on vertical or difficult surfaces. Requires careful grip and positioning. Interruptions during climbing may require an [[Skills|Athletics]] Test to maintain grip.

**Swim** Movement through water. Difficult to initiate quickly from still water.

**Burrow** Movement through loose earth or similar materials. Very slow to begin. Creatures with Burrow create tunnels that may remain passable for others unless collapsed.

**Fly** Movement through the air. Takes time to launch. Flight may have additional [[Conditions|conditions]] such as requiring hover or avoiding obstacles. Costs a Full [[Actions|Action]].

**Crawl** Slow, deliberate movement while low to the ground or through tight spaces. Initiates quickly — you drop immediately — but covers ground very slowly. May be used for [[Skills|stealth]] or navigating confined areas.

**Jump** A specialised burst movement used to cross gaps or obstacles. Covers its distance instantly at the point of initiation — there is no travel rate. Costs a Half [[Actions|Action]]. Repeating a jump requires re-initiating at [[Ticks, Priority & Resolution|Priority]] 8.

Base jump distance is defined by specPriorityntry. If you have moved at least 3 meters by walking or running immediately before jumping, add your [[Attributes|Might]] in meters to the jump distance.

## Using Movement
- Movement can be taken before, after, or between your Full and Half [[Actions]] each [[Rounds|Round]], allowing flexible tactics.
- Different movement types may be combined within a single [[Rounds|round]], respecting individual distances and [[Actions|Action]] costs.
- You may spend your Reaction during the Resolution Phase to change your movement direction, switch to a different destination, or stop entirely at your current position. See [[Reactions]].

## Difficult Terrain
Difficult terrain — deep water, rubble, dense undergrowth, unstable surfaces — impairs movement. The GM adjudicates the effect based on the environment and the movement type being used. Typical effects include reduced Travel Rate or requiring an [[Skills|Athletics]] Test to move through safely.
