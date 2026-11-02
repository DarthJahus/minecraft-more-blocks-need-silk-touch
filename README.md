# Make Silk Touch Great Again
Composite blocks that are crafted from multiple parts no longer drop themselves without **Silk Touch**.
Without Silk Touch, they break into their components (usually one less than the crafting recipe).

Companion to [Logs need Silk Touch](https://modrinth.com/datapack/jahus-logs-need-silk-touch)

## Rules

1. Block is crafted from multiple pieces
2. No crafting-table uncraft path
3. Without Silk Touch, you only get the parts (typically **N−1**)
4. With Silk Touch, you get the block itself
5. Brick-type blocks are excluded (for now)

## Blocks

| Block | Without Silk Touch |
|-------|--------------------|
| Quartz Block | 3 quartz |
| Prismarine | 3 prismarine shards |
| Dark Prismarine | 7 prismarine shards (black dye is not returned) |
| Sea Lantern | 4 prismarine crystals + 4 prismarine shards |
| Amethyst Block | 3 amethyst shards |
| Dripstone Block | 3 pointed dripstone |
| Sulfur | 3 sulfur spikes |
| Magma Block | 3 magma cream |

## Not included
- Logs / stems / wood: use **[Logs need Silk Touch](https://modrinth.com/datapack/jahus-logs-need-silk-touch)**
- Stone bricks, nether bricks, purpur (brick-like)
- Blocks that already uncraft on the crafting table (iron_block, diamond_block, etc.)

## Licence
Apache 2.0
