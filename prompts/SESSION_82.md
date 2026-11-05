# Session 82 — Owner prompt

Status: issued for Session 82. Requested objectives are not completion claims.
Authentic complete owner-input text; exact source and provenance preserved privately.
Only localized sensitive spans are visibly redacted.
See the [development diary](../docs/PROGRESS.md#session-82) for verified results.

---

ITALIAN PLUMBER PONG
SESSION 82 MASTER PROMPT
Allocation Provenance, Authentic Native Progress, and Incremental Coverage

You are continuing the existing Italian Plumber Pong project, a security-conscious static recompilation of Mario Tennis (USA) for Nintendo 64 into a native PC application.

This is SESSION 82.

The owner has authorized one bounded Session 82 engineering cycle under the existing project constraints. Do not launch Session 83, merge to main, create releases, publish binaries or media, change repository visibility, or grant access.

Read this entire prompt before beginning. Work autonomously within its boundaries, preserve reproducible evidence, and complete the normal verified session delivery.

Do not treat this prompt as evidence that an implementation is correct. Authenticate against the actual private repository, existing records, pinned tools, and source material.

====================================================================
0. PROJECT AND REPOSITORIES
====================================================================

Private engineering repository:
[REDACTED: private development repository identifier]

Existing working branch:
[REDACTED: private development branch]

Public documentation repository:
Grognlor/Italian-plumber-pong-roadmap

Public documentation branch:
main

Original target:
Mario Tennis (USA), Nintendo 64, big-endian ROM.

Expected original ROM:
16 MiB
SHA-1:
999047f07cec931ffbdcc7b33b8502ef602807ee

The ROM and any proprietary derived materials must remain outside Git.

Primary development platform:
ASUS ROG Ally running Bazzite Linux.

Platform priorities:
1. Linux.
2. Windows after Linux is stable.
3. Other platforms only when feasible or supported by collaborators.

Long-term product goals:
- Native playable Mario Tennis.
- Original gameplay and multiplayer behavior.
- Widescreen presentation.
- Smooth 60 FPS or higher where technically appropriate.
- Multiple controller support.
- In-game graphics and gameplay settings.
- Simple ROM-drop installation without a separate launcher.
- An eventual in-application update mechanism.

These are product goals, not claims of current functionality.

Do not implement unrelated frontend features at the expense of authentic native execution.

====================================================================
1. SESSION 81 VERIFIED BASELINE
====================================================================

Read, in full:

[REDACTED: private engineering document path]
[REDACTED: private engineering document path]
[REDACTED: private engineering document path]

Also review relevant prior session reports and authenticated evidence referenced by the Session 81 handoff.

Session 81 established:

A. Newly isolated original function

- Complete original thread-start function.
- 240 bytes.
- 60 static instruction locations.
- One fresh native execution case.
- 65 dynamic instructions including certified callees.
- Original stopped-to-ready path matched independent interpretation and authenticated same-run Session 80 evidence.
- Full applicable CPU, HI/LO, Status, genuine FCSR, raw floating-point words, ordered dispatch, and four-MiB RAM comparison.
- Upper four MiB unchanged in the authenticated reference.
- Eight comparison mutations rejected.
- Native instruction-budget unwind passed.
- Unexecuted alternate scheduling paths still reject.

B. Isolated original code

17 extents.
1,300 bytes.
325 static instruction locations.
28 cases.

C. Connected original code

Six routines.
1,368 bytes.
342 static locations.
Five normal returns.

Do not add these categories together or claim that isolated execution is integrated native startup.

D. Coverage ledger

Baseline:
mt-us-census-v1

Reviewed lower bounds:
10 complete functions plus one partial prefix.
481 identified/generated/compiled locations.
285 executed locations.
118 strictly validated locations.
167 connected locations.

Five complete functions strictly validated.
Five complete functions connected.

Whole-ROM function count:
UNKNOWN.

Whole-ROM percentages:
UNKNOWN.

Twelve older isolated extents still require canonical identity, source-alias, boundary, and historical-qualification review.

E. Verification

Session 81 final:
299 repository tests passed.
Three generator regressions passed.

Session 81 baseline also includes:
Nine CTest checks.
Four conventional comparisons.

Cross-build whole-RAM parity remains FAIL.
General determinism remains UNKNOWN.

F. Graphics

Retained color equality:
FAIL at 4,783 and 4,374 pixels.

Retained depth equality:
PASS.

All twelve reviewed diagnostic shader variants declare R32ui while the selected storage texel-buffer view is R16_UINT.

This is an identified format-contract incompatibility, not a proven explanation for the modified-shader compiler crash.

No live native first frame exists.

G. Project state

No playable game.
No original ROM service integrated into conventional native startup.
No runnable original-worker host adapter.
All eight milestones remain open.

Preserve these distinctions throughout Session 82.

====================================================================
2. SESSION 82 PRIMARY OBJECTIVE
====================================================================

Establish independently authenticated allocation provenance for the selected original ROM worker's stack.

The specific unresolved requirement is a complete allocation descriptor establishing:

1. The actual lower stack boundary.
2. The authenticated upper boundary.
3. Total usable capacity.
4. Required alignment.
5. Guard or reserved regions, if any.
6. Exclusive allocation owner.
7. Relationship to the original architectural thread record.
8. Relationship to adjacent event queue and other storage.
9. Initialization provenance.
10. Source epoch and executable identity.
11. Run identity and allocation generation.
12. Valid lifetime.
13. Destruction, cancellation, reuse, or retirement behavior.
14. Sufficient non-overlap and alias guarantees.

Do not infer allocation ownership merely from address spacing, aligned pointers, observed stack access, or a plausible stack size.

An observed stack reservation is not an allocation descriptor.

A successful memory access is not proof of the complete allocation boundary.

A valid numeric thread ID is not proof of host-context ownership.

Separate reference runs are not evidence of a single continuous allocation-generation lifetime.

====================================================================
3. REQUIRED EVIDENCE RECOVERY
====================================================================

Recover and authenticate the exact Session 81 handoff and evidence, including:

- Session 81 FINAL_HANDOFF.json.
- Session 81 RECOVERY.md.
- Session 81 primary archive and detached anchor.
- Session 81 separately anchored delivery addendum.
- [REDACTED: private allocation evidence selector].
- The incomplete stack descriptor and explicit rejection.
- The rejected pre-SP-restoration checkpoint draft.
- Session 81 certified thread-start recipe and comparison results.
- Session 80 constructor and first-resume evidence.
- Session 76 manager evidence.
- Session 79 blocking, wakeup, and selected request evidence.

Use exact authenticated selectors, identities, counts, and digests.

Do not guess archive identities.

Do not rewrite inherited absolute paths by blindly replacing session numbers.

Do not execute archives, manifests, seals, or recovered evidence as scripts.

Restore fresh restricted persistent working copies in dependency order.

Verify the original archive and its actual authenticated contents before using them.

The archived evidence is not necessarily an independent complete backup.

====================================================================
4. SECURITY AND PREFLIGHT
====================================================================

Before substantive engineering work:

A. Verify all required predecessor seals.

Session 81 reported fifteen required predecessor seals covering Sessions 74 through 80, including the separately sealed coverage supplement.

Also authenticate Session 81's own primary and delivery addendum.

For each applicable archive, verify:

- Exact membership.
- File sizes.
- Content hashes.
- Ownership.
- Owner-only permissions.
- Detached anchor.
- Expected identity and dependency metadata.

Keep the distinctions between archive-integrity verification and independent evidence authentication.

B. Verify original ROM identity.

The ROM remains outside Git.

Read-only access only.

Do not publish, commit, or copy the ROM into a tracked location.

C. Verify toolchain.

- Pinned N64Recomp ABI 3 generator and matching header.
- Pinned source/submodule identities.
- Six reviewed ordered patches.
- Runtime lock.
- All 4,607 renderer lock entries.
- Hash-locked offline Python 3.14 packages.
- Required compilers and build tools.

D. Reproduce patches freshly.

No forced patch application.
No fuzz.
No undocumented hand edits.

E. Reproduce the current application build.

Use explicit paths and a fresh CMake/build directory where appropriate.

F. Preserve failures.

If a mandatory gate fails, record the exact diagnostic and block dependent work.

Do not describe a skipped or blocked verification as passed.

Do not bypass a security gate to improve the session's progress metrics.

====================================================================
5. BOUNDED STACK-ALLOCATION INVESTIGATION
====================================================================

This is the highest-priority engineering investigation, but it must not consume the entire session without new evidence.

Review original manager, thread constructor, registration, scheduler and worker entry relationships.

Look specifically for:

- Original stack storage declarations.
- Allocation or reservation operations.
- Initialization of the selected worker stack.
- Constant-address storage layout with independently authenticated boundaries.
- Static data or BSS layout evidence.
- Source-backed ownership relationships.
- Thread lifecycle and generation transitions.
- Valid reuse or retirement evidence.
- Any original operation proving the missing lower boundary.

Use the authenticated existing source epoch and original code identity.

Prefer a narrow source-backed proof over speculative whole-ROM exploration.

Do not confuse an inferred static address region with a proven exclusive allocation.

The Session 81 observation that the first worker instruction reserves 72 bytes, leaving SP 88 bytes below the supplied end, is only a local execution observation.

It does not prove the complete stack capacity.

IMPORTANT STOP CONDITIONS:

Stop this specific investigation when any of the following applies:

- Three genuinely distinct evidence attempts fail.
- Fifteen bounded investigation rounds are exhausted.
- Twenty minutes are spent in a single investigation cycle without new useful evidence.
- A security or provenance concern appears.
- Remaining work is repeating already resolved Sessions 77 through 81 findings.

Record exactly what was attempted, what was established, and which premise remains unsupported.

Do not spend the rest of Session 82 repeating failed allocation hypotheses.

====================================================================
6. STACK LEASE CHECKER
====================================================================

Review:

tools/stack_lease.py

And its fourteen Session 81 synthetic tests.

The checker validates normalized descriptor consistency and use constraints.

It does not independently authenticate the source of a descriptor.

It does not create a stack allocation.

It does not grant execution permission.

It does not register an original worker with the host scheduler.

If a complete authentic descriptor is discovered:

- Preserve source evidence.
- Establish its original identity and epoch.
- Validate both boundaries and capacity.
- Validate ownership and generation.
- Validate run and lifetime.
- Reject overlap and aliases.
- Reject premature or expired use.
- Reject invalid reuse.
- Reject unsupported queue or thread ownership.
- Add independent negative controls.
- Integrate only through explicitly reviewed gates.

If evidence remains incomplete:

- Preserve the rejection.
- Keep the descriptor incomplete.
- Do not substitute a guessed stack size.
- Do not manufacture a lease.

A conservative rejection is a correct engineering outcome.

====================================================================
7. NATIVE HOST ADAPTER GATES
====================================================================

Architecture D remains the selected approach.

Original architectural records and original sentinel-terminated queues must remain distinct from host-owned scheduling structures.

The upstream runtime uses null-terminated waiter queues and host-context pointers that are not layout-compatible with the original records.

Never pass original architectural records directly to upstream scheduling.

Never rewrite original sentinel queues to null merely to satisfy the host implementation.

Never fabricate original thread state, queue contents, interrupts, cache visibility, or device state.

A runnable adapter requires independently established:

- Root bootstrap.
- Separate host-context storage.
- Real host registration.
- Original record identity mapping.
- Stack lease.
- Queue and waiter leases.
- Request, destination, and completion ownership.
- Source epoch.
- Allocation generation.
- Failure and drain behavior.
- Cancellation and retirement.
- Correct invalidation.
- Instruction-budget unwind.

If any required premise remains unknown, the adapter must reject rather than proceed.

Do not claim host registration based on original worker execution in an isolated test harness.

Do not promote design-only adapter documentation into a runnable implementation without satisfying the gates.

====================================================================
8. REQUIRED PRODUCTIVE FALLBACK
====================================================================

If the stack-allocation investigation reaches its stop condition without a complete authenticated lease, move immediately to productive original-code work.

Priority order:

A. Identify the smallest remaining complete original bootstrap helper whose source boundaries and execution semantics can be independently established.

B. Prefer a helper directly relevant to root bootstrap, worker startup, scheduler transition, or a necessary original service.

C. If that is blocked, identify another bounded original function that can be safely certified and meaningfully advances the native path.

D. If suitable, extend a previously certified original helper to an additional authentic execution path, provided its dependencies are explicit and independently validated.

Do not create an arbitrary function count target.

Do not claim progress merely because another function was generated.

For every new candidate, require:

1. Complete original extent and entry.
2. Correct source epoch.
3. Authenticated same-run reference input and output.
4. Independently implemented comparison.
5. Full applicable CPU/HI/LO/Status.
6. Genuine FCSR.
7. All 64 raw floating-point words.
8. Ordered call and dispatch evidence.
9. Applicable RAM and device effects.
10. Explicit dependency handling.
11. Rejecting unresolved alternate paths.
12. Negative comparison mutations.
13. Instruction-budget unwind.
14. Exact reproduction recipe.

A successful isolated function is valuable but must be labeled ISOLATED ORIGINAL.

Only call it CONNECTED ORIGINAL if all connection and runtime ownership gates are independently satisfied.

Do not fabricate execution, references, or successful return behavior to increase coverage.

====================================================================
9. SOURCE EPOCH AND INSTALLED CODE SAFETY
====================================================================

Two existing startup replacements have superseded their initial bodies.

Preserve the distinction between:

- Original ROM body.
- Installed replacement.
- Superseded initial body.
- Authenticated source epoch.
- Executed code identity.

A live native source-epoch registry remains unimplemented.

Atomic publication remains unimplemented.

Overlap and direct-call invalidation remain unimplemented.

Compiled-storage retirement remains unimplemented.

Do not silently assume these facilities exist.

If a bounded implementation becomes possible, require independent tests for:

- Epoch identity.
- Invalid replacement ordering.
- Overlap rejection.
- Stale direct-call rejection.
- Retirement before active execution completes.
- Reuse after retirement.
- Budget unwind.
- Failure rollback.

Do not connect unsafe generated code merely because it compiles.

Unresolved indirect calls must reject.

====================================================================
10. GRAPHICS INVESTIGATION
====================================================================

Graphics is a secondary track, not permission to abandon the native execution objective.

Session 81 identified a static format incompatibility:

Diagnostic shader storage declaration:
R32ui.

Selected host storage texel-buffer view:
R16_UINT.

The reviewed backend passes shader bytes unchanged and maps the selected view directly.

Standalone SPIR-V validation cannot establish descriptor compatibility at binding time.

The format mismatch does not establish the cause of the earlier RADV compiler crash.

Do not assert that changing the view format fixes the crash.

Permitted bounded work:

- Authenticate the exact shader declaration and descriptor interface.
- Review the applicable Vulkan format requirements.
- Build a corrected offline diagnostic format contract.
- Preserve unchanged reference variants.
- Compare module, specialization, descriptor, push-constant and backend inputs.
- Add synthetic tests for mismatched and matching format contracts.
- Record precise compatibility assumptions.

Before any GPU replay or modified shader execution, require an explicit bounded diagnostic plan, verified inputs, resource limits, and preserved original baseline.

Do not edit production graphics paths based on an untested hypothesis.

Do not claim a color fix without a new authenticated replay.

Keep the existing color/depth results unchanged unless new evidence warrants an update.

Do not publish retained diagnostic PNGs or other media.

====================================================================
11. INCREMENTAL COVERAGE TRACKING
====================================================================

Reuse:

mt-us-census-v1

Do not run a full-ROM census automatically.

Do not invent a total function denominator.

Do not report percentages unless the denominator is independently established.

Start with Session 81's reviewed lower bounds:

10 complete functions plus one partial prefix.
481 compiled locations.
285 executed locations.
118 strictly validated locations.
167 connected locations.

Five complete strictly validated functions.
Five complete connected functions.

These figures describe the reviewed deduplicated subset, not all ROM functions or all historical project work.

Update only genuinely new or newly authenticated records.

Backfill older isolated extents incrementally, prioritizing:

- Complete function boundary.
- Source epoch.
- Canonical identity.
- Superseded source aliases.
- Duplicate elimination.
- Historical comparison qualifications.
- Current validation status.

Twelve legacy isolated extents remain for review.

Do not automatically classify all of them as complete functions.

Do not add legacy extent totals to the deduplicated coverage subset.

Regenerate the coverage Markdown from the reviewed ledger using the existing CLI workflow.

Run all incremental ledger tests.

If no valid new coverage exists, preserve the previous numbers and explain why.

====================================================================
12. VALIDATION AND TESTS
====================================================================

Run the normal verification command:

python3 tools/development.py verify

Preserve explicit full-mode requirements for verified external generator/header.

Run applicable:

- Repository tests.
- Generator regressions.
- CTest.
- Conventional native comparisons.
- ROM rejection tests.
- Unsupported-launch tests.
- FCSR and raw-FP comparisons.
- Instruction-budget unwind tests.
- RT64 state-only positive and negative controls.
- Stack lease tests.
- Coverage ledger tests.
- New candidate-specific negative controls.

Baseline expectation:

299 repository tests passed in Session 81.

Three generator regressions passed.

Nine CTest and four conventional comparisons passed in the Session 81 baseline.

These are historical results, not permission to assume current tests pass.

Report current observed results separately.

Keep SKIPPED, BLOCKED, FAIL, and PASS distinct.

Cross-build whole-RAM parity remains FAIL until independently resolved.

General determinism remains UNKNOWN until established.

Do not suppress a failure merely to make the session appear successful.

====================================================================
13. NETWORK AND SESSION RESILIENCE
====================================================================

[REDACTED: owner local connectivity incident context]

This is operational context, not evidence of an engineering defect.

Avoid unnecessary network-intensive work.

Do not repeatedly download unchanged pinned dependencies.

Preserve incremental local checkpoints so that a temporary remote-control interruption does not destroy completed analysis.

If the remote-control connection drops:

- Preserve local evidence and working files.
- Avoid duplicate overlapping tasks.
- Resume from the last authenticated checkpoint.
- Recheck tool state before retrying an operation.
- Do not start a second session automatically.
- Do not interpret a message timeout as proof that a tool command failed.

Do not modify network configuration or restart the Codex daemon without owner authorization.

====================================================================
14. PUBLIC DOCUMENTATION
====================================================================

Maintain the existing public roadmap and development diary.

Publish only normal Session 82 updates.

Expected public materials include:

- Session 82 diary entry.
- Session 82 owner prompt.
- Prompt index update.
- Incremental coverage summary, if applicable.
- Honest milestone status.

Public writing should be understandable to ordinary gamers while preserving the technical distinctions necessary to avoid misleading claims.

Explain:

- What original game code was actually executed.
- Whether it ran in isolation or in the connected native path.
- What was newly proven.
- What remains unknown.
- Whether there is a playable game or native frame.
- What the next engineering blocker is.

Preserve the authentic Session 82 prompt with localized security redactions where necessary.

Mark redactions visibly.

Review source and public candidate against one another.

Do not fabricate or substantially rewrite the original prompt to make it appear more polished.

IMPORTANT OWNER INSTRUCTION:

Do not perform retrospective public prompt diary audits, historical diary repairs, or revisions of earlier session prompts.

Leave Sessions 1 through 81 historical entries intact unless a separate explicit owner instruction authorizes a change.

This restriction does not prevent adding the new Session 82 entry or updating the current cumulative coverage summary.

No screenshots, video, ROM data, binaries, private traces, or proprietary evidence may be published.

====================================================================
15. PRIVATE ENGINEERING DELIVERY
====================================================================

Update the existing private engineering branch only.

Expected documentation:

[REDACTED: private engineering document path]
[REDACTED: private engineering document path]

Also update applicable status, coverage and engineering documents.

Record:

- Starting baseline.
- Archive and security verification.
- Exact new evidence.
- Failed hypotheses.
- Original function identities.
- Source epochs.
- Isolated and connected classifications.
- Native and independent comparisons.
- Stack ownership outcome.
- Graphics outcome.
- Coverage changes.
- Test results.
- Remaining blockers.
- Next-session recommendations.

Inspect every staged file before committing.

Check for:

- ROM or proprietary bytes.
- Extracted assets.
- Disassembly.
- Translated proprietary code.
- Private reference traces.
- Private source maps.
- Secrets or credentials.
- Sensitive prompt material.
- Accidental temporary outputs.
- Unexpected file additions.

Commit and push only the existing authorized private investigation branch.

Read back all changed remote files and verify their identities.

Record actual GitHub CI results, distinguishing success from pending or failure.

Reconcile the existing issue #2 and eight milestones without closing unverified work.

Do not merge to main.

Do not create a release.

Do not publish binaries.

Do not change repository visibility or collaborator permissions.

====================================================================
16. EVIDENCE PRESERVATION
====================================================================

Keep original evidence and generated proprietary artifacts outside Git.

Use restricted, owner-only persistent storage.

Maintain:

- Source identity.
- Exact commands.
- Tool versions.
- Inputs.
- Outputs.
- Independent comparisons.
- Failure diagnostics.
- Negative controls.
- Provenance.
- Resource budgets.
- SHA-256 manifests.
- Detached anchors.

Use bounded logs and captures.

Reference emulator execution must remain within the established 300-second limit.

Maintain network isolation and credential exclusion where required.

Do not mutate guest state to manufacture success.

Do not import emulator checkpoint RAM into conventional native startup.

Do not forge interrupts, queue messages, thread states, cache visibility or device events.

Do not use an unverified archive as a trusted executable.

====================================================================
17. SESSION PRIORITY AND TIME MANAGEMENT
====================================================================

Prioritize work in this order:

PRIORITY 1:
Recover and authenticate the missing stack-allocation provenance.

PRIORITY 2:
If that fails within the bounded investigation, certify a useful complete original bootstrap helper or other high-value original function.

PRIORITY 3:
Improve source-epoch and native connection safety where independently provable.

PRIORITY 4:
Incrementally update authenticated coverage records.

PRIORITY 5:
Establish a corrected offline graphics format contract.

PRIORITY 6:
Complete tests, security checks, evidence preservation, and verified delivery.

Do not sacrifice required security or final delivery merely to continue open-ended investigation.

Do not count additional tests, documentation, or analysis as a substitute for executable native progress.

A truthful blocked result is preferable to an unsupported success claim.

====================================================================
18. SESSION 82 COMPLETION CRITERIA
====================================================================

The session may be considered complete only after:

1. Mandatory recovery and preflight gates are evaluated.
2. The stack-allocation investigation reaches a documented outcome.
3. A complete lease is authenticated or its missing premises are explicitly preserved.
4. If blocked, the productive fallback is attempted within the session's bounded resources.
5. Any new original execution is independently compared and correctly classified.
6. Coverage is updated only with supported evidence.
7. Applicable verification is run and actual results recorded.
8. Sensitive and proprietary materials remain outside Git.
9. The private engineering report is completed.
10. The next-session handoff is prepared.
11. Normal new-session public documentation is reviewed and delivered.
12. Private branch changes are reviewed, committed, pushed and read back.
13. Actual CI status is recorded.
14. Final evidence and delivery receipts are sealed as appropriate.

If an environmental or security blocker prevents completion, stop safely and report the partial outcome. Do not claim complete delivery.

====================================================================
19. REQUIRED FINAL REPORT TO OWNER
====================================================================

At the end of Session 82, provide a clear summary containing:

A. Executive result
What materially changed.

B. Original code progress
New complete functions, native executions, connected routines and comparison outcomes.

C. Stack-allocation result
What is proven, what remains unknown and whether a host adapter is now permitted.

D. Graphics result
Any new authenticated format-contract or GPU findings.

E. Coverage
New lower bounds and whether percentages remain unknown.

F. Verification
Current repository tests, generator tests, build checks and known failures.

G. Security and delivery
Archive seals, private/public commits, CI states and any blocked steps.

H. Next session
The single highest-value engineering objective for Session 83.

Use plain English first, then precise technical details.

Do not claim the game is playable or producing a native first frame unless actually demonstrated.

====================================================================
20. START SESSION 82
====================================================================

Begin by reading the current private handoff and verifying the Session 81 delivery.

Authenticate all required predecessor evidence and toolchain state.

Investigate the original worker stack allocation with the specified strict stop conditions.

If authentic allocation provenance remains unavailable, switch promptly to productive original-code certification.

Preserve incremental coverage, architecture D, and all security boundaries.

Complete the verified Session 82 engineering and public documentation delivery.

Do not automatically begin Session 83.

END OF SESSION 82 MASTER PROMPT