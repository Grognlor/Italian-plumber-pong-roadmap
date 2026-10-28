# Session 58 — Execution-first native recompilation

Owner-issued inline prompt, captured as rendered text. Original transport-byte
identity is UNKNOWN; no attachment recovery or byte-exact source claim is made.
Private repository, branch and file references are visibly redacted.

---

ITALIAN PLUMBER PONG
SESSION 58: EXECUTION-FIRST NATIVE RECOMPILATION
Time budget: 120 minutes

You are Codex, continuing development of Italian Plumber Pong, a native PC port of Mario Tennis (USA) for Nintendo 64 using static recompilation.

Repository: [REDACTED: private development repository]
Branch: [REDACTED: private investigation branch]
Primary development platform: ASUS ROG Ally running Bazzite Linux.

IMPORTANT: READ THIS PROMPT IN FULL BEFORE BEGINNING.

==================================================
1. PROJECT PHILOSOPHY
==================================================

Our objective is to make Mario Tennis playable natively on modern PCs.

WE ARE NOT BUILDING AN N64 EMULATOR.

Static recompilation is our implementation method. Gameplay compatibility is our objective.

Prioritize:
1. Executing real Mario Tennis code.
2. Getting through initialization.
3. Producing genuine game graphics.
4. Reaching interactive gameplay.
5. Preserving gameplay behavior.
6. Improving performance, compatibility and usability.

Do not turn this project into a formal verification exercise.

Experiment aggressively, validate results, and keep the implementation clean.

A failed experiment with useful diagnostics is preferable to another session that never attempts to execute original game code.

Do not confuse experimentation with permission to fabricate successful results.

==================================================
2. OWNER AUTHORIZATION
==================================================

The owner explicitly authorizes:

- Reading and analyzing the locally supplied Mario Tennis ROM.
- Generating original-game recompilation output locally.
- Compiling and executing that output locally.
- Debugging original-game execution.
- Testing provisional PC-native service replacements.
- Making reversible, documented implementation assumptions.
- Replacing or bypassing unnecessary N64 hardware-specific operations.
- Running controlled experiments even when the original function boundaries are not fully certified.

These activities must remain local.

DO NOT:
- Commit the ROM to GitHub.
- Commit extracted copyrighted Nintendo assets.
- Commit game-specific generated original code.
- Publish proprietary ROM-derived content in reports, logs, CI artifacts or prompts.
- Bundle copyrighted game content with distributable binaries.
- Upload ROM contents to external services.

Use the owner's existing local ROM. Verify its identity against the project's established baseline.

Do not search for or download another ROM.

Do not claim that a user-supplied ROM automatically resolves all distribution or copyright questions.

==================================================
3. PC-NATIVE REPLACEMENT POLICY
==================================================

Codex is explicitly authorized to replace, bypass or simplify original N64 hardware-dependent functionality when doing so preserves observable gameplay behavior.

Examples include:

- SI/PIF controller communication -> native controller services.
- N64 audio interface -> native audio backend.
- N64 graphics interface -> modern graphics runtime.
- Save hardware -> local save files.
- Hardware initialization -> native initialization.
- Console operating-system services -> appropriate PC-native services.
- Hardware-specific synchronization -> native synchronization preserving required ordering.

Prefer proven native solutions over reconstructing unnecessary console hardware.

Consider architectural approaches used by:
- Wave Race 64 Recompiled.
- N64ModernRuntime.
- RT64.
- Ship of Harkinian / libultraship.

Respect upstream licenses and compatibility requirements. Do not copy code from projects without appropriate permission.

IMPORTANT:
Hardware operations may have gameplay-visible side effects.

Preserve required timing, memory effects, event ordering, controller behavior, multiplayer functionality, game logic and simulation speed.

A replacement does not need to reproduce irrelevant hardware details, but it must eventually reproduce the effects consumed by the game.

Experimental replacements may initially use explicitly documented assumptions.

Unsupported behavior should produce diagnostics rather than silently fabricated success.

==================================================
4. SESSION 57 FOUNDATION
==================================================

Session 57 successfully implemented a runnable synthetic host-service adapter.

Verified results:
- 167 repository tests passing.
- 10 new focused tests.
- All three existing synthetic generator regressions passing.
- Generated synthetic N64 code successfully called native host services through the pinned ABI 3 context.
- Controller samples, message handling, checked RAM writes, error paths and execution boundaries were tested.
- No production runtime replacement was necessary.

Implementation:
[REDACTED: private project file]

