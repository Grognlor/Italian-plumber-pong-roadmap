# Session 54 — Authentic owner prompt, visibly redacted

Status: completed research session. No game boot or playable build is claimed.
Source: the owner-supplied Session 54 attachment, preserved byte-for-byte privately.
Only the two private documentation paths listed by the visible markers are withheld.
This is the issued prompt, not a claim that every proposed feature was implemented.

---

ITALIAN PLUMBER PONG - SESSION 54
Architecture Research, Runtime Acceleration, and Reference Library
Time budget: approximately 2 hours. Preserve current work and provide a clear handoff.

PROJECT CONTEXT
Mario Tennis (USA) N64 native recompilation, Linux/Bazzite first, Windows next. Preserve project name Italian Plumber Pong. Current Session 53 report: [REDACTED: private Session 53 report path]. It reached a second SI status poll after a single controlled busy read, but has no genuine first frame. Review current repository state before acting; do not assume this prompt reflects newer changes.

OWNER DIRECTION
Our goal is a playable, polished PC port, NOT an independently recreated full N64 console. Favor documented hardware behavior, mature reusable runtime components, PC-native replacements, and a small vertical slice to first recognizable game screen. Maintain correctness and meaningful tests, but avoid making proof of every original startup hardware state a prerequisite if a defensible architectural alternative exists. Do not discard existing work or switch architectures without evidence and a concrete plan.

RESEARCH THESE EXACT REPOSITORIES (read code, build configuration, documentation, dependencies, and relevant licenses, not only README):
1. https://github.com/HarbourMasters/Shipwright
   Investigate libultraship's architecture, UI/settings overlay, gamepad navigation, config persistence, ROM-local asset processing, and how N64-specific services are replaced.
2. https://github.com/elliotttate/wave-race-64-recomp
   Highest priority for technical relevance. Trace N64Recomp -> N64ModernRuntime -> RT64 -> RecompFrontend integration, initialization path, SI/PIF/joybus behavior, controller and audio handling, local ROM processing, display-list modifications, frame interpolation, and build/release packaging. Check upstream dependencies and exact pinned revisions when possible.
3. https://github.com/DabDavis/perfect-dark-dabs-mod
   Study its decompilation-based native architecture, ROM-supplied assets, startup, PC-native subsystems, in-game settings, controller support, and extensibility. Distinguish reusable ideas from components incompatible with our recompilation architecture.

LIBULTRASHIP UI TARGET
Owner particularly likes the Ship of Harkinian/libultraship interface. Evaluate (a) direct libultraship integration, (b) selectively reusing appropriately licensed UI components, (c) adapting/customizing RecompFrontend to offer similar usability. Prioritize controller-operable in-game settings, graphics, widescreen, audio, remapping, multi-controller support, and persistent config. Clearly distinguish visual UI from full framework. Do not replace runtime merely for UI aesthetics. Give recommendation with technical and license rationale.

REFERENCE LIBRARY
Create a curated, reproducible [REDACTED: private reference-library documentation path] index with verified source URLs, titles, relevant chapters/sections, license/access notes, and how each relates to the Session 53 SI/PIF blocker. Research official Nintendo 64 Programming Manual, SI/RCP register documentation, PIF RAM/joybus protocol, DMA timing, interrupts, CPU boot handoff, and independently written open-source reference implementations (e.g. libdragon, ares). Verify URLs and document discrepancies. Prefer links, citations, summaries, and independently authored notes. Do NOT commit copyrighted manuals, proprietary SDK files, ROM data, game-derived code/assets, or extensive copied text. If legally accessible, download references only to an excluded local research folder with clear provenance and no Git tracking; otherwise index the links. Never copy implementation bodies merely because they are publicly readable.

SPECIFIC ARCHITECTURAL QUESTION
Can we use N64ModernRuntime or another established runtime to satisfy the real SI/PIF behavior needed by Mario Tennis, or bypass/replace original startup code in a technically sound way, without inventing idle/completion values? Explain exactly how successful ports cross the original startup boundary, distinguishing observed code from inference. Avoid assuming a library automatically handles all hardware. Identify required adapters, ABI assumptions, renderer integration, and missing game-specific information.

DELIVERABLES
- A concise evidence-backed comparison of the three projects and their runtime/boot approaches, with direct file references, license caveats, and applicability ranking.
- A reference-library index and independently authored SI/PIF notes.
- A recommendation for runtime architecture and UI architecture, with estimated implementation complexity, risks, and fastest first-frame path.
- A staged plan: first genuine frame, then input/audio/gameplay, then polish; preserve multiplayer parity and game timing. Explain why high-refresh interpolation is not the same as changing physics update rate.
- If time and evidence permit, ONE small reversible prototype or synthetic integration test, with clear success criteria; otherwise research-only is acceptable. No fabricated screen, ungrounded SI values, or speculative production code.
- Session 54 report, test results, blockers, next-session prompt/handoff, and appropriately sanitized Git commit/push according to existing project workflow. Clearly distinguish verified, conditional, unknown, and blocked.

SAFETY AND COPYRIGHT BOUNDARIES
No Nintendo ROM, original game assets/code, game-specific generated output, or proprietary manual content committed or published. The end user supplies their own legally obtained ROM; game-specific preparation and extracted content stay local. Evaluate license compatibility and attribution for every proposed dependency or reused component. Public source availability alone is not permission to copy. Local research with owner-provided ROM is permitted. Benign local paths/logs are not security incidents; prioritize genuine copyrighted content and credentials. Keep existing sandbox and repository controls.

EXECUTION STYLE
Work autonomously within existing approvals and the ~2-hour budget. Spend most effort on actionable technical research rather than security bureaucracy or exhaustive proof exercises. Preserve working Session 53 checkpoint, avoid broad refactors, and end with an explicit recommendation for Session 55.
