# Session 84 — Owner prompt

Status: issued for Session 84. Requested objectives are not completion claims.
Authentic complete owner-input text; exact source and provenance preserved privately.
Only localized sensitive spans are visibly redacted.
See the [development diary](../docs/PROGRESS.md#session-84) for verified results.

---

ITALIAN PLUMBER PONG
SESSION 84 MASTER PROMPT
Authentic Preempting Handoff and Context-Save Certification

You are continuing Italian Plumber Pong, the security-conscious static recompilation of Mario Tennis (USA) for Nintendo 64 into a native PC application.

THIS IS SESSION 84.

The owner authorizes one bounded Session 84 engineering cycle under the existing security, evidence, repository, validation and publication constraints.

Work autonomously within those boundaries. Authenticate every technical premise, preserve genuine failures, and complete the normal verified engineering and public-documentation delivery.

Do not launch Session 85.

====================================================================
1. PROJECT AND AUTHORIZED SCOPE
====================================================================

Private engineering repository:
[REDACTED: private development repository identifier]

Authorized branch:
[REDACTED: private development branch]

Public roadmap:
Grognlor/Italian-plumber-pong-roadmap

Public branch:
main

Target:
Mario Tennis (USA), Nintendo 64.

Expected ROM:
16 MiB, big-endian.

SHA-1:
999047f07cec931ffbdcc7b33b8502ef602807ee

Primary development platform:
ASUS ROG Ally, Bazzite Linux.

Linux is the first release target. Windows follows after stable Linux execution. Other platforms remain conditional.

Long-term goals include faithful native gameplay, multiplayer, widescreen, smooth high-framerate presentation, multiple controllers, in-game settings, ROM-drop installation and eventual in-app updates.

These goals are not current capabilities.

The ROM, proprietary assets, disassembly, translated original code, private traces and sensitive source maps must remain outside Git.

Do not merge to main, publish binaries/media, create releases, change visibility/access or modify host/network configuration.

====================================================================
2. REQUIRED STARTING REVIEW
====================================================================

Read:

[REDACTED: private engineering document path]
[REDACTED: private engineering document path]
[REDACTED: private engineering document path]
[REDACTED: private engineering document path]

Recover and authenticate:

- Session 83 FINAL_HANDOFF.json.
- Session 83 RECOVERY.md.
- Selected Session 83 primary archive and detached anchor.
- Separately anchored Session 83 delivery addendum.
- Exact source and delivery receipts.
- Session 83 root-priority certification and source review.
- Authentic [REDACTED: private reference-run identity] observations.
- Session 82 event-registration certification.
- Relevant Sessions 79–81 scheduler, worker and bootstrap evidence.

Use authenticated selectors and exact identities.

Never guess original addresses, archive paths, source epochs, stack boundaries or reference-run identities.

Never execute or modify an archive seal.

Never blindly replace session numbers in inherited absolute paths.

====================================================================
3. VERIFIED SESSION 83 BASELINE
====================================================================

One complete original root-priority-change function was certified in isolation.

Complete extent:
200 bytes / 50 static locations.

Authentic returning path:
Root priority 10 to 150.

Executed:
36 function locations.
50 dynamic instructions including two retained Status leaves.

Six same-run checkpoints matched:

- Applicable GPRs.
- HI/LO.
- CP0 Status.
- Genuine FCSR.
- All 64 raw FP words.
- Ordered instructions and calls.
- Full applicable four-MiB RAM.

Genuine pending-interrupt bits were zero at all six selected checkpoints.

No interrupt delivery or MMIO occurred in the selected trace.

Fourteen strict comparison controls passed.
Two native interrupt-state rejection controls passed.
Three alternate throwing-boundary controls passed.
One-instruction RAM-safe budget unwind passed.

The unexecuted queue-removal, queue-insertion and preempting-yield/context-switch paths remain uncertified.

Current isolated original:
19 extents.
1,672 bytes.
418 static locations.
30 cases.

Current connected original:
Six routines.
1,368 bytes.
342 locations.
Five normal returns.

No original ROM service enters conventional native startup.
No runnable worker host adapter exists.
No native first frame exists.
No playable game exists.

All eight milestones remain open.

Current reviewed coverage lower bounds:
13 complete functions plus one partial prefix.
582 compiled locations.
357 executed locations.
190 strictly validated locations.
167 connected locations.

Eight strictly validated complete functions.
Five connected complete functions.

Eleven legacy isolated extents remain.

Whole-ROM totals and percentages remain UNKNOWN.

Session 83 verification:
307 repository tests PASS.
Three generator regressions PASS in full verification.
Nine CTest checks PASS.
Four conventional comparisons PASS.

Cross-build whole-RAM parity remains FAIL.
General determinism remains UNKNOWN.

====================================================================
4. SESSION 84 PRIMARY OBJECTIVE
====================================================================

AUTHENTICATE THE ORIGINAL PREEMPTING YIELD / CONTEXT-SAVE BOUNDARY AND THE LATER ROOT-TO-WORKER HANDOFF.

This is distinct from the early root-priority increase certified in Session 83.

Session 83 certified the returning 10-to-150 invocation.

Session 84 targets the later original execution where the root priority is reduced and the scheduler may select the worker.

The objective is to establish the genuine original behavior, not to force the native runtime into switching threads.

Recover the exact original identities from authenticated source evidence.

Determine:

1. Which original function initiates the later priority reduction.
2. Which original scheduler and queue operations execute.
3. Whether a preempting yield occurs.
4. Which architectural context is saved.
5. Which architectural context is restored.
6. How the root and worker identities are represented.
7. Which ready-list transitions actually occur.
8. Which Status/Cause transitions occur.
9. Whether interrupt or device effects participate.
10. What constitutes the authentic outcome boundary.

Do not assume the original operation returns normally to its initial caller.

A context switch may transfer execution to another architectural thread rather than return through the ordinary call chain.

Do not fabricate a return to simplify comparison.

====================================================================
5. SOURCE AND BOUNDARY AUTHENTICATION
====================================================================

Review complete original source boundaries before generation.

Authenticate:

- Original priority-change invocation.
- Original yield/context-save routine.
- Direct and indirect targets.
- Architectural register-save layout.
- Context restoration.
- Stack pointer handling.
- Ready-list operations.
- Sentinel queue semantics.
- Scheduler ownership transitions.
- Original current-thread record.
- Installed source epoch.
- Original versus superseded code.
- Return or non-return behavior.
- Interrupt and device dependencies.

Use reviewed maps and authentic original bytes.

Relevant tools include:

tools/blocker_investigator.py
tools/mips_subset.py
tools/reference_compare.py
tools/validate_checked_recomp.py

Also review the existing Status bridge, native call/instruction tracing and applicable runtime tests.

Tool output is guidance, not proof.

Reject unresolved indirect targets.

Do not invent an original function boundary or use a convenient partial region as a complete function.

Do not assume the context-save routine can be certified independently of its actual scheduler dependencies.

====================================================================
6. AUTHENTIC REFERENCE OBSERVATION
====================================================================

Capture the genuine later root-priority reduction and resulting scheduler behavior.

Use the existing secured original reference framework.

Requirements:

- Read-only ROM.
- No guest-state mutation.
- No fabricated architectural records.
- No fabricated queue entries.
- No synthetic interrupt events.
- No invented cache/device visibility.
- Network namespace isolation.
- Cleared environment and credential exclusion.
- Bounded CPU, memory, files, logs and captures.
- Maximum 300-second reference process wall time.

Capture genuine same-run evidence for:

- Priority-change entry.
- Relevant scheduler entry.
- Context-save boundary.
- Current-thread ownership before transition.
- Ready-list contents and ordering.
- Root architectural state.
- Worker architectural state.
- CP0 Status/Cause and genuine pending bits.
- Context restoration.
- First authenticated worker continuation, if observed.
- Applicable RAM and device effects.

Preserve ordered instruction/call/dispatch evidence.

Do not combine unrelated reference runs into a fictional continuous handoff.

If the reference stops at a non-returning scheduler transition, preserve that exact outcome.

If required state cannot be observed, classify it UNKNOWN and stop dependent certification.

====================================================================
7. CONTEXT-SAVE AND INTERRUPT CORRECTNESS
====================================================================

The context-switch boundary is more demanding than an ordinary function return.

Do not assume that all architectural registers retain their previous values across a thread switch.

Authenticate which state belongs to:

- The outgoing root.
- The incoming worker.
- The scheduler.
- The host harness.
- The original saved-context records.

Require exact evidence for:

- General-purpose registers.
- HI/LO.
- CP0 Status.
- CP0 Cause.
- Genuine FCSR.
- All 64 raw FP words.
- Stack pointer.
- Return/program-counter identity.
- Saved context layout.
- Ordered scheduling transitions.
- Applicable RAM and device effects.

Capture genuine pending-interrupt state whenever Status becomes enabled.

Do not infer zero pending state from another run.

Do not mask genuine pending interrupts to manufacture a successful transition.

Do not fake a context restore.

Do not substitute a host-owned pointer for an original architectural record.

Do not change original sentinel queues to null queues.

Do not create a host context from guessed original stack capacity.

If the complete transition cannot be authenticated, certify only a smaller independently supported original boundary.

====================================================================
8. NATIVE GENERATION AND COMPARISON
====================================================================

Use the pinned N64Recomp ABI 3 generator and matching header.

Generate only complete original functions with authenticated boundaries and source epochs.

For any selected authentic execution path, require:

- Exact source identity.
- Same-run reference input and outcome.
- Independent interpretation.
- Bounded native execution.
- Full applicable CPU/HI/LO/Status comparison.
- Genuine FCSR.
- All 64 raw FP words.
- Ordered instruction and dispatch evidence.
- Applicable RAM comparison.
- Correct device and interrupt effects.
- Correct context ownership.
- Correct return or non-return outcome.
- Negative mutations.
- Native instruction-budget unwind.

Do not treat a context switch as a normal return unless the authentic reference demonstrates that behavior.

Reject unsupported scheduler paths.

Reject missing interrupt state.

Reject unresolved indirect calls.

Reject unowned host contexts.

Reject unsupported queue manipulation.

Reject an unknown allocation generation.

Preserve failed attempts, exact diagnostics and source identities outside Git.

A successful isolated original context-save path is valuable but does not establish a runnable host scheduler.

====================================================================
9. CLASSIFICATION AND INTEGRATION
====================================================================

Label a successfully certified isolated path:

ISOLATED ORIGINAL.

Do not call it CONNECTED ORIGINAL without independently satisfying every runtime ownership and lifetime gate.

Architecture D remains mandatory.

Original architectural records and sentinel queues must remain separate from host contexts and null-terminated host queues.

A runnable original worker adapter requires:

- Real bootstrap.
- Real host registration.
- Authenticated stack lease.
- Queue and waiter ownership.
- Request/destination/completion leases.
- Source epoch and generation.
- Correct scheduler mapping.
- Failure and drain behavior.
- Cancellation and retirement.
- Safe code lifetime and invalidation.

No complete authenticated stack lease currently exists.

No live source-epoch registry exists.

No atomic publication or overlap/direct-call invalidation exists.

No compiled-storage retirement exists.

Do not claim these mechanisms have been implemented merely because original context-save code executes in isolation.

====================================================================
10. STACK BLOCKER
====================================================================

The original worker's complete stack allocation remains unauthenticated.

UNKNOWN:

- Lower boundary.
- Complete capacity.
- Guard/reserved regions.
- Exclusive owner.
- Allocation generation.
- Untouched saved-slot provenance.
- Continuous lifetime.
- Destruction.
- Reuse.
- Cancellation and retirement.

Preserve the incomplete descriptor and explicit rejection.

Preserve Session 81's separately sealed null owner/generation clarification.

Preserve the rejected pre-SP-restoration draft.

Do not repeat Sessions 76–83 manager, constructor, adjacency or observed-stack-access investigations.

Reopen only if genuinely new independent original allocation or lifetime evidence is discovered.

No authenticated lease means no runnable original-worker host adapter.

====================================================================
11. BOUNDED INVESTIGATION AND FALLBACK
====================================================================

Apply strict stop conditions:

- Three distinct failed evidence attempts.
- Fifteen bounded investigation rounds.
- Twenty minutes in one cycle without useful evidence.
- Missing required source/interrupt/context evidence.
- Repeated resolved findings.
- Any security or provenance concern.

If the complete preempting handoff cannot be certified:

1. Preserve the exact missing premise.
2. Preserve failed reference and native attempts.
3. Identify the smallest useful complete original bootstrap helper.
4. Prefer a helper directly supporting scheduler, root startup, worker startup or event delivery.
5. Certify one authentic path if independently supportable.
6. Keep unsupported context transitions rejecting.

Do not choose arbitrary functions merely to inflate coverage.

Do not manufacture a successful scheduler return.

Do not spend the entire session repeatedly investigating a known blocker.

====================================================================
12. RECOVERY AND SECURITY PREFLIGHT
====================================================================

Authenticate the Session 83 primary and delivery addendum and all nineteen required predecessor seals.

Session 83 primary:
3,212 files.

Manifest SHA-256:
[REDACTED: private archive manifest digest]

Session 82 primary:
2,867 files.

Manifest SHA-256:
[REDACTED: private archive manifest digest]

Session 82 delivery:
331 files.

Manifest SHA-256:
[REDACTED: private archive manifest digest]

Recover the Session 83 delivery addendum's exact identity from authenticated private closeout.

Never guess missing archive identities.

For every required seal, verify:

- Exact membership.
- File sizes.
- Content hashes.
- Ownership.
- Owner-only permissions.
- Detached anchors.
- Expected source identity.
- Dependency order.

Restore fresh restricted persistent copies.

Never execute or modify seals.

Dependent archives are not necessarily independent complete backups.

Verify:

- Original ROM identity.
- Pinned ABI 3 generator/header.
- Source and five submodules.
- Six ordered patches.
- Runtime lock.
- All 4,607 renderer entries.
- Hash-locked offline Python 3.14 packages.
- Build dependencies.

Reproduce all six patches freshly using the documented zero-context option.

No force.
No fuzz.
No hand edits.

Run fresh application CMake/build and actual session_paths checks.

Failed mandatory gates block dependent work.

Do not download unchanged dependencies unnecessarily.

====================================================================
13. INCREMENTAL COVERAGE
====================================================================

Reuse:

mt-us-census-v1

Starting lower bounds:

13 complete functions plus one partial prefix.
582 compiled locations.
357 executed locations.
190 strictly validated locations.
167 connected locations.

Eight strictly validated complete functions.
Five connected complete functions.

Eleven legacy isolated extents remain.

Add only genuinely authenticated new original-code records.

For each record establish:

- Canonical identity.
- Complete or partial boundary.
- Source epoch.
- Alias deduplication.
- Generation status.
- Execution status.
- Strict validation status.
- Connected status.
- Historical qualifications.

Do not run a full-ROM census automatically.

Do not invent whole-ROM denominators.

Do not report percentages without independently established totals.

Do not add isolated extents to deduplicated function totals.

Use the existing coverage CLI to regenerate aggregate JSON and Markdown.

Run incremental ledger tests.

Preserve all prior records and qualifications.

====================================================================
14. GRAPHICS
====================================================================

Graphics remains secondary.

No new GPU attempt or production graphics correction occurred in Session 83.

The twelve retained R32ui/R16_UINT storage-format mismatches remain.

The hypothetical matching diagnostic allocation is only an offline consistency finding.

Actual device features, index bounds, synchronization, resource lifetimes and compiler safety remain unverified.

The RADV compiler crash cause remains UNKNOWN.

Retained color equality:
FAIL at 4,783 / 4,374 pixels.

Retained depth equality:
PASS.

No live native first frame.

Do not claim a graphics fix without authenticated new evidence.

Do not perform unsafe modified GPU replay.

Do not publish retained diagnostic PNGs or other media.

====================================================================
15. VERIFICATION
====================================================================

Run:

python3 tools/development.py verify

Use full mode when authenticated external generator/header are supplied.

Run applicable:

- Repository tests.
- Generator regressions.
- CTest.
- Conventional native comparisons.
- ROM rejection.
- Unsupported launch.
- FCSR/raw-FP tests.
- Status/Cause/interrupt controls.
- Scheduler rejection controls.
- Budget unwind.
- Stack lease tests.
- Coverage ledger tests.
- Storage texel contract tests.
- RT64 state-only positive/negative controls.
- New context-save comparison tests.

Historical Session 83 baseline:

307 repository tests PASS.
Three generator regressions PASS.
Nine CTest PASS.
Four conventional comparisons PASS.

Report fresh current results.

Keep PASS, FAIL, SKIPPED, BLOCKED and UNKNOWN distinct.

Cross-build whole-RAM parity remains FAIL until resolved.

General determinism remains UNKNOWN.

Do not suppress failures.

====================================================================
16. PRIVATE ENGINEERING DELIVERY
====================================================================

Update:

[REDACTED: private engineering document path]
[REDACTED: private engineering document path]

Also update relevant status and coverage documents.

Record:

- Starting baseline.
- Recovery and security checks.
- Authentic root-to-worker observations.
- Original function identities.
- Source epochs.
- Context-save evidence.
- Interrupt state.
- Native execution results.
- Independent comparisons.
- Negative controls.
- Budget unwind.
- Isolated/connected classifications.
- Stack blocker.
- Coverage deltas.
- Graphics status.
- Tests and known failures.
- Next engineering objective.

Inspect every staged file.

Prevent commits of:

- ROM data.
- Proprietary assets.
- Disassembly.
- Translated proprietary code.
- Private execution traces.
- Sensitive source maps.
- Credentials.
- Temporary build outputs.

Run whitespace, staged-file and history safeguards.

Commit and push only the authorized private investigation branch.

Read back all changed remote files and verify exact identities.

Record actual GitHub CI results.

Reconcile private issue [REDACTED: private issue identity] and all eight milestones without closing unverified work.

No main merge.
No release.
No binary/media publication.
No visibility/access changes.

====================================================================
17. PUBLIC ROADMAP AND DEVELOPMENT DIARY
====================================================================

Publish only the normal new Session 84 updates:

- Session 84 diary.
- Authentic Session 84 owner prompt.
- Prompt index.
- Current coverage summary if applicable.
- Accurate milestone status.

Explain in gamer-friendly language:

- What original code was actually executed.
- Whether a real context switch was observed.
- Whether native execution matched it.
- Whether the result remains isolated.
- What prevents connected startup.
- Whether a playable game or first frame exists.
- What Session 85 should tackle.

Preserve the authentic owner prompt with localized security redactions.

Mark redactions visibly.

Review public candidate and private source for provenance, ordering, transparency and sensitive content.

Do not retrospectively audit, rewrite, repair or republish Sessions 1–83 public diary or prompt history.

Normal new-session entries and current cumulative coverage regeneration are authorized.

No media publication.

====================================================================
18. EVIDENCE PRESERVATION AND CLOSEOUT
====================================================================

Keep private original evidence outside Git in restricted owner-only persistent storage.

Preserve:

- Exact source identities.
- Authentic reference inputs and outcomes.
- Original scheduler/context observations.
- Genuine pending-interrupt state.
- Source epochs.
- Generation recipes.
- Native outputs.
- Independent interpretations.
- Failed attempts.
- Negative controls.
- Budget unwind.
- Coverage provenance.
- Exact commands and tool versions.
- Security reviews.
- Archive manifests and SHA-256 digests.
- Detached anchors.
- GitHub CI and delivery receipts.

Seal the primary evidence and separately anchored final delivery receipts using the established workflow.

Do not alter predecessor seals.

Do not claim dependent archives are independent complete backups.

If mandatory security, recovery or delivery is blocked, stop safely and report partial completion.

====================================================================
19. REQUIRED FINAL OWNER REPORT
====================================================================

Provide a plain-English summary followed by technical findings.

Include:

A. Executive result.
B. Original preempting handoff evidence.
C. Native context-save certification outcome.
D. Original-code progress and isolated/connected totals.
E. Genuine interrupt and scheduler behavior.
F. Stack ownership and host adapter status.
G. Incremental coverage.
H. Graphics status.
I. Current verification results.
J. Security, commits, CI and evidence seals.
K. Highest-value Session 85 objective.

Do not claim a playable game or first native frame unless actually demonstrated.

Do not automatically begin Session 85.

====================================================================
20. EXECUTION ORDER
====================================================================

1. Authenticate Session 83 handoff and delivery.
2. Verify all required predecessor seals.
3. Verify ROM, toolchain, source, patches and runtime.
4. Reproduce patches and fresh application build.
5. Recover the exact later priority-reduction invocation.
6. Review the original preempting yield/context-save boundaries.
7. Capture genuine same-run root-to-worker evidence.
8. Authenticate CP0, interrupt, scheduler and context state.
9. Generate only independently bounded original functions.
10. Execute safely in an isolated native harness.
11. Compare full applicable architectural state and memory.
12. Run strict negative controls and budget unwind.
13. Reject unsupported scheduler/context transitions.
14. Apply the bounded productive fallback if blocked.
15. Update incremental coverage.
16. Run full applicable verification.
17. Preserve private evidence.
18. Complete private engineering report and next handoff.
19. Publish reviewed normal Session 84 public updates.
20. Push authorized private changes and verify remote readback.
21. Record actual CI and seal final receipts.
22. Report verified results to the owner.

The goal is authentic progress toward a runnable native game, not speculative scheduling behavior or inflated coverage.

BEGIN SESSION 84.

END OF SESSION 84 MASTER PROMPT.