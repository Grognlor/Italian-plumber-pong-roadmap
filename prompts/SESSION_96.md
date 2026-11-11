# Session 96 — Owner prompt

Status: Session 96 completed. These are authentic owner instructions, not a claim
that every requested result was achieved. The exact captured prompt and its
provenance are preserved privately. Four private project file paths and one branch
are visibly redacted; all other wording and order are preserved.

[Read the Session 96 development diary](../docs/PROGRESS.md#session-96).

---


ITALIAN PLUMBER PONG
SESSION 96 - VIDEO MANAGER AND CONTINUED NATIVE BOOT

Continue accelerated experimental development.

Our priority remains:
GET IT RUNNING. GET IT PLAYABLE.
GET PEOPLE INVOLVED. THEN POLISH IT.

Resume from:
[Redacted: private project branch]

Read [Redacted: private project file path], [Redacted: private project file path],
[Redacted: private project file path] and
[Redacted: private project file path].

Preserve all completed Session 95 work.
Do not restart or recreate the boot system.

PRIMARY OBJECTIVE

Get past the original Mario Tennis video-manager
initialization and continue genuine native game
execution as far as safely possible.

Implement the missing host VI/retrace event
producer and required video-manager services.

Include:
- Owned event registration and queues
- Bounded retrace scheduling and wakeups
- Safe worker lifecycle and cancellation
- Correct memory and resource ownership
- Explicit rejection of unsupported tasks
- Focused regression tests

Do not fabricate successful graphics operations,
skip required initialization or replay a frozen
diagnostic frame.

SECONDARY OBJECTIVE

Continue cold ROM execution after the video
manager is initialized.

Identify and implement the next actual blockers.

Prioritize a genuine game-requested ROM transfer
and successful completion consumption.

This is required to pass M2.

STRETCH OBJECTIVE

If M2 is reached, continue immediately toward
the first original live graphics task and frame.

Investigate integration with the existing RT64
renderer and establish safe ownership of live
rendering inputs through completion.

A visually incorrect frame is acceptable.
A frozen diagnostic image is not.

DEVELOPMENT METHOD

Build, execute, observe, fix and repeat.

Use the smallest practical implementation
that preserves memory safety, genuine game
execution and required service behavior.

Do not spend the session independently
certifying every original instruction.

Do not reopen historical hardware timing or
stack-allocation investigations unless a new
actual boot blocker requires it.

Continue through multiple implementation
milestones when safe and productive.

Keep documentation and explanations concise.
Prioritize working code and actual execution.

Preserve the established isolation, ROM
confidentiality, dependency integrity,
Architecture D and unknown-target rejection.

Do not merge to main, publish binaries or
change repository visibility.

SESSION CLOSEOUT

Report:
1. What was implemented
2. Furthest genuine game execution reached
3. Whether M2 passed
4. Whether any live graphics were produced
5. Next concrete blocker
6. Recommended Session 97 task

Preserve private evidence, run relevant tests,
update the handoff and verify GitHub delivery.

Do not automatically launch Session 97.

BEGIN SESSION 96.
