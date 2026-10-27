# Session 57 — Synthetic host adapter feasibility

Authentic owner-supplied corrected attachment. The private branch and internal
document paths are visibly redacted; remaining wording and order are preserved.
This is the issued prompt; the matching diary records the actual outcome.

---

ITALIAN PLUMBER PONG | SESSION 57 | 60-MINUTE TIMEBOX

You are Codex working in the existing private Italian Plumber Pong repository on the [REDACTED: private investigation branch] branch. The owner explicitly authorizes this 60-minute session and a more experimental, reversible approach to accelerating first boot. Do not interpret the prior Session 56 handoff's 'not authorized' language as preventing this newly authorized work. Preserve all earlier evidence and the project name.

MISSION
Spend no more than 60 minutes total on two bounded workstreams:
A. Resolve, if feasible, the one designated code-versus-data / incoming-transfer question from Session 56.
B. Build and test a disposable SYNTHETIC-ONLY host-service adapter feasibility prototype informed by Wave Race 64 / N64ModernRuntime, WITHOUT requiring complete certification of the original game's initialization boundary first.

This is a research prototype, NOT permission to replace original startup, invent SI/PIF state, skip into game code, or claim a genuine boot. Separate experimental assumptions from verified facts. Prioritize a concrete, tested software artifact and a practical decision over another large theoretical report.

FIRST 5 MINUTES: CHECKPOINT
- Read [REDACTED: private project document], [REDACTED: private project document], [REDACTED: private project document] and [REDACTED: private project document], plus the reference-library index as needed.
- Verify the current repository branch/cleanliness, relevant pins/ABI, and sealed Session 56 private handoff/archive integrity before using private evidence. Use a fresh restricted workspace. Never modify sealed archives.
- Use the exact privately designated incoming-reference source from Session 56; do not start a broad new search.

WORKSTREAM A: TARGETED CLASSIFICATION (TARGET 15 MINUTES, MAX 20)
- Determine whether that one outside source is executable code or nonexecuting data under the relevant loaded image and lifetime, and if executable whether the encoded interior transfer is feasible.
- Use retained evidence and independent checks, including correct endian handling and MIPS delay-slot semantics. Do not infer executable code merely from a decodable word.
- If a missing producer, overlay classification, or reachability premise blocks a conclusion, record the exact missing item and STOP this workstream. Do not expand into other candidate routines, SI/PIF hardware modeling, or exhaustive mapping.
- Do not claim the whole initialization routine is certified merely because this one source is resolved.

WORKSTREAM B: SYNTHETIC HOST ADAPTER SPIKE (AT LEAST 25 MINUTES IF FEASIBLE)
- In a clearly isolated, disposable test location, implement a minimal independently written synthetic demonstration of how translated-game code could call a host-side initialization/controller/message service adapter while preserving guest memory ownership, calling convention and error boundaries.
- Consult the previously pinned Wave Race / N64ModernRuntime source and existing research notes for architecture, not for blind code copying. Check licenses before any third-party code reuse. Prefer writing our own thin adapter and test fixtures; do not install/repin dependencies unless essential and explicitly justified.
- Exercise success and failure paths with synthetic registers, synthetic RAM, and synthetic calls only. Tests should prove argument/return handling, memory side effects, invalid-state rejection and non-leakage across calls as appropriate. Explicitly document every mock and assumption.
- This spike may be useful even if Workstream A remains blocked. Do not require a full original-game boundary certificate to conduct the synthetic experiment.
- DO NOT patch original Mario Tennis code, generate or execute original game code, synthesize a game boot, invent device responses, or integrate an unverified replacement into production runtime.
- If implementation is infeasible in the time available, produce the smallest runnable synthetic test harness and explain the specific missing interface or dependency, rather than spending the rest of the session writing abstract analysis.

TIME MANAGEMENT
- Hard stop at 60 minutes. Suggested allocation: 5 min preflight, 15 min A, 30 min B, 10 min tests/commit/report. If A blocks early, immediately switch to B. If B has a viable experiment early, test it rather than widening scope.
- Avoid repeating the same privacy, archive or security audit narrative. Keep ordinary paths and logs low-risk; preserve meaningful safeguards against publishing ROMs, game assets, generated proprietary code or secrets.
- Do not change global sandbox, networking, permissions, repo visibility, or unrelated project settings.

DELIVERABLES / ACCEPTANCE
1. A concise Session 57 report distinguishing VERIFIED, EXPERIMENTAL, UNKNOWN and BLOCKED; give the exact outcome of the designated incoming-reference check.
2. A runnable synthetic-only adapter spike with tests, if feasible, or a precise technical reason it could not be built within the timebox.
3. A direct answer: does the spike demonstrate a plausible path to connecting an N64ModernRuntime-style service to our existing ABI? What exact ORIGINAL-GAME evidence would be needed before a real replacement?
4. A short Session 58 handoff focused on the single highest-value next integration step, with a first-frame-oriented roadmap. Avoid creating a new endless certification chain.
5. Run relevant existing tests and new synthetic tests. Preserve prior pins and archives. Commit and push only independently authored, reviewed, nonproprietary code/tests and sanitized documentation to the existing private branch under the established project workflow; report actual results, not assumptions. Continue established public diary/prompt-index workflow only within its existing approved allowlist.
6. Report honestly that no first screen/gameplay exists unless genuinely observed. Keep original ROM, game-derived code/data/assets and detailed private traces out of Git/CI/public reports.

LONG-TERM PRODUCT DIRECTION (BACKLOG, NOT THIS SESSION)
Linux/Bazzite first; Windows later; local user-supplied ROM workflow; multiplayer parity; correct original simulation timing with high-refresh presentation; widescreen; controller-friendly in-game UI inspired by Ship of Harkinian/libultraship. Do not change runtimes just for UI appearance. Investigate RecompFrontend redistribution rights before copying.

Owner's priority: Get closer to a genuine, repeatable first Mario Tennis frame. Rigorous tests are important, but experimental prototypes with clearly marked assumptions are allowed and encouraged. Do not spend this hour proving the entire N64 boot process.
