# Session 55 — Authentic owner prompt, visibly redacted

Status: completed bounded review; no host adapter or game frame claimed.
Source: the exact owner-supplied Session 55 attachment, preserved privately.
Private repository/branch, documentation paths and execution metrics are visibly
withheld. This is the issued prompt, not a claim that its optional prototype ran.

---

ITALIAN PLUMBER PONG | CODEX SESSION 55
Goal: Find a verified game-facing initialization/service boundary around the current SI polling path and determine whether a PC-native host replacement can safely accelerate first genuine boot.
Time budget: Approximately 2 hours. Work autonomously within existing approvals and constraints. Do not exceed the budget pursuing tangents.

PROJECT CONTEXT
Repo: [REDACTED: private development repository]
Branch: [REDACTED: private investigation branch]
Start by reading [REDACTED: private Session 54 report path], [REDACTED: private handoff path], [REDACTED: private architecture research path], [REDACTED: private reference-index path] and [REDACTED: private SI/PIF notes path]. Follow their actual evidence and local archive pointers rather than assuming a new environment. Session 54 verified 157 tests and three synthetic generator fixtures. Session 53's controlled original execution stopped before a repeated SI read after [REDACTED: private execution metrics]. Neither constitutes a coherent cold boot or a frame.

OWNER DIRECTION
The goal is a native PC game, not a complete N64 emulator. Prefer verified game-facing service replacements and established PC-native runtime interfaces over painstakingly reproducing irrelevant original console initialization. Preserve the existing static-recompilation investment and validated work. We are targeting a first real, recognizable Mario Tennis screen, not a mockup or a forced skip to an arbitrary later state. Linux/Bazzite first, Windows next. Aim for original gameplay behavior; higher display refresh must not accelerate game simulation.

PRIMARY TASK: ONE BOUNDED SERVICE BOUNDARY
1. Verify the Session 54 sealed research archive and relevant Session 53 evidence/identities before private original-dependent work. Use a fresh restricted workspace; never modify sealed archives. Preserve generator pin, five submodule revisions, six ordered patches, and ABI3 unless a separate, justified proposal is made.
2. Trace the minimum original-game caller/callee and dataflow needed to identify a genuine initialization/service boundary enclosing the observed SI polling path. Use retained local evidence and bounded analysis. Distinguish confirmed function boundaries from provisional ones.
3. Document the complete proposed replacement contract: call site(s), calling convention/ABI, inputs, outputs, registers, stack, RAM/global writes, timing, return/handoff, error/interrupt behavior, ownership, and all downstream state consumers that must remain valid. Explicitly mark UNKNOWNs.
4. Crosswalk the contract against N64ModernRuntime and the Wave Race implementation reviewed in Session 54, using specific pinned source locations. Determine whether a host service can reproduce the required observable effects without simulating the original raw SI polling loop. Distinguish existing upstream functionality from game-specific glue and any assumptions about SDK version.
5. Stop at the first material unmatched effect or ambiguous boundary. Do not invent an SI idle/completion observation, arbitrary DMA/PIF contents, firmware state, or an unsupported return value. Do not jump ahead in original execution to manufacture a screen.
6. If and ONLY if the boundary and replacement effects are independently justified, create a small isolated synthetic/host-adapter proof of concept with negative tests, without replacing the production runtime. A prototype is optional, not a success requirement. Do not install or repin dependencies simply to force a demo.

SECONDARY WORK, ONLY IF TIME REMAINS
- Note the smallest practical next integration test toward a genuine first frame, including what would count as success and what must still be measured.
- Keep the three reference projects and SI/PIF manuals indexed in the private technical library; add original, concise findings and source links, not copied manuals or third-party source bodies.
- Record a short UI backlog note: Ship of Harkinian/libultraship-style controller-operable in-game settings are desired; evaluate licensed LUS components, independently authored ImGui UI, or RecompFrontend only after its redistribution permission is established. Do not change runtime merely for the UI.

COPYRIGHT, LICENSING AND PRACTICAL SECURITY
Do not commit or publish ROMs, original Nintendo assets, extracted game content, generated game-specific bodies/binaries, or other protected original material. Keep private original-dependent evidence local, not in GitHub/CI/model-facing reports. End-user ROM processing should remain local in the eventual distributed app. Check licenses and transitive implications before proposing any third-party code adoption; studying architecture is not permission to copy. Ordinary local paths and harmless compiler logs are not incidents. Focus security attention on actual protected material and credentials. Do not allow low-risk documentation hygiene to consume the session.

VERIFICATION AND REPORTING
- Run appropriate existing tests and any new focused tests; report observed counts and failures precisely. Never imply a playable build, genuine frame, complete function or successful host integration without direct evidence.
- Maintain a clear VERIFIED / CONDITIONAL / UNKNOWN / BLOCKED distinction.
- Preserve immutable previous archives, make a new evidence archive with inventory and independent verification if required by the established workflow.
- Update the private technical report, [REDACTED: private handoff filename], and approved public-facing sanitized diary/roadmap/prompt index as appropriate. Commit and push only reviewed, allowed project-owned changes on the current branch; check observed Git/CI receipts and report actual results. Do not publish protected game-derived details.
- End with one crisp recommendation for Session 56: the single highest-leverage next experiment or missing contract item. Stop after roughly two hours even if blocked; summarize rather than expanding into an open-ended hardware reconstruction.

SUCCESS CRITERION
A source-backed, independently checked boundary/contract and an explicit supported-versus-missing host-runtime crosswalk sufficient to make a concrete go/no-go decision for a subsequent isolated integration test. If the boundary cannot be established, identify the exact missing evidence and smallest next verification step. No first-screen claim unless a genuine frame was actually rendered.
