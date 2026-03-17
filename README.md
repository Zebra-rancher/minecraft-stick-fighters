# Minecraft Stick Fighters

A 2D stick figure fighting game that runs entirely in the browser. Inspired by Alan Becker's "Animation vs Minecraft" series.

## Play

Open `index.html` in any modern browser - no server or build step required.

Or play on GitHub Pages: https://zebra-rancher.github.io/minecraft-stick-fighters/

## Features

- **19 playable characters** with unique movesets and Minecraft weapons
- **3 Minecraft mob fighters** with square heads and unique proportions (Skeleton, Spider, Enderman)
- **5 Minecraft-themed stages** (Plains, Nether Fortress, The End, Jungle, Village)
- **Multiple game modes**: VS CPU, 1v1 Local, Story Mode, Training Camp, Training
- **Training Camp** - 19 unique minigames that unlock bonus attacks for each character
- **Final Smash system** - break the floating Smash Ball to unleash a devastating super move
- **Item drops**: Golden Apples, Potions, TNT, Ender Pearls, and more
- **Character unlocks** through Story Mode progression (14 unlockable fighters)
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
| Bonus Attack | M | R |

Combine directions with attack for different moves (up+attack = uppercut, forward+attack = thrust, etc.)

**Final Smash**: When you have the Smash Ball power (golden glow), press attack with NO direction held to trigger your Final Smash!

**Bonus Attack**: Complete a character's Training Camp minigame to unlock their bonus attack. Press M (P1) or R (P2) during battle to use it!

## Characters

### Stick Fighters

| Character | Color | Weapon | Style |
|-----------|-------|--------|-------|
| Second Coming | Orange | Adaptive (all items) | Creative crafter - every attack uses a different Minecraft item |
| Red | Red | Diamond Axe | Berserker - slow but devastating, rage mode below 30% HP |
| Blue | Blue | Bow + Potions | Alchemist Archer - ranged attacks with cycling potion effects |
| Green | Green | Trident + Fishing Rod + Sword | Multi-tool fighter - grab, throw, slash |
| Yellow | Yellow | TNT + Redstone | Demolitionist - explosions and chain reactions (Unlockable) |
| Purple | Purple | Elytra + Fists | Elytra Brawler - aerial glide with heavy punches (Unlockable) |
| King Orange | Gold | Command Block | Command Block Overlord - /commands and golden energy (Unlockable) |

### Animator vs. Animation Characters

| Character | Color | Weapon | Style |
|-----------|-------|--------|-------|
| Ballista | Brown | Heavy Crossbow | Mercenary Marksman - heavy bolts, slow but devastating (Unlockable) |
| Hazard | Green | Toxic Vials | Mercenary Chemist - poisons, acids, toxic clouds (Unlockable) |
| Primal | Sienna | Bone Club | Mercenary Savage - bone club brawler, ferocious combos (Unlockable) |
| Agent | Dark Blue | Tactical Pistol | Mercenary Operative - fast tactical fighter, pistol & gadgets (Unlockable) |
| The Mouse | White | Cursor Arrow | Alan's Cursor - fast click attacks, drag throws (Unlockable) |
| The Chosen One | Black | Fire Fists | Legendary fighter - fire powers, laser eyes (Unlockable) |
| The Dark Lord | Dark Red | Virus Swords | Virus-corrupted warrior - dual virus swords (Unlockable) |
| The Hacker | Matrix Green | Hack Tablet | Digital manipulator - glitch attacks, code injection (Unlockable) |
| Bed Wars Player | Red | Iron Sword | Strategic fighter - bridge building, bed defense (Unlockable) |

### Minecraft Mobs

| Character | Appearance | Weapon | Style |
|-----------|------------|--------|-------|
| Skeleton | Square head, bone limbs | Enchanted Bow | Sniper - ranged focus, rapid arrows, fragile (1.2x damage taken) (Unlockable) |
| Spider | Wide body (1.3x), 6 legs | Fangs + Web | Grappler - web grab, venom, wall cling passive (Unlockable) |
| Enderman | Tall (1.35x), purple eyes | Ender blocks | Teleporter - block attacks, 15% auto-dodge, territorial (Unlockable) |

## Training Camp

Complete each character's unique minigame to unlock a powerful bonus attack!

