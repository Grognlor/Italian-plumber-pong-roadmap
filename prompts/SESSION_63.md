# Session 63 — Established runtime integration

Authentic owner-issued user-message text, preserved privately from this session.
Internal evidence/report paths and the private handoff filename are visibly
withheld. Other wording and order are preserved. Original transport-byte identity
is UNKNOWN; this is captured user-message text, not an attachment recovery.
Status: issued; the completed session's verified results appear in its diary entry.

---

ITALIAN PLUMBER PONG
SESSION 63: ESTABLISHED RUNTIME INTEGRATION
ARCHITECTURAL PIVOT TOWARD A PLAYABLE PC PORT

You are continuing Italian Plumber Pong, our native PC recompilation project for Mario Tennis (USA), Nintendo 64.

Session 62 is complete.

This is a new Codex session, and the project owner has approved an important change in development direction.

READ THIS FIRST

We have completed 62 sessions of extensive investigation, function discovery, controlled execution, validation, and game-specific hardware experiments.

These efforts have produced valuable technical results, but we still do not have a launchable native PC game.

The owner wants us to move toward the architecture used by established N64 recompilation projects, particularly Wave Race 64 Recompiled and Zelda 64: Recompiled.

Our preferred technology stack is:

- N64Recomp for static recompilation of game code
- N64ModernRuntime for N64 operating-system and runtime services
- RT64 for graphics
- RecompFrontend for menus, input and application integration

These are preferred established components, not permission to force incompatible integrations or make unverified assumptions.

The experimental execution harness must become a development and diagnostic tool, not the default architecture of the finished application.

Our objective is a playable native PC port of Mario Tennis.

PRIMARY SESSION OBJECTIVE

Build the first practical integration between Mario Tennis's existing recompilation work and the established N64 PC runtime ecosystem.

Produce a concrete, compilable application/runtime integration milestone, not merely a proposal or research report.

Preserve existing progress, security requirements, and validated behavior.

PROJECT RECOVERY

1. Confirm repository, branch, working tree and project instructions.

2. Read:
   - [REDACTED: private Session 62 report path]
   - [REDACTED: private next-session plan path]
   - [REDACTED: private graphics service contract path]
   - Existing N64Recomp/runtime/RT64 research
   - Relevant architecture documentation
   - The private Session 62 [REDACTED: private handoff filename]

3. Verify the designated final Session 62 archive:
   - Manifest and detached anchor
   - Complete membership and file modes
   - Toolchain and dependency pins
   - Original ROM identity

4. Work in a fresh restricted workspace where appropriate.

5. Do not modify sealed archives or repeat completed investigations without a specific reason.

CURRENT VERIFIED BASELINE

Session 62 achieved:

- 2,092,000 matched original instructions
- 3,080 distinct instruction locations
- 510 native body entries
- 324 normal returns
- 186 boundary unwinds
- 22 original ERET transfers
- 43 interrupt-mask accesses
- Four ROM transfers totaling 4,448 bytes
- A processed original graphics task containing 32 commands
- 27 retained graphics-state entries
- Both original graphics completion messages consumed

195 repository tests and three generator regressions passed.

These are controlled partial execution envelopes.

We do not yet have:
- A coherent native boot
- A complete game executable
- A rendered frame
- Audio output
- Controller-driven gameplay

The longer experimental path encounters the existing 512-body limit. A longer reference-only path encounters unsupported LWL.

Do not mistake these experimental limitations for proof that the established runtime cannot support the game.

PHASE 1: ESTABLISHED TOOLCHAIN AUDIT

Inspect the actual repository and pinned N64Recomp integration.

Determine:

1. Which N64Recomp components are already functional.
2. What function metadata and symbol information are available.
3. Which original Mario Tennis functions can currently be generated and compiled conventionally.
4. Which existing experimental modifications are game-specific and worth retaining.
5. Which experimental mechanisms duplicate functionality already provided by N64ModernRuntime.
6. What prevents the existing generated code from linking into a conventional PC runtime.

Inspect current upstream documentation and source for:

- N64Recomp
- N64ModernRuntime
- RT64
- RecompFrontend

Use established interfaces and examples wherever possible.

Do not assume all four components are automatically compatible with our current code or with each other.

