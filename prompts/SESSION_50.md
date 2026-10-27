# Session 50 — Authentic owner prompt with visible redactions

Source: the owner-supplied Session 50 attachment, preserved byte-for-byte privately
and independently reread. Marked spans are withheld; no private discussion or
original-game evidence is included. The diary records what actually ran.

```text
# ITALIAN PLUMBER PONG — SESSION 50
# Autonomous Original-Game Integration and First Boot Attempts

You are Codex working on the existing private Italian Plumber Pong Nintendo 64 Mario Tennis (USA 1.0) native recompilation project, on the user's ASUS ROG Ally running Bazzite.

PROJECT ROOT: [REDACTED: PRIVATE PROJECT PATH]
PRIVATE ORIGINAL-GAME MATERIALS ROOT: [REDACTED: PRIVATE MATERIAL ROOT]
EXPECTED REPOSITORY: [REDACTED: PRIVATE REPOSITORY]
EXPECTED BRANCH: [REDACTED: PRIVATE BRANCH]

## OWNER AUTHORIZATION — NEW IN SESSION 50
The owner explicitly authorizes you to inspect and process their locally stored Mario Tennis ROM and existing private original-game materials; perform local analysis and code generation; compile and execute locally generated original-game-derived code; and attempt bounded, local Mario Tennis startup/boot on the Ally. This is authorization for local development only, not for redistribution or remote transmission. Do not interpret it as permission to weaken the privacy controls below.

## PRIMARY GOAL
Make the largest verifiable step toward booting the actual Mario Tennis game on this Ally, ideally obtaining a locally executed original-game startup path or first frame. Prefer working code, builds, runtime traces, and observed behavior over reports and abstract proof. A boot or frame is an aspiration, not a claim to manufacture.

## NON-NEGOTIABLE PRIVACY / SAFETY
- Never upload, commit, push, paste into remote AI context, or transmit original ROM bytes, proprietary game assets, disassembly dumps, extracted code/data, generated ROM-derived source/binaries, or private sensitive evidence to GitHub, CI, remote model services, or third-party servers. Keep them entirely local and outside tracked directories.
- The project may already have stricter local controls; honor them. Before processing original materials, identify the applicable local privacy boundaries and use only permitted local paths and tooling. If any step would transmit original material to a remote service, do not perform it.
- Only project-owned source, tests, safe tooling, and sanitized high-level documentation may be committed or pushed after existing scans/review. If a generated artifact is plausibly ROM-derived, treat it as private by default.
- No network downloads or dependency upgrades without explicit approval. Do not change sandbox/approval policy or bypass controls. Avoid destructive commands, privilege escalation, or changing system settings.
- Local execution is authorized, but constrain it with timeouts, resource limits where practical, and isolated working directories. Do not run unknown privileged code. Do not launch into Steam Gaming Mode automatically; begin with Desktop Mode / CLI execution.
- Do not include private paths, ROM hashes, disassembly, code snippets, or game data in public-facing reports. Existing local private logs can retain details under established controls.

## WORKING STYLE: AUTONOMOUS AND IMPLEMENTATION-FIRST
- Make routine technical decisions yourself. Inspect, modify, compile, test, run, diagnose, and iterate through multiple cycles without requesting approval for ordinary engineering steps.
- Do not spend the session rereading every historical archive, repeating seals, or writing elaborate feasibility reports. Read only what materially helps current implementation or security.
- Reuse the established reference library locally, existing toolchain, generated-function work, and test harness. Don't restart the project or rebuild already working infrastructure without evidence of need.
- Do not let previous unapproved *design proposals* block newly authorized local implementation. Distinguish actual safety failures from historical process gates; preserve technical correctness and security.
- When something fails, capture concise local diagnostics, hypothesize, patch, and retry. If a true blocker arises, switch to the next most useful implementation task rather than spending the whole session on paperwork.

## REQUIRED STARTUP CHECK
1. Confirm working directory, branch, Git status, and origin. Preserve uncommitted user changes; don't overwrite them.
2. Read docs/SESSION_49_REPORT.md, current progress, and the relevant runtime/runner code. Verify what actually exists in the checkout, not just what prior reports claim.
3. Locate local original-game inputs without copying them into the repository. Confirm that local processing will not trigger uploads, telemetry, or remote builds. Use existing project-approved local tools and reference materials.
4. Establish a small reproducible baseline: existing synthetic tests and build/run entry points. Keep the pre-existing passing tests green as you work.

## ENGINEERING PRIORITIES (ADAPT BASED ON EVIDENCE)
A. Bridge Session 49's checked-memory owner to the actual generated/native execution path. The checked synthetic adapter alone is not sufficient; inspect the real raw ABI, backing representation, address translation, lifetimes, alignment, and state transitions. Implement a sound local integration strategy rather than declaring it proven by synthetic tests.
B. Exercise real original-game-derived function execution locally, starting with a bounded, well-chosen function or startup segment. Capture actual outcomes, not inferred results. Instrument nested calls/returns, register/state propagation, and error handling where needed.
C. Advance toward coherent startup: map the actual boot entry, initial CPU/memory state, necessary libultra/OS services, dispatch, graphics setup, and dependencies. Implement minimal accurate runtime support as needed. Do not hardcode fabricated success or frame output.
D. If the runtime reaches a meaningful startup point, try a bounded local game boot in Desktop Mode. Log failures, crashes, missing symbols/services, and progress markers; iterate. A first frame or title screen is an excellent outcome, but not required to report genuine progress.
E. Add focused regression tests around every resolved integration defect, including negative cases, and retain the existing synthetic test coverage.

## EXECUTION AND TIME BUDGET
Target up to approximately 2 hours of active engineering for this session, subject to actual CLI/session constraints. Checkpoint after meaningful progress. If execution time or context is limited, prioritize a tested implementation and clean handoff. Do not claim to have run a command, inspected a ROM, reached a frame, or fixed a defect unless it actually happened.

## CHECKPOINTS AND GIT
- Commit useful, safe, project-owned changes to the existing private branch, after running the established pre-push/privacy checks. Push only when permitted by current Git approvals and when scans pass. Do not publish private ROM-derived outputs even to a private repository.
- Keep private local artifacts and detailed evidence in the existing private archive area, outside Git. Preserve prior checkpoints without unnecessary copying or rereading.
- Avoid opening unrelated issues or expanding process bureaucracy. A concise status report is enough.

## SESSION 50 HANDOFF
Write docs/SESSION_50_REPORT.md (sanitized, no proprietary material) and update progress with:
- Actual code changes and commands/tests executed
- Whether original ROM was processed locally (yes/no) and whether original-derived code was executed locally (yes/no), without exposing private material
- Furthest *observed* startup/boot milestone, including explicit 'not reached' where applicable
- Specific integration blockers and next implementation step
- Test pass/fail totals and any untested limitations
- Commit/push status and privacy scan results

SUCCESS IS MEASURED BY ACTUAL ORIGINAL-GAME INTEGRATION AND RUNNING CODE, NOT DOCUMENTATION VOLUME. Begin now; work autonomously within these boundaries.
```
