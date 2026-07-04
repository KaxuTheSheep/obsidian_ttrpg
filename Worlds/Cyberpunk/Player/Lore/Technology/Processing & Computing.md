---
tags: [technology, computing, processing, hardware]
---

# Processing & Computing

*How processors actually work in 2100. Grounded in real research directions, extrapolated forward.*

---

## The Core Advance — 3D Stacking

The fundamental shift from present-day computing is vertical. Rather than etching circuits flat on a silicon wafer and hitting the physical limits of miniaturisation, processors in 2100 are built in three dimensions — chiplets stacked vertically and connected through their faces rather than laid side by side on a flat plane.

This is not a speculative leap. 3D stacked chiplets already exist in early form today. By 2100 the architecture is mature, dense, and the engineering problems that limited early versions are solved.

**What 3D stacking produces:**
- Far higher transistor density per unit volume than any flat architecture can achieve
- Shorter signal paths between processing units — less distance means less latency and less power loss in transmission
- Specialised layers optimised for specific functions stacked together — memory adjacent to processor, different processor types layered by task

---

## Transistor Architecture — Gate-All-Around

3D stacking addresses the physical organisation of chips. The transistors themselves have also evolved.

Current transistors use FinFET architecture — a fin-shaped 3D gate that wraps around the channel on three sides, providing better gate control than flat predecessors and reducing quantum tunnelling leakage. Gate-All-Around transistors extend this — the gate wraps the channel on all four sides, providing maximum control and allowing transistors to be pushed smaller before tunnelling becomes fatal to reliable switching.

By 2100 the successor to Gate-All-Around is probably vertical pillar transistors — the channel runs vertically rather than horizontally, and the gate surrounds it entirely. These can be stacked in genuine 3D arrangements rather than just etched on a flat plane, which is what makes the density of 2100 processors possible.

**Why this matters:** transistors that can be switched off more completely waste less power as leakage and can be made smaller without becoming unreliable. Both feed directly into the power efficiency and performance of [[Quantum & Solid State Batteries|battery-powered]] augment systems.

---

## Interconnects — Photonic Data Buses

The bottleneck in 3D stacked processors is communication between layers. Copper interconnects — the wiring between components — have resistance and capacitance that limits how fast data can move and generates heat proportional to data rate. At the density of 2100 processors this becomes the limiting factor.

The solution is photonic interconnects between chiplet layers — light rather than electrons carrying data between processing nodes. Light in a photonic waveguide moves faster than electrons in copper, generates less heat in transit, and can carry more data simultaneously through wavelength multiplexing — multiple data streams on different light frequencies sharing the same physical channel.

The logic operations themselves — the actual computation — still happen at electro-optical junctions where photonic and electronic systems meet. Light carries data between nodes; the computation happens at the node. This is the resolution of the pure photonic computing problem: you don't need all-photonic logic gates, you need photonic data movement between electronic logic elements.

---

## Materials — Graphene and Diamond

Two materials solve specific problems that silicon and copper cannot address at 2100 densities.

**Graphene as interconnect material**
Graphene is extraordinarily electrically conductive — far more so than copper — and can be deposited in extremely thin layers. In 2100 processors graphene serves as the wiring between transistors rather than the transistors themselves. Its high conductivity means less resistance, less heat generation, and faster signal propagation at the local level within a chiplet layer.

Note: graphene cannot replace silicon as the transistor material itself because it lacks a natural bandgap — it conducts too well to be switched off cleanly. Engineered bandgap graphene in nanoribbon form is a research direction but remains a specialist rather than universal material by 2100.

**Diamond for thermal management**
3D stacking creates a heat problem — buried layers cannot dissipate heat the way surface components can. Diamond has extraordinary thermal conductivity, higher than any other material, and is electrically insulating — it conducts heat without conducting electricity, which is exactly what a heat spreader needs.

Lab-grown diamond is already used in specialist electronics today. By 2100 diamond heat spreader layers and diamond substrates are standard in high-tier processors including high-end [[Framework Tiers|MPU]] configurations. Sapphire serves a similar role as an electrically insulating, thermally stable substrate material in certain configurations.

A high-tier MPU in this world is approximately: Gate-All-Around or pillar transistors, graphene interconnect mesh within layers, photonic buses between layers, diamond or sapphire substrate for thermal management. All of these are extrapolated from real present-day research.

---

## The MPU Placement Logic

The MPU in augment systems is housed in the chest cavity. This is a thermal decision as much as an anatomical one — the chest cavity provides the largest available volume for heat management infrastructure and surgical access. Signal travel between the MPU and brain-adjacent augments has a measurable round trip delay at this distance, which premium augment manufacturers address through local processing in limb and sensory augments rather than by relocating the MPU.

See [[Core Stack]] for the full MPU dependency chain.

---

## Class Implications

Processor technology in this world is not uniformly accessible. The materials and architectures described above represent high-tier MPU configurations — what conglomerate employees and wealthy residents can access through premium frameworks.

Mid-tier frameworks run earlier generation 3D stacked designs without the photonic interconnect layer. Budget and salvage frameworks run flat or early 3D architectures with copper interconnects and silicon substrates — functional but generating more heat, consuming more power, and processing more slowly than current-generation equivalents.

The performance gap between a Tier 1 and Tier 5 framework is not just a number. It is a different class of hardware at the materials level.

---

*See [[Framework Tiers]], [[Quantum & Solid State Batteries]], [[Building Management Systems]], [[Augment System Overview]].*