| Character | Minigame | Description | Bonus Attack |
|-----------|----------|-------------|--------------|
| Second Coming | Pixel Artist | Draw shapes on a grid - move cursor with arrows, place pixels with Space | Pixel Blast (14 dmg ranged) |
| Red | Fox Friend | Care for a fox - feed, pet, and protect it from hostile mobs | Fox Fury (12 dmg companion lunge) |
| Blue | Potion Lab | Mix potions - pick the right ingredients across 3 rounds | Mega Potion (10 dmg AoE splash) |
| Green | Rhythm Block | FNF-style beat game - hit arrow keys to the rhythm, 15/20 to pass | Note Blast (11 dmg shockwave) |
| Yellow | Redstone Circuit | Complete 3 redstone circuits by placing wire to connect levers to lamps | Redstone Surge (15 dmg lightning) |
| Purple | Elytra Course | Fly through rings using up/down arrows, 9/12 rings to pass | Dive Bomb (18 dmg aerial dive) |
| King Orange | Command Console | Pick the correct /command for each situation, 4/5 to pass | /smite (16 dmg lightning) |
| Skeleton | Target Range | Aim and shoot at hay bale targets, 12/15 hits to pass | Piercing Arrow (10 dmg, long range) |
| Spider | Web Weave | Connect dots in sequence to form a web pattern before time runs out | Venom Spit (8 dmg poison projectile) |
| Enderman | Block Memory | Memory matching game - find all 6 pairs in under 20 flips | Ender Slam (14 dmg teleport + slam) |
| Ballista | Siege Defense | Aim crossbow turret and shoot down incoming enemies | Siege Shot (16 dmg ranged bolt) |
| Hazard | Chemical Mix | Mix chemicals to match 3 formulas | Toxic Cloud (6 dmg AoE poison) |
| Primal | Bone Toss | Throw bones at targets with a power meter | Primal Roar (16 dmg shockwave) |
| Agent | Stealth Ops | Sneak past guard vision cones to reach the exit | Smoke Bomb (12 dmg AoE) |
| The Mouse | Click Speed | Click targets with cursor as fast as possible | Right Click Menu (14 dmg AoE) |
| The Chosen One | Fire Control | Aim and shoot fire at targets | Laser Eyes (18 dmg beam) |
| The Dark Lord | Virus Purge | Slash incoming virus blocks within your range | Virus Surge (15 dmg AoE poison) |
| The Hacker | Code Breaker | Memorize and enter 4-digit binary codes | DDoS Attack (12 dmg multi-shot) |
| Bed Wars Player | Bed Defense | Build walls to protect your bed from enemies | Fireball Rush (14 dmg explosive) |

## Final Smashes

Break the floating Smash Ball (3 hits) to charge your super move!

| Character | Final Smash | Type |
|-----------|-------------|------|
| Second Coming | Awakened Form Rush | Cinematic - golden transformation, rapid combo |
| Red | Herobrine Possession | Cinematic - white eyes, obsidian colossus slam |
| Blue | Potion Storm | Cinematic - giant cauldron, potions rain from sky |
| Green | Note Block Staff | Cinematic - musical note barrage |
| Yellow | Mega TNT Cannon | Cinematic - builds cannon, fires TNT volley |
| Purple | Champion Data Form | Transformation - 12 sec of 2x strength, 1.5x speed, 3 jumps |
| King Orange | Minecraft Icon Staff | Cinematic - white void blast |
| Skeleton | Arrow Storm | Cinematic - arrows rain across entire stage |
| Spider | Web Prison | Cinematic - wraps opponent, spider swarm attacks |
| Enderman | Block Storm | Cinematic - rips up blocks and hurls them at opponent |
| Ballista | Siege Barrage | Cinematic - rapid-fire crossbow volley |
| Hazard | Toxic Meltdown | Cinematic - massive acid explosion |
| Primal | Primal Fury | Cinematic - savage bone club flurry |
| Agent | Tactical Strike | Cinematic - coordinated tactical assault |
| The Mouse | Ctrl+A Select All | Cinematic - selects and drags opponent |
| The Chosen One | Full Power Unleashed | Transformation - 12 sec of 2.5x strength, 1.8x speed |
| The Dark Lord | Virus Corruption | Cinematic - virus infection spread |
| The Hacker | System Override | Cinematic - matrix-style reality hack |
| Bed Wars Player | Bed Destruction | Cinematic - TNT bed explosion chain |

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

Fight through 19 battles to unlock all characters:

**Arc 1 - Minecraft Fighters**
1. vs Red (Plains)
2. vs Blue (Jungle)
3. vs Green (Village)
4. vs Spider (Plains)
5. vs Yellow (Nether) - **Unlocks Yellow**
6. vs Skeleton (Jungle) - **Unlocks Skeleton**
7. vs Purple (The End) - **Unlocks Purple**
8. vs Enderman (Village) - **Unlocks Enderman**
9. vs King Orange (Nether) - **Unlocks King Orange**
10. vs King Orange Final (The End) - BOSS FIGHT!

**Arc 2 - Animator vs. Animation**
11. vs Ballista (Plains) - **Unlocks Ballista**
12. vs Hazard (Nether) - **Unlocks Hazard**
13. vs Primal (Jungle) - **Unlocks Primal**
14. vs Agent (The End) - **Unlocks Agent**
15. vs The Mouse (Plains) - **Unlocks The Mouse**
16. vs The Chosen One (The End) - LEGENDARY FIGHT! **Unlocks The Chosen One**
17. vs The Dark Lord (Nether) - DARK BOSS! **Unlocks The Dark Lord**
18. vs The Hacker (The End) - **Unlocks The Hacker**
19. vs Bed Wars Player (Jungle) - FINAL CHALLENGE! **Unlocks Bed Wars Player**

## Win Conditions

- Deplete your opponent's health bar
- Knock them off the stage

## Tech

Single HTML file, vanilla JavaScript, HTML5 Canvas. No dependencies.
