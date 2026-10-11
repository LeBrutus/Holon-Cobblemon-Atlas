# Holon Cobblemon Atlas

Where every Pokémon spawns on the **Holon** Cobblemon server, and what spawns in every biome.

| | |
| --- | --- |
| **[Pokémon](pokemon/README.md)** | One page per Pokémon, by generation: every biome it spawns in, with rarity, conditions and level range. |
| **[Biomes](biomes/README.md)** | One page per biome, by dimension: every Pokémon that spawns there, by rarity. |
| **[Full index](INDEX.md)** | Every Pokémon and biome page on one list. |
| **[Search page](https://lebrutus.github.io/Holon-Cobblemon-Atlas/)** | Search by name or Pokédex number and filter by dimension, rarity and type (`index.html`, served by GitHub Pages). |
| **[spawn_atlas.json](spawn_atlas.json)** | All the data as JSON. |

Tip: on GitHub, press **t** and type a Pokémon or biome name to jump straight to its page.

Covers all 1,025 Pokémon and 354 biomes across the Overworld, Nether, End, Aether and Otherside: vanilla, Terralith, Regions Unexplored, Sengoku Overhaul, BetterEnd, BetterNether, the Aether and Deeper and Darker.

## How to read a page

- **Rarity** is the spawn bucket: Common, Uncommon, Rare, Ultra rare, or **Alpha** (Cobblemon 1.8 boss Pokémon leading a herd).
- **Conditions** say when it spawns: night, rain, underground, water, fishing, villages, herd, with an alpha, a regional form, or biomes it avoids.
- **Lv** is the level range.
- **All Overworld biomes** means the Pokémon can appear in any overworld biome, unless the conditions exclude some.

The same information is in the in-game **Spawn Guide** books, which you receive when you pick your starter. `/trigger holon_guide` gives the guide again, and `/trigger holon_dex set <No.>` gives one Pokémon's book.

## Search page hosting

`index.html` is served by GitHub Pages. To turn it on: Settings → Pages → *Deploy from a branch* → `main` / `(root)`.

## Updating

Everything here is generated from the server's spawn datapack (`world/datapacks/holon_spawns_v2` in the server config repo). After changing spawns, regenerate the files and replace them here.
