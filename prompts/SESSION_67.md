# Session 67 — Owner prompt

Status: completed with limited progress. The original ownership proof remains
incomplete; the [development diary](../docs/PROGRESS.md#session-67) records the
results. This is the authentic owner-issued prompt with visible redactions.
The exact source is preserved privately. These are requested objectives, not
claims of achieved game execution. No conversation or hidden instructions appear.

---

# ITALIAN PLUMBER PONG
# SESSION 67 MASTER PROMPT
# Graphics Buffer Ownership, SP/DP Synchronization,
# and the Path Toward Live RT64 Execution

You are Codex, continuing development of Italian Plumber Pong, an experimental native PC recompilation of Mario Tennis (USA) for Nintendo 64.

This is SESSION 67.

Work autonomously within the established project security, verification, evidence-preservation, and publication boundaries.

PRIMARY OBJECTIVE:

Certify the original graphics-task pool and referenced-buffer lifetime across SP completion, RT64 parsing, and DP completion.

Use independently checked evidence to determine whether the pinned runtime's current completion ordering is safe, or whether a narrowly scoped compatibility adapter is necessary.

If and only if the ownership contract is established and verified, enable the smallest authentic connected graphics submission path.

Do not manufacture graphics output or treat a captured task as live game execution.

A first rendered frame is a stretch goal, not an acceptance requirement.

============================================================
1. REPOSITORIES AND ENVIRONMENT
============================================================

[Withheld: private project configuration, recovery records, original-code findings, detailed evidence or closeout instructions.]

============================================================
2. MANDATORY PREFLIGHT AND RECOVERY
============================================================

[Withheld: private project configuration, recovery records, original-code findings, detailed evidence or closeout instructions.]

============================================================
3. VERIFIED SESSION 66 BASELINE
============================================================

[Withheld: private project configuration, recovery records, original-code findings, detailed evidence or closeout instructions.]

============================================================
4. THE CENTRAL SESSION 67 PROBLEM
============================================================

[Withheld: private project configuration, recovery records, original-code findings, detailed evidence or closeout instructions.]

============================================================
5. ORIGINAL PRODUCER AND CONSUMER ANALYSIS
============================================================

[Withheld: private project configuration, recovery records, original-code findings, detailed evidence or closeout instructions.]

============================================================
6. FORMALIZE THE OWNERSHIP CONTRACT
============================================================

[Withheld: private project configuration, recovery records, original-code findings, detailed evidence or closeout instructions.]

============================================================
7. SP/DP COMPLETION STRATEGY
============================================================

Compare the recovered original lifetime model with the pinned upstream runtime and RT64.

Evaluate these possibilities without assuming the answer:

A. Existing SP-before-send_dl ordering is safe because original ownership constraints prevent reuse.

B. A narrowly scoped post-parse SP notification adapter is necessary.

C. A stronger input-lifetime or buffer-ownership mechanism is necessary.

D. The original producer/consumer evidence remains insufficient to select a safe strategy.

If a compatibility adapter is justified:

- Keep the change narrowly scoped.
- Preserve original observable ordering where required.
- Avoid changing global upstream behavior.
- Do not invent SP or DP messages.
- Do not signal completion before the corresponding work is complete.
- Preserve original queue ownership and message values.
- Reject unknown task types or unsupported ownership states.
- Verify both normal and adversarial scheduling.
- Ensure errors cannot leave original threads falsely awakened.

Do not implement a timing workaround merely because it allows execution to advance.

============================================================
8. IMPLEMENT FOCUSED OWNERSHIP REGRESSIONS
============================================================

Add tests that directly exercise the identified lifetime contract.

Where supported by recovered evidence, test:

- A second producer becoming runnable after SP.
- A producer attempting to reuse a task-pool record.
- Descriptor reuse while nested display-list memory remains referenced.
- Callback-triggered submission.
- Outstanding-work counter boundaries.
- Framebuffer wait and release ordering.
- SP and DP queue delivery.
- Priority scheduling and wakeup.
- Aliased task buffers.
- Rejected early reuse.
- Safe reuse after the proven completion boundary.
- Failure and cancellation behavior.

Distinguish:

SYNTHETIC MODEL TESTS:
Useful for checking the proposed contract.

ORIGINAL-CODE TESTS:
Execute recovered original Mario Tennis instructions.

UPSTREAM INTEGRATION TESTS:
Exercise real N64ModernRuntime and RT64 behavior.

INDEPENDENT REFERENCE TESTS:
Verify original CPU state, ordered traces, and memory effects.

Do not present a synthetic model as proof that original game code follows that model.

Prefer the smallest tests that expose the actual ownership hazard.

============================================================
9. CONDITIONAL LIVE GRAPHICS INTEGRATION
============================================================

Only after the ownership and completion contract is established:

Attempt the smallest authentic connected graphics submission path.

Required evidence:

1. Original Mario Tennis code executes and creates the task.

2. Task descriptor and referenced memory identities are verified.

3. Original producer ownership is established.

4. All relevant inputs remain valid through RT64 consumption.

5. Real RT64 processes the task.

6. Original SP/DP consumers receive justified notifications.

7. Original scheduling and wakeups remain correct.

8. CPU, FP, ordered trace, and full game RAM match the independent reference.

9. No unsupported producer or alias is silently admitted.

10. No synthetic game progress is substituted.

If this cannot be established, leave asynchronous submission disabled and report the precise blocker.

Do not replay the captured task and call it live production.

Do not substitute synthetic display lists or a fabricated framebuffer.

============================================================
10. OPTIONAL STARTUP PROGRESS
============================================================

[Withheld: private project configuration, recovery records, original-code findings, detailed evidence or closeout instructions.]

============================================================
11. REQUIRED VERIFICATION
============================================================

[Withheld: private project configuration, recovery records, original-code findings, detailed evidence or closeout instructions.]

============================================================
12. SECURITY REQUIREMENTS
============================================================

Preserve the established ROM and proprietary-asset isolation.

Never publish:

- The Mario Tennis ROM
- Extracted copyrighted game assets
- Proprietary generated game code
- Private RAM snapshots
- Private disassembly or traces
- Restricted address mappings
- Sensitive filesystem paths
- Private evidence archives
- Credentials or secrets

Only approved project-owned host code, synthetic tests, configuration, and sanitized documentation may enter Git.

Public CI remains synthetic-only.

Keep private technical evidence outside Git.

Do not change repository visibility or permissions.

Do not merge into main.

Do not publish a release, executable, screenshot, or video without separate approval.

Maintain the existing security and staged-history checks.

============================================================
13. DEVELOPMENT WORKFLOW
============================================================

Follow the established one-blocker workflow:

1. Recover existing evidence.
2. Identify the smallest unresolved dependency.
3. Form a testable ownership hypothesis.
4. Investigate the relevant original code and upstream behavior.
5. Implement a focused test or justified adapter.
6. Verify against independent evidence.
7. Record the result.
8. Continue only when the dependency is satisfied.

Do not repeatedly pursue an unsupported hypothesis.

Preserve useful failed attempts privately.

Stop on unresolved ownership, unknown callback behavior, repeated failures, resource limits, or security uncertainty.

A clear, independently supported negative result is preferable to an unsafe implementation.

============================================================
14. SESSION 67 DOCUMENTATION
============================================================

[Withheld: private project configuration, recovery records, original-code findings, detailed evidence or closeout instructions.]

============================================================
15. PRIVATE PRESERVATION
============================================================

[Withheld: private project configuration, recovery records, original-code findings, detailed evidence or closeout instructions.]

============================================================
16. GITHUB AND PUBLIC DOCUMENTATION
============================================================

[Withheld: private project configuration, recovery records, original-code findings, detailed evidence or closeout instructions.]

============================================================
17. FINAL HANDOFF
============================================================

[Withheld: private project configuration, recovery records, original-code findings, detailed evidence or closeout instructions.]

============================================================
18. EXECUTION AUTHORIZATION
============================================================

You are authorized to:

- Investigate the existing private project evidence.
- Implement reviewed project-owned code and tests.
- Run bounded native builds and verification.
- Preserve private evidence.
- Commit and push approved changes to the existing private branch.
- Update the authorized public documentation.

You are not authorized to:

- Publish proprietary game data.
- Change repository visibility.
- Merge into main.
- Publish a release or media.
- Disable verification or security protections.
- Fabricate original execution or graphics output.
- Begin Session 68.

Begin with the mandatory Session 66 preflight and recovery.

Then investigate the smallest unresolved graphics ownership dependency.

Proceed autonomously within the established boundaries.

Prioritize evidence-backed progress toward live graphics execution over speculative features.