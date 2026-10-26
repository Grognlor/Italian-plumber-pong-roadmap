# Progress

<a id="session-44"></a>
## Session 44 — Checking the instruction against its original manual

The owner supplied a processor manual, and we checked its identity and relevant
pages. This let us independently establish the memory instruction's byte rules.
The PC helper's result calculation agrees under the reviewed conditions, but we
still need to justify its memory accesses before trying the original routine pair.
We stopped at that remaining safety question. Next, we will focus on that one
memory contract. All 108 existing tests and both made-up conversion checks pass;
no new tests or executable changes were added. No original game code was converted,
compiled or run. Mario Tennis remains unplayable through this project.

Reference: NEC, *VR4300, VR4305, VR4310 64-Bit Microprocessor User's Manual*,
U10504EJ7V0UMJ1, seventh edition, August 2000; printed pages 498–500, with
notation and memory-operation definitions on pages 364–368.

[Session 44 authentic prompt with visible redactions](../prompts/SESSION_44.md)

<a id="session-43"></a>
## Session 43 — Stopping when the reference could not be verified

We tried three narrowly scoped downloads of public processor manuals, but each
retrieval failed. Search results supplied leads, not a verified manual we could
use to check the memory operation. We stopped at the attempt limit and kept the
comparison unproved. Next, we need an authenticated copy of the reference before
trusting the expected result. All 108 existing tests and both made-up conversion
checks pass; no new tests or executable changes were added. No original game
code was converted, compiled or run. Mario Tennis remains unplayable through
this project.

[Session 43 authentic prompt with visible redactions](../prompts/SESSION_43.md)

<a id="session-42"></a>
## Session 42 — Keeping an independent memory check honest

We rechecked the saved instruction and the PC helper's memory accesses, then
looked for an independent instruction reference in the approved local records.
The records contain citations, but no verified source copy for the needed check.
We stopped there and kept the comparison unproved. Next, we need an authenticated
reference before trusting the expected result. No new reference was downloaded,
no original game code was converted, compiled or run, and no executable changes
or new tests were added. Mario Tennis remains unplayable through this project.

[Session 42 authentic prompt with visible redactions](../prompts/SESSION_42.md)

<a id="session-41"></a>
## Session 41 — Narrowing the utility test's memory question

We checked how the leading utility pair would receive its inputs and use memory
in a small, controlled test. One memory operation still needs an independent
check before we can trust the full expected result, so the pair is not ready
to run. We stopped there. Next, we will focus on that single memory question.
No new game code was converted, compiled or run, and no executable changes or
new tests were added. Mario Tennis remains unplayable through this project.

[Session 41 authentic prompt with visible redactions](../prompts/SESSION_41.md)

<a id="session-40"></a>
## Session 40 — Looking for a smaller first step

We changed direction: instead of following the whole startup sequence, we
reviewed three possible pairs of original game routines for a smaller PC test.
A utility pair looks most promising, but none has enough evidence for integration
yet. Next, we need to verify that pair's starting conditions and memory rules.
The earlier startup question remains open and is deferred. No new game code was
converted, compiled or run, and no executable changes were made. Mario Tennis
remains unplayable through this project.

[Session 40 prompt source record](../prompts/SESSION_40.md) — source-limitation
placeholder; an exact original byte source was unavailable for verification.

<a id="session-39"></a>
## Session 39 — Tracing working memory and checking recorded handoffs

We connected several saved startup steps to the area where a setup flag could
be changed. The missing link is whether the first task actually receives the
working memory prepared for it, so startup remains blocked. Separately, the
made-up native tests now reject success or test-limit reports with missing or
inconsistent handoffs. All eleven focused runner tests pass, and the five
existing outcomes remain intact. No new original game piece was converted or
run; Mario Tennis remains unplayable through this project. Next, we need evidence
for that first handoff and its working memory.

[Session 39 authentic prompt with visible redactions](../prompts/SESSION_39.md)

<a id="session-38"></a>
## Session 38 — Checking a setup assumption and rejecting misleading test results

The saved data contains the expected starting value for a setup flag, but we
cannot yet prove that earlier memory writes leave it intact when needed. We
stopped at that gap, so startup remains blocked. Separately, the made-up native
tests now reject error reports whose messages or recorded handoffs disagree.
All ten focused runner tests pass, and the five existing test outcomes are
preserved. No new original game piece was converted or run; Mario Tennis remains
unplayable through this project. Next, we need evidence for the earlier memory
setup before trusting that flag value.

[Session 38 authentic prompt with visible redactions](../prompts/SESSION_38.md)

<a id="session-37"></a>
## Session 37 — Checking an earlier setup step and a public reference

We found an earlier setup step whose starting condition still needs proof, so
the startup investigation stopped there. We also checked the small public
Mario Tennis N64 reference already listed in our notes. It clarified the source
and its limits, but did not answer the missing startup question. Separately,
one new made-up test checks that an invalid memory access is reported clearly
after a handoff. All nine focused runner tests pass. No new original game piece
was converted or run; Mario Tennis remains unplayable through this project.
Next, we need evidence for that earlier setup condition.

[Session 37 authentic prompt with visible redactions](../prompts/SESSION_37.md)

<a id="session-36"></a>
## Session 36 — Finding an earlier task and making test outcomes clear

We found an earlier task-starting step that can affect which work is waiting
when the game reaches the loading handoff. Its actual state and return still
need evidence, so startup remains blocked. Separately, our new native test
command now reports success, unsupported work, a test limit and a timeout as
different outcomes. Eight new tests pass using made-up functions only. No new
original game piece was converted or run; Mario Tennis remains unplayable
through this project. Next, the game investigation needs the state at that
earlier task-starting step.

