# Progress

## Latest update

This session we fixed a problem in how our PC test program hands control from
one task to another. We used a small made-up test to confirm that this handoff
works. The original Mario Tennis game still has not run in our PC program.

For players, this removes one obstacle on the way to testing real pieces of the
game, but it does not mean the game is playable. Next, we are working on the
game's timing and task-switching needs so we can connect more original game
code safely. There is no release date.

## Where things stand

The game is **not playable yet**. We have not reached its title screen or shown
a running game.

Earlier work checked the game version, added project safety checks, and helped
us understand important pieces involved in startup. We have also converted
and tested small parts of the game.

Those tests are useful steps, but they do not mean the game itself runs on a PC.
We are still working toward the first real game code running in the new PC
program.

## What comes next

We are working on how the original game saves and restores its tasks so it can
continue running correctly on a PC. After that, the next goal is to connect
enough original game parts to try a carefully checked startup.

The [roadmap](ROADMAP.md) lists the larger goals. There is no release date.
