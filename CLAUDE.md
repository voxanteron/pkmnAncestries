# CLAUDE.md

Fan project: playable ancestries for every Pokémon, for Pathfinder 2e and Starfinder 2e
(Remaster / Player Core rules).

## Conventions

- One ancestry per **evolution line**, one Markdown file each, in `ancestries/gen-<n>/`. The
  ancestry is the line's base (lowest) Pokémon; the filename and generation folder come from it
  (lowercase, hyphenated: `ancestries/gen-1/bulbasaur.md` covers Bulbasaur → Ivysaur → Venusaur).
- Evolved forms are **heritages** of that ancestry (one per branch for branching lines).
- Pathfinder 2e and Starfinder 2e are covered in the same file.
- Regional variants (Alolan, Galarian, Hisuian, Paldean, …) are **versatile heritages**, one
  shared file per region in `versatile-heritages/` (from `templates/regional-heritage-template.md`).
  Line-specific changes go in the ancestry's "Regional Forms" section.
- **Shiny** is a single versatile heritage (`versatile-heritages/shiny.md`) shared by every line.
- Every new ancestry starts from `templates/ancestry-template.md`; keep its section order.
- Use Remaster terminology (attribute boosts/flaws, not ability scores; "edicts/anathema").
- Balance against official Player Core ancestries: 6–10 HP, standard boost/flaw pattern,
  feats at levels 1/5/9/13/17.
- Starfinder-specific changes go only in the "Starfinder 2e Notes" section.
- Shared mechanics (Pokémon type traits, balance rules) live in `reference/` — reuse rather
  than reinventing per ancestry.
- No remote is configured; do not add one.
