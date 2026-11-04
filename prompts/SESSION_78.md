# Session 78 — Owner prompt

Status: issued for Session 78. Requested objectives are not completion claims.
Authentic owner-input text; exact original and provenance preserved privately.
Published under the maximum-safe-transparency standard: retain the actual engineering instructions and mark only sensitive spans.
See the [development diary](../docs/PROGRESS.md#session-78) for verified results.

---

ITALIAN PLUMBER PONG
SESSION 78 MASTER PROMPT
NATIVE ROM SERVICE ADMISSION + PUBLIC DEVELOPMENT TRANSPARENCY

PROJECT:
Mario Tennis (USA), Nintendo 64 native PC recompilation

SESSION: 78
PRIMARY PLATFORM: Linux / Bazzite / ASUS ROG Ally

PRIVATE REPOSITORY:
[REDACTED: private development repository identifier]

BRANCH:
[REDACTED: private development branch]

PUBLIC ROADMAP:
Grognlor/Italian-plumber-pong-roadmap

============================================================
0. OWNER AUTHORIZATION AND SESSION OBJECTIVES
============================================================

The owner authorizes Session 78 to begin.

Continue autonomous engineering from the authenticated
Session 77 handoff.

This session has TWO major objectives.

OBJECTIVE A: NATIVE ENGINEERING

Determine whether the original asynchronous queued ROM
transfer, now authenticated through completion, can be
safely admitted into the conventional native application.

Establish the missing cache, DMA, completion ownership,
queue, scheduler and lifetime contracts.

Implement the smallest safe native integration if
independent evidence supports it.

OBJECTIVE B: PUBLIC TRANSPARENCY

Repair the excessive redaction in the public development
prompt diary.

The owner wants other developers to understand how
ChatGPT and Codex are being used to create this native
recompilation.

Existing public prompts often hide almost all substantive
engineering instructions.

This is contrary to the purpose of the public diary.

Review and correct historical public prompts, prioritizing
Sessions 76 and 77, and establish a better publication
standard for Session 78 onward.

Do not sacrifice proprietary-content security to
improve transparency.

PRIORITY:

Native engineering remains the main technical objective.

The public prompt transparency repair is a mandatory
deliverable, not optional housekeeping.

Allocate bounded time to each objective and preserve
sufficient time for final verification and delivery.

SECONDARY OBJECTIVES:

- Certify additional original native functions.
- Advance authenticated code-installation support.
- Investigate the RT64 graphics color mismatch.
- Improve engineering productivity.
- Preserve complete evidence.
- Prepare Session 79.

Do not recursively start another Codex session.

============================================================
1. MANDATORY RECOVERY AND SECURITY PREFLIGHT
============================================================

Read the current repository state:

[REDACTED: private session report path]
docs/NEXT_SESSION_PLAN.md
DEVELOPMENT_WORKFLOW.md
ARTIFACT_HANDOFF.md

Recover Session 77 using its authenticated:

FINAL_HANDOFF.json
RECOVERY.md
Selected primary inventory
Detached anchor
Separately anchored delivery addendum

SESSION 77 SELECTED PRIMARY:

1,558 files

Manifest SHA-256:

[REDACTED: private evidence seal]

Recover the final delivery addendum's exact identity,
count and seal from the authenticated private handoff.

Do not invent missing identifiers.

Verify the complete accepted dependency chain:

SESSION 74 PRIMARY:
9,932 files
[REDACTED: private evidence seal]

SESSION 74 ADDENDUM:
34 files
[REDACTED: private evidence seal]

SESSION 75 SELECTED PRIMARY:
377 files
[REDACTED: private evidence seal]

SESSION 75 ADDENDUM:
29 files
[REDACTED: private evidence seal]

SESSION 76 SELECTED PRIMARY:
1,539 files
[REDACTED: private evidence seal]

SESSION 76 ADDENDUM:
54 files
[REDACTED: private evidence seal]

Verify:

- Exact file membership
- File sizes and cryptographic hashes
- Detached anchors
- Owner-only permissions
- File ownership
- Archive dependency relationships
- Source provenance

Use the reviewed verify_seal helper where applicable.

The helper does not independently establish trust in
expected digests or dependency relationships.

Restore required predecessors in authenticated order
into a NEW restricted persistent workspace.

Never execute or modify sealed evidence.

Preserve failed diagnostics.

Selected archives are not independent complete backups.

Revalidate:

- Original ROM identity
- Pinned N64Recomp ABI 3 generator/header
- Source and submodule pins
- Six reviewed patch identities and application order
- N64ModernRuntime lock
- All 4,607 renderer-lock entries
- Pinned analysis package hashes
- Compiler/build dependencies
- Existing security restrictions

Use explicit tools/session_paths.py configuration.

Create fresh CMake build state.

Do not reuse stale absolute paths or substitute session
numbers blindly.

Failed authentication blocks affected original execution.

============================================================
2. VERIFIED SESSION 77 STARTING POSITION
============================================================

Session 77 established a bounded original eight-byte
ROM request through:

1. Requester queue construction and request submission
2. Original worker consumption
3. PI RAM address register write
4. PI cartridge address register write
5. PI transfer-length register write
6. Emulator DMA visibility
7. Deferred PI interrupt
8. Original interrupt acknowledgement
9. Resident interrupt-event publication
10. Worker event consumption
11. Worker completion-message publication
12. Requester completion consumption
13. Original lookup return

An independent device-effect model matches all 8 MiB
of reference RAM around the DMA initiation.

Four strict original execution slices match:

- CPU registers
- HI/LO
- Status
- Genuine FCSR
- All 64 raw FP words
- Ordered dispatch
- Full 4 MiB native-harness RAM

The observed upper 4 MiB remains unchanged.

Sixteen synthetic contract mutation controls reject.

IMPORTANT LIMITATIONS:

This is a bounded reference-emulator device/completion
contract.

It is NOT a complete native asynchronous ROM service.

It does NOT establish:

- Physical cache coherence
- N64 hardware timing
- General scheduler correctness
- Universal thread ownership
- Complete request lifetime
- Cancellation behavior
- Failure behavior
- Continuous native startup

The interrupt event and completion message were already
queued before their respective receives.

A completion wakeup was NOT demonstrated.

Do not claim otherwise.

The selected stack-backed request remains valid across
the observed send/receive interval.

General lifetime and reuse remain UNKNOWN.

============================================================
3. CURRENT NATIVE RECOMPILATION COVERAGE
============================================================

CONNECTED ORIGINAL:

6 routines
1,368 bytes
342 static instruction locations
5 normal returns

ISOLATED ORIGINAL:

12 extents
744 bytes
186 static instruction locations
21 authenticated comparisons

19 retained authenticated cases
2 fresh Session 77 executions

Session 77 added:

- Complete byte-copy loop
- Complete command-queue accessor

Together:

72 bytes
18 static instruction locations

Both were generated with pinned ABI 3, compiled and
executed natively with authentic same-run state.

The byte-copy comparison covers 665 dynamic instructions.

The queue-accessor comparison covers eight dynamic
instructions.

Both pass independent interpretation and strict
mutation/rejection controls.

No new original service entered conventional startup.

No live native first frame exists.

No playable game exists.

All eight milestones remain open.

============================================================
4. PRIMARY ENGINEERING TRACK A
CACHE AND DMA VISIBILITY
============================================================

Start from the authenticated selected ROM request.

Read the private Session 77 evidence:

[REDACTED: private evidence path]
[REDACTED: private evidence path]
[REDACTED: private evidence path]
[REDACTED: private evidence path]
[REDACTED: private evidence path]
[REDACTED: private evidence path]

Use the exact private roots selected by the handoff.

These are evidence references, not public Git artifacts.

Investigate:

1. Exact original cache operation
2. Address and span alignment
3. Cache-line boundaries
4. CPU-visible memory
5. Device-visible memory
6. DMA source and destination
7. Ordering requirements
8. Completion visibility
9. Native host memory model
10. Upstream runtime responsibilities

Distinguish:

AUTHENTIC ORIGINAL OBSERVATION
INDEPENDENT DEVICE MODEL
HARDWARE SEMANTICS
UPSTREAM RUNTIME CONTRACT
PROPOSED NATIVE IMPLEMENTATION

Do not treat reference-emulator behavior as proof of
physical N64 hardware semantics.

Do not replace original cache operations with no-ops
without an explicit reviewed equivalence contract.

Do not invent a synchronous ROM copy in place of an
original asynchronous request.

If the native host architecture does not require
physical cache maintenance for a specific operation,
prove that the chosen host implementation preserves
the original program's observable visibility and
ordering requirements.

Do not assume this equivalence.

Define:

- Preconditions
- Inputs
- Memory effects
- Event ordering
- Completion guarantees
- Failure behavior
- Lifetime requirements
- Rejection conditions

SUCCESS:

One independently justified cache/DMA visibility
contract suitable for native admission, or one
precisely resolved premise with the remaining
dependency documented.

============================================================
5. PRIMARY ENGINEERING TRACK B
THREAD, QUEUE AND COMPLETION OWNERSHIP
============================================================

Use authenticated original records, not thread IDs
alone, to establish ownership.

Review:

- Requester thread record
- Worker thread record
- Manager-published pointers
- Original command queue
- Original interrupt-event queue
- Requester completion queue
- Stack-backed request storage
- Resident interrupt sender
- Completion consumer
- Scheduler state

Define ownership for:

1. Request creation
2. Submission
3. Worker consumption
4. DMA initiation
5. Interrupt-event publication
6. Event consumption
7. Completion-message publication
8. Requester consumption
9. Storage release or reuse

Investigate:

- Queue layout compatibility
- Queue capacity
- Message identity
- Full/empty transitions
- Blocking behavior
- Waiter ownership
- Scheduler initialization
- Thread identity mapping
- Request lifetime
- Queue lifetime
- Failure and cancellation

Do not mix original queues with upstream waiters
without a reviewed compatibility contract.

Do not invent scheduler state.

Do not assume numeric thread IDs are universally unique.

Do not claim an unobserved wakeup.

If a wakeup contract is required for integration,
design a bounded experiment to authenticate it.

If the necessary evidence cannot be obtained,
mark the premise BLOCKED.

DELIVERABLE:

A complete bounded ownership and completion-delivery
admission proposal with verified facts, assumptions,
negative controls and remaining blockers.

============================================================
6. PRIMARY ENGINEERING TRACK C
NATIVE SERVICE ADMISSION
============================================================

Determine the smallest safe original service boundary
that can enter conventional native startup.

Acceptable outcomes:

A. A genuinely verified native asynchronous service
   integration.

B. A smaller safe original helper/service integration.

C. A defensible blocked admission contract with one
   newly resolved prerequisite.

Do not prioritize apparent functionality over
correctness.

Before integrating, verify:

- Correct original code residency
- Correct active code epoch
- Original-to-upstream thread mapping
- Initialized scheduler state
- Compatible queue layout and waiters
- Valid request lifetime
- Valid queue lifetime
- Cache/DMA visibility
- Completion ownership
- Event ordering
- Failure/cancellation handling
- No unsafe buffer reuse

Do not import emulator checkpoint RAM into startup.

Do not inject fake cache hits.

Do not substitute synchronous copies for unverified
asynchronous behavior.

Do not fabricate transfer completions.

Do not enable unsafe live graphics submission.

If integration becomes possible:

- Implement the smallest reviewed change.
- Add positive and negative tests.
- Validate event ordering.
- Validate ownership and lifetime.
- Confirm no regression to existing native execution.
- Preserve exact evidence and rollback instructions.

If integration remains blocked, document the
smallest remaining missing premise.

============================================================
7. ORIGINAL CODE INSTALLATION AND NATIVE FUNCTIONS
============================================================

Session 77 authenticated an original startup copy
installing [REDACTED: private code-installation extent] ROM-backed bytes of a replacement
resident interrupt sender.

The complete original copy passed a 665-instruction
native/interpreter/reference comparison.

The initial decoded handler is NOT the resident body.

Never compare resident execution against the
superseded initial handler.

Investigate the correct active code epoch and
original installation lifetime.

Determine whether existing compiled entry mappings
need invalidation or versioning after the original
code-installation transition.

Do not enable live activation without a reviewed
source identity and compiled-entry lifetime contract.

Continue seeking complete small original functions
with authenticated:

- Entry
- Return
- Source extent
- Residency epoch
- CPU state
- Memory effects
- Independent interpretation

For suitable functions:

1. Review exact source and boundaries.
2. Generate with pinned ABI 3.
3. Compile and execute natively.
4. Use authentic same-run input.
5. Compare CPU/HI/LO/status/FCSR/raw FP.
6. Compare ordered trace.
7. Compare full applicable RAM.
8. Run rejection/mutation controls.
9. Preserve evidence.

Do not execute privileged cache/device instructions
as ignored host instructions merely to increase
coverage.

Keep CONNECTED ORIGINAL and ISOLATED ORIGINAL
counts separate.

Do not inflate progress percentages.

============================================================
8. GRAPHICS CORRECTNESS TRACK
============================================================

Session 77 freshly rendered both complete authentic
frozen graphics tasks through unchanged native RT64.

Task 3:

4,783 unequal color pixels

Task 4:

4,374 unequal color pixels

Depth equality PASS.

Color equality FAIL.

The first unequal pre-overlay pixel has authenticated
software diagnostic values:

Texture/combiner RGB: [REDACTED: private per-pixel diagnostic value]
Dither: [REDACTED: private per-pixel diagnostic value]
Software output: [REDACTED: private per-pixel diagnostic value]
Five-bit channel value: [REDACTED: private per-pixel diagnostic value]

The equal-input RT64 writeback model yields [REDACTED: private per-pixel diagnostic value].

This is partial causal evidence.

The actual native GPU pre-write float and precise
texture sampling coordinates remain UNKNOWN.

NEXT EXPERIMENT:

Capture the native pre-write value, texture sample,
sampling coordinates and dither coordinates before
RGBA5551 conversion.

Use actual task modes.

Compare:

- Source texel
- Converted texture value
- Combiner input/output
- Blend input/output
- Dither selection
- Pre-write float
- Quantization
- Final GPU readback

Preserve separate evidence classes:

AUTHENTIC ORIGINAL COMPLETE TASK
MODIFIED DIAGNOSTIC REPLAY
INDEPENDENT SOFTWARE REFERENCE
NATIVE RT64 GPU READBACK

Do not tune renderer settings simply to reduce
the mismatch count.

Any proposed renderer correction must pass:

- Both authentic complete tasks
- Depth comparison
- Ownership controls
- Rejection controls
- Repeatability controls
- RT64 state-only tests

Preserve useful unaltered lossless private PNGs.

Do not publish game imagery.

Do not claim frozen replay is a live native frame.

============================================================
9. TOOLING AND PRODUCTIVITY
============================================================

Use existing tools productively.

GHIDRA:

Ghidra 12.2 remains available for restricted headless
analysis using the reviewed MIPS64-register,
32-bit-address, o32 profile.

Use selectively for:

- Control flow
- Call relationships
- Data references
- Privileged boundaries
- Function-body inspection
- Code-installation dependencies

Do not treat pseudocode as independent proof.

Do not repeat full toolchain benchmarking.

SPLAT:

Not operational for the required N64 import because
of the unresolved compression dependency.

Do not spend significant time repairing it unless
the current engineering task clearly requires it.

REA:

Disabled for this raw MIPS workflow.

Do not install or connect without new compatibility
evidence and a security review.

N64LoaderWV:

Disabled.

Its failed evaluation included unverified bundled
boot firmware.

Do not load, install or repair it.

AUTOMATION:

Retain tools/session_paths.py and verify_seal.

Look for small improvements that reduce repeated
engineering work without weakening validation.

Measure actual productivity where feasible.

Do not claim speed improvements without evidence.

============================================================
10. MANDATORY PUBLIC PROMPT DIARY REPAIR
============================================================

The owner has identified excessive redaction in the
public Italian Plumber Pong prompt diary.

The purpose of the public prompt archive is to
document how ChatGPT and Codex are being used
to develop the native Mario Tennis recompilation.

Other developers should be able to understand:

- What Codex was asked to do
- Why particular investigations were performed
- How engineering decisions evolved
- What tools were used
- What experiments were attempted
- What failed and why
- How verification and security were handled
- How the project progressed between sessions

The current practice of withholding entire
engineering sections is unacceptable when
those sections contain information that can
safely be shared.

PRIMARY PUBLICATION RULE:

MAXIMUM SAFE TRANSPARENCY.

Redact genuinely sensitive content, not entire
sections merely because they are technical.

------------------------------------------------------------
10A. RETROACTIVE AUDIT
------------------------------------------------------------

Audit the public prompt archive for Sessions 1-77,
where authenticated original prompts are available.

Compare each public prompt against its authenticated
private source.

Identify:

- Completely withheld engineering sections
- Unnecessarily broad redactions
- Missing non-sensitive technical instructions
- Missing methodology
- Missing development objectives
- Missing validation requirements
- Missing tool usage explanations
- Missing non-sensitive workflow context

Prioritize Sessions 76 and 77, which are known
examples of excessively withheld content.

Do not invent missing historical prompts.

Do not reconstruct a prompt from session summaries
and present it as an authentic original.

If the authentic source is unavailable, record that
limitation and leave the historical source unaltered.

------------------------------------------------------------
10B. CONTENT THAT SHOULD REMAIN PUBLIC
------------------------------------------------------------

Preserve as much authentic prompt text as possible.

Generally retain:

- Project objectives
- Recompilation methodology
- Engineering priorities
- Analysis workflows
- Tool selection and configuration methods
- Ghidra usage
- Reference emulator methodology
- Native function certification criteria
- Validation and rejection requirements
- Graphics investigation strategy
- Performance observations
- Security philosophy
- Development setbacks
- Session planning
- Development automation
- Milestone criteria
- Future-session handoffs
- Non-sensitive public repository information

Do not redact these merely because they contain
detailed engineering instructions.

Public repository names, public tool names and
already published non-sensitive project information
do not automatically require redaction.

------------------------------------------------------------
10C. CONTENT THAT MUST REMAIN PRIVATE
------------------------------------------------------------

Continue protecting:

- ROM files and copyrighted game bytes
- Extracted proprietary assets
- Original disassembly
- Translated proprietary game code
- Private source/address maps
- RAM snapshots
- Private emulator traces
- Restricted evidence archives
- Credentials and tokens
- Private personal information
- Sensitive host/account details
- Unverified third-party firmware
- Material prohibited by existing project policy

Public discussion of a methodology is not equivalent
to publishing the restricted original data used by
that methodology.

Do not weaken existing security rules.

------------------------------------------------------------
10D. REQUIRED REDACTION STANDARD
------------------------------------------------------------

Use narrow, localized redactions.

Examples:

[REDACTED: private filesystem path]

[REDACTED: proprietary ROM-derived bytes]

[REDACTED: authentication credential]

Retain the surrounding authentic instructions.

Preserve:

- Original section order
- Headings
- Engineering context
- Meaning
- Requested objectives
- Validation requirements

Never replace an entire engineering section with
a generic withholding notice when safe content
can be retained.

Never silently rewrite historical prompts.

Do not replace authentic instructions with
retrospective descriptions of completed work.

If a passage cannot safely be separated,
redact only the smallest necessary portion.

Record the reason privately.

------------------------------------------------------------
10E. HISTORICAL CORRECTIONS
------------------------------------------------------------

Prepare improved public versions of affected
historical prompts.

Prioritize:

1. Session 77
2. Session 76
3. Other heavily redacted recent sessions
4. Earlier sessions with authenticated originals

Preserve chronological order and session numbering.

Preserve the authentic original prompt privately.

Do not erase evidence that earlier public versions
were more heavily redacted.

Record a short revision note explaining that the
public prompt was updated for improved transparency.

Preserve the distinction between:

OWNER INSTRUCTIONS
ENGINEERING RESULTS

A requested objective is not proof of completion.

Only publish reviewed allowlisted Markdown files.

Do not publish private evidence or game imagery.

------------------------------------------------------------
10F. SESSION 78 PROMPT PUBLICATION
------------------------------------------------------------

Publish a substantially complete safely redacted
version of this Session 78 master prompt.

The default is to retain its actual engineering
instructions.

Redact only sensitive passages.

Do not publish a document consisting mostly of
section headings and withholding notices.

Use the same standard for future session prompts.

------------------------------------------------------------
10G. TRANSPARENCY VALIDATION
------------------------------------------------------------

Before publication:

- Compare against authenticated private originals
- Review every redaction
- Scan for credentials and proprietary content
- Inspect every public changed file
- Verify the public path allowlist
- Confirm no restricted evidence is included
- Read back the published remote content

Add a focused documentation regression that detects
obvious whole-section blanket withholding in future
prompt publication candidates.

The regression must not automatically publish
unreviewed text.

A passing scan does not replace manual security review.

------------------------------------------------------------
10H. REQUIRED TRANSPARENCY REPORT
------------------------------------------------------------

Include in the Session 78 report:

- Historical prompts reviewed
- Prompts corrected
- Prompts requiring no change
- Prompts unavailable for review
- Excessive redactions removed
- Sensitive redactions retained
- New publication rules
- Documentation regression results
- Links to corrected public prompts
- Remaining archive-repair work

If full historical review is too large for one session,
complete the highest-value corrections and prepare
a specific continuation plan.

Do not let this work consume the primary engineering
session.

SUCCESS:

A public prompt archive that genuinely teaches
other developers how this project is being built
without exposing restricted original material.

============================================================
11. SECURITY AND STRATEGY D
============================================================

Mandatory architecture:

N64Recomp ABI 3
N64ModernRuntime
RT64

Strategy D remains mandatory.

PROHIBITED:

- Fabricated SP/DP completions
- Unsafe live graphics submission
- Invented scheduler/current-thread state
- Fake cache hits
- Invented DMA completion
- Unsupported cache no-ops
- Unreviewed callbacks
- Unsafe buffer reuse
- Emulator RAM imported into startup
- Unauthenticated function boundaries
- Hidden comparison failures

NEVER COMMIT OR PUBLISH:

- ROM files
- Extracted game assets
- Original disassembly
- Translated proprietary code
- Generated proprietary game source
- RAM snapshots
- Emulator traces
- Private maps
- Unredacted sensitive prompts
- Private evidence bundles
- Game screenshots
- Credentials
- Unverified firmware

Keep original analysis material outside Git.

Reference execution must remain:

- Network-disabled
- Credential-free
- Read-only ROM
- Resource-bounded
- Process-bounded
- No guest mutation
- Capture before RSP where required

No main merge.

No release binaries.

No media publication.

No repository visibility or access changes.

No unrelated privileged host changes without
separate explicit approval.

Linux remains first priority.

Windows follows stable Linux.

macOS and other platforms remain conditional.

In-game settings, easy ROM installation and
application updates remain long-term goals.

============================================================
12. EXECUTION MANAGEMENT
============================================================

Work autonomously within approved limits.

Do not ask routine questions.

Use established bounds:

- Three attempts per blocker
- Fifteen closure rounds
- Twenty minutes per tool cycle
- 300 seconds per reference process
- Bounded logs, memory and captures

Do not run unbounded background processes.

Do not recursively launch Codex.

Do not assume remaining usage allowance.

Suggested priority order:

1. Authenticated recovery
2. Baseline validation
3. Cache/DMA visibility investigation
4. Completion ownership and queue contract
5. Safe native admission opportunity
6. Additional native function certification
7. Focused graphics investigation
8. Public prompt diary repair
9. Full verification and delivery

Begin the public diary audit early enough that
its required corrections are not forgotten.

Keep the transparency work bounded.

Preserve persistent checkpoints.

Switch tracks when a blocker is established.

Reserve sufficient time for final validation,
archival, GitHub delivery and reporting.

If interrupted, preserve a complete recoverable
handoff rather than losing progress.

============================================================
13. REQUIRED VERIFICATION
============================================================

Session 77 baseline:

244 repository tests PASS
3 generator regressions PASS
9 CTest PASS
4 conventional comparisons PASS
21 isolated authenticated cases

Of the isolated cases:

19 retained
2 fresh in Session 77

Also verify:

- ROM identity
- ROM rejection
- Unsupported launch
- Genuine FCSR
- Raw FP comparison
- Native instruction-budget unwind
- RT64 state-only positive/negative checks
- Documentation consistency
- Eight milestone statuses
- Security checks

Run:

python3 tools/development.py verify

Full verification requires the verified external
generator/header.

Archive checks require explicit root and manifest.

Report fresh executions separately from retained
authenticated evidence.

Do not count retained comparisons as fresh execution.

Do not call unavailable checks PASS.

Known unresolved failures:

Cross-build whole-RAM parity: FAIL

Complete textured color equality: FAIL

General determinism: UNKNOWN

Do not hide or reclassify these failures.

For new original execution evidence, require:

- Authenticated same-run state
- Independent interpretation
- Correct source epoch
- Complete applicable CPU state
- Genuine FCSR
- Raw FP values
- Ordered trace
- Full applicable RAM
- Rejection/mutation controls

Report exact coverage changes.

Do not infer broad game completion percentages.

============================================================
14. PRIVATE EVIDENCE AND PRESERVATION
============================================================

Create a restricted persistent Session 78 workspace.

Preserve:

- Exact authentic owner prompt
- Tool/source provenance
- Original reference observations
- Independent models
- Cache/DMA contract evidence
- Completion ownership evidence
- Queue and scheduler investigation
- Native compilation/execution results
- Graphics diagnostics
- Failed experiments
- Test receipts
- Public redaction review decisions
- Historical prompt comparison records
- Final source state
- Reproduction instructions

Create a new selected Session 78 evidence archive.

Verify:

- Exact membership
- Sizes and hashes
- Owner-only permissions
- Ownership
- Detached anchor
- Dependency chain

Preserve final GitHub and CI receipts in a separately
anchored delivery addendum.

Do not modify predecessor seals.

Do not claim selected evidence is an independent
complete backup.

============================================================
15. GITHUB AND PUBLIC DELIVERY
============================================================

Create:

[REDACTED: private session report path]

Update:

docs/NEXT_SESSION_PLAN.md

Update the approved public development diary.

Publish the reviewed Session 78 prompt with
maximum safe transparency.

Correct historical public prompts as authorized
under Section 10.

Preserve prior diary entries and milestone ordering.

Use only reviewed public Markdown paths.

Do not publish original proprietary data,
private evidence, or game media.

Before committing:

- Run full verification
- Inspect every staged file
- Check whitespace
- Scan staged content
- Scan available Git history
- Review public redactions
- Verify public allowlist
- Confirm no restricted files entered Git

Commit reviewed changes to the existing private
investigation branch.

Push and read back remote file contents.

Verify public corrections through remote readback.

Check security CI.

Record actual observed states:

QUEUED
IN_PROGRESS
SUCCESS
FAILURE
CANCELLED

Never report queued or running CI as PASS.

Preserve exact commit IDs and delivery receipts.

Do not merge main.

Do not publish binaries or releases.

============================================================
16. SESSION 79 HANDOFF
============================================================

Prepare an accurate Session 79 plan.

Include:

1. Exact cache/DMA visibility findings
2. Completion ownership findings
3. Original-to-upstream thread mapping status
4. Queue and scheduler compatibility status
5. Request and queue lifetime findings
6. Native service admission status
7. Newly certified original functions
8. Code-installation/epoch progress
9. Graphics causality progress
10. Public prompt archive corrections
11. Remaining documentation repairs
12. Highest-value next engineering experiment
13. Exact recovery and validation instructions

Prioritize the clearest achievable step toward
continuous authentic native startup.

Do not automatically start Session 79.

============================================================
17. FINAL OWNER REPORT
============================================================

At the end, provide a clear plain-language report.

A. ORIGINAL ROM LOADING

Did we establish the cache/DMA visibility contract?

Can the original queued transfer be used safely
by the native application?

What remains blocked?

B. NATIVE RECOMPILATION

How many additional original functions were
compiled and executed?

Did connected original coverage increase?

Did any original service enter conventional startup?

C. GRAPHICS

Did we identify the actual native color mismatch?

Did either authentic task achieve pixel equality?

Were new private diagnostic images captured?

Is there a live native first frame?

D. PUBLIC PROMPT DIARY

How many historical prompts were reviewed?

How many were corrected?

Are Sessions 76 and 77 now substantially readable?

Is the Session 78 public prompt substantially complete?

What sensitive material remains appropriately redacted?

What remains for future sessions?

E. VALIDATION

Report exact tests, failures, evidence seals,
commits, remote readbacks and CI states.

F. NEXT STEP

What is the single highest-value Session 79 objective?

Use accurate evidence classifications.

Do not exaggerate progress.

============================================================
18. FINAL DIRECTIVE
============================================================

BEGIN SESSION 78.

Recover the authenticated Session 77 state.

Investigate the native admission requirements for
the original asynchronous queued ROM transfer.

Establish cache/DMA visibility, completion ownership,
thread mapping, queue compatibility and lifetime
contracts as far as independently supported.

Implement the smallest safe native integration if
the evidence permits.

Certify additional original functions where useful.

Advance graphics color-causality investigation.

Repair the excessively redacted public prompt diary,
starting with Sessions 76 and 77.

Publish the Session 78 prompt with maximum safe
transparency.

Preserve all security boundaries.

Run full verification.

Archive and deliver reviewed results.

Prepare Session 79 without starting it.

The objective is measurable progress toward a
continuously running native Mario Tennis application,
alongside a genuinely useful public record of how
the project is being developed.