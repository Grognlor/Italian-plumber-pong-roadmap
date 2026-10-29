# Session 65 — Connected startup and RT64 integration

Authentic owner-issued user-message text, preserved privately from this session.
Private recovery/archive evidence, report paths and a graphics descriptor detail
are visibly withheld. Other wording and order are preserved. Original transport-
byte identity is UNKNOWN; this is captured user-message text.
Status: issued; verified results are recorded separately in the diary entry.

---

ITALIAN PLUMBER PONG
SESSION 65: CONNECTED STARTUP AND RT64 INTEGRATION

You are continuing Italian Plumber Pong, our native PC recompilation project for Mario Tennis (USA), Nintendo 64.

Session 64 is complete and verified.

The project owner wants aggressive, practical progress toward a playable native PC port using established recompilation technology.

PRIMARY DEVELOPMENT STACK

- N64Recomp: Original game-code translation
- N64ModernRuntime: N64 OS and runtime services
- RT64: Graphics rendering
- RecompFrontend: Future frontend and configuration

The conventional native application is our primary development target.

The experimental execution harness is retained for diagnostics and independent reference comparisons. Do not return to extending it as the primary development strategy.

PRIMARY SESSION 65 OBJECTIVES

1. Extend connected original Mario Tennis startup execution through upstream N64ModernRuntime services.
2. Implement and test real thread creation, scheduling, and message blocking/wakeup where supported.
3. Advance the authentic graphics-task path toward actual RT64 submission.
4. Preserve the working ROM-only executable and existing integration tests.

Prioritize implementation and execution over research and documentation.

RECOVERY

[REDACTED: private recovery paths, archive identity and detailed Session 64 evidence]

PHASE 1: EXPAND CONNECTED ORIGINAL STARTUP

Recover the actual startup caller and OS symbol metadata already discovered during previous sessions.

Identify the next meaningful connected original-code dependency.

Prioritize functions involved in:

- Thread creation
- Thread startup
- Scheduling
- Message queues
- Cartridge access
- Startup initialization
- Event registration

Determine the original thread entrypoint, stack, priority, argument, and ownership contracts.

Use N64Recomp to generate the required original game functions.

Compile and link them into the conventional native application.

Prefer a connected startup chain over unrelated isolated routines.

Do not invent missing function metadata.

Use existing discoveries wherever possible.

If function discovery is incomplete, identify the exact missing boundaries and implement the smallest justified extension.

PHASE 2: UPSTREAM THREAD AND QUEUE INTEGRATION

Connect original game calls to N64ModernRuntime's established thread and scheduling services.

Investigate the actual pinned runtime APIs rather than assuming interfaces.

Implement the smallest necessary game-specific adapters.

Requirements:

- Preserve ABI 3.
- Preserve original calling conventions.
- Preserve correct delay-slot behavior.
- Preserve checked call/return boundaries.
- Preserve original queue and thread ownership.
- Handle canonical versus word-swapped RAM correctly.
- Avoid incompatible CPU-context casts.
- Reject unknown thread entries and unresolved function lookups.
- Preserve the existing validated nonblocking queue behavior.

IMPORTANT BLOCKING REQUIREMENT

Session 64 permits blocking-flag receives only when a message is already available.

Actual blocking and wakeup remain unsupported.

Implement real blocking/wakeup only when the original game's thread and event ownership can be represented correctly.

Test both:

1. Immediate receive when a message exists.
2. Blocking receive followed by a legitimate wakeup.

Do not fabricate messages or pretend a blocked thread resumed.

If full scheduling cannot be safely implemented, preserve the supported behavior and report the precise blocker.

PHASE 3: CONNECT MORE ORIGINAL GAME CODE

Expand the conventional native executable beyond the Session 64 routine set.

Use the original ROM and established N64Recomp generation pipeline.

Test connected original routines through actual upstream services.

Compare results against the independent reference where practical.

Validate:

- Ordered instruction execution
- Integer registers
- HI/LO/status
- FP state where relevant
- Full owned RAM
- Queue and thread effects
- Return and delay-slot behavior
- Generated-code identity

Prioritize useful connected execution over raw instruction-count increases.

Do not artificially increase experimental harness limits.

PHASE 4: REAL RT64 GRAPHICS INTEGRATION

This is a major priority.

[REDACTED: private graphics descriptor verification detail]

Now investigate and implement the next genuine renderer integration step.

Preferred pipeline:

Original Mario Tennis graphics task
→ N64ModernRuntime task submission
→ RendererContext
→ RT64
→ PC graphics output

Inspect the actual pinned RT64 and N64ModernRuntime interfaces.

Determine:

- Renderer initialization requirements
- Window and graphics-device lifecycle
- Supported graphics microcode
- Task memory ownership
- Display-list address handling
- Graphics task submission
- SP and DP completion timing
- Event queue ownership
- Renderer error handling

IMPORTANT:

The pinned runtime currently posts SP completion before RendererContext::send_dl and DP completion afterward.

