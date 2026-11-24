# Tether Vortex Design Blueprint

*A persistent-world strategy game where synthesis under pressure matters more than the perfect plan.*

---

# PART I. THE PITCH

## 1. Elevator Pitch

Tether Vortex is an always-on 3D strategy sandbox. Build a factory, join a faction, or take what you can carry and leave. The world keeps running while you're offline. There are no matches, turns, or scheduled waves.

A layout that works today can fail tomorrow. Sustained extraction near the Hive can change how it attacks, and a deal that kept a factory supplied can fall apart while its owners are offline. Even the odds of a civilization-wide reset move with conditions in the world.

Engineers design networks, Operatives hold formations together in real time, and Masterminds decide what the systems each player runs owe one another.

## 2. Core Fantasy (Four Ways to Play)

The game offers one shared world and four fundamentally different genres of play within it, each with a real skill ceiling and a real reason to exist.

- **Nomad.** Start here and return whenever you like. Wander, build a shelter, or automate a small workshop. A Nomad with good intel can matter to a faction without taking on an entire base.
- **Engineer.** Shape a network inside the boundaries a Mastermind sets. You can move a whole sector while keeping its pipes connected, or add a second route so one break can't starve production.
- **Operative.** Sketch temporary formations from an RTS-style view and keep them together with Attention. Watch where the fight is going and set up a response before it gets there.
- **Mastermind.** Define the contracts the faction builds around. When the factory, the front line, and a rival all demand attention, decide which information you need current before you act.

## 3. The World

A reset can sweep away the current civilization and leave its wreckage for the next one. The odds compound exponentially as risks accumulate. Extraction and neglected infrastructure can push the world closer to collapse, while mitigation can ease the pressure. A reset can happen at any time.

Anyone can raid a town, a faction, or a lone Nomad at any time. Factions can also agree to a Declared Campaign, which adds public terms and raises the stakes of a conflict. See Section 9.3.

## 4. Tone & Identity

The visual and tonal language draws from Matrix-clean command interfaces, Half-Life-grimy industrial reality, Red Alert's bold factional propaganda, techno's cold mechanical rhythm, and an industrial-horror dread that lives at the edges of the map and, sometimes, at the edges of trust between players.

## 5. What Makes This Different
- **Different work for each role.** An Engineer can keep a line supplied, but the Mastermind sets what that line owes the rest of the base. An Operative has to put the resulting units to work before conditions change.
- **Three real engineering disciplines, not three difficulty flavors of the same game.** Systems architecture, structural engineering, and real-time systems engineering are genuinely different skills in the real world; this game is the first to make all three simultaneously playable, interdependent, and equally deep.
- **Tech is the real currency.** Money exists, but it's a lubricant, not the point. What you actually fight, trade, and betray each other for is the tech that lets your civilization keep surviving, continuously, one more day.
- **Exponential costs.** Baseline technology can counter even catastrophic threats if you can afford enough of it. At the high end, exotic technology offers a way around costs that few factions could pay.
- **Exposure grows with the base.** Every new sector gives threats more infrastructure to hit and gives the faction more to maintain as those threats change.
- **The Saboteur.** A player may briefly see how a sequence of ordinary actions could bring on a civilizational reset. They may never see the opportunity or choose to take it. The game keeps no record identifying the player as the Saboteur.

---

# PART II. DESIGN PHILOSOPHY

## 6. On the Name

*Tether* refers to the Mastermind's work of keeping a coherent picture of the world while conditions change. *Vortex* refers to The Deep, the force beneath the game's other threats. Players can wound it. They can never confirm its death.

## 7. The Mastermind as Noncanonical Protagonist

The Mastermind is the closest thing Tether Vortex has to a protagonist. Their view of the world is incomplete and already aging when they act on it. That's true for every player, but the Mastermind has to make decisions that depend on several parts of the world at once, including The Deep, which always keeps something hidden.

The Engineer understands the network in more detail. The Operative can see a fight developing several moves ahead. The Mastermind depends on both to know which promises the faction can keep and which plans it needs to abandon.

## 8. The Psychological Framework (Phases of Matter)

The formal roles borrow from phases of matter. The analogy shapes how each role thinks, what it sees on screen, and what its player can do there (Section 11).

### 8.1 The Engineer (Crystalline Solid)
The Engineer sees a network through its connections. Change a junction and they can see which routes become fragile, even if everything downstream is still running. Sherlock Holmes and Einstein are reference points for that way of thinking. The Engineer trusts structures whose logic they can work out for themselves. The Evil Engineer mistakes obedience to a rule for evidence that it works (8.5). The live world puts pressure on work the Engineer would happily keep doing until the answer was clear.

*Genre reference.* Factorio's grid and production ratios reward precise placement and calculation. The Engineer in Tether Vortex works with properties that survive reshaping, such as whether two buildings still share an independent backup route (11.1).