Identify exact APIs, versions, dependencies, integration points and blockers.

Keep this audit focused and time-boxed.

Do not spend the session producing a lengthy architecture comparison.

PHASE 2: BUILD A CONVENTIONAL RECOMPILATION PIPELINE

Make N64Recomp the central game-code translation component.

Use the existing discovered function metadata, validated code locations, and generated source wherever legitimately reusable.

Establish or improve a reproducible pipeline that:

1. Accepts a locally supplied supported Mario Tennis ROM.
2. Validates its identity and byte order.
3. Uses N64Recomp and appropriate project-owned metadata.
4. Generates or prepares native game-code output.
5. Compiles that output using the normal host compiler.
6. Links it against an appropriate runtime foundation.
7. Produces clear errors for unsupported or unresolved game code.

Do not claim complete recompilation unless the entire required code set is actually covered.

Do not embed or publish proprietary generated game code.

Where function metadata is insufficient, identify the smallest concrete missing pieces needed for a working native integration.

Prefer an incremental vertical slice that can compile and link over attempting to certify the entire ROM.

PHASE 3: INTEGRATE N64MODERNRUNTIME

Investigate and implement the smallest practical connection to N64ModernRuntime.

Prefer its existing facilities for:

- N64 OS services
- Thread scheduling
- Message queues
- Timing
- Cartridge/ROM access
- Memory management
- Task submission
- Audio and input infrastructure

Do not recreate these systems independently when established compatible implementations exist.

Review our custom experimental services against the runtime's actual capabilities.

For each major service, classify it as:

A. Replaceable with an existing runtime implementation
B. Requires a small Mario Tennis-specific adapter
C. Requires a game-specific patch
D. Not yet supported by the established runtime

Implement at least one meaningful integration or adapter if technically feasible.

Preserve correct game-visible behavior.

Do not force arbitrary hardware results or silently bypass unsupported operations.

PHASE 4: GRAPHICS AND APPLICATION FOUNDATION

Investigate the established RT64 integration path.

The objective is to eventually submit original Mario Tennis graphics tasks to a real PC graphics backend.

Reuse the Session 62 graphics-task discoveries and verified display-list behavior.

Do not treat our state-only experimental graphics service as a substitute for an actual renderer.

If feasible, establish a minimal runtime graphics integration or initialization path.

Investigate RecompFrontend for the eventual launcher, settings, and controller integration.

Use its existing functionality where appropriate instead of inventing a custom frontend.

Create a minimal application executable or integration target using the established architecture.

A first development build may only initialize the runtime, validate a ROM and report unsupported game-code dependencies.

That is acceptable if it is genuine, compilable, and independently launchable.

Do not fake a boot, rendered frame or successful game launch.

PHASE 5: DEFINE THE DISTRIBUTION ARCHITECTURE

The owner wants a user experience similar to Wave Race 64 Recompiled:

1. Download the project/application from GitHub.
2. Launch it.
3. Supply a legally obtained Mario Tennis ROM.
4. Have the application process the ROM locally.
5. Launch the native PC port.
6. Reuse cached local results on subsequent launches.

Users must not require Codex or developer command-line tools.

Linux/Bazzite is the primary target.
Windows follows.
macOS is optional.

IMPORTANT DISTINCTION

Investigate whether local static recompilation is actually required for ordinary end users.

Some established recompilation projects distribute precompiled game logic and use the supplied ROM for proprietary assets.

Our preferred initial architecture is local ROM processing and, where necessary, local code generation/building.

However, do not blindly require a full compiler toolchain on every user's computer if a simpler lawful architecture provides the same experience.

Document the options and tradeoffs.

Do not silently change the owner's intended user experience or weaken proprietary-content restrictions.

Any change to the distribution model requiring owner approval must be proposed rather than assumed.

PHASE 6: IMPLEMENT AND TEST

Prioritize a working vertical slice over broad unfinished scaffolding.

Preferred deliverable:

- Conventional CMake or equivalent native build integration
- Actual N64Recomp-generated Mario Tennis code included in a private local build
- An established runtime component linked successfully
- A real Linux executable or development integration target
- Explicit runtime status and errors
- Reproducible local build commands
- Focused automated tests

If a complete executable is not feasible, deliver the furthest genuinely compiled and linked integration.

