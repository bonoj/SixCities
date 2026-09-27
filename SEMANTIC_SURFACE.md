# Six Cities — Semantic Surface

## What this artifact is

Six Cities is a standalone browser-resident Three.js civilization experiment. It asks whether six functionally different city-machines can participate in one shared physical world strongly enough that their combinations produce behavior that was not individually storyboarded.

The executable is the authority for present capability. This document interprets the meaning earned by that executable: its shared truths, ownership boundaries, capabilities, useful failures, and limits. Historical comments embedded in `index.html` preserve how those meanings were discovered.

This realization was generated independently from a frozen semantic contract and perceptual reference evidence, without access to the predecessor Foundry implementation. Similar mechanisms are therefore not recovered implementation lineage; they are evidence of what survived semantic transmission.

## The governing idea

There is **one civilization in one world**, not six isolated demonstrations.

The six cities are differentiated by verbs rather than by a shared chassis with interchangeable machinery. Their forms, interfaces, storage, and behavior are consequences of what each city currently does. Shared civilization identity comes afterward through material and construction language.

The observer is primarily an investigator. The useful interactions perturb real state: move a city, interrupt infrastructure, alter terrain, isolate a route, change support, or watch supply and backpressure propagate. The world should remain causally active without requiring the observer to trigger six canned demos.

## Authorities

### Terrain owns substrate truth

`terrain` owns a mutable sampled heightfield, support, and extraction. Excavation changes the rendered and collidable substrate. Removed terrain becomes quantified material; it does not replenish itself, and a lower bedrock bound exists.

Actors may cause or request deformation. They do not privately own the resulting terrain truth.

### Matter owns conserved material truth

`world.lots` owns exposed, contained, carried, routed, and ballistic matter.

A lot carries:

- exact quantities of four mineral/aggregate constituents;
- processing stage;
- meaningful location or owner;
- origin witnesses.

Splitting partitions quantity. Combining sums it. Separation preserves it. Productive cooldowns do not create matter.

Initial inventory plus extracted terrain accounts for all extant material. Runtime conservation auditing is part of the apparatus; a conservation failure stops execution visibly.

Origin witnesses are sets, not an exact per-origin mass ledger. Constituent quantities are exact.

### Physics owns support and gravity

Loose lots, launched loads, and whole cities are subject to shared gravity where that consequence matters.

Cities are atomic supported bodies at the simulation level. Support is sampled from terrain; cities may settle when that support changes. They do not currently tilt, fracture, or simulate district-scale structural mechanics.

Powered drone flight and ring transport explicitly provide lift rather than silently opting out of gravity.

### The world owns the transport graph

Cities expose capabilities and interfaces. They do not own private pairwise knowledge of other named cities.

Ring freight is hub-mediated. Every inter-city ring-freight journey passes through Link City. Dijkstra resolves currently available paths, but endpoints do not create direct peer-to-peer conduits.

Terrain clearance, endpoint power, interface availability, link state, capacity, and compatible material stage can affect whether transport is possible.

In-flight material is not permitted to teleport when topology changes. It attempts physical recovery through an available adjacent interface; where that is impossible, existing spill/fall behavior remains the consequence.

### The observer owns investigation

Camera, pause/speed, selection, relocation, and investigation interventions belong to the observer layer.

Selection does not move the camera. Relocation moves the container and its contents, thereby changing actual spatial reach and route availability. Undercutting terrain is actual extraction and therefore tests support rather than playing an animation.

## The six capabilities

### Launcher

Launcher consumes usable processed material and commits a conserved 75-unit packed payload to a ballistic delivery.

Numerical aim and physical actuation are separate. The rotating accelerator must yaw and pitch into alignment before firing, and the visible muzzle is the launch origin. Projectile-only temporal scaling changes traversal time while preserving the accepted spatial parabola.

Launches currently occur at an irregular autonomous cadence when sufficient material is available. The cadence is presentation rhythm, not evidence of intelligent demand scheduling.

Landed cargo becomes recoverable raw material with its original constituent quantities. This is not combat and is not a disguised resource sink.

The three reclamation grounds remain experimental scaffolding. The artifact has **not** earned a deep civilization-level reason for ballistic delivery.

### Drone City