### 8.2 The Operative (Superfluid)
The superfluid analogy is about the lack of friction between thought and action. The Operative anticipates how a fight might unfold and keeps several responses in mind while holding a formation together. When their attention shifts, the formation can come apart. Green Lantern's constructs and Doctor Who's Time Lord are reference points. The Operative thinks on the scale of the current fight and the next one they can see.

### 8.3 The Mastermind (Liquid Crystal)
A liquid crystal can flow and respond to external fields while retaining some internal order. The Mastermind has to hold on to enough structure for others to build on and still be willing to spend or abandon parts of it within a minute. Too much planning can leave the faction unable to act. Too little can burn through the resources that kept it functioning.

The Mastermind reads people as well as systems. An Engineer may have time to fix a bottleneck, an Operative may already be stretched thin, and a rival may take the same move as a threat. The Mastermind sees less detail than either specialist and needs both views to make a decision. Nikola Tesla, Mr. House, and the Archangel Michael are character references.

### 8.4 The Deep (Annealing)
The Deep takes its cue from annealing. Heat lets a material's internal structure rearrange, and what happens as it cools determines what structure remains. A civilization can emerge from The Deep's influence in a more stable form, or come apart again.

Loki, Coyote, and Anansi are private references for The Deep (Section 13). An expedition can bring home something valuable while raising the odds of a reset. The Deep has no stake in which result players consider a victory, and when it returns can feel arbitrary.

The Operative's superfluidity follows from extreme cold. The Deep makes rigid structures mobile through heat.

| Figure | Phase | Temperature | Alignment | Time-relationship | Core cognition | Discipline |
|---|---|---|---|---|---|---|
| **Engineer** | Crystalline solid | Cold | Lawful (self-evident structure) | Timeless, truth persists outside the clock | Topological, relationships between parts | Structural/topological engineering |
| **Operative** | Superfluid | Cold | Chaotic (pure becoming, engagement-scale) | Bounded present, this fight and the next | Constructive-under-load, real-time architecture of decisions | Real-time systems engineering |
| **Mastermind** | Liquid crystal | Cold | Neutral (holds both without collapsing) | Both, timeless structure and live pressure, simultaneously | Synthetic, relationships between domains | Systems architecture |
| **The Deep** | Annealing (molten) | Warm→Hot, ascending | Trickster, process, not malice or play | Ancient, continuous, indifferent to any one civilization's clock | Restructuring-through-disorder | N/A |

### 8.5 The Full 3×3 (Alignment × Temperature Reference Grid)

The top row groups the three formal roles as cold. The rows below show what rising heat does to order. The Deep sits in the warm row as the process that acts on the rest of the grid. The hot end represents a civilization or a mind that has lost the structure it depended on.

> This grid is a reference for writing and design. Beyond the formal roles and The Deep, its entries are conceptual examples that may inform future antagonists or corruption.

```
┌────────────────────┬────────────────────┬────────────────────┐
│       LAWFUL         │       NEUTRAL        │       CHAOTIC        │
├────────────────────┼────────────────────┼────────────────────┤
│      ENGINEER         │      MASTERMIND       │      OPERATIVE         │  ← COLD
│  Crystalline Solid     │    Liquid Crystal     │      Superfluid          │
│  fixed lattice,        │   ordered + mobile,   │   frictionless flow,     │
│  timeless order        │   responsive          │   near-zero resistance   │
├────────────────────┼────────────────────┼────────────────────┤
│      (unnamed)         │      (unnamed)        │       THE DEEP           │  ← WARM
│  Amorphous Solid/       │    Gel / Colloid      │  Annealing (molten)      │
│  Glass,  rigid but      │    part-order,        │  structure liquefied     │
│  order lost, brittle    │    part-flow,         │  by heat, restructuring  │
│  under heat             │    energized          │  through disorder        │
├────────────────────┼────────────────────┼────────────────────┤
│    EVIL ENGINEER        │      (unnamed)        │     PURE PLASMA           │  ← HOT
│    Plasma Crystal       │       Plasma          │    Ionized Chaos          │
│  (dusty plasma),        │    energetic,         │   total structure         │
│  hot, but structure     │    coherence          │   collapse, no lattice,   │
│  forcibly held rigid    │    failing            │   no flow-memory left     │
│  = dogma under heat     │                       │                           │
└────────────────────┴────────────────────┴────────────────────┘
```

**Reference archetypes for the mirror cells** (non-canonical, illustrative only):

- **Evil Engineer (Plasma Crystal, Hot/Lawful).** Obeys a rule long after the system it describes has changed. In a dusty plasma, charged grains can arrange themselves in a lattice. That's the image here: forces keep the structure in place. See 8.1 for the Factorio comparison.
- **Corrupted Mastermind (Plasma, Hot/Neutral).** The self-serving executive who still talks as though they see the whole faction. Their decisions no longer take the Engineer's constraints or the Operative's situation seriously.
- **Pure Plasma or The Unthinking (Ionized Chaos, Hot/Chaotic).** Acts on each impulse as it arrives. One move leaves no usable structure for the next.
- **Glass and Gel (Amorphous Solid and Colloid, warm row).** Glass suggests an Engineer who clings to a damaged structure until it breaks. Gel suggests a Mastermind who can still bring people and systems together, but whose decisions have started to lose their shape.

