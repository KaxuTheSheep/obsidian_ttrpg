---
tags: [technology, network, infrastructure, communications]
---

# Network Infrastructure

*How data moves across New Halcyon. Two layers — backbone and local. Coverage inequality is physical, not just economic.*

---

## The Two Layer Model

New Halcyon's network infrastructure operates on two distinct layers that serve different purposes and have different coverage profiles.

---

## Layer One — Vacuum Optical Trunks

The backbone of the city's network is a system of vacuum optical conduits running beneath the city through utility corridors and dedicated infrastructure tunnels. These carry data between major nodes — district switching points, conglomerate facilities, the CFA port infrastructure, and connection points to the wider Federal States network.

**The physics:** conventional fibre optic cable guides light through glass, which slows it to roughly two thirds of its vacuum Priority due to the refPriorityve index of the medium. Hollow-core photonic crystal fibre — or purpose-built vacuum conduit with periodic focusing elements — guides light through air or near-vacuum, recovering that Priority loss. The latePrioritymprovement over conventional fibre is approximately 30-50% for equivalent distances. At city scale this is meaningful for high-frequency financial transactions, real-time military coordination, and conglomerate logistics systems where milliseconds matter.

**The focusing problem:** light does not travel in a perfectly straight line indefinitely without medium to guide it. Vacuum optical trunks require periodic focusing elements — reflective or refractive elements inside the conduit at regular intervals to keep the beam coherent over long distances. These are passive optical elements rather than active electronics, making them reliable and low-maintenance, but they are physical infrastructure that must be installed and occasionally serviced.

**Coverage:** the trunk network passes under most of New Halcyon, including forgotten districts. The trunk does not care about the district above it — it was routed for geographic and engineering reasons, not social ones. A forgotten district may have a high-capacity trunk running beneath it with no local infrastructure tapping into it. The cable is there. The connection point is not.

---

## Layer Two — Terahertz Wireless

Local coverage — the last metre to last kilometre — is handled by terahertz wireless rather than the millimetre-wave systems of present-day 5G. Terahertz frequencies offer significantly higher bandwidth than current wireless standards and lower latency than conventional radio, at the cost of shorter effective range and higher atmospheric absorption.

**Why terahertz requires dense infrastructure:** the shorter range of terahertz signals means more base stations closer together to maintain coverage. A terahertz network in a dense urban environment needs antenna nodes every few hundred metres at most, integrated into building surfaces, street furniture, and infrastructure elements. Installing and maintaining this density of hardware requires ongoing investment that only occurs where someone is paying for it.

**Coverage inequality:** terahertz coverage density tracks conglomerate territory and investment directly. In conglomerate core districts the coverage is dense, redundant, and high bandwidth — the infrastructure is a business asset. Moving outward, coverage becomes patchier as the investment rationale weakens. In forgotten districts there may be no terahertz coverage at all, or isolated nodes around specific commercial operations that paid for their own infrastructure.

Residents in forgotten districts with no terahertz coverage fall back to older, lower-bandwidth wireless standards that propagate further on less infrastructure — slower, higher latency, but present where terahertz is not. The difference is felt in what applications are usable. High-bandwidth applications — rich media, real-time paired device communication, building system interaction — require terahertz. Basic connectivity on older standards is functional but limited.

---

## The Co-Dependency Problem

The vacuum optical trunk network and the local wireless coverage layer are operationally co-dependent in a way that compounds district inequality.

The terahertz antenna nodes that provide local coverage connect to the trunk network to move data beyond their immediate area. No trunk connection means a local terahertz node is an island — it can handle communication within its own coverage area but cannot reach anything outside it. A forgotten district that somehow acquired terahertz infrastructure would still have limited utility without a trunk tap point.

More critically: both layers require power infrastructure to operate. A power disruption in a district does not just affect lights and appliances — it takes down local wireless coverage and potentially the active elements in any trunk tap points in the area simultaneously. Three infrastructure systems failing together rather than independently. In wealthy districts backup power and redundant infrastructure prevent this cascade. In forgotten districts it happens regularly and nobody is contractually obligated to fix it.

---

## Security Implications

The trunk network's physical routing through the city creates specific vulnerabilities. Access to a trunk conduit provides access to the data moving through it — not easily, given encryption, but physically. Certain factions with knowledge of trunk routing and physical access capability have the ability to place monitoring hardware at trunk access points. Whether any faction currently does this is not publicly known.

Trunk tap points — where the backbone connects to local distribution infrastructure — are the most physically accessible part of the system and therefore the most monitored. Conglomerate-owned tap points have physical security commensurate with their importance. Tap points in transitional or forgotten areas may have no physical security at all beyond the locked access hatch they were installed behind decades ago.

---

*See [[Pairing Protocol & Network Security]], [[Building Management Systems]], [[Energy Infrastructure]], [[Communications & Broadcasting]].*
