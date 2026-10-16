# Snakes Not Spiders

A Minecraft Java Edition resource pack that replaces **spiders** and **cave spiders** with snakes, including their spawn eggs, eyes, names, and entity models.

**Target version:** Java Edition 26.3 (resource pack format 97.1)

Custom snake models require [Entity Model Features](https://modrinth.com/mod/entity-model-features) (Fabric, Quilt, Forge, or NeoForge) **or** OptiFine with Custom Entity Models enabled. Without that, only the textures apply and spiders stay on the vanilla 8-legged mesh. Hitboxes are unchanged either way.

Placeholder textures are stubs. Real snake art will replace them later; file paths stay the same.

## Install

1. Install EMF **or** OptiFine (CEM on).
2. Copy or symlink this folder into `resourcepacks` (on macOS: `~/Library/Application Support/minecraft/resourcepacks`).
3. Enable **Snakes Not Spiders** in Options → Resource Packs.

## Layout

| File | Role |
| --- | --- |
| `assets/minecraft/textures/entity/spider/spider.png` | Snake stub for spiders |
| `assets/minecraft/textures/entity/spider/cave_spider.png` | Snake stub for cave spiders |
| `assets/minecraft/textures/entity/spider_eyes.png` | Transparent (hides vanilla glowing eyes) |
| `assets/minecraft/optifine/cem/spider.jem` | Custom snake model |
| `assets/minecraft/optifine/cem/cave_spider.jem` | Same mesh, smaller scale |
| `assets/minecraft/lang/en_us.json` | Snake names for mobs and items |
| `assets/minecraft/textures/item/spider_spawn_egg.png` | Snake spawn egg |
| `assets/minecraft/textures/item/cave_spider_spawn_egg.png` | Cave snake spawn egg |
| `assets/minecraft/textures/item/spider_eye.png` | Snake eye |
| `assets/minecraft/textures/item/fermented_spider_eye.png` | Fermented snake eye |
