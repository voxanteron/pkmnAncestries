# Official Ancestry Baseline

Survey of every official Pathfinder 2e and Starfinder 2e ancestry from **Player Core (Nov 2023)
onward**: Pathfinder Player Core 1/2 and later books, and all of Starfinder 2e. This is the raw
comparison data that `reference/balance-guidelines.md` is derived from.

- **Source:** Foundry VTT `pf2e` system data (`packs/pf2e` and `packs/sf2e`), commit
  `4cf4c97` (2026-10-12). Only entries Foundry flags as remastered are included; all are ORC
  content. Rules text is summarized, not reproduced; see [Archives of Nethys](https://2e.aonprd.com)
  / [AoN Starfinder](https://2e.aonsrd.com) for full text.
- **Excluded:** legacy (OGL) ancestries such as Anadi, Conrasu, Fleshwarp, Ghoran, Goloma,
  Kashrishi, Kitsune, Nagaji, Poppet, Shisk, Shoony, Skeleton, Sprite, Vanara, Vishkanya,
  the PF2e Android and Azarketi, and the Rage of Elements versatile heritages (published
  before Player Core).
- **Counts:** 34 Pathfinder + 60 Starfinder = 94 ancestries.
- **Remaster rule for every ancestry:** a player may swap the listed boosts and flaw for two
  free boosts and no flaw.

## Summary Statistics

| Stat | Pathfinder (34) | Starfinder (60) | Combined (94) |
| --- | --- | --- | --- |
| HP 6 | 7 | 26 | 33 (35%) |
| HP 8 | 20 | 25 | 45 (48%) |
| HP 10 | 6 | 9 | 15 (16%) |
| HP by size choice | 1 (Awakened Animal) | 0 | 1 |
| Tiny | 1 | 3 | 4 |
| Small | 9 | 14 | 23 |
| Medium | 19 | 34 | 53 |
| Large | 3 | 7 | 10 |
| Size by choice | 2 | 2 | 4 |
| Land Speed 20 | 4 | 16 | 20 |
| Land Speed 25 | 27 | 40 | 67 |
| Land Speed 30 | 2 | 2 | 4 |
| Land Speed 5 (non-walker) | 1 | 2 | 3 |
| Swim Speed at 1st level (ancestry) | 2 | 3 | 5 |
| Fly Speed at 1st level (ancestry) | 0 | 4 | 4 |
| Boosts: 2 fixed + free, 1 flaw | 27 | 54 | 81 |
| Boosts: 1 fixed + free, no flaw | 5 | 0 | 5 |
| Boosts: 2 free, no flaw | 2 | 5 | 7 |
| Boosts: other | 0 | 1 (Lashunta) | 1 |
| Darkvision | 12 | 17 | 29 |
| Low-light vision | 15 | 21 | 36 |
| Normal vision | 7 | 22 | 29 |

## Patterns That Matter for Pokémon

### HP, Size and Speed

- **HP 8 is the default; 6 and 10 are the edges.** No official ancestry goes outside 6–10.
  HP 10 usually pairs with a Con or Str boost and/or a slow Speed (Dwarf, Vesk, Hardor at
  Speed 20). HP 6 pairs with mobility, Dex, or small size (Elf at Speed 30, Goblin,
  Halfling).
- **HP can scale with size.** Awakened Animal picks its size at creation: Tiny 6 / Small 6 /
  Medium 8 / Large 10 HP. This is the closest official model for Pokémon of very different
  sizes.
- **Size is set by heritage more often than by ancestry.** Heritages move size up or down
  one step: Towering Bugbear and Hopeful Athamaru (to Large), Littlehorn Minotaur and
  Ponygait Centaur (to Medium), New Moon Sarangay and Ant Kholo (to Small), and Proudhome
  vs. Sand Roamer Pahtra (Large vs. Small). This supports evolution heritages that grow a
  size step.
- **Tiny ancestries** (Dragonet, Mecenaic, Novian, Raxilite) run 6–8 HP and Speed 20–25. Some
  get a workaround for reach or manipulation (Raxilite's LFAN, Novian's gravitational hands).
  Dragonet compensates with a 1d4 jaws attack and no falling damage.
- **Large ancestries** (Centaur, Minotaur, Jotunborn, Dragonkin, Izalguun, Ord, Sarcesian,
  Shobhad, Trox, Urog) range from 6 HP (Urog) to 10 HP, with Speed 20–30. Large size has no
  consistent stat cost; its price is mostly practical (space, squeezing, gear size).
- **Land Speed 25 is standard.** 30 appears only four times: on Elf (6 HP, both games), Centaur
  (a quadruped), and Verthani. 20 usually offsets high HP (Dwarf, Vesk, Hardor) or a Tiny body.

### Special Movement at 1st Level

- **Swim** at 1st level is common and cheap: swim 25 for Athamaru and Merfolk, 10–30 for
  Kalo (30), Brenneri (20) and Ijtikri (10), plus many 1st-level heritages with swim 10–30 (Aquatic Elf 30,
  Wetlander Lizardfolk 15, Seaweed Leshy 20).
- **Climb** at 1st level appears on ancestries (Gnarefuroid 15, Ikeshti 15, Khizar 20,
  Vulkarisu 15) and on heritages (Climbing Animal 20, Jungle Brenneri 20).
- **Burrow** at 1st level is rare: Talphi 15 (ancestry), and heritages Burrow-Sworn
  Vulkarisu 10 and Builder Formian 5.
- **Fly at 1st level does not appear in Pathfinder.** Strix, Dragonet and Awakened Animal
  (Flying Animal heritage) get jump or fall benefits instead. Flying Animal points to a 1st-level
  Take Flight feat for limited flight, and full flight comes later through feats; Phase 2 will
  survey those levels. Starfinder allows a **fly 20** base Speed on four ancestries. Three pay for
  it: Barathu and Contemplative have land Speed 5, and Novian is Tiny with 6 HP. Dragonkin is the
  outlier (Large, 10 HP, land 20, fly 20, two free boosts). Starfinder heritages also grant fly 15–20 (Winged Shirren, Winged Bantrid).
- **Non-walkers** (Merfolk, Barathu, Contemplative) use land Speed 5 and get their real
  movement as swim or fly.

### Natural Attacks

- **1st-level unarmed attacks** are 1d4 (usually agile + finesse: Lizardfolk claws, Ratfolk
  teeth, Dragonet jaws) or 1d6 (Kholo jaws, Tengu beak, Sarangay horns with shove). The
  largest is 1d8 (Nuar horns). Many heritages add one 1d4–1d6 attack instead (Clawed Catfolk,
  Razortooth Goblin, Cactus Leshy, Taloned Tengu).
- A few attacks deal a **non-physical type** at 1st level: Fork-tongued Vesk (1d4 poison) and
  Swarm Exile Shirren (1d6 acid). Typed Pokémon attacks (Fire Fang, Thunder Punch) can follow
  this precedent.

### Senses, Resistances and Built-in Powers

- **Darkvision vs. low-light vision** has no visible cost difference in the stat lines: about
  a third of ancestries get each, and a third get neither. Starfinder also sells darkvision as a 1st-level feat (Ancestral
  Darkvision, requires low-light vision).
- **Imprecise senses** appear at 1st level: scent 60 (Vlaka), thoughtsense 20
  (Contemplative), emotionsense 20 (Moyishuu), and precise hearing 60 (Ord, which is
  sightless).
- **Resistance comes from heritages, not ancestries.** About 45 remaster heritages grant
  **one resistance equal to half your level (minimum 1)** at 1st level: fire (Forge Dwarf,
  Charhide Goblin), cold (Arctic Elf, Snow Goblin), electricity (Stormtossed Tengu), poison,
  acid, void, mental and sonic. This is the standard size of a heritage benefit, and the natural
  model for a Pokémon type resistance. Only Ijtikri (precision) has resistance as an ancestry
  feature. Feats add more resistance from 5th level (see
  [ancestry-feat-benchmarks.md](ancestry-feat-benchmarks.md)). Heritages with a weakness are rare (Surithic Worlanisi, mental).
- **Limited telepathy (30 ft)** is a common Starfinder ancestry feature (12 ancestries).
- **Signature attack at 1st level:** G'folian Fire Breath is a 15-ft cone of
  (level/2)d4 fire, basic Reflex save, recharging in 1d4 rounds. It is the only official
  breath-weapon-style innate ability, and the closest model for Ember, Water Gun and similar
  moves.
- **Change Shape:** Tanuki, Yaoguai and Astrazoan get innate transformation. This is a model
  for Ditto/Zoroark-style lines.

### Drawbacks That Pay for Power

Powerful ancestries often carry a written drawback, not just a stat flaw:

- Merfolk and Kalo: Hydration (penalties after 24 hours out of water).
- Contemplative: Atrophied (reduced Bulk, clumsy with heavy items) in exchange for fly 20 and telepathy.
- Worlanisi: Psychic Reverb (mental weakness and save penalty) in exchange for four arms.
- Bantrid: Restless (frightened while immobilized).
- Brenneri: Empathetic Whiskers (a Will penalty against emotion effects).
- Urog: Direct Approach (−1 Deception and Diplomacy).

This is the template for Pokémon weaknesses, such as Fire types in water or Bug types and
Flying.

### Heritage Counts

Player Core ancestries have 6–12 heritages (counting later books); most others have 3–6. For Pokémon,
evolution heritages plus regional/Shiny versatile heritages usually land at 2–4, which is
fine. Lines with only one stage may need 1–2 non-evolution heritages, such as habitat or
temperament variants.

## Starfinder Standardized Ancestry Feats

Starfinder 2e defines one shared set of feats. Each ancestry fills in the values: its two
skills, its attack, its resistance type, and its climb, swim or fly Speed. This is very likely
the right architecture for 541 Pokémon lines: define the feats once in `reference/`, and give
each ancestry file a short table of values.

| Level | Feat | What the ancestry supplies |
| --- | --- | --- |
| 1 | Ancestral Skills | Two trained skills + an ancestry Lore |
| 1 | Ancestral Unarmed Attack | One or more listed attacks; crit specialization at 5th |
| 1 | Ancestral Cantrip | A list of cantrips (repeatable) |
| 1 | Ancestral Darkvision | Requires low-light vision |
| 1 | Ancestral Weapon Familiarity | Ancestry weapons |
| 1 | Swimming Specialist | Swim Speed (10–30) |
| 1 | Basic Flight | Once per minute Fly at the Flight Specialist Speed; fall if not landed |
| 1 | Creature Speech | A related creature type |
| 1 | Enhanced Senses / Distant Telepath / Linguistic Prodigy | Extends an existing sense or telepathy |
| 5 | Climbing Specialist | Climb Speed (10–25) |
| 5 | Ancestral Magic | 1st-rank innate spell 1/day; rank 3/5/7 if taken at 9/13/17 |
| 5 | Ancestral Pest | Pest Form limited to a listed animal |
| 5 | Prehensile Limbs | Tail or tendril works as an extra hand |
| 5 | Mount | Large only |
| 5 | Wind Walker | Requires fly Speed or Basic Flight; Stride as Fly |
| 9 | Ancestral Resistance | Resistance equal to half your level vs. a listed type |
| 9 | Burrowing Specialist | Burrow Speed (10–15) |
| 9 | Flight Specialist | Permanent fly Speed (requires Basic Flight) |
| 13 | Creature Ally | 5th-rank summon of a listed creature, 1/day |
| 17 | Creature Shape | 8th-rank polymorph into the listed creature, 1/day |

Each ancestry's values live in its entry (examples): Ysoki burrow 10 / climb 10, Brenneri
swim 30, Raxilite fly 20, Kasatha resistance fire or cold, Vesk attacks claw/jaws/tail.

**Level gates in one line:** swim and limited flight at 1st, climb at 5th, burrow, full flight
and a second resistance at 9th, innate spells starting at 5th, summons at 13th, battle form at
17th.

## Versatile Heritages (Player Core onward)

These are models for the Shiny and regional-form versatile heritages.

| Game | Versatile heritage | Source |
| --- | --- | --- |
| Pathfinder | Aiuvarin, Changeling, Dromaar, Nephilim | Player Core |
| Pathfinder | Dhampir, Dragonblood, Duskwalker | Player Core 2 |
| Pathfinder | Hungerseed | LO: Tian Xia Character Guide |
| Pathfinder | Reflection | Dark Archive (Remastered) |
| Starfinder | Borai, Prismeni | Player Core |
| Starfinder | Cyborg | Tech Core |
| Starfinder | Corpsefolk | Guilt of the Grave World |
| Starfinder | Gap-Touched, Xenometric Android | Galactic Ancestries |

## Pathfinder 2e Ancestries

Speed is land Speed in feet; other movement types are in parentheses. "Type" is the creature
type trait. "Heritages" counts heritages in Foundry's data for that ancestry, which may include
heritages from later books.

| Ancestry | Source | Rarity | HP | Size | Speed (other) | Boosts | Flaw | Vision | Type | Heritages | Innate features |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Athamaru | Howl of the Wild | Uncommon | 8 | Medium | 20 (swim 25) | Str, Wis, Free | Int | Low-light | humanoid | 5 | — |
| Automaton | Guns & Gears | Rare | 8 | Medium/Small (choice) | 25 | Str, Free | — | Low-light | construct | 6 | Automaton Core; Constructed Body |
| Awakened Animal | Howl of the Wild | Rare | 6–10 (by size) | Tiny–Large (choice) | 20 | Con, Wis, Free | Int | — | beast | 4 | Awakened Mind; Awakened Form; land 20 + attack set by heritage |
| Bugbear | LO: Cheliax, Infernal Inheritance | Uncommon | 10 | Medium | 25 | Str, Cha, Free | Int | Darkvision | humanoid | 6 | — |
| Catfolk | Player Core 2 | Uncommon | 8 | Medium | 25 | Cha, Dex, Free | Wis | Low-light | humanoid | 8 | Land on Your Feet |
| Centaur | Howl of the Wild | Uncommon | 8 | Large | 30 | Str, Wis, Free | Cha | Darkvision | beast, humanoid | 6 | Mount; Robust |
| Dragonet | LO: Draconic Codex | Rare | 8 | Tiny | 20 | Dex, Cha, Free | Con | Darkvision | dragon | 5 | Big Sharp Teeth (1d4 piercing); Wings (Dragonet) |
| Dwarf | Player Core | Common | 10 | Medium | 20 | Con, Wis, Free | Cha | Darkvision | humanoid | 9 | Clan Dagger |
| Elf | Player Core | Common | 6 | Medium | 30 | Dex, Int, Free | Con | Low-light | humanoid | 8 | — |
| Fetchling | LO: Cheliax, Infernal Inheritance | Uncommon | 8 | Medium | 25 | Dex, Free | — | Darkvision | humanoid | 5 | — |
| Gnome | Player Core | Common | 8 | Small | 25 | Cha, Con, Free | Str | Low-light | humanoid | 7 | — |
| Goblin | Player Core | Common | 6 | Small | 25 | Cha, Dex, Free | Wis | Darkvision | humanoid | 8 | — |
| Halfling | Player Core | Common | 6 | Small | 25 | Dex, Wis, Free | Str | — | humanoid | 7 | Keen Eyes |
| Hobgoblin | Player Core 2 | Uncommon | 8 | Medium | 25 | Con, Int, Free | Wis | Darkvision | humanoid | 7 | — |
| Human | Player Core | Common | 8 | Medium | 25 | Free, Free | — | — | humanoid | 6 | — |
| Jotunborn | Battlecry! | Rare | 10 | Large | 25 | Str, Wis, Free | Cha | Low-light | giant, humanoid | 5 | Iivlar Weaving |
| Kholo | Player Core 2 | Uncommon | 8 | Medium | 25 | Str, Int, Free | Wis | Low-light | humanoid | 7 | Bite (1d6 piercing) |
| Kobold | Player Core 2 | Uncommon | 6 | Small | 25 | Cha, Dex, Free | Con | Darkvision | humanoid | 10 | — |
| Leshy | Player Core | Common | 8 | Small | 25 | Con, Wis, Free | Int | Low-light | plant | 12 | Plant Nourishment |
| Lizardfolk | Player Core 2 | Uncommon | 8 | Medium | 25 | Str, Wis, Free | Int | — | humanoid | 9 | Aquatic Adaptation; Claws (1d4 slashing) |
| Merfolk | Howl of the Wild | Uncommon | 8 | Medium | 5 (swim 25) | Dex, Cha, Free | Con | Low-light | humanoid | 6 | Hydration (Merfolk); Aquatic Grace |
| Minotaur | Howl of the Wild | Uncommon | 10 | Large | 25 | Str, Con, Free | Cha | Darkvision | beast, humanoid | 6 | Horns (unarmed attack) |
| Orc | Player Core | Common | 10 | Medium | 25 | Free, Free | — | Darkvision | humanoid | 7 | — |
| Ratfolk | Player Core 2 | Uncommon | 6 | Small | 25 | Dex, Int, Free | Str | Low-light | humanoid | 7 | Sharp Teeth (1d4 piercing) |
| Samsaran | LO: Tian Xia Character Guide | Uncommon | 8 | Medium | 25 | Con, Wis, Free | Cha | Low-light | humanoid | 5 | Cryptomnesia; Wanderer's Soul |
| Sarangay | LO: Tian Xia Character Guide | Rare | 8 | Medium | 25 | Str, Cha, Free | Wis | — | humanoid | 5 | Head Gem; Horns (Sarangay) (1d6 piercing) |
| Strix | LO: Cheliax, Infernal Inheritance | Rare | 8 | Medium | 25 | Dex, Free | — | Low-light | humanoid | 5 | Wings |
| Surki | Howl of the Wild | Rare | 8 | Medium | 25 | Con, Free | — | Darkvision | humanoid | 4 | Magiphage |
| Tanuki | LO: Tian Xia Character Guide | Uncommon | 10 | Small | 25 | Con, Cha, Free | Wis | — | humanoid | 5 | Change Shape (tanuki form) |
| Tengu | Player Core 2 | Uncommon | 6 | Medium | 25 | Dex, Free | — | Low-light | humanoid | 7 | Sharp Beak (1d6 piercing) |
| Tripkee | Player Core 2 | Uncommon | 6 | Small | 25 | Dex, Wis, Free | Str | Low-light | humanoid | 7 | Natural Climber |
| Wayang | LO: Tian Xia Character Guide | Uncommon | 8 | Small | 25 | Dex, Cha, Free | Con | Darkvision | humanoid | 5 | — |
| Yaksha | LO: Tian Xia Character Guide | Rare | 8 | Medium | 25 | Con, Cha, Free | Int | Low-light | spirit | 6 | — |
| Yaoguai | LO: Tian Xia Character Guide | Rare | 8 | Medium | 25 | Cha, Con, Free | Int | — | humanoid | 5 | Change Shape (animal/object form) |

## Starfinder 2e Ancestries

| Ancestry | Source | Rarity | HP | Size | Speed (other) | Boosts | Flaw | Vision | Type | Heritages | Innate features |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Android | Player Core | Common | 8 | Medium | 25 | Dex, Int, Free | Cha | Low-light | humanoid | 9 | Constructed |
| Astrazoan | Galaxy Guide | Common | 8 | Medium | 25 | Dex, Cha, Free | Con | Low-light | aberration | 5 | Change Shape |
| Atraxid | Secrets of the Swarm Adventure Path | Common | 8 | Medium | 20 | Dex, Int, Free | Wis | Darkvision | beast, humanoid | 3 | Climbing Prowess |
| Bantrid | Galactic Ancestries | Common | 6 | Small | 25 | Con, Dex, Free | Wis | Darkvision | aberration | 6 | Restless; Anosmatic |
| Barathu | Player Core | Common | 8 | Medium | 5 (fly 20) | Con, Wis, Free | Dex | — | aberration | 10 | Limited Telepathy; Genetic Adaptation |
| Binnaquid | Secrets of the Swarm Adventure Path | Common | 10 | Medium | 25 | Con, Wis, Free | Cha | Darkvision | beast, humanoid | 3 | Breathing Underwater |
| Brenneri | Galactic Ancestries | Common | 8 | Medium | 25 (swim 20) | Con, Cha, Free | Str | Darkvision | humanoid | 6 | Empathetic Whiskers; Breath Control |
| Contemplative | Galaxy Guide | Common | 6 | Medium | 5 (fly 20) | Cha, Int, Free | Str | Low-light | aberration | 5 | Limited Telepathy; Atrophied; Thoughtsense |
| Copaxi | Galactic Ancestries | Common | 6 | Medium | 25 | Con, Cha, Free | Wis | — | humanoid | 6 | Gravitonic Attunement; Regenerative Evolution |
| Dragonkin | Galaxy Guide | Common | 10 | Large | 20 (fly 20) | Free, Free | — | Darkvision | dragon, humanoid | 5 | Partner Bond |
| Dwarf | Galactic Ancestries | Common | 10 | Medium | 20 | Con, Wis, Free | Cha | Darkvision | humanoid | 5 | Clan Crystal |
| Elebrian | Guilt of the Grave World | Common | 6 | Medium | 25 | Con, Int, Free | Wis | — | humanoid | 4 | Magical Sense |
| Elf | Galactic Ancestries | Common | 6 | Medium | 30 | Dex, Int, Free | Con | Low-light | humanoid | 4 | — |
| Entu Colony | Galactic Ancestries | Common | 6 | Small | 20 | Con, Wis, Free | Cha | — | — | 5 | Limited Telepathy |
| Fonqugon | Galactic Ancestries | Common | 6 | Small | 20 (climb 5) | Con, Int, Free | Cha | Low-light | ooze | 5 | Oozy |
| Formian | Galactic Ancestries | Common | 6 | Medium | 25 | Free, Free | — | Low-light | — | 5 | Limited Telepathy |
| G'folian | Galactic Ancestries | Common | 8 | Medium | 25 | Con, Wis, Free | Str | Low-light | beast | 5 | Fire Breath |
| Gnarefuroid | Absalom Station | Rare | 8 | Small | 20 (climb 15) | Con, Int, Free | Cha | Low-light | aberration | 5 | Stowaway |
| Gnome | Galactic Ancestries | Common | 8 | Small | 25 | Con, Cha, Free | Str | Low-light | humanoid | 4 | — |
| Goblin | Galactic Ancestries | Common | 6 | Small | 25 | Dex, Cha, Free | Wis | Darkvision | humanoid | 4 | — |
| Halfling | Galactic Ancestries | Common | 6 | Small | 25 | Dex, Wis, Free | Str | — | humanoid | 4 | Keen Eyes |
| Hardor | Secrets of the Swarm Adventure Path | Common | 10 | Medium | 20 | Con, Wis, Free | Cha | Low-light | plant | 4 | Plant Nourishment (Hardor); Limited Telepathy |
| Human | Player Core | Common | 8 | Medium | 25 | Free, Free | — | — | humanoid | 9 | — |
| Ijtikri | Galactic Ancestries | Common | 8 | Medium | 25 (swim 10) | Con, Wis, Free | Cha | Darkvision | aberration | 5 | Mantle |
| Ikeshti | Invasion's Edge Player's Guide | Common | 6 | Small | 25 (climb 15) | Dex, Int, Free | Wis | — | humanoid | 6 | — |
| Izalguun | Galactic Ancestries | Common | 8 | Large | 20 | Str, Int, Free | Dex | Darkvision | beast, humanoid | 5 | Four-Armed; Posture |
| Kalo | Galaxy Guide | Common | 6 | Medium | 20 (swim 30) | Dex, Cha, Free | Con | Darkvision | humanoid | 4 | Hydration |
| Kasatha | Player Core | Common | 8 | Medium | 25 | Str, Wis, Free | Cha | — | humanoid | 9 | Four-Armed |
| Khizar | Murder in Metal City Deluxe Adventure | Uncommon | 8 | Medium | 20 (climb 20) | Con, Wis, Free | Dex | — | plant | 4 | Limited Telepathy; Verdant |
| Lashunta | Player Core | Common | 6 | Medium | 25 | Cha, Free | Any (choice) | — | humanoid | 7 | Limited Telepathy |
| Leshy | Galactic Ancestries | Common | 8 | Small | 25 | Con, Wis, Free | Int | Low-light | plant | 5 | Plant Nourishment |
| Living Hologram | Tech Core | Common | 6 | Small/Medium/Large (choice) | 25 | Dex, Cha, Free | Str | — | construct | 6 | Hardlight Healing; Virtual Storage; Hardlight Body |
| Madrosarai | Galactic Ancestries | Common | 8 | Medium | 25 | Dex, Cha, Free | Str | — | humanoid | 6 | Contained Emotions |
| Maraquoi | Galactic Ancestries | Common | 8 | Medium | 25 (climb 15) | Free, Free | — | Low-light | humanoid | 5 | Prehensile Tail; Dermal Hearing |
| Mecenaic | Secrets of the Swarm Adventure Path | Common | 8 | Tiny | 20 | Str, Int, Free | Dex | — | aberration | 4 | Four-Armed; Limited Telepathy |
| Moyishuu | Galactic Ancestries | Common | 8 | Medium | 25 | Dex, Cha, Free | Wis | — | fey, humanoid | 4 | Soulfeel; Emotionsense |
| Novian | Galactic Ancestries | Common | 6 | Tiny | 20 (fly 20) | Str, Cha, Free | Wis | — | — | 6 | Gravitational Hands; Solar Luminance |
| Nuar | Absalom Station | Uncommon | 10 | Medium | 25 | Con, Int, Free | Cha | Darkvision | humanoid | 5 | Gravitational Adept; Horns (1d8 piercing) |
| Orc | Galactic Ancestries | Common | 10 | Medium | 25 | Free, Free | — | Darkvision | humanoid | 5 | — |
| Ord | Secrets of the Swarm Adventure Path | Common | 8 | Large | 25 | Dex, Cha, Free | Int | — | humanoid | 4 | Sightless; Precise Hearing |
| Orocoran | Galactic Ancestries | Common | 6 | Medium | 25 | Dex, Wis, Free | Con | Darkvision | aberration | 5 | Limited Telepathy |
| Osharu | Galactic Ancestries | Common | 6 | Medium | 25 | Int, Wis, Free | Con | Darkvision | humanoid | 6 | Slime Squirt |
| Pahtra | Player Core | Common | 8 | Medium | 25 | Cha, Dex, Free | Con | Darkvision | humanoid | 8 | — |
| Phasorq | Secrets of the Swarm Adventure Path | Common | 6 | Medium | 25 | Int, Wis, Free | Con | Low-light | humanoid | 4 | Wakeful; Twice the Training |
| Raxilite | Galactic Ancestries | Common | 6 | Tiny | 25 | Dex, Int, Free | Str | Low-light | plant | 5 | LFAN |
| Ryphorian | Galactic Ancestries | Common | 8 | Medium | 25 | Con, Wis, Free | Str | Low-light | humanoid | 6 | Notched Ears |
| Sarcesian | Galaxy Guide | Common | 8 | Large | 25 | Dex, Cha, Free | Str | — | humanoid | 5 | Suspended Respiration; Energy Wings |
| Shirren | Player Core | Common | 10 | Medium | 25 | Con, Wis, Free | Cha | — | humanoid | 9 | Limited Telepathy |
| Shobhad | Invasion's Edge Player's Guide | Common | 8 | Large | 25 | Str, Wis, Free | Cha | — | humanoid | 6 | Four-Armed |
| Skittermander | Player Core | Common | 6 | Small | 25 | Cha, Dex, Free | Wis | Low-light | humanoid | 9 | Six-Armed |
| SRO | Tech Core | Common | 8 | Small/Medium/Large (choice) | 25 | Dex or Str, Int, Free | Cha | — | construct | 6 | Frame; Robotic Body; Healing Circuits |
| Talphi | Galactic Ancestries | Common | 6 | Small | 20 (burrow 15) | Dex, Cha, Free | Wis | — | humanoid | 5 | — |
| Trox | Galactic Ancestries | Common | 10 | Large | 25 | Str, Con, Free | Dex | Darkvision | humanoid | 5 | Vestigial Arms |
| Urog | Galactic Ancestries | Common | 6 | Large | 20 | Con, Int or Wis, Free | Cha | Darkvision | beast | 6 | Epistemological Approach; Direct Approach; Limited Telepathy |
| Verthani | Tech Core | Common | 8 | Medium | 30 | Con, Int, Free | Str | Low-light | humanoid | 6 | Skin Artistry |
| Vesk | Player Core | Common | 10 | Medium | 20 | Con, Str, Free | Wis | Low-light | humanoid | 10 | — |
| Vlaka | Galaxy Guide | Common | 6 | Medium | 25 | Wis, Cha, Free | Dex | — | humanoid | 6 | Sensory Diversity; Versed |
| Vulkarisu | Beyond the Blood Door Player's Guide | Common | 6 | Small | 25 (climb 15) | Cha, Dex, Free | Str | Low-light | humanoid | 6 | Land on Your Feet |
| Worlanisi | Galactic Ancestries | Common | 6 | Small | 20 | Str, Cha, Free | Wis | Low-light | humanoid | 5 | Psychic Reverb; Limited Telepathy; Four-Armed |
| Ysoki | Player Core | Common | 6 | Small | 25 | Dex, Int, Free | Str | Low-light | humanoid | 8 | Sharp Teeth |
