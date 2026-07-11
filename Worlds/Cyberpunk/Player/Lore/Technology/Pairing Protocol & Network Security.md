---
tags: [technology, security, network, pairing, augments]
---

# Pairing Protocol & Network Security

*The universal connection standard. What it enables, what it exposes, and how people get killed through it.*

---

## The Protocol

The pairing protocol is a universal network standard used across all connected devices — augment network cards, conventional electronics, building systems, vehicles, consumer devices. It predates SOMA and was adopted by SOMA rather than invented by it. The same way TCP/IP works across devices with completely different hardware and operating systems, the pairing protocol works across the full range of connected technology regardless of what's running underneath.

This universality is the point. A SOMA framework network card, a proprietary framework network card, a conventional device with no biological component — all speak the same protocol. Augmentation status is irrelevant to whether you can pair. What is relevant is whether you have a network card, which requires a framework, which requires SOMA or proprietary installation.

**Implication:** a truly unaugmented person — no framework, no network card — cannot pair with anything and is therefore immune to the entire class of network-mediated attack. Their vulnerability profile is entirely physical rather than digital. This is not universally a disadvantage.

---

## How Pairing Works

Pairing is a mutual authentication handshake between two devices. Both parties must initiate or accept the connection — a device cannot be paired with unilaterally against the resistance of both endpoints. The user controls what they pair with and what permissions they grant to each paired device.

Permissions are tiered — analogous to accepting necessary versus all cookies. A device might be granted:
- Presence awareness only — the paired device knows you are connected but nothing else
- Command receipt — you can send instructions to the device
- Status read — the device can report its state to you
- Data access — the device can read specific data from your MPU via network card relay
- Full biometric access — the device receives physiological data as permitted

Each paired relationship has its own permission set. A paired television has different access than a paired building leader agent.

---

## Spokesless Interaction

The pairing protocol combined with the framework's NI and NN enables interaction without physical input or speech. Intended commands form in the user's mind, the NI reads the relevant neural signals, the NN interprets them as intent, the MPU formats the instruction, and the NC transmits it to the paired device.

In practice for most users this means turning on a television, adjusting climate systems, or sending a message without touching anything. For users paired with a building leader agent it means the building responds to thought. For users paired with a vehicle it means driving through intention rather than physical input.

This is the normalised baseline in middle and upper tier New Halcyon. The friction of having to physically interact with devices feels archaic to people who have lived with spokesless control for years.

---

## The Injection Attack

The pairing protocol's openness is its vulnerability. Any device that can be paired can potentially carry a malicious payload in its firmware — code that executes through the legitimately established connection rather than bypassing the connection's security.

This is the augment equivalent of SQL injection: not attacking the security system directly but exploiting a legitimate input channel to execute illegitimate instructions. The user paired correctly, granted appropriate permissions, and the attack used those permissions against them.

**Delivery vectors:**
- Gifted devices with compromised firmware — the most common attack vector. A device that presents as a legitimate consumer product but contains an injection payload in its software layer
- Secondhand devices with unknown firmware history — not necessarily malicious by intent but carrying vulnerabilities from previous owners or modification
- Devices with forged certification signatures that pass automated security screening

**What an injection can do** depends on what permissions were granted and how sophisticated the payload is:

- **Device manipulation** — controlling paired consumer devices against the user's intent
- **Limb takeover** — injecting false motor commands through the NI/NN pathway, causing augmented limbs to execute [[Actions|actions]] the user did not choose. The user is conscious and aware. They cannot stop it. This is probably the most psychologically significant attack in this world
- **NI overload** — pushing the write channel of the neural interface beyond biological tissue tolerance. The NI limiter (see below) exists specifically to prevent this becoming fatal

---

## Defences

### Device Certification

Manufacturers meeting security standards receive certification signatures that the pairing protocol verifies during handshake. A certified device presents valid credentials; the pairing system flags uncertified devices before connection completes.