---

# PART III. SYSTEMS REFERENCE

## 9. World Model

### 9.1 Persistence & Perspective
- Each server runs one persistent 3D world. Time keeps moving while players are away. Threats build or ease as conditions change, without turns, matches, or scheduled waves.
- **Camera.** All three formal roles use an RTS-style top-down or near-bird's-eye view. Operatives focus on the immediate fight, while Masterminds work at a wider scale. The 3D terrain still matters, especially around the Hive and The Deep.
- Players can switch to closer third-person or first-person views where those options are available.
- The Mastermind's top-down schematic shows zones divided by interface membranes. Fog and delays leave gaps in the projection, and the view abstracts terrain and network details (11.3).
- World-per-server. Worlds are independently persistent; merging is possible (see 9.4) but not routine.

### 9.2 The Sandbox Floor
- Nomads and faction specialists share the same sandbox. Switching roles leaves the player in the same world.
- There is no forced progression. A player may remain a Nomad, indefinitely, as a complete and legitimate way to play the entire game.

### 9.3 Conflict (Ambient Violence and Optional Declared Campaigns)

A faction, town, or Nomad can be attacked without consent, regardless of the size of either side. Section 16 describes what makes small settlements hard or costly to wipe out.

- **Ambient conflict.** Scouting, sabotage, skirmishes, raids, and sieges can happen at any time. Most conflict takes this form, from a Nomad skirmish to a siege that ends a faction.
- **Declared Campaign.** Both Masterminds sign a contract on the membrane between their territories (11.3.4). It defines victory conditions and makes the conflict visible to other factions. Breaking the terms costs resources and reputation. Ambient conflict remains available throughout.
- Campaign costs and what other factions can see still need tuning. See Part IV.

### 9.4 World Merging (STUB)
Worlds can merge; mechanism, triggers, and stitching logic are intentionally undefined at this stage. Best current instinct: merges should be rare, deliberate events, likely timed around reset-adjacent drift spikes (Section 15) rather than continuous, to avoid resolving live territorial/resource conflicts across two full, thriving worlds simultaneously. Full design deferred.

## 10. Roles (Overview)

### 10.1 Three Engineering Disciplines
Faction play draws on systems architecture, topological engineering, and real-time systems engineering. Each has its own decisions and a different view of the same world.

- **Mastermind = Systems Architect.** Designs interfaces and boundaries between systems. Doesn't touch implementation; defines what each system is contractually obligated to promise the systems around it. Broadest scope, shallowest depth per-system, the discipline of architecture.
- **Engineer = Structural/Topological Engineer.** Works freely within whatever boundary the Mastermind hands them, optimizing connectivity, redundancy, and flow with full depth and no time pressure. Narrowest scope (bounded to their sector/domain), deepest depth, the discipline of structural correctness.
- **Operative (Real-Time Systems Engineer).** Uses the interfaces the Mastermind defined and the structures the Engineer built. Their work is making those systems respond under live load.

A Mastermind's interface can define what a base sector supplies, how a unit fits into a formation, or what a treaty commits two factions to. The Engineer can choose any implementation that meets the terms. The Operative uses the resulting systems through constructs (11.3.4).

### 10.2 Roles as a Thin Layer
Players of any role can design, direct, and command. A formal role gives a small bonus and a kit perk in its specialty, similar to Quake-style class systems. The shared toolkit remains available to everyone. Section 11 describes the specialized play.

### 10.3 Function Summary

| Role | Title | Function | Emphasis | Skill Ceiling |
|---|---|---|---|---|
| **Mastermind** | *Synthesis under incomplete information, in real time* | Originates interfaces and boundaries; owns strategy, logistics, diplomacy, external relations, Declared Campaign initiation. Rarely micromanages. Operates on necessarily short planning horizons. | Both macro and micro, the only role spanning the full range, though it rarely dwells in micro for long. | Uncapped. Compounding, multiplicative value to the team. |
| **Engineer** | *Optimization under constraint, solved once, defended forever* | Implements freely within Mastermind-defined boundaries: base topology, blueprints, unit templates. Full modular design authorship (11.1, 17.4). | Pure macro, deep structural work, no real-time pressure by nature. | Capped but necessary. A real, satisfying, but bounded skill expression. |
| **Operative** | *Reflexive command of force, moment to moment* | Consumes interfaces and structures through real-time constructs; deploys and commands units/defenses. Retains live Field Modification privilege over unit configuration (11.2.6). Lives almost entirely in ambient conflict (9.3). | Pure micro, real-time execution, no design/architecture authority by nature. | High but narrow by convention, not by hard restriction. |

