## Code coverage tracking — Session 97

The earlier reviewed test counts below remain separate from the new experimental
cold startup. Their overlap has not been counted, so the groups are not added.
The experiment now finishes its first live graphics request and continues loading.
That request prepares drawing settings without drawing pixels. Live drawing remains
unfinished.

The reviewed subset remains eighteen complete functions and one partial routine:
883 compiled instruction locations, 571 executed, 404 independently validated
and 167 with connected execution evidence. These stages overlap. The older
classification has twenty-four isolated extents (719 compiled locations,
34 retained cases) and six connected routines (342 compiled locations). These
groups overlap and must not be added. Eleven older isolated extents still need
tracking review. Whole-game totals and percentages remain unknown.

# Roadmap

The game is **not playable**. The experimental build finishes the game's first live
graphics request, receives its completion messages and continues loading. That work
only prepares drawing settings and produces no picture. A check protecting message
queue storage blocks later loading. Safe storage reuse, actual drawing and showing
a live picture are next. Earlier saved-task pictures remain separate diagnostics.

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