[Session 36 prompt source record](../prompts/SESSION_36.md) — source-limitation
placeholder; an exact original byte copy was unavailable for verification.

<a id="session-35"></a>
## Session 35 — Checking an earlier handoff and strengthening our tests

The saved code shows an earlier task-priority change can hand off control before
the loading task is prepared. We still need evidence for the state at that
point, so the startup investigation remains blocked. Separately, we added a
native PC test that checks unsupported work is reported as an error after a
handoff, and wrote a practical plan for the runtime pieces we can test safely.
That test uses made-up examples only. No new original game piece was converted
or run, and Mario Tennis remains unplayable through this project. Next, the
game investigation needs the state at that earlier priority change; independent
runtime tests can continue under their own scope.

[Session 35 prompt record](../prompts/SESSION_35.md)

<a id="session-34"></a>
## Session 34 — Checking how a loading task is prepared

We traced the code that prepares one task and offers it for selection. This
clarifies its initial information and working memory, but does not prove the
game chooses it at the loading handoff. That choice depends on the task already
running and others waiting, whose state still needs checking. We stopped at
that gap. No new game piece was converted or run, and Mario Tennis remains
unplayable through this project. Next, we need evidence for the task-selection
conditions at that handoff.

[Session 34 prompt record](../prompts/SESSION_34.md)

<a id="session-33"></a>
## Session 33 — Finding the missing loading context

We narrowed the loading question to how the game chooses the active task and
its working memory. We also checked that two different pieces of task information
must not be confused. The saved evidence does not yet establish which task is
active at the first handoff, so we stopped there. This gives us a more precise
next check, but does not prove that loading finishes. No new game piece was
converted or run. Mario Tennis remains unplayable through this project. Next,
we need to trace how that first task is prepared and selected.

[Session 33 prompt record](../prompts/SESSION_33.md)

<a id="session-32"></a>
## Session 32 — Checking the first loading handoff

We checked how the game prepares its first loading request and found a failure
path that the caller does not check. The saved evidence still does not establish
the active memory setup or show that the request completes. We stopped at that
gap. The earlier size check remains useful, but does not mean loading succeeded.
No new game piece was converted or run, and Mario Tennis remains unplayable
through this project. Next, we need evidence for the memory setup used at that
first handoff.

[Session 32 prompt record](../prompts/SESSION_32.md)

<a id="session-31"></a>
## Session 31 — Checking the first decoded piece

We checked the first data stream from the owner's local game copy. Under the
reviewed conditions, its decoded output fits the space requested and stops
before the next reserved area. This clears the specific size concern from the
last session. We still need to prove how the game delivers that data and
reports completion, so the opening sequence has not run. No new game piece
was converted or executed. Mario Tennis remains unplayable through this
project. Next, we will check that first loading handoff and its effects.

[Session 31 prompt record](../prompts/SESSION_31.md)

<a id="session-30"></a>
## Session 30 — Checking space for the first loaded pieces

We checked how the opening code sets aside space for game data. The saved
evidence narrows where the first pieces would go, but does not establish how
much the first load writes. We stopped at that gap before assuming the next
step is safe. This gives us a more specific piece of evidence to collect, but
Mario Tennis still does not start or play through this project. No new game
piece was converted or run. Next, we need to check the first load's actual
size and writes before following the opening route further.

[Session 30 prompt record](../prompts/SESSION_30.md)

<a id="session-29"></a>
## Session 29 — Following the next connections

We checked four connections to the routine under investigation and followed how
the opening code registers work to run later. This gives us a clearer link
between the opening route and those connections, but several conditions and
memory changes still need proof. A possible route through the saved code does
not show that the game actually takes it. We stopped before converting or
running another game piece. Mario Tennis still does not start or play through
this project. Next, we need to check the state and loaded code at the first
handoff to that registered work.

[Session 29 prompt record](../prompts/SESSION_29.md)

<a id="session-28"></a>
## Session 28 — Checking the opening loading route

We checked a saved route through the opening sequence and found another game
part that can occupy the same space as the versions studied earlier. Its small
routine does not make the connection we were looking for. The route also shows
that changing to the next version depends on an earlier result. This narrows
the investigation, but does not prove which version the old attempt used or
that the needed routine is reached. No new game piece was converted or run.
Mario Tennis still does not start or play through this project. Next, we need
to follow the next version's opening route to that routine and check when its
code is replaced.

[Session 28 prompt record](../prompts/SESSION_28.md)

<a id="session-27"></a>
## Session 27 — Checking which game version was active

We reviewed saved notes about two versions of the same game part. The old label
points into the middle of each version, and the notes do not show which one was
active when it was needed. We found separate links from each version to another
small game routine, but cannot yet show that either link is part of the opening
sequence. We stopped before converting another piece rather than guess. This
means Mario Tennis still does not start or play through this project. Next, we
need reliable evidence showing which version the game loads and when.

[Session 27 prompt record](../prompts/SESSION_27.md)


<a id="session-26"></a>
## Session 26 — Checking which version the game uses

We found two different versions of one game part in the saved evidence. The
older notes do not tell us which version was active when it was needed, so we
stopped rather than guess. This keeps the startup investigation honest, but
Mario Tennis still does not start or play through this project. Next, we need
to recover clear evidence showing which version the game uses before following
that connection further.

[Session 26 prompt record](../prompts/SESSION_26.md)

<a id="session-25"></a>
## Session 25 — Checking a missing piece

We rebuilt and independently checked one small piece of Mario Tennis from the
owner's local copy. Our tools can now prepare and compile that piece for PC
testing. It is not connected to a running game, and Mario Tennis still does not
start or play through this project. Next, we need to identify which part of the
game calls it and what else is needed for a complete startup.

[Session 25 prompt record](../prompts/SESSION_25.md)

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

