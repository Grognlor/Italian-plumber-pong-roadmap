# Session 101 — Audio initialization and native startup

Authentic owner prompt, verified against its private source. Two localized spans
are visibly redacted. Session complete: the missing coordination service works
and original sound setup continues. Drawing and presentation were not achieved;
there is no playable game.

## Owner prompt


ITALIAN PLUMBER PONG
SESSION 101 - AUDIO INITIALIZATION AND NATIVE STARTUP

Continue accelerated experimental development.

Resume from:
[REDACTED: private development branch]

Read:
[REDACTED: private project instruction, handoff and design-document paths.]

Preserve all Sessions 95-100 work.

GUIDING PRINCIPLE

Get it running. Get it playable.
Get people involved. Then polish it.

PRIMARY OBJECTIVE

Implement the interrupt-mask exchange
required by the original game's audio
registration code.

Review the actual caller and required
previous-mask return behavior.

Implement a narrow, owned host service
supporting:

- CPU and device interrupt-mask state
- Previous-mask token fidelity
- Masking and restoration
- Nested critical sections
- Correct scheduling and event delivery
- Deferred events and safe unmasking
- Worker switching and cancellation
- Rejection of unsupported mask operations

Do not fabricate interrupt success,
read physical MI registers through RDRAM
or bypass required audio initialization.

Once implemented, resume the actual
cold-ROM execution path.

SECONDARY OBJECTIVE

Continue through the remaining original
audio and game startup routines.

Implement the next required services
when their behavior and ownership can
be established safely.

Do not fake audio task completion.
Actual audio playback is not required
before the first visible frame.

GRAPHICS OBJECTIVE

Continue toward the first genuine
drawing task and presented game frame.

Reuse the existing RT64 implementation.

Extend only the supported graphics
commands and memory dependencies
needed by the actual game.

Preserve GPU completion and memory
ownership guarantees.

Connect authentic VI framebuffer
selection and presentation.

A visually imperfect frame is acceptable.
A state-only task or blank window is not.

CONTROLLER REQUIREMENTS

Preserve the functioning live controller
reads from Session 100.

Retain the documented long-term goal of
broad Xbox, PlayStation, Nintendo, 8BitDo,
generic USB/Bluetooth and ROG Ally support.

Four independent players, hotplugging,
mapping and in-game controller settings
remain requirements.

Do not replace the experimental evdev
backend during this session unless
necessary for actual startup progress.

DEVELOPMENT METHOD

Build, run, inspect and correct actual
blockers iteratively.

Prioritize real native execution over
unnecessary certification expansion.

Preserve security, ROM confidentiality,
checked memory, dependency integrity,
isolation and unknown-target rejection.

Do not publish ROM-derived material,
binaries or media, merge to main or
change repository visibility.

SESSION CLOSEOUT

Report:
1. Whether interrupt-mask handling works
2. How far original startup progressed
3. Whether audio initialization continued
4. Whether drawing or presentation occurred
5. Next concrete blocker
6. Recommended Session 102 priorities

Run focused and full relevant tests.
Update private reports and handoff.
Verify GitHub delivery.

Do not automatically start Session 102.

BEGIN SESSION 101.
