# Session 98 — Owner prompt

Status: Session 98 completed. These are authentic owner instructions, not a claim
that drawing or a live frame was achieved. The exact captured prompt and its
provenance are preserved privately. Four private file paths and one branch are
visibly redacted; all remaining wording and order are unchanged.

[Read the Session 98 development diary](../docs/PROGRESS.md#session-98).

---


ITALIAN PLUMBER PONG
SESSION 98 - QUEUE RETIREMENT AND FIRST DRAWING

Continue accelerated experimental development.

Our priority remains:
GET IT RUNNING. GET IT PLAYABLE.
GET PEOPLE INVOLVED. THEN POLISH IT.

Resume from:
[Redacted: private project branch]

Read:
- [Redacted: private project file path]
- [Redacted: private project file path]
- [Redacted: private project file path]
- [Redacted: private project file path]

Preserve all Session 95-97 implementation
and verified progress.

PRIMARY OBJECTIVE

Resolve the specific queue-lifetime blocker
preventing the next original ROM transfer.

The game has already completed a genuine
RT64 graphics task and consumed its SP/DP
completion messages.

A subsequent ROM transfer overlaps a
registered temporary queue on a host-owned
worker stack.

Investigate the exact queue lifecycle:

- Original creation and registration
- Producer and completion activity
- Message consumption
- Remaining waiters and references
- Device/event registrations
- Authenticated worker return
- Cancellation and resource retirement

Implement explicit safe queue retirement
with appropriate generation and invalidation
checks.

Do not silently delete queue registrations
or assume empty storage is safe to reuse.

Do not reopen unrelated historical original
stack-allocation investigations.

SECONDARY OBJECTIVE

Resume genuine cold-ROM execution.

Continue through subsequent original ROM
transfers, overlays, game threads and
graphics tasks as far as safely possible.

Build, run, diagnose and fix actual blockers
rather than producing another planning-only
session.

GRAPHICS OBJECTIVE

Reach the first authentic graphics task
that contains drawing commands.

Extend the existing live RT64 integration
only for the required supported commands
and their memory dependencies.

Preserve coherent renderer input ownership
through GPU completion and safe retirement.

Connect actual framebuffer selection and
VI presentation.

A frame with broken textures, colors,
geometry or effects is acceptable.

A state-only task, blank renderer window
or frozen diagnostic replay is not a
successful game frame.

AUTONOMY

Continue through multiple related
implementation blockers if safe and useful.

Use focused tests and bounded debugging.
Avoid exhaustive certification work that
does not directly advance native execution.

Preserve ROM confidentiality, memory
bounds, dependency integrity, isolation,
Architecture D and unknown-target rejection.

Never commit ROM-derived proprietary code,
assets or binaries to Git.

Do not merge to main, publish game binaries,
change visibility or publish media without
separate approval.

SUCCESS CRITERIA

Primary success:
The queue is demonstrably retired safely,
and the previously blocked ROM transfer
can proceed.

Stretch success:
The game submits a live drawing task,
RT64 processes it and a genuine frame
is presented.

If rendering succeeds, continue toward
repeated frames and title-screen startup.

SESSION CLOSEOUT

Report concisely:

1. What was implemented?
2. Was the queue retirement verified?
3. How far did original execution progress?
4. Were live drawing commands processed?
5. Was a real frame presented?
6. What is the next concrete blocker?
7. What should Session 99 implement?

Update private reports and handoff.
Run relevant tests and security checks.
Verify private GitHub delivery.

Do not automatically launch Session 99.

BEGIN SESSION 98.
