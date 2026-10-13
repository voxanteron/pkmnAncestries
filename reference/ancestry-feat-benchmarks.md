# Ancestry Feat Benchmarks

The level at which official ancestry feats grant each kind of power. Use this to decide the
feat level for a Pokémon ability. Companion to [official-ancestries.md](official-ancestries.md),
which covers the ancestry statistics.

- **Scope:** ancestry feats of the 94 ancestries in `official-ancestries.md`, plus Starfinder's
  standardized ancestry feats and Pathfinder's shared ancestry feats. Versatile-heritage feats
  are excluded. In total, 2,235 feats (Pathfinder 790, Starfinder 1,445).
- **Source:** Foundry VTT `pf2e` system data, commit `4cf4c97` (2026-10-12). Feats were sorted
  by their rule elements and text, then read by hand. Counts are approximate; the examples are
  exact.
- Formulas use L = character level. "Half level" means `floor(L/2)`, minimum 1, unless noted.

## Quick Lookup

| Power | 1st | 5th | 9th | 13th | 17th |
| --- | --- | --- | --- | --- | --- |
| **Fly** | Burst: Fly 15 ft 1/round, fall if not landed | Burst upgrades to 20–25 ft; or 1/day fly for 10 min | **Permanent fly 20–25 ft** (or = land Speed) | Conditional fly (zero-g, mood) | Fly = land Speed; 1/day Huge fly 40 |
| **Swim** | Swim 10–20 ft (some to 30) | Swim 15 ft (25–40 with a heritage) | — | Swim or climb 20 ft | — |
| **Climb** | Rare; conditional climb 10–15 ft | **Climb 10–25 ft** or = land Speed | Climb 10 ft | — | — |
| **Burrow** | — | — | Burrow 15 ft (Starfinder) | **Burrow 15 ft** (Pathfinder) | — |
| **Land Speed** | +5 ft; or a 1-action Stride at +10 ft | — | +5 ft to all Speeds | +5 ft | 1/day quickened + 10 ft for 1 min |
| **Unarmed attack** | **1d6** (1d8 without agile/finesse; 1d4 for agile+finesse, energy or ranged) | Rare | 1d8 acid / 1d10 thrown | — | 1/day 3d8 energy cannon |
| **Breath / area attack** | **2 actions, ⌈L/2⌉d4, 15-ft cone or 30-ft line, recharge 1d4 rounds** | — | 1/hour or 1/day cone, about (L/2)d6 | 1/day 7d6–8d6 cone or line | 1/day 10d8–14d6 (+ persistent) |
| **Resistance** | Rare as a feat (heritages grant half level) | **Half level to one type**, or flat 5 to one energy | Half level to a 2nd type; or upgrade to = level | Extra types; flat 5 to two; **immunity to one energy** | Resistance 20 to one type; immunity to conditions |
| **Innate spell** | **Cantrip at will** | Rank 1, 1/day | Rank 3, 1/day | Rank 5, 1/day | Rank 7, 1/day |
| **Senses** | Scent 30–60 ft (imprecise); darkvision (needs low-light) | Tremorsense, wavesense or thoughtsense 15–30 ft (imprecise) | Lifesense 30; echolocation; a precise sense at 30 ft | Precise thoughtsense; tremorsense 20 | Echolocation 60–120 precise |
| **Size / form** | Permanent +1 size step (Tiny to Small); cosmetic Change Shape | Pest Form (Tiny animal) 1/day | Enlarge (2nd rank) 1/day | **Permanent Large**; constant Enlarge | **Permanent Enlarge + max HP +L**; 1/day battle form or Huge |
| **Max HP** | — | — | +L max HP | — | +L max HP (with size growth) |
| **Healing** | — | Regain about L HP, 1–2/day | Fast healing ½L for 1 min 1/day; or regain Con × ½L after 10-min rest | Regain 6d6 or fast healing 10, 1/day | Avoid death + regain 6d8+½L 1/day; regeneration 20 for 1 min |

## Movement

### Flight

