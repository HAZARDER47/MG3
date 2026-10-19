# MG3
## Devlog

1. What are the default values for floats, ints, bools, and strings?
The default values shown in the Inspector are 0 for floats, 0 for ints, false for bools, and an empty field for strings.

2. How does the Update method get called?
The Update() method is automatically called by Unity every frame, so we don't need to call it ourselves. It is useful for things that need to be checked or updated continuously, such as a timer.

3. Explain how either the KickWeapon or TimerText class uses the timer.
The KickWeapon class uses a timer to control how long a kick lasts. When the player kicks, the timer starts counting down. The Update() method checks whether the timer has finished. Once the time runs out, the kick is deactivated so it doesn't stay active forever.

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)