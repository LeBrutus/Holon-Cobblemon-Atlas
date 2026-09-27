# Holon Cobblemon Atlas

Where every Pokémon spawns on the **Holon** Cobblemon server, and what spawns in every biome.

- **[Open the Atlas](https://lebrutus.github.io/Holon-Cobblemon-Atlas/)**: a searchable page.
  - **Pokémon view:** search by name or Pokédex number to see every biome it spawns in, with rarity, conditions and level range.
  - **Biomes view:** see everything that spawns in a biome.
  - Filters for dimension, rarity and type.
- **[Browse the pages](gitbook/README.md)**: one page per Pokémon and per biome, readable right here on GitHub or as a GitBook site.
- **[spawn_atlas.json](spawn_atlas.json)**: all the data as JSON.

Covers all 1,025 Pokémon and 354 biomes across the Overworld, Nether, End, Aether and Otherside: vanilla, Terralith, Regions Unexplored, Sengoku Overhaul, BetterEnd, BetterNether, the Aether and Deeper and Darker. Rarity is the spawn bucket (Common, Uncommon, Rare, Ultra rare). Conditions are when it spawns: night, rain, underground, water, fishing, villages or a regional form.

The same information is in the in-game **Spawn Guide** books, which you receive when you pick your starter. `/trigger holon_guide` gives the guide again, and `/trigger holon_dex set <No.>` gives one Pokémon's book.

## Hosting

- **GitHub Pages:** Settings → Pages → *Deploy from a branch* → `main` / `(root)`. The site is then at `https://lebrutus.github.io/Holon-Cobblemon-Atlas/`.
- **GitBook:** connect this repo with Git Sync on branch `main`, leaving the project directory empty. `gitbook-docs.yaml` maps the space to `gitbook/`.

## Updating

This repo is generated from the server's spawn datapack (`world/datapacks/holon_spawns_v2` in the server config repo) by `tools/holon_spawns/export.py` and `gitbook.py`. Regenerate and replace the files here after changing spawns.
