# Spellstorm
 
A bullet-heaven game built in Unreal Engine 5. University team project, 04/2025 – 05/2025, team of 3

<img width="1280" height="591" alt="image" src="https://github.com/user-attachments/assets/00ec996f-c67c-42a0-be1d-2c7ff682cf3c" />


## What it is
 
You fight escalating waves of enemies with automatic weapons, picking up items and upgrades between them. The design problem of the genre is keeping the screen readable while the enemy count climbs — that is where most of the work went.
 
## Credits
 
- **[D4rnet](https://github.com/D4rnet)** — gameplay programming and game design
- **ShkiperD3** — UX/UI and game design
- **darkmagicmods** — level design and game design

## What I (D4rnet) built
 
- **Character progression** — the hero stat structure (HP, Speed, Damage) as an extensible base, so new items and upgrades could hook into it without reworking the system.
- **Combat** — three distinct fire modes, tuned for readability and impact with around 50 enemies on screen simultaneously.
- **Enemy behaviour** — AI and player interactions designed to keep pressure constant without overwhelming the player.
- **Tech art** — a custom post-process pixel-art shader with outlining, which gives the game its retro look.
## Notes on this repository
 
The gameplay logic is in Blueprints, which GitHub stores as binary `.uasset` files and cannot display. This README is the readable summary.
 
## Built with
 
Unreal Engine 5 · Blueprints · UMG · post-process materials