**Authorship.** The Mastermind defines an interface. The Engineer builds within it, and the Operative uses the resulting systems in live constructs. These are peer roles.

**Quorum.** A faction has full team status while all three seats are actively occupied. If a seat goes vacant, a grace period gives the faction time to fill it before capabilities begin to degrade. Enemies can still attack during that window or after it (9.3).

**Role switching.** Players can switch mid-game. The likely cost is a team resource payment and a short period before the new role reaches full capability. Frequent switching may also affect reputation.

## 11. Role Gameplay Design

### 11.1 The Engineer (Topological Engineering)

The Engineer works on a network's shape. Moving a building can improve its cover without changing which inputs reach it. The overlays show which connections work, which have backups, and where flow is constrained.

**11.1.1 Nodes and edges.** Extractors, refiners, assemblers, storage, and defenses are nodes with typed inputs and outputs. Drag belts, pipes, and power lines between nodes as freeform curves. Connections work without grid snapping.

**11.1.2 Grab and deform.** Grab part of a live network and stretch it, rotate it, compress it, or move it. Edges follow their endpoints. Redraw a connection when you want to change what it joins. Moving the network changes its exposure while preserving its existing topology. When an edge snaps, its loose ends show where the break happened, so you can work from the damaged layout.

**11.1.3 Real-time overlays**
- **Connectivity overlay**. Nodes pulse green (live path to required inputs/outputs) or red (cut off). Binary, immediate.
- **Redundancy overlay (genus visualization)**. Single-point-of-failure edges glow amber; edges that are one of several independent paths glow cool blue. Fragility becomes a visible color pattern, not a calculation.
- **Bottleneck overlay (min-cut highlighting)**. The network's actual current chokepoint (the minimum edge-set that would starve the most downstream production) is continuously computed and highlighted directly. The player sees the seam that's constraining everything, rather than deriving it from ratios.

**11.1.4 Working the network.** Read the overlays and pick a problem you can act on. Add a backup route, widen a bottleneck, or pull back an exposed section. Move the existing network or add nodes and edges, then check the overlays for the result.

**11.1.5 How threats break a network.** The Hive severs edges and destroys nodes at the frontier. Add a backup route or cut off an exposed branch before it takes the rest down. Collapse grows with the footprint and output of the network. A regional disaster tests whether backup paths are far enough apart to survive the same event. Entropy frays neglected edges, and at its most severe The Deep may change which nodes connect. Larger networks expose more edges and take longer to repair per unit of damage (Section 16).

**11.1.6 Progression.** The connectivity overlay is usually enough while the network stays small and ambient pressure is low. As extraction and neglect accumulate, players need to read redundancy and bottlenecks too. An expert can recognize when a damaged network still has the shape of a known solution and find the smallest change that restores it. That is the role's use of homeomorphism (8.1).

**11.1.7 Sector boundaries.** The Mastermind defines the inputs and outputs a sector owes the rest of the base (11.3). The Engineer can arrange anything inside that boundary as long as it meets the contract.

### 11.2 The Operative (Real-Time Construction)

Operatives work from an RTS view. Their advantage comes from seeing an engagement develop early enough to have a formation in place when it matters.

**11.2.1 Sketching a construct.** Draw a pincer or a fallback line on the map. Available units spend a short time moving into the formation. The Operative can then direct it as a group.

**11.2.2 Holding a construct.** A construct holds its shape and adapts while the Operative spends Attention on it (11.2.3). Shift focus without a handoff and the units lose coordination. You can preview the shape as a ghost or wireframe before spending Attention.

**11.2.3 Attention.** One formation is cheap to maintain. Split Attention across several and each becomes less coherent. Attention regenerates fastest when you release a construct deliberately. Experienced Operatives can bring new formations online while keeping others intact, then let them go when their job is done.

**11.2.4 Preemptive countering.** The game shows an imperfect projection of where the fight may go in the next few seconds. It refreshes on the scale of seconds. Sketch a counter against that projection and it can be in place when the attack comes. Guess wrong and it costs Attention to break formation and turn the units around.

**11.2.5 Engagement view.** The Operative sees the current fight, the ground around it, and the near-future projection. The next engagement appears if it is already telegraphed. Campaign strategy and faction politics live in the Mastermind's view (11.3.6).

**11.2.6 Field Modification.** Engineers design base unit templates and stock modular parts in advance (11.1, 17.4). During an engagement, the Operative can requisition a module swap or change which units make up a construct. The base template remains the Engineer's design.

**11.2.7 Terrain and network resilience.** A construct along a redundant path is more resilient. One caught in a bottleneck is more fragile. Both roles see the same overlay cues (11.1.3), so an Operative can ask the Engineer for a second path out of a sector during the fight.