Drone City maintains twenty-four collectors.

Collectors claim exposed world matter, approach it, physically carry authoritative cargo, deliver that cargo through the civilization's earned intake, and return home before beginning another work cycle.

Collection is authorized by ownership plus meaningful local proximity. Exact mathematical docking against a presentation witness is not required.

Destination and admission are distinct. A loaded drone can travel toward the correct intake even when that intake cannot yet accept its cargo; capacity governs unloading rather than whether the drone departs. Waiting drones are admitted locally and sequentially rather than reserving aggregate future capacity and accidentally synchronizing the swarm.

Drone City is **not** a ring-freight endpoint and owns no generic authoritative material buffer merely because it is a city.

### Unzip

Unzip is the civilization's explicit intake for newly collected world material.

Ground → drone → Unzip is the current collection boundary. Drones do not bypass it by selecting some other city merely because that city has spare capacity.

Unzip separates raw mixed lots into single-constituent sorted lots. Four architectural output witnesses make that classification legible.

Its processing and forwarding cadence has deliberately been tuned so that Unzip expresses processing without becoming the governor of the entire civilization's rhythm. That tuning does not change conservation or material identity.

### Thumper

Thumper excavates mutable terrain.

Its supported swept arm and reciprocating head act at the same world location as the terrain cut. Excavation therefore changes world substrate rather than incrementing a private resource counter.

Available exposed stock regulates work. Reach, bedrock, and accumulated loose material can stop productive excavation.

Thumper's output exists directly as exposed world-space matter. Thumper owns neither generic city storage nor a ring-freight interface.

### Reservoir

Reservoir owns bounded material storage and packaging behavior.

It retains exact constituent amounts and origin witnesses. Its visible fill is a **persistent spatial witness** of inventory history rather than a frame-by-frame repacking. Incoming composition accretes as strata inside the hemispherical containment envelope; withdrawals peel compatible visible history from the newest side.

That spatial history is presentation, not a claim of granular rigid-body accessibility.

Internal sorted-to-packed processing may change packaging without visually shuffling unchanged composition. Mixed recoverable loads preserve their constituent truth; packaging does not homogenize matter away.

Reservoir is overflow in the current allocation grammar, not a mandatory upstream supplier.

### Link City

Link is required transit infrastructure and the owner of current inter-city allocation policy.

A freight interface grants access to the network; it does not grant peer-to-peer routing. Link therefore mediates every ring-freight journey between processing/storage endpoints.

Link owns no ordinary warehouse inventory. Cargo may wait at its interface while traversing a route without becoming Link stock.

Current allocation is deliberate priority rather than fairness: Launcher has first claim on usable processed material; Reservoir receives overflow when Launcher cannot accept more. Stored Reservoir material may re-enter Link allocation when Launcher has headroom.

Isolating Link partitions the ring logistics layer. That is the point of the capability, not an error to route around with hidden endpoint links.

## Matter and representation

Authoritative matter and visible matter are deliberately different layers.

The simulation must answer what exists, how much exists, what materially consequential composition it has, where it meaningfully is, and what owns it. Presentation answers how that state remains legible at miniature scale.

A rendered bead is a sample of an authoritative lot, not an independent rigid body and not a promise of one bead per unit. Matter may appear as packets, streams, cargo, sampled beads, or persistent fill without changing the authoritative ledger.

Transported lots remain conserved packets. Their visible matter stretches along route geometry, becoming spatially extended near mid-route and compact near interfaces. This makes distance legible without changing authoritative packet timing.

Once that extent became visible, opposing packets passing through one another became a physical contradiction. Conduits therefore earned a minimal half-duplex rule: an occupied conduit temporarily admits only the current direction; same-direction followers require headway; opposing packets wait. Occupancy is traffic, not topology failure, and it does not trigger congestion-aware rerouting.

The implementation deliberately spends discrete spatial resolution where multiplicity matters instead of asserting universal particle-level simulation.

## Cityhood is not capability

One of the most important corrections in the expedition was withdrawing the generic-city abstraction.

Being a city does **not** automatically confer:

- storage;
- material ownership;
- ring-freight connectivity;
- processing;
- network routing.

Those are independent capabilities earned by behavior.

