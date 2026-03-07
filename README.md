# Minecraft Stick Fighters

A 2D stick figure fighting game that runs entirely in the browser. Inspired by Alan Becker's "Animation vs Minecraft" series.

## Play

Open `index.html` in any modern browser - no server or build step required.

Or play on GitHub Pages: https://zebra-rancher.github.io/minecraft-stick-fighters/

## Features

- **7 playable characters** with unique movesets and Minecraft weapons
- **5 Minecraft-themed stages** (Plains, Nether Fortress, The End, Jungle, Village)
- **Multiple game modes**: VS CPU, 1v1 Local, Story Mode, Training
- **Item drops**: Golden Apples, Potions, TNT, Ender Pearls, and more
- **Character unlocks** through Story Mode progression (3 unlockable fighters)
- **Combo attacks** using directional inputs + attack button
- **Enchanted weapons** with pixel-art rendering and shimmer effects
- **Training stage** with walls so you can't fall off

## Controls

| Action | Player 1 | Player 2 |
|--------|----------|----------|
| Move | Arrow Keys | WASD |
| Jump | Up Arrow | W |
| Crouch | Down Arrow | S |
| Attack | Space | E |

Combine directions with attack for different moves (up+attack = uppercut, forward+attack = thrust, etc.)

## Characters

| Character | Color | Weapon | Style |
|-----------|-------|--------|-------|
| Second Coming | Orange | Adaptive (all items) | Creative crafter - every attack uses a different Minecraft item |
| Red | Red | Diamond Axe | Berserker - slow but devastating, rage mode below 30% HP |
| Blue | Blue | Bow + Potions | Alchemist Archer - ranged attacks with cycling potion effects |
| Green | Green | Trident + Fishing Rod + Sword | Multi-tool fighter - grab, throw, slash |
| Yellow | Yellow | TNT + Redstone | Demolitionist - explosions and chain reactions (Unlockable) |
| Purple | Purple | Elytra + Fists | Elytra Brawler - aerial glide with heavy punches (Unlockable) |
| King Orange | Gold | Command Block | Command Block Overlord - /commands and golden energy (Unlockable) |

## Stages

| Stage | Features |
|-------|----------|
| Plains | Grass platforms, trees, clouds |
| Nether Fortress | Lava below, nether brick platforms |
| The End | Floating end stone, void below, end crystals |
| Jungle | Massive trees, vine platforms, leaf canopy, parrots |
| Village | Rooftop platforms, villagers watching, hay bales |
| Training | Walled arena, grid background, can't fall off |

## Story Mode

Fight through 7 battles to unlock all characters:
1. vs Red (Plains)
2. vs Blue (Jungle)
3. vs Green (Village)
4. vs Yellow (Nether) - **Unlocks Yellow**
5. vs Purple (The End) - **Unlocks Purple**
6. vs King Orange (Nether)
7. vs King Orange final (The End) - **Unlocks King Orange**

## Win Conditions

- Deplete your opponent's health bar
- Knock them off the stage

## Tech

Single HTML file, vanilla JavaScript, HTML5 Canvas. No dependencies.
