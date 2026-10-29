# Session 64 — Accelerated established-runtime integration

Authentic owner-issued user-message text, preserved privately from this session.
Internal evidence/report paths, the private handoff filename and an archive count
are visibly withheld. Other wording and order are preserved. Original transport-
byte identity is UNKNOWN; this is captured user-message text.
Status: issued; the completed session's verified results appear in its diary entry.

---

ITALIAN PLUMBER PONG
SESSION 64: ACCELERATED ESTABLISHED-RUNTIME INTEGRATION

You are continuing Italian Plumber Pong, our native PC recompilation project for Mario Tennis (USA), Nintendo 64.

Session 63 is complete.

The owner explicitly approves aggressively advancing the new established-runtime architecture, provided existing security, correctness and provenance safeguards remain intact.

PRIMARY DIRECTION

The conventional native PC application is now the primary development target.

Use:
- N64Recomp for original game-code translation
- N64ModernRuntime for N64 OS/runtime services
- RT64 for graphics when technically ready
- RecompFrontend for eventual frontend integration

The old experimental execution harness remains available for diagnostics, reference comparisons and discovering game-specific behavior.

Do not make expanding its instruction count the primary session objective.

SESSION 63 VERIFIED BASELINE

A conventional CMake executable, ipp-runtime-dev, successfully:

- Linked genuine N64Recomp-generated Mario Tennis code
- Linked upstream N64ModernRuntime ultramodern
- Executed an original 84-byte / 21-instruction routine
- Called upstream message queue creation and sending
- Verified message delivery through upstream receiving
- Matched all 32 integer registers, HI/LO/status and full 4 MiB RAM against an independent reference
- Passed two local CTest integration cases

199 repository tests and three generator regressions passed.

The original Session 62 experimental baseline of 2,092,000 matched instructions remains preserved.

This is not yet coherent game boot, rendering or gameplay.

PRIMARY SESSION 64 OBJECTIVES

1. Remove the development executable's dependency on a preprepared private runtime image wherever feasible.
2. Expand genuine original Mario Tennis code integration beyond the single Session 63 routine.
3. Establish a practical route from original game startup through N64ModernRuntime toward RT64 graphics.

Prioritize implementation, compilation and execution.

Do not spend most of the session on another broad feasibility investigation.

PHASE 1: RECOVER AND VERIFY

Read:
- [REDACTED: private Session 63 report path]
- [REDACTED: private next-session plan path]
- [REDACTED: private runtime design path]
- Relevant application and CMake source
- Private Session 63 [REDACTED: private handoff filename]

Verify the final designated Session 63 archive:
- [REDACTED: private archive membership count]
- Detached anchor and manifest
- Complete membership and permissions
- Toolchain pins
- Original ROM identity

Use a fresh restricted workspace.

Do not modify sealed archives.

Reproduce the working Session 63 integration before extending it.

PHASE 2: ROM-ONLY LOCAL PREPARATION

The current pipeline requires a reviewed prepared runtime image.

This is not suitable for the eventual consumer application.

Investigate the previously verified ROM unpacking and loading procedures.

Extract the minimum deterministic processing required to construct the necessary runtime image directly from the user's validated ROM.

Implement a standalone local preparation stage where technically justified.

Requirements:
- No replay of millions of startup instructions during ordinary preparation
- No network access required
- No proprietary data embedded in distributed tools
- No hardcoded private source paths
- Clear input validation
- Deterministic outputs
- Reproducible tests
- Explicit unsupported states
- Safe caching and cleanup

If some data genuinely depends on executing original initialization code, distinguish that from deterministic ROM unpacking.

Do not fabricate unknown RAM contents or silently substitute snapshots.

A successful ROM-only preparation path is a major priority.

PHASE 3: EXPAND ORIGINAL GAME CODE INTEGRATION

Identify the next meaningful original Mario Tennis dependency slice.

Prefer actual startup, initialization, thread or OS interactions that move us toward coherent game execution.

Use existing function discoveries and validated metadata.

Generate additional original code using the pinned N64Recomp pipeline.

Compile and link it into the conventional native executable.

Connect complete, reviewed OS API boundaries to upstream N64ModernRuntime implementations.

Avoid duplicating upstream functionality.

Important:
- Preserve original calling conventions and ABI behavior.
- Keep unresolved symbols explicit.
- Do not mix original console thread/queue internals with upstream host structures.
- Do not cast incompatible runtime contexts.
- Preserve memory ownership and byte-order correctness.
- Test actual blocking/wakeup behavior before enabling it.
- Reject unsupported thread entries and function lookups.

Target a meaningful increase in conventional native game-code coverage, not just more isolated test routines.

Prefer a connected execution path over a collection of unrelated functions.

PHASE 4: PREPARE REAL GRAPHICS INTEGRATION

Use the existing RT64 research and Session 62 graphics-task discoveries.

Inspect the practical integration route:

Original Mario Tennis graphics task
→ N64ModernRuntime task submission
→ Renderer context
→ RT64 display-list processing
→ PC framebuffer presentation

