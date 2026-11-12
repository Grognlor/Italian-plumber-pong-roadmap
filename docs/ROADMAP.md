## Code coverage tracking — Session 103

The earlier reviewed test counts below remain separate from the new experimental
cold startup. Their overlap has not been counted, so the groups are not added.
The first real sound-processing task now runs and the game receives its
completion. Its initial output is silence while startup voices are idle. The
next step is safely submitting those finished samples for sound output. Live
controller reads and eleven loading requests finish. The completed graphics
request only prepares drawing settings; there is no sound playback, live game
picture or playable game.

The reviewed subset remains eighteen complete functions and one partial routine:
883 compiled instruction locations, 571 executed, 404 independently validated
and 167 with connected execution evidence. These stages overlap. The older
classification has twenty-four isolated extents (719 compiled locations,
34 retained cases) and six connected routines (342 compiled locations). These
groups overlap and must not be added. Eleven older isolated extents still need
tracking review. Whole-game totals and percentages remain unknown.

# Roadmap

The game is **not playable**. Its first sound-processing task now runs and
completes, but submitting finished samples for sound output is still blocked. Live button and stick
reads work during startup, but gameplay controls and broad controller compatibility
still need testing. Four independent players, reconnecting, mapping, dead zones
and controller-operated settings inside the game remain requirements. There is
still no live game picture; earlier saved-task pictures are separate diagnostics.

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
