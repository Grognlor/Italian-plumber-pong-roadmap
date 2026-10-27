# Session 49 — Authentic owner prompt with visible redactions

Source: the owner-supplied Session 49 attachment, preserved byte-for-byte privately
and independently reread. Marked spans are withheld; no chat or reconstructed
instructions are included. The diary records the actual implementation results.

```text
SESSION 49 — ITALIAN PLUMBER PONG
AUTONOMOUS DEVELOPMENT WORKFLOW RESET

Project: Italian Plumber Pong (Mario Tennis N64, USA 1.0)
Repository: [REDACTED: PRIVATE REPOSITORY]
Branch: [REDACTED: PRIVATE BRANCH]
Local repository: [REDACTED: PRIVATE PROJECT PATH]
Private game-material root: [REDACTED: PRIVATE MATERIAL ROOT]

OWNER AUTHORIZATION FOR THIS SESSION
The owner explicitly changes the project's development preference from documentation-first, one-gate-per-session research to PLAYABILITY-FIRST autonomous engineering. You are authorized to make ordinary technical design choices; edit project-owned source, build scripts, tests and local tooling; compile, run, debug and iteratively fix synthetic/project-owned code; and create multiple commits in this session. Work in bounded, testable increments. Do not stop merely to request approval for routine implementation details. Existing narrow session-handoff restrictions are superseded only to the extent this new owner authorization explicitly allows. Maintain clear records of what is authorized and what is not.

IMPORTANT AUTHORIZATION BOUNDARY
This prompt does NOT itself grant permission to inspect, extract, copy, execute, or process the proprietary Mario Tennis ROM, game assets, or original executable code. It does NOT authorize running original-game-derived functions or distributing original assets. Before any of those steps, prepare a concise, concrete local-only request explaining exactly what would be accessed or run, how data would be contained, and what success/failure would mean, and ask the owner for explicit approval. Once the owner approves a clearly defined class of local ROM operations, avoid re-asking for each routine action within that approved scope. No authorization to change access control, network policy, sandbox configuration, filesystem permissions, visibility, or secrets handling without explicit approval.

NONNEGOTIABLE SECURITY AND PRIVACY
- Keep ROMs, original game bytes, extracted game assets, private source evidence, private technical addresses/operands, credentials, and personal paths out of GitHub, public logs, CI, release artifacts, issue comments and PRs.
- Never upload or transmit ROM or extracted game material to AI services, remote build systems, or external sites. Keep original-game processing local to the Ally after separate owner authorization.
- Preserve repository privacy and .gitignore safeguards. Before each push inspect staged content, diffs and tracked paths for leaks. Do not assume that a private GitHub repository is an acceptable location for copyrighted game bytes.
- Do not weaken security controls or bypass tool approvals. Stop on a genuine leak risk or unclear owner permission.
- Preserve old evidence and commits; no destructive resets, history rewrites or deletion of previous archives.

STARTUP AND PRIOR WORK
1. Verify expected repository, branch, origin, clean starting status, toolchain and relevant existing project instructions. Read docs/SESSION_48_REPORT.md, docs/NEXT_SESSION_PLAN.md, current readiness and security docs. Treat Session 48's 4 MiB ipp::Rdram allocation as a PROPOSAL, not an approved safety certificate. Do not pretend P1 is ready.
2. Review current actual source and build/test structure. Identify what can be built and exercised immediately using synthetic data. Reuse the pinned N64Recomp toolchain and existing infrastructure where practical; do not repin or download dependencies without approval.
3. Briefly record a practical milestone ladder: (A) reproducible native project-owned executable or harness, (B) verified memory and call mechanics with synthetic fixtures, (C) owner-authorized local original-function execution, (D) first visible boot/frame, (E) input, graphics, audio and playable game. Report objective pass/fail evidence, not inflated completion percentages.

AUTONOMOUS ENGINEERING OBJECTIVE
Make the largest safe, verifiable improvement toward a playable native Mario Tennis build possible within the current permissions. Do not spend this session writing another proposal about why a design cannot be implemented. Implement and test the synthetic, project-owned foundation that is possible now. In particular:
- Implement a controlled, project-owned memory owner/harness and explicit bounded guest-address-to-host-span admission for synthetic test cases. Choose a reasonable documented backing extent for synthetic tests, such as 4 MiB, but do not label that choice as approved for actual game execution. Ensure checks occur before unsafe pointer formation. Account for the full helper footprint, address translation, alignment, typed access/aliasing/object lifetime and failure handling; if raw helper semantics cannot be made safe without altering ABI, isolate them behind a checked adapter or use a byte-safe synthetic implementation, with tests that clearly distinguish simulation from actual ABI validation.
- Make memory lifetime and no-reallocation assumptions enforceable where feasible; otherwise encapsulate and verify them. Add meaningful positive, negative and boundary tests, including deliberately invalid addresses, near-end spans, misalignment and failure paths.
- Build an executable native synthetic smoke-test target (if one does not exist) and run it. Integrate tests with existing project test commands. Do not claim a synthetic harness is a playable game.
- Investigate the next real technical integration blocker only after completing a concrete implementation increment. Where multiple valid engineering approaches exist, choose one, explain briefly and proceed.
- Keep changes small enough to diagnose and revert. Iterate build → test → fix. Do not modify pinned third-party source or ABI without owner permission.

EFFICIENCY AND AUTONOMY
- Do not repeat large archival provenance sweeps, all-history rereads, sealed-evidence rebuilds or extensive ceremonial preflights unless a specific project security requirement or observed change makes them necessary. Perform proportionate integrity checks and keep existing evidence untouched.
- Prefer direct tests and working code over reports. Do not spend an entire session on a single decision sheet.
- Make local commits at coherent checkpoints, push only sanitized project-owned work to the expected private branch after review. If a repository policy conflicts with this new owner directive, identify the exact conflict, honor higher-priority security restrictions and seek clarification only for the conflict.
- You may work through multiple implementation/debug cycles autonomously. Use a practical time budget of up to 90 minutes of active work; at the end, finish the current safe checkpoint and report. Stop early for genuine permission, safety, or environment blockers. Avoid runaway loops; cap repeated failed approaches at three before changing strategy.

REQUIRED END-OF-SESSION OUTPUT
Provide a concise report with: actual source files changed; commands run and tests passed/failed; executable artifact and how to launch it if produced; measurable technical progress toward native execution; any outstanding safety/ROM approval request; Git commit and push status; known risks; and a concrete next engineering step. Update docs/SESSION_49_REPORT.md and docs/NEXT_SESSION_PLAN.md without exposing sensitive material. Do not claim original game progress when only synthetic code ran. Preserve owner control over original-ROM access and execution.

SUCCESS CONDITION
A working, tested native synthetic execution/memory integration increment with code committed, or an accurately documented specific technical blocker after real implementation attempts. This is a development session, not a paperwork session.
```
