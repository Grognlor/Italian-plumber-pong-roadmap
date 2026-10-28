# Session 61 — FPU exception handling and forward execution

Authentic owner-issued user-message text, preserved privately as captured in the
local session. This public rendering visibly withholds internal evidence paths
and handoff/archive filenames. Other wording and order are preserved. Original
transport-byte identity is UNKNOWN; no attachment recovery is claimed.
Status: issued; the completed session's verified results appear in its diary entry.

---

ITALIAN PLUMBER PONG
SESSION 61: FPU EXCEPTION HANDLING AND FORWARD EXECUTION

You are continuing development of Italian Plumber Pong, our native PC recompilation project for Mario Tennis (USA), Nintendo 64.

This is a new Codex conversation. Session 60 is complete, committed, pushed and verified.

PRIMARY OBJECTIVE

Resolve the original floating-point coprocessor exception encountered at the end of Session 60, then continue executing original Mario Tennis code as far as practical.

Our long-term objective remains a fully playable native PC port, not an N64 emulator.

START WITH THE EXISTING HANDOFF

1. Confirm the repository, investigation branch, working-tree status and applicable project instructions.
2. Read:
   - [REDACTED: private Session 60 report path]
   - [REDACTED: private next-session plan path]
   - The locally preserved Session 60 [REDACTED: private handoff filename]
3. Identify the final sealed Session 60 archive using private [REDACTED: private final archive designation filename]. Do not accidentally use the earlier failed seal.
4. Verify archive membership, detached anchor, source/tool pins and original ROM identity.
5. Create a fresh restricted working directory. Never modify or execute directly from sealed archives.
6. Reuse the exact retained scripts, source designation, reference results and negative controls.

Do not repeat completed investigations without a specific technical reason.

CURRENT VERIFIED BASELINE

Session 60 achieved two matched native execution profiles:

- 2,066,286 original instructions
- 1,807 distinct instruction locations
- 228 native body entries
- 164 normal returns
- 64 boundary unwinds
- 11 original ERET transfers
- 21 interrupt-mask accesses
- One bounded native cartridge-word read
- 13 original video configuration writes
- 31 original indexed-TLB writes

183 repository tests and three generator regressions passed.

These are controlled partial execution envelopes, not a coherent boot or playable game.

CURRENT BLOCKER

After original thread startup disables COP1, original code attempts to read floating-point control/status (FCSR).

The reference requires a coprocessor-unusable exception.

Native execution correctly stops because the required exception/FPU ownership behavior has not yet been implemented.

Do not simply force COP1 enabled or skip the instruction.

SESSION 61 WORK PLAN

PHASE 1: REPRODUCE AND UNDERSTAND

Reproduce the saved Session 60 FCSR stopping point.

Inspect the actual original thread startup, exception handler, FPU ownership and retry path.

Determine the minimum game-visible effects needed to handle this particular exception correctly.

Pay particular attention to:
- COP1 enable/disable ownership
- CP0 Status and Cause
- EPC and faulting instruction PC
- Branch-delay behavior
- Thread state and FPU context
- Exception entry and return
- Original handler decisions and instruction retry

Do not implement a general-purpose N64 exception emulator unless the reached original code genuinely requires it.

PHASE 2: IMPLEMENT A BOUNDED SOLUTION

Implement the smallest justified experimental exception-delivery or PC-native FPU ownership service.

Prefer executing original handler code when feasible.

If a native replacement is simpler and preserves the meaningful game-visible behavior, that is acceptable.

The implementation must:
- Respect actual thread/FPU ownership
- Preserve defined register and RAM state
- Maintain correct exception and retry semantics
- Avoid inventing unobserved hardware events
- Reject unsupported states explicitly
- Remain reversible and isolated from production code

Add focused synthetic tests and negative controls.

PHASE 3: RUN THE ORIGINAL GAME

Generate, compile and execute the actual Mario Tennis code using the corrected service.

Compare native execution with the independent reference.

Validate:
- Ordered instruction trace
- Defined integer and control state
- Owned RAM
- Supported floating-point state
- Exception and return ordering
- Host service effects
- Image activation and instruction validity

Preserve the entire previously matched prefix.

Do not report a longer reference-only path as successful native execution.

PHASE 4: PUSH FORWARD

Once the FCSR boundary is resolved, immediately continue toward the next original execution dependency.

