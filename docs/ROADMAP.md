## Code coverage tracking — Session 86

Code coverage measures authenticated recompilation progress, not overall gameplay completion.

| Measure | Reviewed ledger subset |
| --- | --- |
| Estimated total original functions | UNKNOWN |
| Estimated total executable instructions | UNKNOWN |
| Identified complete functions | At least 18 |
| Analyzed complete functions | At least 18 |
| Generated complete functions | At least 18 |
| Compiled complete functions | At least 18 |
| Executed complete functions | At least 18 |
| Validated complete functions | At least 13 |
| Connected complete functions | At least 5 |
| Startup complete functions | At least 0 |
| Compiled instruction locations | At least 883 |
| Compiled function coverage | UNKNOWN |
| Compiled instruction coverage | UNKNOWN |
| Baseline revision | mt-us-census-v1 |
| Last coverage update | Session 86 |


These are lower bounds for a reviewed subset of eighteen complete functions and
one partial routine. They do not measure how close the game is to being playable.
Two new complete routines were generated, compiled, executed in isolation and
independently validated this session.

Within this subset, 565 instruction locations have executed, 398 have strict
independent validation and 167 have connected execution evidence. The stages
can overlap. The short resumed-worker sequence checked only in the original run
and a separate interpreter is excluded from new native execution counts.
Connected execution comes from development checks; the full game does not start.

The older classification has twenty-four isolated extents (719 compiled locations,
33 cases). Connected coverage stays six routines (342 compiled locations).
These categories may overlap and must not be added together. Eleven older
isolated extents still need tracking review. The baseline is unchanged;
whole-game totals and every percentage remain unknown.

# Roadmap

The game is **not playable**. Original message handling runs across real PC threads
in a local developer build. Separate frozen replays now draw saved original startup
logos through the native graphics engine, with pixel differences still unresolved.
The native game still needs its actual loading and startup path, thread ownership
and safe graphics completion handling. No live native first frame exists.

| Status | Milestone | What it means for players |
| --- | --- | --- |
| **Working On It** | Building the Foundation | Prepare the tools and learn how the original game starts. |
| **Working On It** | Bringing the Game to Life | Get original Mario Tennis code running directly on a PC. |
| **Coming Later** | First Successful Startup | Start the game and reach its title screen. |
| **Coming Later** | Time to Play Tennis! | Play a complete tennis match. |
| **Coming Later** | Making the Whole Game Work | Support the original modes, players, courts, sound, saving and multiplayer. |
| **Coming Later** | Making It Better on PC | Add widescreen, more display choices, smoother play, modern controllers and settings you can change from inside Mario Tennis. |
| **Coming Later** | Ready for Everyone | Make a stable version that people can install on supported Linux systems. |
| **Coming Later** | Bringing Mario Tennis to More Systems | After Linux is ready, bring the game to Windows, then look at Mac and other systems if testing help is available. |

Our first target is Linux, including Bazzite, ROG Ally, Steam Deck and supported
desktop systems. After that version is stable, we'd like to make a Windows
version that runs directly on Windows. Mac and other systems may follow if
people with suitable equipment can help test them. These are future plans, not
working versions.

These are goals, not promises or release dates. Planned features are not
finished until they work in the game and have been checked.

### Settings That Feel Like Part of Mario Tennis

Later on, we want a PC Settings menu that looks and feels like it belongs in
Mario Tennis. Players could change supported screen, graphics, performance,
sound and controller options from inside the game, using a controller. It
would not be a separate launcher. This is a future plan, after the game is
running; it does not exist yet.
