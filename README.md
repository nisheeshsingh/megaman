# Mega Man Game

A small, classic-style Mega Man platform shooter built with Python and Pygame. Run, jump, and fire your way through a tile-based level filled with enemies, hazards, and pickups.

## Getting Started

You will need Python 3 and Pygame.

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install pygame
python megaman.py
```

Run the game from the repository root so it can find the `images/` assets and custom font. Close the game window to exit.

## Controls

| Action | Keys |
| --- | --- |
| Move left / right | `A` / `D` or `Left` / `Right` arrows |
| Jump | `W` or `Up` arrow |
| Shoot | `X` or `Space` |
| Restart after game over | `Enter` |

## Gameplay

Fight Metall and Blader enemies, avoid spikes, and collect life energy to restore health. Score balls add points. The game ends when Mega Man runs out of health or falls off the level.

## Project Files

- `megaman.py` contains the Pygame game loop, player and enemy behavior, and rendering.
- `tile_map.py` defines the level layout.
- `images/` contains the sprites, tiles, and background used by the game.
- `megaman-game-font.otf` is the in-game font.

## License

This project is distributed under the Apache License 2.0. See [LICENSE](LICENSE) for details.