Certification is mandatory in practice in wealthy and conglomerate territory — building management systems refuse to allow uncertified device pairings inside their perimeter. In middle districts it is expected but not enforced. In forgotten districts certification is effectively meaningless — secondhand devices have often had firmware modified or certification signatures stripped or replaced with forgeries.

Forged certification signatures are their own black market. A device that passes automated certification screening but contains a payload underneath is more dangerous than an obviously uncertified device.

### Antivirus

An MPU-level process that inspects data arriving through the NC before the MPU executes it. Positioned at the MPU rather than the NC level because the protection needs to cover everything the NC passes to the MPU, not just what arrives at the card.

Antivirus operates on signature matching — known attack patterns are caught, novel attacks are not until they have been observed, analysed, and added to the signature database. This creates a threat intelligence ecosystem: organisations that collect novel injection samples, analyse them, and push signature updates to subscribed systems. Conglomerate security teams do this internally. Independent researchers sell intelligence commercially. Criminal organisations track what has been detected to understand what remains viable.

The update infrastructure is itself a vulnerability. Antivirus receiving signature updates over the network requires trusting the update source — a compromised update pipeline is a legitimate channel into the MPU with elevated trust. Supply chain attacks on security software are a real attack vector.

### NI Limiter

A hardware ceiling on the write channel of the neural interface — a physical constraint that limits what signal the NI can push to biological tissue regardless of what software is instructing it to do. Dumb but reliable in a way software never fully is.

The NI limiter does not need to identify an attack. It monitors the write channel signal level and cuts it if it exceeds the safe threshold. It does not care what the signal is or where it came from. This makes it resistant to novel attacks that antivirus has not yet catalogued — it catches the consequence rather than the method.

**Limitation:** the NI limiter protects against overload attacks on the write channel. It does not protect against limb takeover attacks that use the legitimate motor command pathway rather than overloading the NI. Those are caught by antivirus if the signature is known, and pass through if it is not.

### Network Card Removal

The most complete defence against network-mediated attacks is removing the NC entirely. No NC means no pairing capability, no wireless injection surface, no antivirus required for wireless vectors.

The cost is complete disconnection from the pairing ecosystem — no spokesless device control, no building system interaction, no wireless communication through the augment stack. A significant functional reduction in an environment built around network connectivity.

For Greyback Company personnel and others whose operational security justifies the tradeoff, NC removal is a standard security measure rather than an extreme one. They retain their full augment capability in every other dimension while closing the wireless attack surface entirely.

---

## The Wired Port Vulnerability

The framework charging port is also a data transfer port. A wired connection to the charging port is a physical-layer access point that bypasses wireless security measures entirely — it does not go through the NC's wireless pairing protocol.

For operators who have removed their NC to close the wireless surface, the wired port remains. Physical access to the port — which requires proximity, usually requires the target to be incapacitated or cooperative — is the remaining attack vector.

Antivirus still inspects data arriving through the wired port before MPU execution. The NI limiter still monitors the write channel. The wired attack surface is significantly harder to exploit than wireless — it requires physical access rather than network range — but it is not zero.

---

## The Unaugmented Position

A person with no framework has no network card and cannot pair with any device. They are invisible to the pairing protocol entirely — not an unknown device, not an uncertified device, simply absent from the system.

This means:
- No injection attack surface of any kind
- No surveillance through paired device networks
- No spokesless device interaction
- No building management system relationship
- Payment through physical means only
- Communication through physical or conventionally networked devices only

In New Halcyon's infrastructure, genuine disconnection accumulates friction everywhere. The city assumes connectivity. An unaugmented person navigates that friction daily as the price of their attack surface immunity.

Some pay it deliberately. Some cannot afford the alternative. The reasons are different; the technical position is identical.

---

*See [[Framework]], [[Building Management Systems]], [[Weapons Technology]], [[Quantum & Solid State Batteries]], [[Network Infrastructure]].*