Do not create an unrelated decorative launcher merely to satisfy an executable milestone.

Do not spend the session implementing custom UI components while the core game runtime remains disconnected.

PERFORMANCE AND PRODUCT REQUIREMENTS

Long-term goals:

- Native Linux and Windows support
- Widescreen resolutions
- Multiple controllers
- Stable 60+ FPS where feasible
- Audio
- Save functionality
- In-game settings overlay
- Simple installation and updates
- Steam compatibility
- Linux AppImage packaging

These are future milestones.

Do not attempt to implement them all now.

SECURITY AND COPYRIGHT

The original Mario Tennis ROM is owner-supplied and remains local.

Never commit or upload:

- Original ROM files
- Extracted proprietary assets
- Proprietary generated game code
- Private execution traces
- Sensitive diagnostics or local paths

Only reviewed, distributable project-owned source, configuration, metadata, tests and sanitized documentation may enter Git.

Review any proposed function metadata or generated tables for proprietary content before committing.

Preserve existing sandbox restrictions and archive integrity.

No public release, main merge, repository visibility change, access change or media publication is authorized.

Keep existing pinned dependencies unless a version change is necessary, reviewed and documented.

Do not weaken existing safety checks simply to make integration easier.

WORKFLOW AND TIME MANAGEMENT

Prioritize implementation over documentation.

Suggested order:

1. Recover verified baseline.
2. Audit established runtime integration.
3. Select the smallest practical vertical slice.
4. Implement and compile it.
5. Test actual behavior.
6. Preserve results and commit.

Do not spend most of the session repeating reference execution or expanding instruction counts.

Do not automatically enlarge the 512-body guard.

The experimental harness remains available for diagnosing actual game-specific problems.

If an established runtime cannot support an observed Mario Tennis behavior, record the precise incompatibility and implement a bounded adapter or patch where justified.

Avoid speculative rewrites.

If time or usage limits approach, preserve a recoverable checkpoint before exhausting context.

MANDATORY SESSION 63 REPORT

Create [REDACTED: private Session 63 report path].

Answer these questions clearly:

1. Are we now using N64Recomp as the central conventional code-generation pipeline?
2. How much of Mario Tennis can currently be generated and compiled?
3. What existing runtime components are integrated and tested?
4. Which custom services can be replaced by N64ModernRuntime?
5. Is RT64 connected to any actual Mario Tennis graphics task?
6. Is there an independently launchable Linux executable?
7. If yes, what exact command launches it on Bazzite?
8. Does it accept and validate a user-supplied ROM?
9. What prevents a genuine rendered frame?
10. What is the shortest credible path to a playable build?

Distinguish:
- Implemented and executed
- Compiled but not executed
- Investigated but not integrated
- Planned
- Unsupported

Do not overstate success.

CLOSEOUT

1. Run focused tests.
2. Run standard/full repository verification.
3. Preserve essential private artifacts outside Git.
4. Verify archive integrity and record the final accepted designation.
5. Update [REDACTED: private next-session plan path].
6. Update the roadmap and public development diary where appropriate.
7. Update the redacted prompt archive.
8. Run staged/history security scans.
9. Commit and push reviewed changes to the existing investigation branch.
10. Check CI results where possible.

Do not claim CI passed unless confirmed.

SESSION 63 SUCCESS CRITERIA

MINIMUM:

A verified, concrete integration of existing Mario Tennis recompilation work with at least one established runtime component, supported by an actual build or execution test.

PREFERRED:

A conventional native Linux development executable that links genuine N64Recomp-generated Mario Tennis code with established runtime infrastructure.

STRETCH:

The first original Mario Tennis code running through the conventional application/runtime path, with a credible route to RT64 graphics submission.

No fabricated progress.

FINAL INSTRUCTION

We are changing how this project is developed.

The experimental harness is no longer the primary product architecture.

N64Recomp and established PC runtime components should become the foundation wherever technically compatible.

Preserve the useful results of Sessions 1 through 62, but stop reinventing existing functionality unnecessarily.

Make practical progress toward a genuine, distributable Mario Tennis PC port.

Do not stop after writing a plan.

IMPLEMENT, BUILD, TEST, DOCUMENT AND PUSH.

BEGIN SESSION 63.