Determine the smallest next integration step.

If feasible, implement and test the actual task-submission adapter.

If RT64 can be linked and initialized safely within the session, do so.

If it cannot, implement the nearest genuine runtime interface and document the precise remaining dependency.

Do not write another custom graphics renderer.

Do not fabricate graphics-task completion, drawing commands or rendered frames.

The first authentic graphics task only initializes state. It cannot produce a visible frame by itself.

PHASE 5: MAKE THE APPLICATION MORE USEFUL

Continue improving ipp-runtime-dev as the real development application.

Prioritize:
- ROM validation
- Automatic local preparation
- Reproducible native builds
- Explicit runtime initialization
- Useful error reporting
- Independent launch without Codex

Avoid cosmetic GUI development until the actual game runtime advances.

Keep Linux/Bazzite first and Windows compatibility in mind.

The eventual consumer experience remains:

Download application from GitHub
→ Select supported Mario Tennis ROM
→ Perform necessary local processing/build
→ Launch native PC game
→ Cache results for subsequent launches

Users must not need Codex or manually installed developer tools.

PHASE 6: TEST AND VALIDATE

Build and execute the conventional native target.

Compare new original-code behavior against the independent reference where feasible.

Validate:
- CPU and FP state
- RAM
- OS service effects
- Thread/queue ownership
- ROM processing results
- Generated-code provenance
- Correct unsupported behavior

Preserve the working Session 63 integration.

Add focused tests for every new adapter or local preparation step.

Run repository and upstream integration tests.

Do not report compiled-only code as executed.

Do not count reference-only results as native progress.

AGGRESSIVE DEVELOPMENT GUIDELINES

The owner wants meaningful forward progress.

Prefer:
- Existing upstream implementations
- Small game-specific adapters
- Connected original-code execution
- Working build targets
- Real graphics integration
- Reusable application infrastructure

Avoid:
- Reimplementing N64 OS services unnecessarily
- Repeating settled research
- Excessive documentation
- Unrelated synthetic demonstrations
- Arbitrary instruction-count milestones
- Premature launcher polish
- General-purpose emulator development

Be willing to make architectural improvements when evidence supports them.

Do not force incompatible APIs or weaken correctness safeguards merely to advance faster.

SECURITY

The ROM, extracted proprietary assets, original traces, generated proprietary game code and sensitive diagnostics remain outside Git.

Only reviewed distributable project-owned source, configuration, tests and sanitized documentation may be committed.

Preserve the existing investigation branch, access restrictions and private archive workflow.

No public release, main merge, visibility/access change, proprietary upload or media publication is authorized.

Do not silently adopt new dependencies or licenses without review.

Maintain pinned N64Recomp ABI 3 and existing analysis/toolchain versions unless a necessary change is explicitly justified.

TIME MANAGEMENT

Prioritize implementation over reporting.

Suggested effort allocation:
- 10% recovery and verification
- 35% ROM-only preparation
- 35% connected original-code/runtime integration
- 15% RT64 integration
- 5% final reporting and closeout

Adjust allocation based on actual blockers.

If ROM-only preparation becomes unexpectedly difficult, preserve the findings and redirect effort to a genuinely executable runtime integration.

Do not allow one speculative investigation to consume the entire session.

Reserve sufficient time for verification, artifact preservation, documentation and Git closeout.

SESSION 64 DELIVERABLES

1. Updated conventional application/runtime source.
2. Actual compiled and executed integration improvements.
3. ROM-only preparation implementation or precisely documented blocker.
4. Expanded original game-code integration.
5. Progress toward real RT64 task submission.
6. Focused and full verification results.
7. Private artifact preservation and integrity checks.
8. [REDACTED: private Session 64 report path].
9. Updated [REDACTED: private next-session plan path].
10. Updated public diary and redacted prompt archive where appropriate.
11. Reviewed commit and push to the existing investigation branch.
12. CI status checked where possible.

FINAL REPORT MUST ANSWER

- Can ipp-runtime-dev now prepare its required image directly from the user's ROM?
- How many genuine original Mario Tennis routines are conventionally generated, linked and executed?
- Which N64ModernRuntime services are now actually exercised?
- Has connected startup execution advanced?
- Is any authentic graphics task reaching RT64?
- What exact command can the owner run on Bazzite?
- What remains between the current application and a first authentic frame?
- What should Session 65 prioritize?

SUCCESS CRITERIA

MINIMUM:
Preserve the working Session 63 executable and deliver one meaningful tested improvement to the conventional runtime integration.

PREFERRED:
ROM-only preparation plus additional connected original Mario Tennis code executing through N64ModernRuntime.

STRETCH:
A genuine original graphics task submitted through the established runtime toward RT64.

FINAL INSTRUCTION

We have demonstrated that the established-runtime approach works.

Make it the main development path.

Aggressively reuse proven upstream components and the discoveries from Sessions 1-63.

Prioritize real native PC application progress over expanding the experimental harness.

IMPLEMENT, BUILD, EXECUTE, VERIFY, PRESERVE AND PUSH.

BEGIN SESSION 64.