Prioritize meaningful progress toward:
1. Completion of startup and thread initialization
2. Graphics task creation or submission
3. Native rendering integration
4. The first genuine Mario Tennis-generated frame
5. Eventually, interactive gameplay

Investigate the next reached blocker and implement another bounded native service if time permits.

Do not stop merely because the first exception issue has been fixed.

PRACTICAL DEVELOPMENT PHILOSOPHY

We are trying to make Mario Tennis playable on PC.

We are not developing a general-purpose N64 emulator or conducting an academic verification project.

Experiment aggressively, validate results and keep the code clean.

Use native PC services to replace console-specific hardware behavior when the game-visible effects can be preserved.

Avoid:
- Unnecessary function-boundary certification
- Repeating settled investigations
- Excessive documentation
- Speculative hardware emulation
- Arbitrary success values
- Premature production architecture
- Unrelated feature development

The owner's original ROM is authorized for local private analysis, generation, compilation and controlled execution.

Meaningful gameplay behavior must remain intact.

GRAPHICS PRIORITY

We have now reached original video initialization, but no graphics task or rendered frame exists yet.

If execution reaches a genuine graphics workload, investigate the smallest viable path to a real PC-rendered result.

Existing N64 recompilation projects and graphics runtimes may be consulted where useful, but do not migrate frameworks or add dependencies without clear technical justification.

A genuine rendered frame is more valuable than another large body of theoretical research.

Never fabricate a screenshot, graphics result or playable-build claim.

PRESERVE EXISTING MECHANISMS

Keep the successful Session 60 infrastructure:

- Checked call/tail/root return handling
- Saved link values before delay slots
- Generated-body fallthrough guards
- Known-byte activation snapshots
- Per-fetch RAM validation
- Controlled retired-code handling
- Interrupt-mask producer tracking
- Virtual Count
- Provisional host initializer
- Bounded ROM/cartridge service
- Experimental video configuration capture
- Original TLB writes
- FP uncertainty tracking

Do not weaken these mechanisms merely to increase the instruction count.

Keep the pinned ABI 3, N64Recomp toolchain, five submodules, six patches and analysis dependencies unless an essential change is justified.

SECURITY REQUIREMENTS

The ROM, proprietary generated game code, extracted assets, original traces and sensitive diagnostics must remain private and outside GitHub and CI.

Only reviewed project-owned code, tests and sanitized documentation may be published.

Keep current access controls, sandbox restrictions and approval boundaries.

Do not publish private addresses or derived proprietary identifiers through logs or reports.

No release, main-branch merge, access change or public media publication is authorized.

PRODUCT DIRECTION

Linux/Bazzite first, Windows next, macOS if practical.

Eventually support:
- Widescreen resolutions
- Multiple controllers
- Stable high-frame-rate gameplay
- Controller/keyboard/mouse input
- Simple ROM-based installation
- In-game settings overlay
- Persistent settings and update functionality

Do not build the settings UI or launcher now.

SESSION MANAGEMENT

Target approximately two hours of productive development, subject to usage and execution limits.

Prioritize implementation, compilation, original-code execution and validation.

If approaching usage limits or interruption:
- Stop at a safe checkpoint.
- Preserve current work and partial diagnostics.
- Write a concise resumable local checkpoint.
- Do not assume unfinished operations succeeded.
- Do not wait until context is exhausted to record essential findings.

FINAL DELIVERABLES

1. Session 61 technical report with actual observed results.
2. Clear comparison against Session 60.
3. Exact distinction between native, reference-only and hypothetical execution.
4. Focused and full test results.
5. Updated next-session handoff.
6. Verified preservation of essential private artifacts.
7. Updated public roadmap, diary and redacted prompt archive where appropriate.
8. Reviewed, sanitized commit and push to the existing investigation branch.
9. Observed CI status, without claiming checks passed unless confirmed.

SUCCESS CRITERIA

At minimum, resolve or precisely isolate the original COP1 exception and FPU ownership boundary.

Preferred success:
- Correct bounded exception or ownership handling
- Original game execution beyond Session 60
- Independently matched native/reference state
- A newly reached startup or graphics dependency

Stretch goal:
Reach genuine graphics task execution or produce the first authentic Mario Tennis-rendered frame.

START NOW.

Recover the verified Session 60 handoff, reproduce the FCSR boundary, implement the smallest justified fix, and execute the original game.

Do not stop after presenting a plan.