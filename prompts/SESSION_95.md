# Session 95 — Owner prompt

Status: Session 95 completed. These are the authentic primary owner instructions,
not a claim that every requested milestone was achieved. The original and its
provenance are preserved privately. Nine private project paths are visibly redacted;
all other wording and ordering are preserved.

[Read the Session 95 development diary](../docs/PROGRESS.md#session-95).

---


ITALIAN PLUMBER PONG
SESSION 95 - ACCELERATED NATIVE BOOT

OWNER AUTHORIZATION

I approve Session 94's Option C:
a separate experimental native boot development
branch using our existing N64Recomp work.

Our new development principle is:

GET IT RUNNING.
GET IT PLAYABLE.
GET PEOPLE INVOLVED.
THEN POLISH IT.

This session begins our accelerated development
phase. The immediate objective is a genuine
Mario Tennis native boot, progressing toward
the first live original-game frame.

READ FIRST

- [Redacted: private project file path]
- [Redacted: private project file path]
- [Redacted: private project file path]
- [Redacted: private project file path]
- [Redacted: private project file path]
- [Redacted: private project file path]
- [Redacted: private project file path]

Read older reports only when needed for a
specific implementation dependency.

PHASE 1 - ESTABLISH THE EXPERIMENT

Create a separate experimental branch from
the reviewed project state.

Preserve the existing investigation branch,
historical evidence and production admission
requirements.

Add a clearly scoped experimental development
policy to the repository documentation.

The experimental policy may defer exhaustive
original/reference/native architectural
certification before a boot attempt.

It must NOT relax ROM confidentiality,
memory bounds, ownership safety, isolation,
dependency integrity or unknown-target
rejection.

Preserve Architecture D: guest architectural
records and sentinel queues remain distinct
from independently owned host contexts and
host queues.

Make the distinction between experimental
execution and certified execution explicit.

PHASE 2 - BUILD THE NATIVE STARTUP PATH

Do real implementation work.

Investigate and address the known gaps:

- [Redacted: private project file path] currently rejects ordinary
  ROM launch.
- [Redacted: private project file path] deliberately
  stops startup at the video manager.
- General game thread/bootstrap integration
  is incomplete.
- Native OS service bindings are incomplete.
- ROM transfer and completion handling are
  not connected for general game execution.
- Overlay and indirect-call closure are
  incomplete.
- Live renderer task submission and VI
  presentation are not yet integrated.

Reuse the existing ROM decoder, N64Recomp,
ABI 3, reviewed patches, checked guest memory,
runtime components, renderer and tests.

Use Ghidra, Splat, spimdisasm, Rabbitizer or
m2c where they directly accelerate analysis.

Do not begin a complete matching-C decompilation
unless a specific technical blocker makes it
necessary and the approach is justified.

Use practical host implementations of N64
operating-system services where appropriate.

These implementations do not need to reproduce
every original hardware timing detail, but
must preserve the behavior required by the
game and remain memory-safe.

PHASE 3 - EXECUTE, DEBUG AND ITERATE

Attempt a genuine cold boot from the owner's
local Mario Tennis ROM.

Work iteratively:

1. Build the experimental executable.
2. Run it in the reviewed isolated environment.
3. Identify the first actual execution blocker.
4. Investigate the relevant code or service.
5. Implement a bounded correction.
6. Rebuild and run again.
7. Continue toward the next milestone.

Do not stop after one failed attempt if a safe,
reasonable correction is available.

Do not spend the session gathering exhaustive
certification evidence for every new path.

Use focused tests and practical debugging.

Do not fabricate success, inject emulator
snapshots, silently skip required game logic
or substitute frozen diagnostic graphics for
live rendering.

Stop when an unsafe memory operation, unknown
execution target, unreviewed dependency or
unresolvable ABI mismatch prevents safe progress.

PHASE 4 - DEVELOPMENT MILESTONES

Work toward these milestones in order:

M1 - Native executable starts from the
     original owner's ROM and executes
     genuine translated game code.

M2 - A genuine original game thread starts,
     and a real ROM transfer and completion
     are successfully consumed.

M3 - The first live Mario Tennis frame is
     generated and displayed.

M4 - A usable title screen appears.

M5 - Controller input works.

M6 - A tennis match becomes playable.

Continue beyond M2 within the session if
progress and available resources permit.

A build with missing audio, graphical glitches,
inaccurate effects or other noncritical bugs
is an acceptable experimental milestone.

Do not confuse an experimental milestone
with production readiness.

AUTONOMY AND EFFICIENCY

Work as an implementation-focused coding agent,
not primarily as a research reporter.

You are authorized to make ordinary engineering
decisions, edit project-owned infrastructure,
run builds and tests, and commit safe changes
on the experimental branch.

Do not request approval for routine fixes
within this authorized scope.

Use concise plans and reports.

Avoid repetitive historical reviews,
redundant verification and unnecessary
documentation expansion.

Do not collect, compare or report token usage.

Do not recursively launch Codex or another
agent.

Respect bounded process execution and resource
limits. When repeated attempts reveal a genuine
blocker, preserve the evidence and move to the
next useful engineering task.

SECURITY AND PUBLICATION

- Keep both ROMs and all proprietary game
  material outside Git and remote storage.
- Never commit extracted game code, translated
  game code, assets or proprietary binaries.
- Keep ROM-dependent processing isolated.
- Preserve source and dependency integrity.
- Keep the private repository private.
- Do not merge to main.
- Do not publish releases or game binaries.
- Do not change access or visibility.
- Preserve all historical evidence.
- Do not publish screenshots or videos without
  separate approval.

Keep public roadmap updates within the
existing authorized paths and ensure they
accurately describe verified progress.

SESSION CLOSEOUT

Report concisely:

1. What code was actually implemented?
2. What native execution was demonstrated?
3. Which milestones passed?
4. What was the furthest authentic game
   execution point reached?
5. What is the next concrete blocker?
6. What should the next development session
   implement?

Update the private handoff and required
project documentation.

Run relevant tests and security checks,
preserve reproducible evidence and verify
the private GitHub delivery.

Do not start Session 96 automatically.

BEGIN SESSION 95.
