# Pokémon Ancestries for Pathfinder 2e & Starfinder 2e

Fan-made player ancestries for every Pokémon, built for the Pathfinder Second Edition
and Starfinder Second Edition core rules (Player Core / Remaster-compatible).

## Layout

```
ancestries/           One file per evolution line, named for the base Pokémon, grouped by generation
                      (e.g. ancestries/gen-1/bulbasaur.md covers Bulbasaur, Ivysaur, Venusaur)
versatile-heritages/  Regional forms (one per region) and the Shiny heritage, usable across ancestries
templates/            Starting templates for ancestries and regional heritages
reference/            Shared design notes: type-to-trait mappings, balance guidelines, house rules
```

## Writing an ancestry

Every evolution line already has a stub in `ancestries/gen-<n>/`; progress is tracked in
[TODO.md](TODO.md).

1. Open the stub for the line's base Pokémon (`mime-jr.md`, `farfetchd.md`).
2. Keep the pre-filled evolution line, types and regional form lists; replace the `<placeholders>`.
3. The ancestry statistics describe the base form; each evolution is a heritage.
4. Fill in every section; keep PF2e and SF2e differences in the dedicated SF2e section.

## Legal

This is an unofficial, non-commercial fan project. Pokémon and all related names are
trademarks of Nintendo, Creatures Inc., and GAME FREAK inc. Pathfinder and Starfinder are
trademarks of Paizo Inc. Game mechanics reference the ORC License; no affiliation with or
endorsement by any of these companies is implied.