**11.2.8 Progression.** Start with one construct and a generous projection window. As threat pressure and enemy sophistication rise, the window shortens and opponents field more constructs. The Operative has to anticipate several developments at once.

> Attention costs, projection length, and the sketching controls need a prototype before they can be tuned. See Part IV.

### 11.3 The Mastermind (Systems Architecture)

The Mastermind writes the guarantees that let parts of a faction work together. The same interface design applies to a factory sector, a unit template, or a treaty.

**11.3.1 Interfaces.** An interface is a contract between two systems. It specifies the inputs a system needs, what it can supply, and which limits it has to respect. The Mastermind writes the contract. The Engineer decides how to meet it.

**11.3.2 Membranes.** Translucent membranes divide the schematic into zones. The Mastermind sees a compressed silhouette of the topology inside each zone (10.1). The membrane itself shows the current terms, such as 400 ore per minute out in exchange for 200 power per minute in.

**11.3.3 Editing a contract.** A redesign takes longer than moving a network or sketching a formation.
1. Select a membrane.
2. The membrane opens into an editable panel with inputs, output guarantees, tolerances, and priorities.
3. Change a term and the silhouette behind the membrane flickers. The Engineer or Operative responsible for the zone gets a notification during the edit.
4. Commit the contract and the membrane settles back to a steady glow.

**11.3.4 Where interfaces appear.**
- **Base-sector membranes.** Define what a sector exchanges with the rest of the base. Engineers build within those terms (11.1.7).
- **Unit inner-interface panels.** Edit what a unit template promises to the systems that use it. A well-defined interface lets a unit join a construct quickly and cheaply. An awkward fit costs time or Attention mid-fight (11.2.3).
- **Faction-to-faction membranes.** Treaties and Declared Campaign proposals appear between territories on the strategic map (9.3, 19.2). They use the same editor, Bandwidth cost, and cooldown as internal contracts.

**11.3.5 Synthesis Bandwidth.** Focus on the battlespace and its pane sharpens while the network and politics panes gray out and their information ages. Opening a contract panel takes a large, visible share of Bandwidth immediately. Whether you commit the edit or back out, that membrane goes on cooldown.

**11.3.6 Strategic view.** The Mastermind sees a summary of network health and current engagements in the same view. A third pane shows faction reputation and diplomacy, along with live rumors, verified intel, and current reset pressure (19.3, Section 14). Engineers and Operatives get finer detail in their own views.

**11.3.7 Using Bandwidth.** Scan the panes and choose which one needs a current read. Select a membrane, then issue a Directive to shift priorities temporarily or edit the contract itself. Release focus and check what changed in the other panes.

---

## 12. Nomad (The Base State)

Nomad is not a pre-role tier; it is the game's zero-state, always available, always complete. A blend of early Fallout wandering, Minecraft's build-anything freedom, Rust's exposed precarity, and early Factorio's small-scale automation.

Players earn these reputations through play.
- **Honest Trader.** Keeps deals and can trade with factions that distrust one another.
- **Mercenary Scout.** Sells intel and takes short combat contracts, including shifts in a faction's vacant Operative seat.
- **Hermit-Survivalist.** Lives away from faction systems. A quiet, mobile player leaves little for most threats to find (Section 16).
- **Warlord-for-Hire**. Leads loose raiding bands without ever meeting faction quorum; perpetually "almost a faction."
- **Pilgrim**. Drawn to the threat pillars as an observer/thrill-seeker; informal early-warning folklore figure.
- **The Auditor.** A G-Man-like figure said to appear when a civilization is under stress. Players may credit them with tipping events either way.

Joining a faction gives a Nomad access to team resources and a seat to fill. It also makes them easier to track and can cost them old contacts or the reputation they earned as a trader, Spy, or Auditor (Section 16).

## 13. The Deep

### 13.1 In-Game Behavior
- **Ambition-gated:** tied to extraction/depth past a threshold; each engagement raises both risk and reward.
- **Escalation.** Each engagement raises the stakes and worsens the odds of the next. There is no fixed number of encounters after which the Deep settles into a predictable pattern.
- **Failure.** A failed encounter can hit as hard as a titanic disaster and almost always pushes the world close to a reset.
- **Success.** The Deep yields exotic technology and materials. Hive aggression, Collapse pressure, and the frequency of cosmic events briefly fall worldwide, and global luck rises (Section 15). Players can wound The Deep, but whether it can die stays unanswerable.
- **Reappearance is self-deprecatingly random:** no punitive logic tied to who provoked it, no guaranteed return location or timing.
- **Ambient effects.** The Deep influences the other four threats. Changes in Hive aggression, Collapse sensitivity, cosmic events, and Entropy can all reflect its presence.
- **Folklore.** The Hollow Choir, the Deep Current Concordat, or a player who encounters the Saboteur opportunity may believe The Deep has noticed them. The game never confirms it.