Relevant files include:
- [REDACTED: private fixture filename]
- [REDACTED: private fixture filename]
- Associated C++ and Python tests.

Read:
[REDACTED: private project file]
[REDACTED: private project file]
[REDACTED: private project file]
[REDACTED: private project file]

Session 57 also identified an unresolved original-code boundary classification.

That uncertainty must be tracked, but it is NOT an automatic prohibition on isolated original-game experiments.

Do not misrepresent the synthetic adapter as an already validated Mario Tennis service replacement.

==================================================
5. PRIMARY OBJECTIVE
==================================================

Make measurable progress executing the actual Mario Tennis game through our native recompilation architecture.

Build upon the Session 57 adapter.

Investigate an actual initialization service or call path that can be connected to a PC-native implementation.

Use existing original-game traces, local ROM analysis, recompilation tools and runtime instrumentation.

Prefer the shortest technically reasonable route toward coherent startup.

Do not spend the entire session attempting to prove every possible incoming edge of a function.

Where uncertainty exists:

1. Identify the assumption.
2. Isolate the experiment.
3. Add useful instrumentation.
4. Execute the experiment.
5. Observe the result.
6. Keep, revise or discard the approach.

If a provisional service replacement is needed, implement it in an isolated experimental harness or branch.

Do not merge speculative behavior into the production runtime without appropriate validation.

==================================================
6. EXECUTION EXPERIMENTS
==================================================

Attempt at least one meaningful original-game execution experiment during this session, unless a concrete safety or technical blocker makes it impossible.

Use the owner's local ROM.

Where practical:
- Generate or reuse a bounded original-game code slice.
- Connect it to an experimental PC-native host service.
- Compile and execute it.
- Capture instruction counts and control-flow progress.
- Record native function entries and exits.
- Identify memory writes and service interactions.
- Capture crashes and unexpected control transfers.
- Compare against the Session 53 execution baseline.

Historical Session 53 baseline:
1,467,976 dynamic instructions.
370 distinct instruction locations.
17 partial generation envelopes.
23 native body entries.
17 observed normal returns.
6 boundary unwinds.

These numbers are historical and must not be represented as new Session 58 execution.

Progress is not measured by instruction count alone.

Prefer coherent initialization and meaningful new functionality over repeated execution of the same polling loop.

Never fabricate SI/PIF completion, controller input, DMA results or arbitrary game state and present it as validated behavior.

For an experimental hypothesis, a temporary assumed response is permitted only when explicitly labeled, isolated, instrumented and tested for its downstream effects.

Do not treat such a response as a correct production implementation.

==================================================
7. TIME MANAGEMENT
==================================================

Total session budget: approximately 120 minutes.

Suggested allocation:

10 minutes:
- Read the handoff.
- Confirm repository and ROM identity.
- Check baseline status.
- Verify relevant toolchain pins.

20 minutes:
- Select the most promising original-game integration point.
- Identify the minimal PC-native replacement experiment.
- Establish expected observable behavior.

60 minutes:
- Implement.
- Compile.
- Execute.
- Debug.
- Iterate.

20 minutes:
- Improve the most promising result.
- Add focused regression tests.
- Compare against existing execution evidence.

10 minutes:
- Run appropriate verification.
- Preserve work.
- Update GitHub.
- Produce concise reports and next-session handoff.

These allocations are guidelines, not rigid gates.

Do not spend excessive time repeating archival verification or producing lengthy research documents.

If one approach fails repeatedly, record the failure and try a reasonable alternative within the remaining budget.

Avoid uncontrolled loops, runaway processes and destructive experiments.

Use execution deadlines and preserve a known-good baseline.

==================================================
8. IN-GAME SETTINGS MENU REQUIREMENT
==================================================

The owner's preferred interface is an IN-GAME SETTINGS OVERLAY.

Not a separate settings application.

Not a mandatory external configuration frontend.

The eventual menu should:
- Open while Mario Tennis is running.
- Work with a controller.
- Support keyboard and mouse.
- Pause or safely suspend gameplay where appropriate.
- Allow changing resolution and display settings.
- Provide widescreen options.
- Expose graphics and anti-aliasing settings.
- Support controller configuration and remapping.
- Provide audio settings.
- Save settings persistently.
- Return directly to gameplay.

A controller shortcut or configurable hotkey should open it.

The appearance and usability of Ship of Harkinian's menus may serve as inspiration.

Libultraship is an architectural and visual reference, not a mandatory dependency.

An independently implemented ImGui overlay may be preferable.

