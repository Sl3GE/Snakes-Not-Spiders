# Snakes Not Spiders

A Minecraft Java Edition resource pack that replaces **spiders** and **cave spiders** with snakes. Nothing else is overridden.

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