### 13.2 Design Notes (Never Revealed In-Game)
The design team keeps this background out of lore entries and dialogue. The Deep predates the Hive, the map, and every known reset. The other threats exist in its presence. Its role in the Saboteur mechanic is to briefly show a player a possibility they already had (Section 14). See 8.4 for the annealing analogy and mythic references.

## 14. The Saboteur (a Standing, Rare, Undetectable Possibility)

Any player can encounter the Saboteur opportunity without warning. Acting on it is optional.

- **No stored identity, ever.** There is no flag, tag, class name, or hidden variable anywhere in game state (client or server) that marks a player as "the Saboteur." Nothing exists to find, even for a hacker with full memory access.
- **Eligibility is computed, not assigned.** Any check for eligibility is derived at the exact moment it might matter, from real, already-existing world telemetry (current systemic fragility across the five threats), never stored beforehand.
- **Unknowable in advance, even to the player themselves.**
- **The “Neo view.”** When eligibility and opportunity line up, the player briefly sees a personalized sequence of actions generated from the world's current condition. Every action is already available in normal play. Following the sequence gives the player a high chance of triggering a reset.
- **Fully optional, and self-consuming.** The plan cannot be banked, studied, or reused. Declining it yields nothing. There is no version of "peeking for free."
- **The only reward is a single private, non-persisted notification** to the acting player alone. No achievement, no career log entry, no leaderboard. The community only ever learns this system exists through rumor and retrospective, unprovable inference.
- **Distinct from the Spy niche**, an ordinary, repeatable, skill-based Nomad archetype operating at ambient stakes (9.3). The Saboteur operates on the shared civilizational reset curve itself, a categorically different scale.
- **Rarity is emergent, not enforced by a quota.** A high-confidence "plan" can only be constructed when a world's real systemic fragility is already elevated.

## 15. The Five Threats (Continuous Drift, Not Discrete Cycles)

Threat values move in real time. A stretch of missed maintenance raises Entropy on the affected structure. Extraction can change Hive aggression, and rising output can feed Collapse. Escalation follows what happens in the world.

All five threats feed the same exponentially compounding reset risk. As activity and exposure accumulate, the odds can worsen without a set date for catastrophe.

| Pillar | Nature | Trigger |
|---|---|---|
| **The Hive** | Ground-level, geographic | Proximity, migrating nests, output/noise-driven aggro, continuously reassessed |
| **Collapse** | Systemic, self-inflicted | Civilizational scale/output, continuously reassessed |
| **Cosmic/Environmental** | Indifferent, external | A live, continuously-running probability rather than a scheduled event (Asteroids, rare/severe), plus geology-linked variants: Superstorms (frequent/mild), Volcanoes (resource-linked), Seismic Rifting (extraction-correlated, can sever territory) |
| **Entropy** | Universal, neglect-driven | Real elapsed time without maintenance on a specific piece of structure, the one pillar that punishes stillness, closing the "build small and hide" loophole |
| **The Deep** | Ambition-gated, mysterious, escalating | See Section 13 |

### 15.1 Threat Mutation
Threats change behavior as activity accumulates. Sustained extraction near Hive territory can trigger larger broods, altered resistances, or new attack patterns. All five pillars can keep drifting after the activity that set them in motion has stopped. Early exposure is mild while accumulated pressure is low.

### 15.2 Unified Cost Law
Baseline technology can in principle counter any threat, including The Deep. The cost rises exponentially with severity and can reach the point where no faction is likely to pay it. Exotic tech and luck can shorten that climb.

**Luck** adjusts variance across game systems. Each server can tune it, and local modifiers can come from position, faction traits, temporary effects, or persistent curses and blessings with specific removal conditions. Even a new player can occasionally beat steep odds. The game makes that possibility visible.

## 16. Scale, Coexistence & Anti-Steamroll Design

A large faction can attack a small neighbor at any time (9.3). Keeping a large territory operational raises the cost of that attack. It also gives the smaller faction more places to hit back.

### 16.1 Superlinear Scale Cost
The cost of a larger footprint grows faster than its size. These costs come from running the base itself.
- **Collapse pressure.** A larger civilization generates more of its own reset risk through its output and footprint (Section 15).
- **Entropy exposure.** A sprawling network has more edges to maintain. Entropy compounds on each neglected edge (15.1).
- **Interface and logistics load.** Each sector boundary draws on Synthesis Bandwidth (11.3.5). As the faction grows beyond what its Mastermind can keep current, more sectors run on stale information.
- **Threat mutation.** A wider footprint puts more activity near the Hive and more infrastructure in the path of regional disasters. More extraction also feeds escalation from The Deep (15.1).

