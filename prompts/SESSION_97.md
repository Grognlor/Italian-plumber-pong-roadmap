# Session 97 — Owner prompt

Status: Session 97 completed. These are authentic owner instructions, not a claim
that the requested first live frame was achieved. The exact captured prompt and
its provenance are preserved privately. Four private project file paths and one
branch are visibly redacted; all other wording and order are preserved.

[Read the Session 97 development diary](../docs/PROGRESS.md#session-97).

---


ITALIAN PLUMBER PONG
SESSION 97 - FIRST LIVE GAME FRAME

Continue accelerated experimental development.

Our guiding principle remains:
GET IT RUNNING. GET IT PLAYABLE.
GET PEOPLE INVOLVED. THEN POLISH IT.

Resume from [Redacted: private project branch].
Preserve all Session 95 and 96 implementation
and evidence.

Read:
- [Redacted: private project file path]
- [Redacted: private project file path]
- [Redacted: private project file path]
- [Redacted: private project file path]
- Relevant graphics and runtime source files

PRIMARY OBJECTIVE

Render the first genuine, live Mario Tennis
graphics task generated during cold ROM boot.

The game already reaches its graphics worker
and requests a real task.

Do not restart boot development or return to
broad architectural certification.

IMPLEMENTATION PRIORITIES

1. Inspect the real task request and determine
   its required microcode, display lists,
   framebuffer and memory dependencies.

2. Extend the experimental runtime to connect
   the actual game task to our existing RT64
   renderer where technically appropriate.

3. Establish safe ownership of task inputs,
   nested command data, scratch/output memory
   and renderer/GPU resources.

4. Implement the necessary task lifecycle and
   genuine SP/DP completion delivery.

5. Resume original game execution after
   completed graphics work.

6. Connect live VI presentation and attempt
   to display the first original game frame.

7. If successful, continue toward repeated
   frames and a usable title screen.

ACCEPTABLE EXPERIMENTAL LIMITATIONS

- Incorrect colors or textures
- Missing visual effects
- Low frame rates
- Incomplete audio
- Unstable animations
- Temporary rendering compatibility fixes

These are not reasons to delay the first frame.

NON-NEGOTIABLE REQUIREMENTS

- Do not fabricate graphics-task success.
- Do not replay frozen diagnostic frames.
- Do not claim a frame without actual live
  game-generated rendering and presentation.
- Do not post task completion before the
  required work is genuinely complete.
- Do not release borrowed memory while the
  renderer or GPU still needs it.
- Reject unsupported tasks and unsafe spans.
- Preserve ROM confidentiality and isolation.
- Do not commit generated proprietary code,
  assets or ROM material to Git.

WORKING METHOD

Implement, compile, run, observe and debug.

Prioritize actual native execution over
extensive reports and isolated certification.

Use focused tests for graphics ownership,
completion ordering, cancellation and memory
safety.

Continue through multiple related blockers
when safe and productive.

If RT64 cannot handle the reached task,
identify the precise incompatibility and
implement the smallest practical supported
path rather than rewriting the renderer.

Preserve failed attempts and stop at genuine
security or ownership blockers.

SUCCESS CRITERIA

M3 passes only when an authentic cold-game
graphics task produces a live presented frame.

If possible, continue toward repeated frames,
title-screen initialization and controller
input without waiting for another session.

SESSION CLOSEOUT

Report concisely:

1. What graphics functionality was implemented?
2. Was a live original-game frame rendered?
3. Did the game consume graphics completions?
4. Did execution progress beyond the first task?
5. What is the next concrete blocker?
6. What should Session 98 prioritize?

Update private reports and handoff.
Run relevant tests and security checks.
Verify private GitHub delivery.

Do not publish screenshots, binaries or assets
without separate approval.
Do not merge to main or change visibility.
Do not automatically start Session 98.

BEGIN SESSION 97.
