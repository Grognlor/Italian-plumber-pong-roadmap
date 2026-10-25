# Progress

<a id="session-24"></a>
## Session 24 — Checking the tools before going further

We rechecked saved project materials from earlier work, and their listed files
still match the records we kept. We found the missing instruction needed to
restore our conversion tools. All six tool updates then went on correctly, the
main tool rebuilt, and two made-up test examples passed. For players, this
restores our tools but does not mean Mario Tennis has run: the game is still
not playable through this project. Next, we need to recover or carefully
rebuild missing evidence before returning to the startup investigation.

[Session 24 prompt record](../prompts/SESSION_24.md)

<a id="session-23"></a>
## Session 23 — Preserving the work we could recover

We found earlier saved work, checked its contents against the original records,
and preserved copies with a clearer handoff for future sessions. Later saved
work is still missing, and restoring the tools stopped at a compatibility
problem. This protects the groundwork we still have; it did not get the game
running. Mario Tennis remains unplayable through this project. Next, we need to
resolve the tool problem and recover or carefully rebuild the missing evidence.

[Session 23 prompt record](../prompts/SESSION_23.md)

<a id="session-22"></a>
## Session 22 — We paused rather than guess

We checked that the local game copy matches the version expected for this
project. The saved notes and tools needed to examine the next startup step were
not available in the workspace we could inspect, so we stopped rather than
guess or replace them. This is careful groundwork, but it did not get the game
running. Mario Tennis is still not playable through this project. Next, we'll
restore the reviewed notes and tools and continue the same investigation.

[Session 22 prompt record](../prompts/SESSION_22.md)

<a id="session-21"></a>
## Session 21 — We followed the next startup path

[Session 21 prompt record](../prompts/SESSION_21.md)

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

<a id="session-01"></a>
### Session 1 — Earlier record not recovered

[Session 1 prompt record](../prompts/SESSION_01.md)

No reliable report for this session was found. We cannot say what changed
without guessing. The next surviving project record does not appear until a
later session.

<a id="session-02"></a>
### Session 2 — Earlier record not recovered

[Session 2 prompt record](../prompts/SESSION_02.md)

No reliable report for this session was found. We cannot confirm its work or
outcome. We will leave that part of the story open instead of making one up.

<a id="session-03"></a>
### Session 3 — Earlier record not recovered

[Session 3 prompt record](../prompts/SESSION_03.md)

No reliable report for this session was found. We cannot confirm what was
planned or completed. The first detailed surviving technical report is from
Session 4.

<a id="session-04"></a>
### Session 4 — Checking the game copy and first small tests

[Session 4 prompt record](../prompts/SESSION_04.md)

The local game copy was checked, and a few small pieces were prepared for
careful PC tests. This helped establish a trustworthy starting point. The game
still did not start; next came studying how its pieces are loaded and connected.

<a id="session-05"></a>
### Session 5 — Learning how the game moves between pieces

[Session 5 prompt record](../prompts/SESSION_05.md)

The project learned more about how the game brings different pieces into
memory, and tested a few more small pieces in a PC test program. This matters
because the game cannot start until the right pieces are available at the right
time. A full start was still blocked.

<a id="session-06"></a>
### Session 6 — Trying to connect the pieces

[Session 6 prompt record](../prompts/SESSION_06.md)

Work began on joining the small tests to a basic PC-side framework. The first
attempt showed that the original game expects special behavior when it switches
between tasks. The game did not start, so the next step was to understand that
handoff correctly.

<a id="session-07"></a>
### Session 7 — Correcting a handoff boundary

[Session 7 prompt record](../prompts/SESSION_07.md)

The team corrected how a jump between two original game routines was described,
while keeping their separate boundaries. A synthetic test showed the handoff
could be represented safely. This was a test of the new framework, not a run
of Mario Tennis.

<a id="session-08"></a>
### Session 8 — Making dependency checks repeatable

[Session 8 prompt record](../prompts/SESSION_08.md)

A small diagnostic tool was added to explain which game pieces are still
missing during conversion. That makes each next step easier to check instead
of guessing. The startup group remained incomplete.

<a id="session-09"></a>
### Session 9 — Teaching the tools about a game timer

[Session 9 prompt record](../prompts/SESSION_09.md)

A narrowly scoped timer operation needed by the original game was added to the
conversion tools and tested. This cleared one obstacle, but other processor
and memory behavior was still missing. The game did not start.

<a id="session-10"></a>
### Session 10 — Adding a first memory-translation model

[Session 10 prompt record](../prompts/SESSION_10.md)

A limited model for how the original system maps memory was added and tested
with made-up examples. This is groundwork for running more of the original
game accurately. It was not a complete system model, and startup remained
blocked.

<a id="session-11"></a>
### Session 11 — Studying copied code and future PC features

[Session 11 prompt record](../prompts/SESSION_11.md)

The project added a limited, tested account of how the original system handles
code and recorded long-term goals such as widescreen and more display choices.
Those PC features are plans, not working options. The immediate task remained
getting the original game to start.

<a id="session-12"></a>
### Session 12 — Checking shortcuts and correcting a mistaken lead

[Session 12 prompt record](../prompts/SESSION_12.md)

The project mapped more short jumps used by the game and corrected an earlier
misreading of a processor operation. That helped keep the map evidence-based.
The next startup connection was still unresolved.

<a id="session-13"></a>
### Session 13 — Following the main startup route

[Session 13 prompt record](../prompts/SESSION_13.md)

The team checked a large startup routine and its choices, then corrected a
missing connection in the private map. This made the route clearer but did not
produce a complete PC version of that route.

<a id="session-14"></a>
### Session 14 — Recovering more pieces used during startup

[Session 14 prompt record](../prompts/SESSION_14.md)

Three previously missing game images were recovered from the owner's local
copy and checked against the existing loading evidence. The project could
describe more of the startup path, but still could not convert it as one
complete group.

<a id="session-15"></a>
### Session 15 — Understanding how the game resumes a task

[Session 15 prompt record](../prompts/SESSION_15.md)

The team found that the original game saves a task's state and later resumes
from a saved place. A small model of that return behavior was added and tested.
It did not yet connect the whole original task system.

<a id="session-16"></a>
### Session 16 — Building a safe handoff between PC routines

[Session 16 prompt record](../prompts/SESSION_16.md)

A bounded test framework was added so one converted routine can hand control
to another registered routine without jumping unsafely through PC code. Made-up
test routines passed. No original game routine had run in this framework yet.

<a id="session-17"></a>
### Session 17 — Testing the handoff with converted examples

[Session 17 prompt record](../prompts/SESSION_17.md)

Three synthetic converted routines successfully passed control through the
new framework. That showed the handoff design works in a controlled test, but
the original game still had a conversion obstacle and had not run.

<a id="session-18"></a>
### Session 18 — First original game pieces ran in a PC test

[Session 18 prompt record](../prompts/SESSION_18.md)

Three small original helper routines were converted, compiled, and run in
isolation with controlled test state. This was the first verified execution of
original Mario Tennis code in the PC test program. It was not startup: no
coherent game sequence ran, and the game remained unplayable.

<a id="session-19"></a>
### Session 19 — Finding hardware needs and adding a hang guard

[Session 19 prompt record](../prompts/SESSION_19.md)

The team identified that startup depends on conversations with original system
devices, and added a time limit for ordinary tool processes. The time limit
does not make game code safe to run by itself. Device behavior is still
unresolved, and the game did not start.

<a id="session-20"></a>
### Session 20 — Correcting a missing-piece diagnosis

[Session 20 prompt record](../prompts/SESSION_20.md)

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