The earlier generic abstraction produced semantically false state: Drone City accumulated purposeless raw inventory, Thumper advertised storage despite depositing into world space, Link looked like a warehouse despite functioning as transit infrastructure, and direct endpoint routes made Link decorative.

The current topology is intentionally asymmetric because the verbs are asymmetric.

## Perceptual grammar

The cities share a civilization without sharing a canonical chassis.

Primary morphology is verb-derived: directional Launcher massing, porous Drone fabrication/bays, branching Unzip flow, heavy Thumper machinery, hollow Reservoir containment, and sparse Link relay structure.

Brass, stone, selected glass, repeated octagonal forms, rectilinear urban density, and strong hierarchy unify those divergent forms.

This miniature architecture implies districts, internal industry, and population at a larger semantic scale than the simulation explicitly models. Greeble does not establish an ecosystem, civilian population, internal building economy, or hidden capability.

Static architecture may be merged and repeated detail instanced. Representation is free to optimize aggressively so long as required causal truth remains recoverable.

## High-value failures

Several failures materially changed the model of the civilization.

**Direct endpoint freight made Link decorative.**  
Requiring all inter-city freight to traverse Link established the distinction between network access and routing authority.

**Generic cityhood invented capabilities.**  
Removing automatic storage and freight interfaces from Drone City, Thumper, and Link made ownership match actual verbs.

**Nearest-compatible-buffer delivery bypassed the processing story.**  
Giving Unzip an explicit intake capability established a boundary between world collection and civilization logistics.

**Destination was confused with admission.**  
Filtering destinations by immediate capacity stranded loaded drones at pickup sites. Drones now travel toward the earned destination and let admission resolve at the intake.

**Aggregate reservations synchronized independent drones.**  
Treating every inbound drone as reserved future capacity produced clumped release behavior. Local sequential admission restored independent actors.

**Compact packet witnesses hid distance and contradictory traffic.**  
Elastic route extent exposed opposing packets passing through each other, which earned half-duplex conduit occupancy.

**Reservoir repacking erased spatial history.**  
A persistent bounded fill witness preserved storage history without falsely promoting presentation into authoritative granular physics.

**Faster Launcher kinetics did not create meaningful purpose.**  
Ballistic timing and physical aiming earned improvements; the deeper reason for launch did not. The artifact preserves that unresolved boundary instead of rationalizing it after the fact.

## Explicit boundaries

Six Cities does not currently claim:

- a complete economy;
- an earned external demand model;
- strategic city planning;
- civilian or ecosystem simulation;
- exact per-origin mass accounting;
- general rigid-body contact;
- granular Reservoir physics;
- full drone obstacle pathfinding;
- fluid dynamics, hydrology, erosion, or tree collision;
- structural fracture or district-level city physics;
- persistent save state.

Water, vegetation, forests, and decorative rocks may contribute perceptual world identity without becoming collectible or simulated systems.

The current Launcher cadence should not be mistaken for intelligent demand. Reclamation grounds remain provisional scaffolding.

Terrain deformation, gravity-owned loose matter, containment failure, accumulation, and persistent physical consequence remain stronger open questions than further rationalization of the civilization's economy. The completed expedition explicitly points those questions toward independent physical-material/deformation work rather than silently broadening this specimen.

## Extension rule

Extend Six Cities by adding capabilities that compose through existing world truths, or by explicitly introducing a new world truth.

A new material consumer should declare compatibility and capacity. A new terrain cause should act through terrain authority. A new vehicle should transfer ownership rather than mutate counters. A genuine new transformation should be represented in conservation auditing.

Do not infer capability from geometry, labels, cityhood, or implementation convenience.

Prefer reuse of shared semantic owners over named pairwise choreography.

## Archaeology and completion

The executable intentionally carries its own archaeology: the frozen S2 semantic source, collaborative turn records, failed probes, present-tense corrections, and expedition-close evidence.

Those records are not all current truth. Their value is that they preserve the path by which current truth was earned.

The expedition is complete for its present research purpose. Completion does not mean that the world cannot be extended. It means further work should not rationalize its economy, generalize its machinery, or erase useful scars merely because more implementation is possible.

The artifact has finished teaching the questions this expedition was built to expose.
