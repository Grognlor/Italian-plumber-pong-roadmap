# Session 76 — Owner prompt

Status: issued for Session 76. Requested objectives are not completion claims.
Authentic owner-input text; exact original and provenance preserved privately.
Revision note (Session 78): restored safe engineering instructions previously withheld too broadly. Earlier public versions remain in Git history. This is the original owner request, not a retrospective account of results.
See the [development diary](../docs/PROGRESS.md#session-76) for verified results.

---

ITALIAN PLUMBER PONG
SESSION 76 MASTER PROMPT
TOOLCHAIN EXPANSION + AGGRESSIVE NATIVE DEVELOPMENT

PROJECT: Mario Tennis (USA) Nintendo 64 native PC recompilation
SESSION: 76
PRIMARY PLATFORM: Linux / Bazzite / ASUS ROG Ally
DEVELOPMENT AGENT: Codex
PROJECT OWNER: Human manager
RESEARCH AND REVIEW: ChatGPT

============================================================
0. AUTHORIZATION AND MISSION
============================================================

The owner authorizes Session 76 to begin now.

This is a substantial autonomous engineering session, not merely a tooling demonstration.

Two major objectives:

A. Install, configure, evaluate and integrate useful reverse-engineering tools into the Codex development workflow.

B. Use those tools, alongside the existing toolchain, to make measurable progress toward a continuously running native Mario Tennis application.

PRIMARY PRIORITY:
Original game execution, especially the loader, current-thread ownership, worker initialization, scheduler and asynchronous ROM transfer.

SECONDARY PRIORITY:
Accelerate authenticated original-function discovery, validation and native recompilation.

TERTIARY PRIORITY:
Investigate the remaining native RT64 textured graphics discrepancies.

Do not allow tool installation, benchmarks or documentation to displace engineering progress.

Work autonomously within existing project security and approval boundaries.

Do not ask routine questions.

Do not make assumptions about unavailable tools, permissions, host configuration or the remaining Codex usage allowance.

Where authorization is insufficient, record the limitation, continue with permitted alternatives and preserve a useful handoff.

============================================================
1. REPOSITORIES AND RECOVERY
============================================================

Private development repository:

[REDACTED: private development repository identifier]

Branch:

[REDACTED: private development branch]

Public roadmap:

Grognlor/Italian-plumber-pong-roadmap

Read:

[REDACTED: private session report path]
docs/NEXT_SESSION_PLAN.md
DEVELOPMENT_WORKFLOW.md

Recover the exact Session 75:

FINAL_HANDOFF.json
RECOVERY.md
Primary inventory and detached anchor
Separately anchored final delivery addendum

The accepted Session 75 primary contains 377 files.

Manifest SHA-256:

[REDACTED: private evidence seal]

This is a selected archive, not a complete independent baseline.

It depends on the accepted Session 74 primary and its separately anchored 34-file final addendum.

Session 74 primary:

9,932 files

Manifest SHA-256:

[REDACTED: private evidence seal]

Session 74 final addendum digest:

[REDACTED: private evidence seal]

Verify exact membership, hashes, detached anchors, permissions and ownership.

Never modify or execute sealed evidence.

Restore a NEW restricted persistent workspace from authenticated sources.

Recheck:

- ROM identity
- N64Recomp ABI 3
- Generator and header
- Source/submodule pins
- Six reviewed patches
- Pinned analysis packages
- N64ModernRuntime lock
- RT64 renderer lock
- Required build tools
- Security policies

Use a fresh application CMake configuration.

If a required predecessor or seal is missing or invalid, do not substitute unauthenticated material.

Preserve exact recovery evidence.

============================================================
2. VERIFIED SESSION 75 BASELINE
============================================================

CONNECTED ORIGINAL:

6 routines
1,368 bytes
342 static locations
5 normal returns

ISOLATED ORIGINAL:

8 extents
632 bytes
158 static locations
16 retained comparisons

Repository tests:

232 PASS

Generator regressions:

3 PASS

Native CTest:

9 PASS

Conventional comparisons:

4 PASS

Session 75 established that the selected cache's initial [REDACTED: private ROM-derived data value] key is authenticated ROM-backed image data.

This removes the need to invent a post-load initialization store for that specific value.

Still UNKNOWN:

- Exclusive dynamic writer history
- Selected current-thread initialization
- Worker initialization and ownership
- Cache synchronization
- Original queue and worker lifetimes
- PI/DMA and interrupt transitions
- Scheduler closure
- Full original loader integration

Graphics:

Session 74 successfully replayed authentic frozen textured tasks through native RT64/Vulkan.

Recognizable Nintendo 64 startup logos were rendered and captured privately.

Task 3:

4,783 unequal color pixels

Task 4:

4,374 unequal color pixels

Depth equality PASS.

Textured color equality FAIL.

Session 75 established:

- Magic-square RGB dithering is selected
- Alpha dithering is disabled
- RT64 and independent software-renderer quantization differ on 992 of 2,048 equal-input arithmetic cases

Actual pixel mismatch causality remains UNKNOWN.

No live native first frame.
No playable game.
All eight milestones remain open.

Do not misrepresent this baseline.

============================================================
3. NEW TOOLCHAIN OBJECTIVE
============================================================

Evaluate and integrate:

1. Ghidra
2. splat
3. REA (Reverse Engineer Anything)
4. N64LoaderWV, if compatible and useful

Official source candidates:

Ghidra:
https://github.com/NationalSecurityAgency/ghidra

splat:
https://github.com/ethteck/splat

REA:
https://github.com/morluto/rea

N64LoaderWV:
https://github.com/zeroKilo/N64LoaderWV

Do not assume compatibility from repository descriptions.

Review actual upstream source, releases, dependencies, licenses, installation procedures and host requirements.

Use immutable reviewed commits or verified release artifacts.

Record exact versions and hashes.

Do not blindly execute downloaded installation scripts.

Do not use unpinned latest releases as permanent dependencies.

Do not install unnecessary components.

============================================================
4. HOST AND SECURITY PREFLIGHT
============================================================

The development machine is an ASUS ROG Ally running Bazzite.

Before installation, inspect:

- Operating system and architecture
- Available memory
- Free storage
- Existing Java runtime
- Existing Python environment
- Node.js and npm
- Existing Ghidra installation
- Existing splat installation
- Existing REA installation
- Codex MCP configuration
- Podman/container availability
- Existing development dependencies

Do not reinstall working components unnecessarily.

Prefer isolated, reversible installations under an approved project tooling directory.

Use Python virtual environments for Python packages.

Use pinned dependencies.

Use containers when they materially improve isolation and reproducibility.

Do not modify Bazzite system packages, immutable OS configuration, boot settings or unrelated applications.

The owner authorizes project-scoped installation and reversible Codex MCP configuration for these tools, subject to existing approval policies.

Before modifying Codex MCP configuration:

1. Identify the exact target file.
2. Back up its current contents.
3. Review the proposed changes.
4. Preserve unrelated settings.
5. Ensure rollback is possible.
6. Apply only changes within the authorized project scope.
7. Verify that existing Codex functionality remains intact.

If installation requires privileged access, security exceptions, unapproved host changes or broader permissions, stop that specific operation and request approval rather than bypassing controls.

Never expose credentials to external tools.

Never give new MCP servers unrestricted access to the private project, home directory or credential stores.

============================================================
5. GHIDRA INTEGRATION
============================================================

Install or locate a compatible Ghidra release.

Verify the release identity and dependencies.

Configure headless analysis suitable for Codex-driven investigations.

Prioritize:

- Nintendo 64 MIPS analysis
- Correct instruction decoding
- Big-endian memory representation
- Function identification
- Call references
- Branch and control-flow relationships
- Data references
- Cross-references
- Pseudocode where available
- Scriptable analysis
- Reproducible analysis databases

Evaluate N64LoaderWV for:

- N64 ROM mapping
- N64-specific structures
- Loaded code regions
- Compatibility with the installed Ghidra release

Do not force an incompatible extension into the environment.

Do not assume automatically identified function boundaries are correct.

Do not infer dynamic overlay residency solely from static analysis.

Ghidra output is analysis evidence, not authenticated original execution.

============================================================
6. SPLAT INTEGRATION
============================================================

Install splat in an isolated, pinned Python environment.

Evaluate its ability to organize the authenticated Mario Tennis ROM into:

- Main executable image
- Code regions
- Data regions
- Candidate overlay regions
- ROM-backed loaded segments
- Relevant relocation or mapping metadata

Start with existing authenticated segment information.

Do not perform a broad speculative full-ROM reconstruction merely because splat is available.

Use the existing spimdisasm and Rabbitizer results as comparison points.

Do not overwrite existing project analysis.

Keep generated ROM-derived files outside Git.

Use a restricted output directory.

Record the source ROM hash and exact splat configuration.

Treat automatically inferred segment boundaries as hypotheses until independently authenticated.

============================================================
7. REA MCP INTEGRATION
============================================================

Evaluate REA's official setup and MCP integration.

Prefer connecting REA to the reviewed Ghidra installation.

Configure it for Codex only where supported and authorized.

Use minimal necessary tool capabilities.

Limit access to approved analysis inputs and private outputs.

Verify that REA can:

- Open a permitted analysis target
- Identify available procedures
- Inspect MIPS instructions
- Follow references
- Retrieve function analysis
- Query control-flow relationships
- Return structured evidence
- Distinguish unsupported findings

Test that the MCP server starts and stops reliably.

Record configuration, resource usage and rollback procedures.

If REA cannot safely access the necessary N64 inputs, preserve the limitation and continue with direct Ghidra tooling.

Do not weaken the project sandbox to make REA work.

Do not allow REA to send proprietary ROM-derived data to external services.

============================================================
8. MANDATORY TOOLCHAIN BENCHMARK
============================================================

This evaluation is required.

The objective is to establish whether the new tools actually improve Codex's engineering workflow.

Do not simply report that installation succeeded.

BEFORE relying on new tools:

Establish a baseline using the existing:

- spimdisasm
- Rabbitizer
- Project-specific ROM analysis
- Existing function and reference maps
- Existing emulator evidence

Select up to three previously authenticated original functions or code regions.

Choose cases that test distinct capabilities, such as:

A. Small complete scalar function

B. Function with known callers or branches

C. ROM-backed initialization or loaded-code region

Use equivalent inputs and clearly identified source epochs.

Measure, where practical:

1. Wall-clock analysis time
2. Codex interaction/tool-call overhead
3. Function boundary accuracy
4. Reference identification accuracy
5. Control-flow accuracy
6. Additional independently verified discoveries
7. Manual operations eliminated
8. CPU usage
9. Peak memory
10. Storage overhead
11. Failure rate
12. Repeatability

Compare:

EXISTING WORKFLOW

against:

GHIDRA / SPLAT / REA WORKFLOW

Do not assume every tool must participate in every task.

Distinguish:

- Tool-generated hypothesis
- Independently verified finding
- Incorrect result
- Unsupported conclusion
- Unavailable result

Then apply the most promising tools to one genuinely unresolved loader or worker-thread dependency.

Compare the usefulness of the new workflow against the existing workflow on that real investigation.

Avoid claiming a speed improvement based on one uncontrolled observation.

Where exact measurement is impossible, mark it UNKNOWN.

CLASSIFY EACH TOOL:

RETAIN:
Demonstrated improvement and acceptable cost.

SELECTIVE:
Useful for specific investigations.

DISABLE:
No demonstrated benefit or unacceptable cost.

INCONCLUSIVE:
Insufficient evidence.

Record a detailed private benchmark report.

Include a sanitized summary in the Session 76 report.

TIME BUDGET:

Target approximately 15% of the technical engineering effort for initial benchmarking.

This is a planning allocation, not a rigid stopwatch rule.

If installation or benchmarking becomes disproportionately expensive, stop the evaluation and return to native execution work.

Session 77 should assess real development productivity rather than repeating the entire initial benchmark.

============================================================
9. PRIMARY ENGINEERING TRACK
ORIGINAL THREAD AND WORKER OWNERSHIP
============================================================

After the minimum viable toolchain evaluation, prioritize the original game's execution.

Use:

Session 75 cache-provenance evidence
Session 73 transfer evidence
Session 72 lookup evidence
Session 74 strict same-run observations

Do not repeat the already resolved cache starting-value investigation.

Highest-priority question:

How are the selected current-thread record and original worker queue/thread initialized and owned before the ROM transfer?

Find one exact original initialization store, ownership transition or relevant scheduler event.

Use bounded reference execution and per-thread correlation.

Combine static analysis with authentic runtime evidence.

Do not invent missing thread state.

Do not infer a runtime transition merely from a decompiler's interpretation.

For each candidate:

1. Define the exact unresolved premise.
2. Locate the authenticated source.
3. Verify its residency and entry conditions.
4. Establish one testable hypothesis.
5. Design the smallest bounded experiment.
6. Observe original behavior.
7. Independently verify the interpretation.
8. Record the result and limitations.
9. Continue only if the next step is justified.

If thread/worker ownership is established, proceed toward one bounded:

- Cache-maintenance transition
- PI/DMA transition
- Interrupt transition
- Scheduler transition
- Completion-queue transition

Never fabricate hardware responses, scheduler state, ROM transfers, queue messages or cache hits.

Stop at unsupported ownership or hardware boundaries.

============================================================
10. ORIGINAL FUNCTION RECOMPILATION
============================================================

Seek complete original functions suitable for authenticated native execution.

The original cache-maintenance callee reached after the certified completion-queue constructor is a candidate for review, NOT an already certified function.

Determine:

- Exact function extent
- Entry conditions
- Return behavior
- Dependencies
- Memory effects
- Cache or privileged instructions
- MMIO behavior
- Whether native host execution is appropriate

If unsuitable, seek a small complete worker-side scalar helper with authenticated entry and return.

For a certified candidate:

- Generate with pinned N64Recomp ABI 3
- Compile in the approved isolated environment
- Execute natively
- Compare against same-run authentic reference state
- Compare against independent interpretation
- Verify CPU/HI/LO/status/FCSR/raw FP
- Verify ordered trace
- Verify full RAM when applicable and available
- Preserve negative controls

Do not promote partial functions merely to increase coverage.

Do not substitute emulator RAM for ROM-only native startup.

Do not claim isolated execution is equivalent to conventional integration.

Where independently justified, integrate a certified function into the conventional connected path.

Preserve separate coverage accounting.

============================================================
11. CONVENTIONAL NATIVE INTEGRATION
============================================================

The long-term objective is a continuously running native game.

Investigate the smallest safe integration step connecting authenticated original execution with existing native runtime services.

Relevant dependencies include:

- Original thread-ID mapping
- Original worker/request ownership
- Queue lifetime
- Request lifetime
- Completion semantics
- ROM-backed image preparation
- Loaded code activation
- Scheduler interactions

Do not mix original queue layouts with upstream waiters without a reviewed contract.

Do not replace original asynchronous behavior with an invented synchronous transfer.

Do not enable unsafe live graphics submission.

A new conventional integration must have an independently justified state and lifetime contract.

If no safe integration is available, report the precise missing premise rather than forcing progress.

============================================================
12. GRAPHICS TRACK
============================================================

Preserve the authentic Session 74 frozen graphics tasks.

The remaining color mismatch must not be hidden or normalized away.

Next targeted experiment:

Investigate the intermediate color immediately before the black alpha overlay.

For both authentic textured tasks:

- Identify the first unequal source texel
- Examine texture sampling
- Examine integer blending
- Examine 8-bit intermediate color
- Examine per-stage quantization
- Examine final quantization
- Apply the actual RDP mode bits

Distinguish:

AUTHENTIC ORIGINAL TASK
MODIFIED DIAGNOSTIC REPLAY
INDEPENDENT SOFTWARE REFERENCE
NATIVE RT64 GPU READBACK

A diagnostic truncation or modified task must never be represented as the original complete task.

Only change renderer behavior when supported by independently verified evidence.

Any correction requires regression checks against both original tasks, depth behavior, ownership, rejection and repeatability.

Preserve private lossless PNG capture capability.

Capture new authentic rendered graphics automatically when useful and safe.

Use original-resolution, unaltered PNGs.

Record exact private paths and hashes.

Never publish game imagery without separate approval.

Do not claim a frozen graphics replay is a live native frame.

============================================================
13. SECURITY AND STRATEGY D
============================================================

Mandatory architecture:

N64Recomp ABI 3
N64ModernRuntime
RT64

Strategy D remains in force.

PROHIBITED:

- Fabricated SP/DP completion
- Unsafe live graphics submission
- Invented current-thread state
- Invented scheduler state
- Unsafe buffer reuse
- Unreviewed callbacks
- Fabricated cache hits
- Fabricated ROM transfer completion
- Emulator RAM imported into conventional native startup
- Unverified source boundaries
- Hidden comparison failures

NEVER COMMIT:

- ROM files
- Extracted proprietary assets
- Original disassembly
- Translated proprietary game code
- Generated original game source
- Raw RAM snapshots
- Emulator traces
- Private source/address maps
- Exact unredacted prompts
- Private screenshots
- Credentials

New tooling must follow these same restrictions.

ROM-derived splat outputs, Ghidra databases, REA evidence bundles and generated analysis files remain private.

Use restricted workspaces and reviewed ignore rules.

Reference emulator execution remains:

- Network-disabled
- Credential-free
- Read-only ROM
- Resource-bounded
- Process-bounded
- Without guest mutation
- Captured before RSP where required

Never permit a new tool to bypass these controls.

Do not merge main.

Do not change repository visibility.

Do not publish releases or binaries.

Do not publish copyrighted media.

Do not modify unrelated host configuration.

============================================================
14. DEVELOPMENT AUTOMATION
============================================================

Make small improvements that save time in subsequent sessions.

Session 75 exposed a recurring session-number path substitution problem.

Consider replacing private path substitutions with explicit:

- Workspace root
- Build root
- Output root
- Evidence root
- Session identifier

Provide a path preflight.

Preserve existing behavior.

Add focused tests.

Do not undertake a large automation rewrite.

If useful, create compact automated receipts for:

- Native comparisons
- CTest
- Repository verification
- Graphics pixel statistics
- Toolchain benchmark results

Keep original function-boundary certification subject to independent review.

============================================================
15. AUTONOMOUS EXECUTION POLICY
============================================================

Work autonomously within the established security boundaries.

The owner prefers meaningful engineering progress over frequent interruptions.

Do not stop merely because one track becomes blocked.

Switch to another approved track when appropriate.

Suggested order:

1. Mandatory recovery and security preflight
2. Existing workflow benchmark baseline
3. Tool installation and minimum integration
4. Controlled toolchain comparison
5. Original thread/worker investigation
6. Native function certification and execution
7. Conventional integration when safe
8. Focused graphics investigation
9. Automation improvements
10. Validation and delivery

This is not a requirement to complete all tracks sequentially.

If a major original-execution breakthrough occurs, prioritize validating and preserving it.

Use the established bounds:

- Three attempts per blocker
- Fifteen closure rounds
- Twenty minutes per tool cycle
- 300 seconds per reference process
- Bounded output and log sizes

Do not use unbounded background loops.

Do not recursively launch new Codex sessions.

Do not assume the weekly allowance has reset or that a fixed amount remains.

Use a maximum six-hour wall-clock engineering window if resources and authorization permit.

Reserve approximately the final 45 minutes for validation, preservation and delivery.

A shorter successful session is acceptable.

Stop earlier when progress no longer justifies additional resource use.

============================================================
16. CHECKPOINTS
============================================================

Create recoverable private checkpoints after meaningful engineering results.

Record:

- Completed work
- Verified findings
- Unverified hypotheses
- Tool versions
- Tool installation locations
- MCP configuration changes
- Rollback procedures
- Private evidence locations
- Tests
- Remaining blockers
- Next safe action

Do not leave essential findings only in transient Codex context.

Do not modify sealed evidence.

Do not confuse a selected archive with a complete independent backup.

Preserve exact evidence provenance.

============================================================
17. REQUIRED VERIFICATION
============================================================

Preserve the established testing baseline:

232 repository tests
3 generator regressions
9 CTest
4 conventional comparisons
16 retained isolated comparisons
ROM identity/rejection
Unsupported launch
RT64 state-only positive/negative checks
Strict authentic FCSR comparison
Security checks

Run focused tests after changes.

Run full required verification before delivery.

Use:

python3 tools/development.py verify

Use full verification only with the required verified generator/header.

Supply explicit root and manifest when archive verification requires them.

Distinguish fresh executions from retained authenticated evidence.

Do not mark unavailable checks PASS.

Do not convert failures into skips.

Keep these evidence classes distinct:

CONNECTED ORIGINAL
ISOLATED ORIGINAL
INDEPENDENT REFERENCE
REFERENCE EMULATOR EXECUTION
SYNTHETIC
UPSTREAM INTEGRATION
FROZEN ORIGINAL GRAPHICS TASK REPLAY
LIVE NATIVE ORIGINAL EXECUTION

Never claim a playable game or live native first frame without direct evidence.

============================================================
18. GITHUB AND PUBLIC DOCUMENTATION
============================================================

Create:

[REDACTED: private session report path]

Update:

docs/NEXT_SESSION_PLAN.md

Prepare Session 77.

Document:

- Recovery verification
- Tool installation and exact versions
- REA MCP integration status
- Ghidra and splat compatibility
- N64LoaderWV evaluation
- Benchmark methodology and results
- Tools retained, selective, disabled or inconclusive
- Original loader/thread progress
- New original functions
- Conventional integration
- Graphics progress
- Tests and failures
- Security verification
- Remaining blockers
- Exact GitHub receipts

Update the existing public development diary.

Publish only approved sanitized project documentation.

Preserve exact authentic prompts privately.

Publish visibly redacted prompt history through established reviewed paths.

Preserve earlier diary entries and milestone ordering.

Do not disclose private source maps, ROM-derived outputs or game imagery.

Inspect every staged file before committing.

Run required security scans.

Push reviewed changes to the existing private investigation branch.

Verify remote contents.

Check security CI.

Record queued, running, passed and failed states accurately.

Do not claim CI success while jobs are pending.

Do not merge main or publish releases.

============================================================
19. SESSION 77 HANDOFF
============================================================

Prepare an aggressive but evidence-based Session 77 plan.

Include:

1. Highest-value remaining original execution dependency
2. Best newly discovered original-function candidates
3. Safe conventional integration opportunities
4. Which new tools actually helped
5. Toolchain limitations and fixes
6. Any outstanding security or installation issues
7. Next graphics correctness experiment
8. Automation improvements worth retaining
9. Estimated development bottlenecks
10. The clearest achievable step toward a live native frame

Session 77 should measure tool usefulness through real development results.

Do not repeat the entire initial toolchain benchmark without justification.

Do not automatically launch Session 77.

============================================================
20. FINAL REPORT
============================================================

Report to the owner:

A. TOOLCHAIN

- Was Ghidra installed and working?
- Was splat installed and working?
- Was REA connected to Codex?
- Was N64LoaderWV compatible?
- Which tools improved the workflow?
- By how much, where measurable?
- Which tools should remain enabled?

B. NATIVE EXECUTION

- What original dependency was resolved?
- Were new original functions authenticated?
- Did isolated native coverage increase?
- Did conventional native coverage increase?
- Did original thread/worker ownership become clearer?
- Did the loader move closer to working?

C. GRAPHICS

- Was the pixel mismatch explained?
- Were authentic graphics rendered?
- Were new private screenshots captured?
- Is there any genuine live native frame?

D. VALIDATION

- Exact test results
- Failures and unresolved checks
- Security results
- Archive status
- Private and public commits
- CI status

E. NEXT STEPS

- What should Session 77 attack first?
- What is the largest remaining blocker?
- What is the next measurable native-game milestone?

Use concise, understandable language for the owner.

Do not exaggerate.

============================================================
21. FINAL DIRECTIVE
============================================================

Session 76 is authorized.

Recover the authenticated Session 75 state.

Build a stronger reverse-engineering environment using Ghidra, splat and REA.

Evaluate N64LoaderWV.

Measure whether the new tools improve the existing workflow.

Retain only useful, safe capabilities.

Then aggressively pursue the original game's thread, worker, loader and scheduler dependencies.

Certify and execute additional original functions whenever independently supportable.

Seek safe conventional native integration.

Preserve authentic graphics progress and investigate remaining pixel differences.

Maintain strict security and evidence requirements.

Create a recoverable Session 77 handoff.

Do not begin Session 77 automatically.

BEGIN SESSION 76.