Determine whether this ordering is valid for Mario Tennis.

Do not assume it is wrong or correct without examining the original game's consumers.

If necessary, implement a narrow, justified compatibility adapter.

Do not globally alter upstream timing behavior without evidence.

Do not use a dummy renderer.

Do not fabricate successful task completion.

Do not submit unsupported or invalid task memory.

The first authentic graphics task contains state initialization, not drawing commands.

It cannot produce a visible game frame by itself.

STRETCH OBJECTIVE

If genuine RT64 initialization and task submission work, continue original execution toward a graphics task containing actual drawing commands.

If an authentic rendered frame becomes feasible, attempt it.

Do not substitute a test image, placeholder scene, or synthetic frame for original game output.

PHASE 5: IMPROVE THE CONVENTIONAL APPLICATION

Continue treating ipp-runtime-dev as the foundation of the eventual PC port.

Preserve:

- ROM validation
- ROM-only preparation
- Deterministic decompression
- Native compilation
- Upstream runtime integration
- Explicit unsupported states
- Independent executable launching

Do not add a decorative launcher or unrelated UI.

The long-term user experience remains:

Download application from GitHub
→ Select supported Mario Tennis ROM
→ Perform necessary local processing
→ Launch native PC port
→ Reuse cached results on subsequent launches

No Codex or developer environment should be needed by ordinary users.

Linux/Bazzite first.
Windows second.
macOS optional.

Eventually support widescreen, multiple controllers, higher frame rates, audio, saves, in-game settings, and updates.

Do not implement those features prematurely.

PHASE 6: VALIDATION

Run actual compiled native execution tests.

Do not treat compilation alone as successful execution.

Preserve the Session 64 connected-check result.

Add focused tests for new thread, queue, startup, and graphics adapters.

Run:

- Focused unit tests
- CTest integration cases
- Repository tests
- Generator regressions
- Full verification where available
- Security and provenance checks

Distinguish PASS, FAIL, BLOCKED and SKIPPED.

Do not claim successful RT64 rendering unless a genuine original graphics workload was submitted and processed by the real renderer.

SECURITY

Preserve all existing security requirements.

Never commit or publish:

- Original ROMs
- Extracted proprietary assets
- Proprietary generated game code
- Private execution traces
- Original RAM images
- Sensitive diagnostics

Only reviewed, distributable project-owned source, configuration, tests and sanitized documentation may enter Git.

Preserve pinned dependencies unless a change is justified, reviewed and documented.

No public release, main merge, repository visibility change, access change or media publication is authorized.

Keep public CI synthetic-only.

Preserve existing private archive and detached-anchor procedures.

DEVELOPMENT PHILOSOPHY

Move aggressively toward a playable PC port.

Reuse established upstream implementations.

Avoid reinventing N64 hardware behavior.

Avoid repeated investigations already resolved.

Prefer working connected startup execution over isolated demonstrations.

Prefer actual renderer integration over writing another graphics-task simulator.

Do not spend most of the session producing documentation.

Do not force incompatible APIs, weaken validation, or fabricate missing behavior merely to accelerate progress.

If a blocker emerges, isolate it precisely and move to another useful integration task when appropriate.

TIME MANAGEMENT

Suggested effort allocation:

10% recovery and baseline verification
40% connected startup/thread integration
30% RT64 graphics integration
10% application/build improvements
10% verification, preservation and reporting

Adjust based on actual progress.

Reserve enough time for safe closeout.

If model capacity or usage limits interrupt the session, preserve recoverable state and resume from completed work.

Do not discard working changes.

MANDATORY CLOSEOUT

1. Run focused and full verification.
2. Preserve all essential private artifacts.
3. Verify archive integrity.
4. Create [REDACTED: private Session 65 report path].
5. Update [REDACTED: private next-session plan path].
6. Update the roadmap and public development diary where appropriate.
7. Update the redacted prompt archive.
8. Perform staged/history security scans.
9. Commit and push reviewed changes to the existing investigation branch.
10. Verify CI status where possible.

FINAL REPORT MUST ANSWER

- How many original Mario Tennis routines are now conventionally generated, linked and executed?
- How much connected startup execution works?
- Which upstream N64ModernRuntime services are actually exercised?
- Does real thread creation and scheduling work?
- Does actual blocking/wakeup work?
- Can the application still prepare directly from the ROM?
- Is RT64 now linked and initialized?
- Has an authentic Mario Tennis graphics task reached RT64?
- Has any original game-generated frame been rendered?
- What is the next concrete blocker?
- What should Session 66 prioritize?

SUCCESS CRITERIA

MINIMUM:

Preserve Session 64 and execute one additional meaningful connected original-code dependency through established runtime services.

PREFERRED:

Demonstrate genuine thread/scheduling integration and measurable progress toward a real RT64 graphics path.

STRETCH:

Submit an authentic original Mario Tennis graphics task to RT64 and continue toward actual drawing commands.

Do not claim a rendered frame without authentic game-generated pixels.