### 16.2 Local Reversals Over Global Efficiency
A small faction can undo an advantage that took a large faction many hours to build. It needs to find the connection, contract, or formation the larger force is relying on.
- **Sever a connection.** Scout for an edge that feeds much of the downstream network. Cutting it can stall production across sectors even if a raiding party has only a fraction of the larger faction's resources (11.1.3).
- **Find an old bottleneck.** Large bases accumulate work the Mastermind and Engineers have yet to address. A scout can look for those weak points (16.1).
- **Disrupt an interface.** Read what a sector needs from its neighbors. Hitting the route that carries one required input can do more damage than attacking the whole sector (11.3).
- **Split Attention.** An outnumbered Operative can threaten several positions at once. If the opposing Operative divides Attention to cover them, their active formations lose coherence (11.2.3).

### 16.3 Asymmetric Survival Niches
A small footprint makes some places viable that a large faction would struggle to hold.
- **Threat-adjacent terrain.** A Nomad or small town may be able to stay near a Hive migration route or a Deep-touched zone. A large faction has more to protect there and takes longer to repair it when conditions change.
- **Low output.** A quiet settlement can stay small enough to avoid provoking serious threat mutation indefinitely (15.1).
- **Low payoff for raids.** A settlement with little stockpiled wealth or technology may offer too little reward to justify pulling resources away from a large faction's own maintenance and defenses (Section 19).

### 16.4 Scale-Induced Vulnerability to Mutation
Threats can change faster than a centralized network can be repaired. Its topology and contracts may depend on old conditions, and its unit templates can age too. Engineers have only so much time to revise designs, and the Mastermind can keep only so many interfaces current. At sufficient scale, new problems can accumulate faster than the faction can fix them.

### 16.5 Why Size Alone Doesn't Decide a Fight
Quorum, network redundancy, and the ability to keep up with maintenance still matter when a large faction has the resources to attack. A smaller faction can survive by keeping its exposure low or exploiting a dependency the larger faction has left exposed. Either side can lose.

## 17. Tech Tree

### 17.1 Structure
Six branches (five threats + Weapons), each following the same continuous exponential cost curve rather than discrete tiers:
- **Band A**. Cheap, fast, broadly available. Solves Tier 1/nuisance-level problems trivially.
- **Band B**. Exponential, still generic. Solves Tier 2/serious problems with real but escalating investment.
- **Band C**. Near-vertical. Solves Tier 3/catastrophic problems via brute force alone, theoretically possible, practically absurd.
- **Exotic**. Faction-gated shortcuts past most of Band B/C cost, earned through risk-engagement rather than pure resource investment. Tradeable and stealable.
- **Capstone**. Rare, cross-branch tech requiring exotic-tier ingredients from two or more branches. Meaningfully suppresses (never zeroes) the reset-drift's growth rate.

### 17.2 Branch 0 (Pre-Industry)
Branch 0 is available to Nomads and supports basic tools, ovens, and hand-built rifles. Components can be assembled from the start (11.1, 11.2.6).

### 17.3 Sample Named Tech (illustrative, not exhaustive)
- **Hive:** Perimeter Stakes → Adaptive Aggro Dampeners → Total Perimeter Lockdown Array → *Bonegraft Symbiosis, Pherotech Redirection Beacon*
- **Collapse:** Basic Scrubber Stacks → Decoupled Yield Engines → Brute Suppression Grid → *Null-Signature Manufacturing*
- **Cosmic/Environmental:** Storm Shelters/Seismic Bracing → variant hardening → brute-force titanic survival → *Orbital Deflection Array, Calderabond Mastery, Stormbreak Dome, Rift-Seal Doctrine*
- **Entropy:** Manual Maintenance Kits → Extended-Cycle Alloys → Constant Reconstruction Treadmill → *Everlast Frame Doctrine*
- **The Deep:** Tremor-Warning Sensors (early-stage only) → brute-force deep survival (steepest curve in the game) → *Bled Current Alloy, Hollow Resonance Key, and the capstone Abyssal Concordance (counters Deep + a titanic disaster simultaneously)*
- **Weapons:** Standard Ordnance → Area Denial Batteries → Strategic Payload Doctrine → capstone *Extinction Directive* (likely drawing on Abyssal Concordance-adjacent materials, tying the deadliest weapon in the game back to the same source as its strongest defense)

### 17.4 Unit Production & Modularity
- Engineers author both production-facility blueprints and the deployable unit blueprints those facilities produce, within Mastermind-defined interfaces (11.1.7, 11.3.4); Operatives deploy and command in real time, retaining live Field Modification authority over configuration (11.2.6).
- Premade blueprints are quick and reliable. For higher potential at greater risk, Engineers can assemble custom units from components such as a chassis, mounts, armor, and movement hardware.
- A Nomad's hand-built rifle uses the same assembly logic as a faction's custom tank.

## 18. Factions

Twenty factions, each with visual/tonal identity and a mechanical perk tied to Factory/Base/Civ systems. Full roster with palette, silhouette, architecture, propaganda voice, and perk on file (see Faction Appendix). Slot availability per faction is configurable per server (scarce, generous, or uncapped/"infinite").

