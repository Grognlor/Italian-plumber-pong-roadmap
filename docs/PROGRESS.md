# Progress

## Latest update

We have mapped another piece needed by one of the game's startup paths. That
helped our conversion tool move on to the next missing piece, but the startup
group still is not ready to run. We also tested a way to stop a test program
that gets stuck, before trying longer experiments.

For players, this is careful behind-the-scenes progress toward getting the
game to start. We also added a future plan for an in-game settings menu that
would feel like part of Mario Tennis. Next, we are checking the remaining
startup pieces and the hardware behavior the game expects. The game is still
not playable, and there is no release date.

## Where things stand

The game is **not playable yet**. We have not reached its title screen or shown
a running game.

Earlier work checked the game version, added project safety checks, and helped
us understand important pieces involved in startup. A few small original game
helpers now run in the PC test program, but the main game still does not start.

Those tests are useful steps, but they do not mean the game itself runs on a PC.
We are still working toward the first real game code running in the new PC
program.

## What comes next

We are working on how the original game saves and restores its tasks so it can
continue running correctly on a PC. After that, the next goal is to connect
enough original game parts to try a carefully checked startup.

The [roadmap](ROADMAP.md) lists the larger goals. There is no release date.