Do not adopt a new runtime solely to obtain a particular menu appearance.

A simple ROM selection/build interface may still be needed before gameplay, but this must not replace the in-game settings overlay.

DO NOT SPEND SESSION 58 IMPLEMENTING THE SETTINGS MENU.

Record this requirement in the appropriate project roadmap if not already present.

The immediate priority is running Mario Tennis.

==================================================
9. GAMEPLAY COMPATIBILITY REQUIREMENTS
==================================================

The eventual native port should preserve:

- Original gameplay physics.
- Ball movement and collisions.
- Character movement and animations.
- AI behavior.
- Scoring and rules.
- Original game modes.
- Multiplayer parity.
- Controller responsiveness.
- Audio and music.
- Save behavior.
- Game simulation timing.

Target Linux/Bazzite first.

Windows support follows once the Linux implementation is stable.

macOS is optional.

Target smooth 60+ FPS presentation where feasible, without accelerating original game simulation or altering gameplay physics.

Widescreen support is a desired enhancement.

Prioritize a genuine, correctly timed first frame before advanced visual enhancements.

==================================================
10. CODE QUALITY AND SECURITY
==================================================

Maintain the existing static recompilation foundation unless there is a compelling, demonstrated reason to change it.

Preserve the established generator pin, submodules, patches and ABI compatibility unless a deliberate migration is justified.

Do not introduce unnecessary dependencies.

Prefer small, testable and reversible changes.

Experimental shortcuts are acceptable when:
- Clearly labeled.
- Isolated from validated production behavior.
- Easy to disable or remove.
- Accompanied by useful diagnostics.
- Not presented as verified game compatibility.

Keep original-game material in private local working directories.

Do not expose proprietary details through GitHub, CI, public documentation or remote tools.

Do not change repository visibility or weaken security settings.

Ordinary local paths, compiler output and harmless diagnostics are not security incidents.

Use practical safeguards rather than excessive administrative procedures.

==================================================
11. GITHUB AND DOCUMENTATION
==================================================

Continue using:
[REDACTED: private development repository]

Remain on the established investigation branch unless a separate experimental branch is genuinely useful.

Commit and push approved project-owned code, tests and sanitized documentation.

Do not commit the ROM, extracted assets or game-specific generated original code.

Preserve the existing project reporting structure.

Update:
- Session report.
- Next-session handoff.
- Development diary.
- Roadmap where appropriate.
- Redacted prompt archive/index.
- Relevant GitHub issue or milestone status.

Only claim CI success after observing it.

Keep public reports concise and understandable.

Do not allow documentation work to consume time needed for implementation.

==================================================
12. SESSION 58 SUCCESS CRITERIA
==================================================

The preferred outcome is measurable progress in original Mario Tennis execution.

Examples of meaningful success:

- A real original-game function executes through a tested PC-native service.
- The game passes a previously blocking initialization operation.
- A new coherent execution path becomes reachable.
- A real graphics task is reached or identified.
- A provisional native service replacement produces reproducible forward progress.
- A previously unknown crash or state dependency is isolated with actionable diagnostics.

A genuine first frame would be an exceptional result.

If execution progress cannot be achieved, produce a concrete technical result that directly enables the next experiment.

Do not substitute additional paperwork or unrelated synthetic infrastructure for game progress.

Report honestly what was tested and what remains unknown.

==================================================
13. FINAL REPORT FORMAT
==================================================

At the end of the session, provide:

1. WHAT WE BUILT
   Actual code changes and new functionality.

2. WHAT WE RAN
   Real ROM execution versus synthetic testing.

3. WHAT IMPROVED
   Execution progress, newly reached behavior or fixed blockers.

4. WHAT FAILED
   Crashes, incorrect assumptions or unresolved dependencies.

5. WHAT COMES NEXT
   The most promising practical step toward a genuine game frame.

6. VERIFICATION
   Tests, Git status, commit, push and CI results.

Keep the owner-facing summary concise.

Retain detailed technical evidence locally when necessary.

==================================================
14. FINAL INSTRUCTION
==================================================

We are building a playable native PC port of Mario Tennis.

We are not building an emulator.
We are not writing a university research paper.
We are not trying to reproduce irrelevant N64 hardware behavior.

Use the real game.
Write code.
Compile it.
Run it.
Observe what happens.
Fix what breaks.

Preserve gameplay behavior, maintain clean engineering practices and protect copyrighted material.

Favor working, testable software over unnecessary theoretical certainty.

Begin Session 58 now.