Flight is the most carefully gated power. Permanent flight before 9th level does not exist
(outside Starfinder's fly-20 ancestries and the construct Living Hologram).

| Level | Benchmark | Examples |
| --- | --- | --- |
| 1 | 1 action, once per round: Fly with fly 15 ft; fall if not on solid ground at the end | Take Wing (Dragonet), Fledgling Flight (Strix), Take Flight (Awakened Animal, needs Flying Animal heritage) |
| 1 | Starfinder: Basic Flight, once per **minute**, at the ancestry's Flight Specialist Speed | Standardized feat |
| 1 | Outlier: permanent fly = Speed | Aerial Hologram (Living Hologram) |
| 5 | Burst fly increases to 25 ft | Zip! Zoom!, Juvenile Flight, Strong of Wing |
| 5 | Burst fly 20 ft (heritage-gated) | Soaring Flight (Skyborn Tengu) |
| 5 | 1/day: fly = land Speed + 10 for 10 minutes | Atmospheric Flight (Sarcesian) |
| 9 | **Permanent fly 20–25 ft** (requires the 1st and 5th-level feats) | Into the Sky, Fully Flighted (25; 35 if taken twice), Full Flight, Soaring Form (20), Flight Specialist |
| 9 | Permanent fly = land Speed (no prerequisite chain) | Jet Thrusters (SRO), Electromagnetic Flight (Urog), Soaring Vulkarisu |
| 9 | Temporary fly = land Speed, 10 min 1/hour or 5 min 1/day | Gift of Gadrathar (Copaxi), Hull Hop (Gnarefuroid), Arcane Propulsion (Automaton) |
| 13 | Conditional fly (low gravity, emotional state) | Floating Flight (Kalo), Soulfire (Moyishuu) |
| 17 | Permanent fly = land Speed + cosmic trait; 1/day Huge swarm with fly 40 | Connected to the Cosmos (Copaxi), Nanite Form (Android) |

**Pattern:** most permanent flight costs a three-feat chain (1st → 5th → 9th). A heritage
often gates the chain (Flying Animal, Skyborn Tengu, Patagi Maraquoi).

### Swim, Climb, Burrow and Land Speed

| Mode | Level | Benchmark | Examples |
| --- | --- | --- | --- |
| Swim | 1 | Swim 10 ft + breathe underwater 5 min | Sea Legs (Awakened Animal) |
| Swim | 1 | Ancestry's listed swim Speed (10–30) | Swimming Specialist (Starfinder) |
| Swim | 1 | Existing swim → 20–30, or amphibious | Strong Swimmer (Osharu), Waterweave Tripkee |
| Swim | 5 | Swim 15 (25 with an aquatic heritage); 40 with a heritage | Swift Swimmer (Lizardfolk), Super Swimmer (Binnaquid) |
| Swim | 13 | Choice of swim 20 or climb 20 | Arcane Locomotion (Automaton) |
| Climb | 1 | Conditional climb 10–15 | Suction Cups (Astrazoan), Powerful Tail enhancement (Automaton) |
| Climb | 5 | **Climb 10** (20 with a heritage), 20–25, or = land Speed | Climbing Claws (Catfolk 10, Pahtra = land), Prodigious Climber, Climbing Clamps, Climbing Specialist |
| Climb | 9 | Climb 10 | Tree Climber (Elf), Cave Climber (Goblin), Four-Armed Climber |
| Burrow | 9 | Burrow 15 (Starfinder) | Trash Tunneler, Burrowing Specialist, Excavating Tentacles (Barathu) |
| Burrow | 13 | **Burrow 15** (Pathfinder) | Warren Digger (Ratfolk), Generation Digger (Surki), Burrowing Tripkee, Digger (Awakened Animal) |
| Land | 1 | +5 ft Speed | Nimble Elf, Hyper (Skittermander), Long Legs (Ord), and others |
| Land | 1 | Land 15–20 for a non-walker; quadrupedal 30–35 | Land Legs, Adaptable Limbs (Barathu), Quadrupedal Speed (Orocoran) |
| Land | 1 | 1-action Stride with +10 ft (often 1/hour) | Close the Gap (Vesk), Jet (Ijtikri) |
| Land | 9 | +5 ft to all Speeds, or +15 ft Stride 1/10 min | Accelerated Step (Sarcesian), Green Dash (Leshy) |
| Land | 17 | 1/day: +10 ft and quickened for 1 minute | Fast Forward (Living Hologram), Let's Go (Skittermander, affects allies) |

## Offense

### Unarmed Attacks

About 35 1st-level feats grant attacks; very few appear later.

| Die | Typical traits | Examples (1st level) |
| --- | --- | --- |
| 1d4 | Agile + finesse; or energy damage; or ranged (range increment 20–30 ft) | Aggressive Antlers, Natural Hunter; Energy Beam (1d4 fire); Seedpod, Caustic Nectar (acid), Flame Belch (fire), Mindrender (mental) |
| 1d6 | Default; often finesse, or one maneuver trait (shove, grapple, trip, sweep) | Tusks (Orc), Saber Teeth, Iron Belly, Sturdy Vine, Draconic Lethality; Coronal Flare (1d6 fire); Stinging Tendril (1d6 poison, agile + finesse); Blowhole (1d6 ranged, water) |
| 1d8 | No agile/finesse; a maneuver trait at most | Ocean's Bite (Merfolk), Razorsharp Bite (Athamaru), Iruxi Armaments jaws, Shearing Beak (Ijtikri) |
| Fist upgrade | Fist loses nonlethal, gains shove | Iron Fists (Orc), Coral Fists, Massive Fists |

Later attacks are rare: 1d8 acid (Digestive Outburst, 9th), 1d10 thrown 20 ft (Cannonball, 9th),
and 3d8–4d8 fire 1/day as an immobile cannon (Core Cannon, 17th).

Energy damage on a 1st-level unarmed attack is allowed, but usually at 1d4–1d6.

### Breath Weapons and Area Attacks

The 1st-level template is the same across three ancestries:

> **2 actions.** 15-ft cone or 30-ft line. ⌈L/2⌉d4 damage of one type, basic Reflex (or the
> type's save) against the higher of class DC or spell DC. Can't use again for 1d4 rounds.
>
> Kobold Breath, Dragonkin Breath, Dragonet Breath (Homing Drake). G'folian gets it as an
> ancestry feature (Fire Breath).

Higher-level area attacks trade the recharge for a frequency:

| Level | Benchmark | Examples |
| --- | --- | --- |
| 9 | Cone, about (L/2)d6, 1/hour or 1/day; may add sickened | Compost (Leshy, (L/2+1)d6 acid, 1/hour), Spew Acidic Bile (Orocoran, 1/day), Rain of Bolts (Automaton, (L/3)d6, 1/day) |
| 13 | 1/day, 7d6–8d6 cone or line | Digestive Spray (Astrazoan 7d6 cone), Acidic Spit (Shirren 8d6 line, Fortitude), Dwarven Gravity Hammer (4d8 line while moving) |
| 13 | At-will cone ⌈L/2⌉d4 (no recharge, but a drawback) | Ponpoko-Pon! (Tanuki, sonic, Fortitude) |
| 17 | 1/day, 10d8 line or 14d6 + 4d6 persistent cone | Unleash Sota's Flame (Vlaka), World Shards (Talphi), Draconic Breath (Ryphorian) |

## Defense

### Resistance, Immunity and Weakness

| Level | Benchmark | Examples |
| --- | --- | --- |
| 1 (heritage) | **Half level to one type**: the standard heritage benefit (about 45 heritages) | Forge Dwarf, Snow Goblin, Stormtossed Tengu |
| 1 (feat) | Rare: half level to one type; or a reaction for physical resistance ½L | Pharmacologically Impervious (Gnome, poison), Benefactor's Resistance (Kobold), Hunker Down (Trox) |
| 5 | **Half level to one chosen type** | Molecular Modification (Barathu), Junkyard Resistance, Thick Skin (Hardor, piercing), Psychic Irregularity (mental) |
| 5 | Flat 3–5 to one or two energy types | Magical Resistance (Automaton 5), Sonic Sync (5), Blast Resistance (Dwarf, 3 to fire and sonic), Energy Shielding (Sarcesian 5) |
| 5 | Reaction, 1/day: resistance = L against one hit | Withstand the Storm (Yaksha) |
| 9 | Half level to a listed type; two types (fire and cold) | Ancestral Resistance (Starfinder), Harmonic Shielding (sonic), Elemental Favor (Ryphorian) |
| 9 | Upgrade an existing resistance to = L | Genetic Environmental Adaptation (Barathu) |
| 13 | Half level to another type (repeatable); flat 5 to two types | Absorbent Plating (Trox), Perfectly Balanced (Kasatha) |
| 13 | **Immunity to one energy type** (only one example) | Heart of a Sun (Novian, fire) |
| 17 | Resistance 20 to one type; immunity to conditions or effects | Spiritual Wards (Shobhad), Impenetrable Mind, Dragonet Immunities, Ascending Necrovite |

**Weakness as a cost:** weaknesses appear only attached to a benefit, and usually only while
that benefit is active. Swamp Gas Form (Bugbear, 13th) gives fire weakness = L while in vapor
form, and Shed Shell (Mecenaic, 1st) gives physical weakness ½L while the shell is off. The
ancestry-level precedent is Worlanisi's Psychic Reverb (mental weakness ¼L).

### Max HP, AC and Healing

- **Max HP +L** is a 9th-level feat (Mountain's Stoutness, Resilient Polyps), or part of a
  17th-level transformation (Scion Transformation, Strength of Eight Legions, Jotun's Heart).
- **AC:** only circumstance bonuses, +1 or +2 against a single attack, usually as a reaction
  (Deflecting Jewel 5th, Energy Deflection 9th).
- **Healing:**

| Level | Benchmark | Examples |
| --- | --- | --- |
| 5 | Regain about L HP (+1d6), 1–2/day | Siphon Solar Vitality, Life-Giving Light |
| 9 | Fast healing ½L for 1 min, 1/day; or regain Con × ½L after a 10-min rest | Repair Module, Restorative Chatter; Vivacious Conduit, Solar Rejuvenation |
| 13 | Regain 6d6, or fast healing 10 for 1 min, 1/day | Charged Blood, Activate Repair Mode |
| 17 | Avoid death, regain 6d8 + ½L, 1/day; or regeneration 20 for 1 min | Tenth Life, The Cycle Continues, Photosynthetic Regeneration |

## Magic

### Innate Spells

| Level | Typical grant | Count (sample) |
| --- | --- | --- |
| 1 | **One cantrip at will**, heightened to ½L rounded up | 29 of 35 innate-spell feats |
| 5 | Rank 1, 1/day (sometimes rank 2, or 2/day) | 14 rank 1 / 3 rank 2 |
| 9 | Rank 2–3, 1/day (rank 4 is rare) | 13 rank 2 / 12 rank 3 |
| 13 | Rank 3–5, 1/day (mode rank 5) | 14 rank 5 / 9 rank 4 / 10 rank 3 |
| 17 | Rank 6–8, 1/day (mode rank 7) | 16 rank 7 / 6 rank 8 / 4 rank 6 |

**Rule of thumb:** at feat level F ≥ 5, a 1/day innate spell is rank (F − 3) / 2, which gives
1, 3, 5, 7. That's exactly Starfinder's Ancestral Magic. Go one rank lower for 2/day or
1/hour; at will is cantrip-only, with one rank-2 exception (Phantom Orchestra, 9th).

### Senses

| Level | Benchmark | Examples |
| --- | --- | --- |
| 1 | Imprecise scent 30 ft (60 on a water/aquatic ancestry); darkvision if you already have low-light vision | Keen Nose, Sensitive Nose, Sensitive Rhinophores; Ancestral Darkvision |
| 1 | Pick one special sense (Awakened Animal: darkvision, low-light, echolocation 10 precise, scent 30, or tremorsense 30) | Natural Senses |
| 5 | An imprecise special sense, 15–30 ft | Tremorsense (Trox), Briny Beverage (wavesense 20), Electrolocation (15), Sensitive Antennae (thoughtsense 30) |
| 9 | Lifesense 30 imprecise; echolocation; one sense becomes precise at 30 ft | Sense Life, Enhanced Echolocation, Grand Soul! |
| 13 | Imprecise sense becomes precise; tremorsense 20 | Pinpoint Thoughtsense, Super Sensilla |
| 17 | Long-range precise sense (echolocation 60–120) | Enduring Echolocation |

## Size and Transformation

This section is directly relevant to evolution and Mega Evolution.

| Level | Benchmark | Examples |
| --- | --- | --- |
| 1 | **Permanent size +1 step** (Tiny → Small), can't retrain | Mighty Dragonet |
| 1 | Cosmetic Change Shape (a humanoid, an object, or Pest Form in a crawling form) | Everyday Form, Teakettle Form (Tanuki), Crawling Form (Yaoguai) |
| 5 | Pest Form (a Tiny version of the ancestry's animal) | Ancestral Pest, Rat Form (9th in Pathfinder) |
| 5 | 1/day Animal Form when changing shape | Animal Skins (Astrazoan) |
| 9 | Enlarge (2nd rank) as an innate spell, 1/day | Ancestral Growth (Nuar), Unleash Yaoguai Might |
| 13 | **Permanent Large**, or constant Enlarge | Agglomerate Leshy, Enlarged Chassis (Automaton) |
| 13 | Enlarge 2/day; Dragon Form (6th) 1/day | Kaiju's Footfalls (Kobold), Draconic Influence (Ryphorian) |
| 17 | **One-time ritual metamorphosis: permanent Enlarge + max HP +L** | Scion Transformation (Lizardfolk), Strength of Eight Legions (Yaksha) |
| 17 | Permanent Huge + 10-ft reach + max HP +L; permanent Large | Jotun's Heart (Jotunborn), Enlightened Rivener (Ikeshti) |
| 17 | 1/day battle form of the ancestry's "ultimate" or legendary form | Gigafuroid Form ("your species' ultimate evolution"), Legendary Monster (Yaoguai), Creature Shape (8th rank), Size of the Ancients (Huge) |

## Budget per Feat Level

What a single official ancestry feat usually buys:

- **1st:** one of: an unarmed attack (1d6), an at-will cantrip, two trained skills plus a
  Lore, +5 ft Speed, swim 10–20, scent 30, burst flight (fly 15 once per round), a recharge
  breath weapon (⌈L/2⌉d4), or a narrow resistance (half level). About 95 of the
  ~800 1st-level feats are skill training or bonus skill feats, so a "flavor" feat is a
  normal choice.
- **5th:** climb 10–20, a burst-flight upgrade, resistance (half level) to one type, a rank-1
  innate spell 1/day, an imprecise special sense, or small 1–2/day healing.
- **9th:** permanent flight (end of a chain), burrow 15 (Starfinder), a rank-3 innate spell
  1/day, a 1/day area attack of about (L/2)d6, max HP +L, a second resistance, or Enlarge 1/day.
- **13th:** burrow 15 (Pathfinder), a rank-5 innate spell 1/day, permanent Large, immunity to
  one energy type (rare), or a 1/day 7d6–8d6 area attack.
- **17th:** a rank-7 innate spell 1/day, a permanent size increase + max HP +L, a 1/day
  ultimate battle form, death avoidance 1/day, or resistance 20 or condition immunity.

## Implications for Pokémon (Input for Phase 3)

- **Flying types:** the burst → burst upgrade → permanent chain (1/5/9) fits directly. A
  Flying-type evolution heritage can unlock the chain, the way Flying Animal and Skyborn
  Tengu do. Permanent flight before 9th would need Starfinder-style trade-offs (land Speed 5,
  Tiny, or 6 HP).
- **Water types:** swim at 1st level is cheap (ancestry, heritage or feat).
- **Ground types:** burrow belongs at 9th (Starfinder) or 13th (Pathfinder). Pick one level
  for both games, probably 9th.
- **Damaging moves:** the breath-weapon template (1st, recharge) is the standard "signature
  move". Bigger once-per-day moves follow the area-attack ladder at 9/13/17.
- **Type resistances:** half level from a heritage at 1st, plus another at 5th or 9th from
  feats.
- **Type immunities (for example Ground vs. Electric, or Ghost vs. Normal) have almost no
  precedent.** One energy immunity exists, at 13th, after a resistance. Low-level Pokémon
  immunities will need to become resistance, with immunity as a 13th-level capstone.
- **Evolution:** official feats already grow characters a size step (1st, 13th, 17th), and
  a 17th-level ritual metamorphosis adds +L max HP. These are the anchors for how evolution
  heritages and feats should scale.
- **Mega Evolution / Gigantamax:** the 17th-level 1/day "ultimate form" battle form is the
  closest precedent.
