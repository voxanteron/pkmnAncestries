# Pokémon Ancestries for Pathfinder 2e & Starfinder 2e

Fan-made player ancestries for every Pokémon, built for the Pathfinder Second Edition
and Starfinder Second Edition core rules (Player Core / Remaster-compatible).

## Layout

```
ancestries/           One file per evolution line, named for the base Pokémon, grouped by generation
                      (e.g. ancestries/gen-1/bulbasaur.md covers Bulbasaur, Ivysaur, Venusaur)
versatile-heritages/  Regional forms (one per region) and the Shiny heritage, usable across ancestries
templates/            Starting templates for ancestries and regional heritages
reference/    Shared design notes: type-to-trait mappings, balance guidelines, house rules
```

## Writing an ancestry

1. Copy `templates/ancestry-template.md` into the generation folder of the line's base Pokémon.
2. Name the file with the base Pokémon's lowercase, hyphenated name (`mime-jr.md`, `farfetchd.md`).
3. The ancestry statistics describe the base form; each evolution is a heritage.
4. List any regional forms the line has, pointing to the shared versatile heritage.
5. Fill in every section; keep PF2e and SF2e differences in the dedicated SF2e section.

## Legal

This is an unofficial, non-commercial fan project. Pokémon and all related names are
trademarks of Nintendo, Creatures Inc., and GAME FREAK inc. Pathfinder and Starfinder are
trademarks of Paizo Inc. Game mechanics reference the ORC License; no affiliation with or
endorsement by any of these companies is implied.