FINAL INSTRUCTION

The established-runtime architectural pivot is working.

Make the conventional native PC application the primary development path.

Aggressively advance connected original Mario Tennis startup and real RT64 integration.

Keep the experimental harness diagnostic.

Do not stop after presenting a plan.

IMPLEMENT, BUILD, EXECUTE, VERIFY, PRESERVE AND PUSH.

BEGIN SESSION 65.

---

## Continuation — resume and complete Session 65

Authentic continuation user-message text from the same session. Detailed private
verification evidence and internal report/plan paths are visibly withheld.
Other wording and order are preserved. This continues Session 65.

---

Italian Plumber Pong: Resume and Complete Session 65

We are resuming Session 65 after a Codex usage-limit interruption.

This is a continuation of Session 65, not a new development session.

1. Recover the exact previous state

Before making changes:

1. Review the current conversation and the most recent tool outputs.
2. Inspect the working directory, Git status, recent commits, and any uncommitted changes.
3. Read "[REDACTED: private Session 65 report path]", "[REDACTED: private next-session plan path]", and the private Session 65 handoff and evidence records, if they exist.
4. Identify which verification, preservation, sealing, publication, and GitHub operations have already completed.
5. Determine the exact point where the previous execution stopped.

Do not assume that the interruption rolled back any completed operations.

Do not overwrite completed work, regenerate private evidence unnecessarily, or repeat expensive builds unless verification requires it.

2. Preserve the completed technical achievements

The previous Session 65 execution reported these results:

[REDACTED: detailed private implementation and verification evidence]

Treat these as previously reported results requiring confirmation from the existing evidence, not as permission to invent or assume missing verification.

Preserve all working implementations and successful tests.

3. Complete the interrupted closeout

The previous execution appeared to be working through:

- Final verification
- Session 65 report preparation
- Private evidence preservation
- SHA-256 evidence sealing
- Public documentation preparation
- Git diff inspection
- GitHub commit and push preparation

Determine which steps completed successfully and finish only the remaining work.

If a commit or push already succeeded, verify it rather than duplicating it.

If the working tree contains partial files or incomplete documentation, reconcile them carefully against the existing implementation and evidence.

4. Verification requirements

Run the appropriate existing repository checks, including:

- Relevant native integration tests
- Scheduler and blocking/wakeup regression tests
- RT64 initialization and authentic task-processing tests
- ROM-only development executable checks
- Generator regressions
- Repository security checks
- CMake/CTest verification where applicable
- "git diff --check"

Record exact results and distinguish newly executed tests from results recovered from previous logs.

Do not silently weaken assertions or change expected results to make tests pass.

If a test cannot be rerun, report why and preserve the existing evidence.

5. Security requirements

Maintain all existing security protections.

Never commit, publish, or expose:

- The original Mario Tennis ROM
- Extracted copyrighted game assets
- Private RAM images or snapshots
- Proprietary generated code or game-derived data prohibited by the project rules
- Private evidence archives
- Sensitive absolute paths or identifying information

Review all staged changes before committing.

Keep the private development repository and public roadmap repository separate.

Do not change repository visibility.

6. Complete the Session 65 documentation

Ensure the following are accurate and complete:

"[REDACTED: private Session 65 report path]"

Include:

- Session objectives
- Implemented changes
- Verified technical results
- Exact test outcomes
- RT64 integration details
- Scheduler and thread-wakeup results
- Known limitations
- Security verification
- Private evidence references and manifest hashes
- Git commit and push status
- Remaining technical blockers

"[REDACTED: private next-session plan path]"

Prepare a realistic Session 66 plan emphasizing:

1. Authentic graphics task ownership and completion sequencing.
2. Correct SP/DP completion behavior and synchronization.
3. Identification of competing graphics task producers.
4. Advancing original game startup toward drawing-capable display lists.
5. Maintaining ROM-only operation and all established regression protections.

Do not claim a rendered frame, successful game boot, or playable gameplay without direct evidence.

Update the approved development diary and sanitized prompt archive as required by the established workflow.

7. GitHub closeout

After verification and security review:

1. Stage only approved source code, tests, and sanitized documentation.
2. Commit to the existing development branch.
3. Push to the private GitHub repository.
4. Confirm the remote branch contains the expected commit.
5. Verify available CI results.
6. Preserve the private evidence archive and its integrity manifest.

If any operation fails, clearly report the failure and leave the repository in a recoverable state.

8. Final handoff

Once complete, provide a concise but detailed final summary covering:

- What Session 65 accomplished
- Whether the original scheduler and wakeups work
- Whether RT64 processed the authentic graphics task
- Whether any frame was rendered
- All test results
- Security and evidence-preservation status
- GitHub commit SHA and push confirmation
- Remaining blockers
- Recommended Session 66 objectives

Important: Do not begin Session 66 or undertake another major development experiment. The immediate objective is to safely finish and verify Session 65.

If Session 65 is already fully completed, simply verify its final state and report the results without making unnecessary changes.