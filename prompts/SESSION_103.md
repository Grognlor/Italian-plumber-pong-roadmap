# Session 103 — First real audio task

Status: Session closed. These are the authentic owner objectives, with three
visible redactions. Requested outcomes are separate from verified results in the
[matching diary entry](../docs/PROGRESS.md#session-103).

```text

ITALIAN PLUMBER PONG
SESSION 103 - FIRST REAL AUDIO TASK

Continue accelerated experimental development.

Resume from:
[REDACTED: private development branch.]

Read:
[REDACTED: private project document list.]

Preserve Sessions 95-102 and their evidence.

GUIDING PRINCIPLE

Get it running. Get it playable.
Get people involved. Then polish it.

PRIMARY OBJECTIVE

Implement genuine execution of the first
audio task requested by Mario Tennis
during cold-ROM startup.

The game currently submits an authentic
audio task, but the graphics-only task
bridge rejects it.

1. Authenticate the actual audio microcode,
   command format, source epoch and task
   descriptor against the owner ROM.

2. Identify the required input, sample,
   command, state and output memory.

3. Determine whether existing reviewed
   runtime components can execute this
   task, including ABI3 audio support.

4. Implement the smallest safe audio-task
   executor that performs the actual
   requested work.

5. Establish bounded memory ownership,
   completion ordering, failure handling,
   cancellation and safe teardown.

6. Publish SP completion only after the
   task's required processing finishes.

7. Resume original game execution and
   verify that the original consumer
   receives the completion.

Do not fabricate task success, silently
discard commands or bypass required
audio initialization.

Audible playback may be deferred.
Correct task execution and completion
are the immediate requirements.

SECONDARY OBJECTIVE

Continue genuine cold-ROM execution
through subsequent startup dependencies.

Translate only authenticated complete
helpers needed by actual execution.

Preserve the audio dispatcher's checked
jump-table behavior and reject unknown
targets.

GRAPHICS OBJECTIVE

Continue toward the first genuine
drawing task and live presented frame.

Reuse existing RT64 integration.

Extend only the drawing commands and
memory dependencies actually reached.

Preserve renderer/GPU memory ownership
through workload completion and drain.

Connect authentic framebuffer selection
and VI presentation.

Imperfect graphics are acceptable.
State-only tasks, blank windows and
frozen diagnostic replay do not count.

CONTROLLER REQUIREMENTS

Preserve genuine controller sampling
and the documented long-term goal of
broad USB/Bluetooth compatibility,
four local players, hotplugging,
configurable mapping and in-game settings.

Do not replace the working experimental
backend unless actual startup requires it.

WORKING METHOD

Build, execute, diagnose and repeat.

Prioritize native game progress over
unrelated certification work.

Continue through additional related
blockers when safe and productive.

Preserve ROM confidentiality, checked
memory, [REDACTED: private architecture name], dependency
integrity, isolation and ownership safety.

Do not commit proprietary ROM-derived
code or assets.

Do not publish binaries or media,
merge to main or change visibility.

SESSION CLOSEOUT

Report:

1. Was genuine audio-task work executed?
2. Was its completion consumed?
3. How far did startup progress?
4. Were drawing or VI presentation reached?
5. What is the next concrete blocker?
6. What should Session 104 prioritize?

Run focused and full relevant tests.
Update private reports and handoff.
Verify GitHub delivery.

Do not automatically start Session 104.

BEGIN SESSION 103.
```
