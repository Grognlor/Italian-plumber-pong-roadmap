# Session 104 — Audio output and continued game startup

Status: Session closed. These are the authentic owner objectives, with three
localized visible redactions. Requested outcomes are separate from the verified
results in the [matching diary entry](../docs/PROGRESS.md#session-104).

```text

ITALIAN PLUMBER PONG
SESSION 104 - AUDIO OUTPUT AND CONTINUED GAME STARTUP

Resume from:
[REDACTED: private development branch.]

Read:
[REDACTED: private project document list.]

Preserve Sessions 95-103 and their evidence.

GUIDING PRINCIPLE

Get it running. Get it playable.
Get people involved. Then polish it.

PRIMARY OBJECTIVE

Implement the audio-interface sample-buffer
submission service currently blocking
original Mario Tennis startup.

The first genuine audio RSP task now
executes successfully and its completion
is consumed by the original game.

Implement a narrowly reviewed host audio
interface supporting:

- Genuine sample-buffer submission
- Owned and validated sample memory
- Correct FIFO capacity and queue state
- Truthful buffer consumption timing
- Remaining-length reporting
- Required AI completion/event delivery
- Cancellation, errors and safe teardown

Do not fabricate audio completions, discard
required processing or claim audible output
without actual playback.

SECONDARY OBJECTIVE

Enable safe execution of subsequent
original audio tasks.

Review the existing cxd4 interpreter
adapter's SP state, memory and register
continuity requirements.

Implement authentic task reset or
state preservation as appropriate.

Preserve checked DMA access, instruction
budgets, unknown-operation rejection,
ownership and completion ordering.

Test repeated tasks, nonzero output,
cancellation and invalid memory access.

STARTUP OBJECTIVE

Resume genuine cold-ROM execution.

Continue through subsequent actual
startup blockers, translating only
authenticated complete functions.

Build, run, inspect and correct iteratively.

GRAPHICS OBJECTIVE

Continue toward the first genuine
drawing task and presented game frame.

Reuse existing RT64 integration.

Extend only commands and dependencies
actually requested by Mario Tennis.

Preserve GPU input ownership through
workload completion and safe drain.

Connect authentic framebuffer selection
and VI presentation when reached.

Visually incorrect rendering is acceptable.
A state-only task, blank window or
diagnostic replay does not count.

CONTROLLER REQUIREMENTS

Preserve working controller reads.

Retain the long-term requirements for
Xbox, PlayStation, Nintendo, 8BitDo and
generic USB/Bluetooth controllers,
four local players, hotplugging,
remapping and in-game controller settings.

Do not replace the current experimental
input backend unless startup requires it.

SECURITY AND RELEASE REQUIREMENTS

Preserve ROM confidentiality, checked
memory, isolation, [REDACTED: private architecture name],
dependency integrity and safe ownership.

Keep proprietary ROM-derived material
out of Git and public distribution.

Do not publish binaries or media,
merge to main or change visibility.

SESSION CLOSEOUT

Report:
1. Does real audio-buffer submission work?
2. Can multiple original audio tasks execute?
3. Did the original game consume completions?
4. How far did startup progress?
5. Were drawing or VI presentation reached?
6. What is the next concrete blocker?
7. Recommended Session 105 priorities

Run focused and full relevant tests.
Update private reports and handoff.
Verify GitHub delivery.

Do not automatically start Session 105.

BEGIN SESSION 104.
```
