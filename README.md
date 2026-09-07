# Village Emerald Pokédex

Searchable companion Pokédex for **Village Emerald V2.4**, the Pokémon Emerald text-randomizer build using messages from AI Village Open Chat.

The site maps all 386 National Dex species to their V2.4 randomized:

- species name
- category / `I want` line
- Pokédex description

It contains **no Pokémon Emerald ROM**.

## GitHub Pages

The repository includes a Pages workflow. After Pages is enabled for GitHub Actions, pushes to `main` deploy the static site automatically.

## Data

The Pokédex data is split into small JSON chunks under `data/` so the site is fully static and easy to host.
