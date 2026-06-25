---
aliases:
  - Movement
tags:
  - Mechanics/Combat
---
In [[Solasfall]], creatures and characters may have access to various types of movement. Each type represents a different mode of travel with its own mechanical and narrative implications. If a character does not have a value in a movement type, they cannot perform it.
Movement is measured in metres. There are no grids or squares — distances are continuous. Positions are declared either relatively ("2m from this enemy") or absolutely ("here"). If your movement falls short of your declared destination, you end at the furthest point along your declared path that your movement allows.

## How Movement Works
Every movement type has two values:

- **Initiation [[Speed & Resolution|Speed]]** — when you begin moving, this is your [[Speed & Resolution|Speed]] in the resolution order. Higher Initiation [[Speed & Resolution|Speed]] means you start moving earlier in the [[Rounds|round]].
- **Travel Rate** — how far you move per [[Speed & Resolution|Speed]] point spent after initiating. More committed movement types initiate slower but cover ground more efficiently.

Low commitment movement like Walking initiates quickly but travels slowly. High commitment movement like Running initiates slowly but covers ground far more efficiently once underway.
These values are listed as [[human]] baseline. [[Races|Race]] files modify Travel Rate to reflect faster or slower species.

## Movement Type Table

| Movement Type | Initiation [[Speed & Resolution\|Speed]] | Travel Rate                            | [[Actions\|Action]] Cost |
| ------------- | ---------------------------------------- | -------------------------------------- | ------------------------ |
| Walk          | 10                                       | 3m per [[Speed & Resolution\|Speed]]   | Free                     |
| Run           | 8                                        | 8m per [[Speed & Resolution\|Speed]]   | Full                     |
| Climb         | 5                                        | 1.5m per [[Speed & Resolution\|Speed]] | Free                     |
| Swim          | 4                                        | 1.5m per [[Speed & Resolution\|Speed]] | Free                     |
| Burrow        | 2                                        | 1m per [[Speed & Resolution\|Speed]]   | Free                     |
| Fly           | 5                                        | 5m per [[Speed & Resolution\|Speed]]   | Full                     |
| Crawl         | 7                                        | 1m per [[Speed & Resolution\|Speed]]   | Free                     |
| Jump          | 8                                        | 1.5m + Might per Instant<br>1m height  | Half                     |
## Movement Types

**Walk** Standard movement on flat or gently uneven ground. Quick to initiate but covers ground slowly. Most creatures have a walking distance defined by their [[Races|race]].

**Run** An exerted burst of committed movement. Slow to initiate but highly efficient over distance — worth committing to when covering significant ground. Costs a Full [[Actions|Action]].

**Climb** Movement on vertical or difficult surfaces. Requires careful grip and positioning. Interruptions during climbing may require an [[Skills|Athletics]] Test to maintain grip.

**Swim** Movement through water. Difficult to initiate quickly from still water.

**Burrow** Movement through loose earth or similar materials. Very slow to begin. Creatures with Burrow create tunnels that may remain passable for others unless collapsed.

**Fly** Movement through the air. Takes time to launch. Flight may have additional [[conditions]] such as requiring hover or avoiding obstacles. Costs a Full [[Actions|Action]].

**Crawl** Slow, deliberate movement while low to the ground or through tight spaces. Initiates quickly — you drop immediately — but covers ground very slowly. May be used for [[Skills|stealth]] or navigating confined areas.

**Jump** A specialised burst movement used to cross gaps or obstacles. Covers its distance instantly at the point of initiation — there is no travel rate. Costs a Half [[Actions|Action]]. Repeating a jump requires re-initiating at [[Speed & Resolution|Speed]] 8.

Base jump distance is defined by [[Races|race]]. If you have moved at least 3m by walking or running immediately before jumping, add your Might in metres to the jump distance.

## Using Movement
- Movement can be taken before, after, or between your Full and Half [[Actions]] each [[Rounds|Round]], allowing flexible tactics.
- Different movement types may be combined within a single [[Rounds|round]], respecting individual distances and [[Actions|Action]] costs.
- You may spend your Reaction during the Resolution Phase to change your movement direction, switch to a different destination, or stop entirely at your current position. See [[Reactions]].

## Difficult Terrain
Difficult terrain — deep water, rubble, dense undergrowth, unstable surfaces — impairs movement. The GM adjudicates the effect based on the environment and the movement type being used. Typical effects include reduced Travel Rate or requiring an [[Skills|Athletics]] Test to move through safely.