**Selection & counters:** factions have natural counter-relationships (e.g., mass-production factions are vulnerable to raiders; risk-averse factions oppose Deep-pushers), natural diplomatic pairings (shared ideology or complementary niches), and inherently unstable alliances (shared aggression without shared trust). Full matrix on file.

**Political postures.** The broad groups are Competent Ambitious, Incompetent Ambitious, Conservative/Risk-Averse, Nomad-adjacent, and Opportunist. Opportunists profit from instability. A few factions are Reset-Realist or Resigned and plan around recovering from catastrophe. Extinctionism can emerge within Deep-adjacent factions through their internal politics (19.2), with no visible faction label to confirm the ideology.

## 19. Economy & Politics

### 19.1 Economy
- **Raw resources** (gold, oil, iron, gems, etc.) are counted automatically the moment they're acquired, exactly like any other stockpiled material. Gold's physical form (shard/ore vs. bar/coin) affects only convenience/weight, never its underlying value.
- **Money** is the current value of everything a player owns at fixed conversion rates set by design. One unit of gold might count as one Money and one unit of oil as five. Scarcity and demand leave those rates fixed.
- **Crafted goods, blueprints, weapons, and intel** have negotiated prices. A rare design can be worth much more to a faction that needs it, especially if it trusts the seller.
- Exotic and capstone tech come from engaging with threats or from trading with or stealing from a faction that has them. Money cannot buy them directly.

### 19.2 Self-Governance & Diplomacy
- **Self-governance (“Point Z”).** Players choose how to run their faction, whether through voting, a dictator, or some other arrangement. How they govern becomes part of their reputation. Neighbors can call a faction tyrannical, and the accusation can stick.
- **Diplomatic tools:** informal risk treaties, non-aggression guarantees as tradeable leverage, and short-lived coalition treaties scoped to a shared cataclysm event, dissolving automatically once it passes. Since ambient conflict is always possible regardless of any agreement (9.3), a non-aggression guarantee is a genuine, valuable promise precisely *because* it costs the guarantor real optionality, not because it grants the recipient protection they wouldn't otherwise lack recourse against. Mechanically, all of these are interface membranes authored by a Mastermind (11.3.4).
- **Faction schism** is an unscripted emergent outcome of internal ideological conflict (e.g., Conservative-minded Engineers vs. an Ambitious Mastermind) using only existing quorum/role mechanics.
- **Extinctionist drift and Troll-accusation-as-weapon:** any faction may ideologically drift toward openly courting the reset without ever being mechanically flagged as such. Separately, any faction can accuse any rival of harboring a Saboteur, purely as unprovable political ammunition.
- **Nukes and other capstone weapons.** Power scales exponentially. Players may end up in a standoff based on mutual deterrence, or use the weapons and trigger an extinction-tier event.

### 19.3 Reputation & Information
- **Reputation.** Players and factions build reputations that affect trust, trade terms, and who gives them a warning. Career logs and achievements confer no power.
- **Morality system:** a persistent, referential-only axis, tracked per player and per faction, available for others to reference but never gating content or mechanically enforced.
- **Information economy:** scouting reports, vacancy-window intel, and reset-risk assessments are tradeable goods, split into **verified intel** (costly, reliable) and **rumor** (cheap, unreliable, but often just as functionally powerful for deterrence or political attack).

## 20. Onboarding

- **Starting out.** Spend the first hour exploring and building at Nomad scale. The world gives you room because your activity is still small enough to draw little pressure. There is no timed tutorial or scripted grace period.
- **Environmental storytelling.** Let players see the silhouette of a distant base, a passing trader, or ground scarred by a threat they've yet to meet. Players can follow those signs if they want to know more.
- **Player-paced progression.** A player can keep wandering, build a small town with light automation, or take on a faction factory and its politics. Progress follows what the player does in the sandbox.

---

# PART IV. OPEN QUESTIONS

- **Declared Campaigns (9.3, 19.2).** Set the costs of entering or breaking a campaign and decide which terms and events outsiders can see.
- **Scale tuning (Section 16).** Playtest the exponents, thresholds, and rates. Measure when the costs begin to check a dominant faction and when they discourage growth that the faction could reasonably sustain.
- **Interface legibility.** Players should be able to see where Attention is going, how much Bandwidth an edit will cost, and whether moving a network made it easier to cut off. Test whether the interface shows those changes without a tooltip.
- **World merging (9.4).** Define the triggers and how territory and resources carry across.
- **Operative controls (11.2.8).** Tune Attention costs and projection length. Prototype how players sketch formations.
- **Saboteur eligibility (14).** Define when the game can generate a plan and how often that opportunity can appear.
- **Capstone weapon ingredients (17.3).** Decide which materials the weapons require.
- **Saboteur rarity.** Decide whether the server needs a world-level count that carries no player identifiers.

---
