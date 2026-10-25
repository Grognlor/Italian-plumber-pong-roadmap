# Progress

## Session 21 — We followed the next startup path

We traced several more links between parts of the original game, including a
part that had looked like a missing piece. Our tools now get farther through
the startup list, but stop at another part that still needs checking.

For players, this is careful groundwork toward trying a real startup. It does
not mean the game starts yet. Next, we need to identify the newly reached part
before continuing. **Mario Tennis is not playable through this project.**

## Retrospective diary

These entries summarize verified session reports. They were written later
from those reports, not posted during the original sessions. The game has not
reached its title screen.

### Sessions 1–3 — Earlier records not recovered

We could not find reliable session reports for these sessions. We do not know
enough to say what was accomplished, so we will not fill in the gaps by
guessing. The next recorded work begins with checking the game copy and
building a safe way to study it.

### Session 4 — Checking the game copy and first small tests

The local game copy was checked, and a few small pieces were prepared for
careful PC tests. This helped establish a trustworthy starting point. The game
still did not start; next came studying how its pieces are loaded and connected.

### Session 5 — Learning how the game moves between pieces

The project learned more about how the game brings different pieces into
memory, and tested a few more small pieces in a PC test program. This matters
because the game cannot start until the right pieces are available at the right
time. A full start was still blocked.

### Session 6 — Trying to connect the pieces

Work began on joining the small tests to a basic PC-side framework. The first
attempt showed that the original game expects special behavior when it switches
between tasks. The game did not start, so the next step was to understand that
handoff correctly.

### Session 7 — Correcting a handoff boundary

The team corrected how a jump between two original game routines was described,
while keeping their separate boundaries. A synthetic test showed the handoff
could be represented safely. This was a test of the new framework, not a run
of Mario Tennis.

### Session 8 — Making dependency checks repeatable

A small diagnostic tool was added to explain which game pieces are still
missing during conversion. That makes each next step easier to check instead
of guessing. The startup group remained incomplete.

### Session 9 — Teaching the tools about a game timer

A narrowly scoped timer operation needed by the original game was added to the
conversion tools and tested. This cleared one obstacle, but other processor
and memory behavior was still missing. The game did not start.

### Session 10 — Adding a first memory-translation model

A limited model for how the original system maps memory was added and tested
with made-up examples. This is groundwork for running more of the original
game accurately. It was not a complete system model, and startup remained
blocked.

### Session 11 — Studying copied code and future PC features

The project added a limited, tested account of how the original system handles
code and recorded long-term goals such as widescreen and more display choices.
Those PC features are plans, not working options. The immediate task remained
getting the original game to start.

### Session 12 — Checking shortcuts and correcting a mistaken lead

The project mapped more short jumps used by the game and corrected an earlier
misreading of a processor operation. That helped keep the map evidence-based.
The next startup connection was still unresolved.

### Session 13 — Following the main startup route

The team checked a large startup routine and its choices, then corrected a
missing connection in the private map. This made the route clearer but did not
produce a complete PC version of that route.

### Session 14 — Recovering more pieces used during startup

Three previously missing game images were recovered from the owner's local
copy and checked against the existing loading evidence. The project could
describe more of the startup path, but still could not convert it as one
complete group.

### Session 15 — Understanding how the game resumes a task

The team found that the original game saves a task's state and later resumes
from a saved place. A small model of that return behavior was added and tested.
It did not yet connect the whole original task system.

### Session 16 — Building a safe handoff between PC routines

A bounded test framework was added so one converted routine can hand control
to another registered routine without jumping unsafely through PC code. Made-up
test routines passed. No original game routine had run in this framework yet.

### Session 17 — Testing the handoff with converted examples

Three synthetic converted routines successfully passed control through the
new framework. That showed the handoff design works in a controlled test, but
the original game still had a conversion obstacle and had not run.

### Session 18 — First original game pieces ran in a PC test

Three small original helper routines were converted, compiled, and run in
isolation with controlled test state. This was the first verified execution of
original Mario Tennis code in the PC test program. It was not startup: no
coherent game sequence ran, and the game remained unplayable.

### Session 19 — Finding hardware needs and adding a hang guard

The team identified that startup depends on conversations with original system
devices, and added a time limit for ordinary tool processes. The time limit
does not make game code safe to run by itself. Device behavior is still
unresolved, and the game did not start.

### Session 20 — Correcting a missing-piece diagnosis

A part that had looked like invalid game data was found inside a known game
image, and the tools accepted its carefully bounded location. The startup
search moved on to another missing connection. No complete startup group was
built.

### Session 21 — Following more connections, then stopping at a new gap

The project verified several more links and separate entry points, and the
conversion search moved past the previous obstacle. It reached another missing
connection before a complete group could be made. The next step is to check
that new connection, not to assume its role.

## Where things stand

The game is **not playable yet**. We have not reached its title screen or shown
a running game. A few small original pieces have run in a PC test program, but
not as a complete game sequence.

## What comes next

We will check the newly reached part against the saved evidence and continue
only if its role and boundaries are clear. The [roadmap](ROADMAP.md) lists the
larger goals. There is no release date.
