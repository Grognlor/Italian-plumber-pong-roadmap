# Session 60 — Cartridge initialization and forward execution

Authentic owner-issued user-message text, preserved privately as captured in the
local session. This public rendering visibly withholds internal evidence paths
and the private handoff filename. Other wording and order are preserved. Original
transport-byte identity is UNKNOWN; no attachment recovery is claimed.
Status: issued; results are recorded in the matching development diary entry.

---

ITALIAN PLUMBER PONG
SESSION 60: CARTRIDGE INITIALIZATION AND FORWARD EXECUTION

You are continuing development of Italian Plumber Pong, our native PC recompilation project for Mario Tennis (USA), Nintendo 64.

This is a NEW Codex conversation, but an ongoing development project. Session 59 is complete.

FIRST: RECOVER THE PROJECT STATE

1. Confirm the repository, current branch, working-tree status, and applicable project instructions.
2. Read:
   - [REDACTED: private Session 59 report path]
   - [REDACTED: private next-session plan path]
   - The locally preserved Session 59 [REDACTED: private handoff filename]
3. Locate and verify the retained Session 59 experimental files, diagnostics, source designation, archive manifest, and detached anchor.
4. Verify essential toolchain pins and ROM identity without modifying the original ROM.
5. Preserve any uncommitted work. Do not overwrite or discard it.

Use the existing handoff as the technical source of truth. Do not repeat investigations already completed unless necessary to reproduce a specific failure.

PRIMARY OBJECTIVE

Get the original Mario Tennis code executing farther through its startup sequence.

Session 59 successfully executed and independently matched 2,062,859 instructions at 1,047 distinct locations. It repaired native return handling, introduced controlled interrupt-mask bookkeeping, and reached an original PI cartridge-status read.

Your immediate task is to investigate and overcome that PI initialization boundary.

WORK PLAN

1. Reproduce the verified Session 59 stopping point using its retained diagnostics and bounded execution harness.

2. Identify the original cartridge/ROM initialization operation surrounding the reached PI status read, including its actual caller and game-visible effects.

3. Investigate whether that operation can be replaced by a bounded PC-native cartridge/ROM service.

4. Implement the smallest justified experimental replacement that preserves the behavior the game actually depends on.

5. Generate, compile, and execute the original game code with that replacement.

6. Compare the resulting execution against the independent reference, checking supported register state, RAM, control flow, and service ordering.

7. If successful, continue forward immediately toward the next meaningful execution dependency.

Do not simply force the PI status register to report idle or fabricate successful DMA completion. Where a native service legitimately replaces hardware behavior, implement the necessary observable effects and document the assumptions.

DEVELOPMENT PHILOSOPHY

Our goal is a playable PC game, not an N64 emulator or a university research project.

Experiment aggressively, validate what works, and keep the code clean.

You are explicitly authorized to use the owner's locally supplied Mario Tennis ROM for private analysis, code generation, compilation, and controlled execution.

You may introduce reversible, provisional native replacements for console-specific operations when doing so preserves the game's meaningful behavior.

Examples include:
- Cartridge and ROM access
- Console initialization
- Controller interfaces
- Audio hardware configuration
- Interrupt and timing services

Preserve gameplay rules, physics, timing, multiplayer behavior, graphics, audio, and save functionality.

Avoid speculative production hacks, unnecessary certification exercises, and extensive documentation work that does not advance execution.

A controlled experiment may use explicit assumptions, but those assumptions must never be misrepresented as verified hardware behavior.

EXECUTION PRIORITIES

Once the PI boundary is overcome, prioritize actual forward progress.

Look for opportunities to reach:
- More original startup code
- Graphics initialization
- Task submission or rendering paths
- The first genuine game-generated frame

Do not build a renderer, settings UI, launcher, or unrelated infrastructure prematurely.

If the next dependency requires a substantial implementation, identify the smallest useful vertical slice and make measurable progress within the session.

TECHNICAL CONTINUITY

Preserve the successful Session 59 mechanisms, including:

- Checked native tail returns and return scopes
- Root/nonlocal transfer handling
- Known-byte image activation and instruction checks
- Controlled post-ERET code retirement
- Experimental interrupt-mask bookkeeping
- Explicit virtual Count and initialization premises
- Existing FP uncertainty handling
- Independent reference comparisons

Do not weaken these protections merely to increase the executed instruction count.

Keep N64Recomp, ABI 3, submodules, patches, and analysis dependencies pinned unless a change is genuinely necessary and explicitly justified.

SECURITY

The original ROM, extracted Nintendo assets, proprietary generated game code, private traces, and sensitive diagnostics must remain outside GitHub, public CI, and distributable artifacts.

Only reviewed, project-owned source code, tests, and sanitized documentation may be committed.

Keep the existing repository access controls, sandbox restrictions, and approval boundaries.

Do not publish private numeric address metadata through diagnostic output.

No release, main-branch merge, or access change is authorized.

LONG-TERM PRODUCT DIRECTION

Linux/Bazzite first, Windows second, macOS optional.

The finished game should support widescreen, multiple controllers, stable high-frame-rate gameplay, and a straightforward ROM-based installation.

Settings should eventually be accessible through a controller-operable IN-GAME overlay, not a separate settings application.

These are future requirements, not tasks for Session 60 unless genuine gameplay execution makes them immediately relevant.

TIME AND REPORTING

Aim for approximately two hours of productive work, subject to available execution limits.

Spend most of the session implementing, compiling, running, debugging, and validating actual game execution.

Avoid spending the session exclusively planning or researching.

Before finishing:

1. Run focused and full available verification.
2. Record exactly what original code executed and what new behavior was reached.
3. Distinguish fully matched native execution from reference-only progress and speculative experiments.
4. Report any newly encountered blocker and its practical significance.
5. Preserve private artifacts and verify archive integrity.
6. Update the Session 60 report and next-session handoff.
7. Commit and push only reviewed, sanitized project-owned changes to the existing investigation branch, subject to existing repository rules.
8. Confirm the observed Git/CI status without inventing successful results.

SUCCESS CRITERIA

The ideal outcome is a justified native cartridge/ROM service that allows original Mario Tennis code to execute beyond the Session 59 stopping point.

A successful session should demonstrate measurable forward execution, supported by actual native execution and independent validation.

If that cannot be achieved, deliver the narrowest reproducible blocker and a concrete implementation path for Session 61.

START NOW.

Read the handoff, verify the environment, reproduce the PI boundary, and proceed directly into implementation and testing.

Do not stop after presenting a plan.