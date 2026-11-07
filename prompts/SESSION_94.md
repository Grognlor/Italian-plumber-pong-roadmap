# Session 94 — Owner prompt

Status: issued for Session 94; investigation and planning only. Requested objectives
are separate from verified results. The exact original and provenance are preserved
privately. Six localized sensitive spans are visibly redacted; all other wording
and ordering are preserved.

[Read the Session 94 development diary](../docs/PROGRESS.md#session-94).

---

ITALIAN PLUMBER PONG
SESSION 94 - DESTRUCTION DERBY WORKFLOW INVESTIGATION

MISSION:
Investigate how Destruction Derby 64 was
decompiled and ported to PC so quickly.

Use the findings to determine whether our
Mario Tennis N64 project can reach a playable
state substantially faster.

This is an investigation and planning session.
Do not implement a new strategy without approval.

REFERENCE REPOSITORY:
https://github.com/murkantor/Destruction-Decomp-64

LOCAL DESTRUCTION DERBY INSTALLATION:
[REDACTED: local private installation or ROM path]

LOCAL DESTRUCTION DERBY ROM:
[REDACTED: local private installation or ROM path]

OUR PROJECT:
[REDACTED: private repository identifier]

PHASE 1 - EXAMINE THE REFERENCE PROJECT

Inspect the Destruction Derby GitHub repository,
its history, documentation, source code, build
scripts, dependencies and port implementation.

Also inspect the local Linux installation.

Determine whether the local installation
contains source code, compiled binaries,
runtime files or some combination.

Investigate:

1. Which tools were used to decompile the ROM.
2. How functions and assets were identified.
3. How much analysis was automated.
4. How the matching decompilation was verified.
5. How the PC executable was produced.
6. How graphics, audio and input were handled.
7. How N64 OS calls, threads, queues and memory
   were implemented or adapted.
8. What was required for the first playable build.
9. What work was postponed until afterward.
10. Whether the reported development timeline
    is supported by commits and documentation.

Do not confuse developer claims with independently
verified results.

PHASE 2 - ANALYZE THE ORIGINAL ROM

Use the local Destruction Derby ROM as a
read-only reference.

Identify its byte order, region, revision,
size and cryptographic hash.

Compare it against the reference repository's
documented ROM requirements.

Where practical, reproduce the repository's
documented extraction, analysis or build
verification workflow in an isolated workspace.

Determine:

- Whether the decompilation matches the ROM.
- Which tools perform the most automated work.
- How the original binary is mapped to source.
- How the PC port uses the original game data.
- What parts of the workflow could transfer
  directly to Mario Tennis.

A byte-for-byte match must be demonstrated,
not assumed.

Do not modify the original ROM.

PHASE 3 - AUDIT ITALIAN PLUMBER PONG

Review:

- [REDACTED: private project instruction or report path]
- [REDACTED: private project instruction or report path]
- [REDACTED: private project instruction or report path]
- Recent session reports
- Existing N64Recomp tooling
- Current code generation and native runtime
- Security and verification requirements

Answer:

1. Why have we completed 93 sessions without
   reaching a playable game?

2. Which existing components are valuable
   and should be preserved?

3. Which requirements protect ROM privacy?

4. Which requirements are optional correctness
   certification rather than necessary
   prerequisites for experimental execution?

5. Are we spending excessive effort proving
   individual execution paths before attempting
   native integration?

6. Could Ghidra, Splat, m2c, matching
   decompilation techniques or existing
   N64Recomp capabilities accelerate progress?

7. What specifically prevents us from attempting
   a first native frame?

Be critical of the existing approach.
Do not defend prior decisions simply because
we have already invested time in them.

PHASE 4 - RECOMMEND A NEW STRATEGY

Compare:

A. Continue our current certification-first
   development approach.

B. Adopt a Destruction Derby-style automated
   decompilation and native port approach.

C. Develop a hybrid approach using existing
   security infrastructure with a separate,
   experimental native boot target.

Recommend the most practical option.

Consider establishing a separate experimental
branch while preserving all existing work.

Propose milestones:

1. Native executable boots.
2. First rendered game frame.
3. Working controller input.
4. Title screen.
5. First playable tennis match.
6. Multiplayer.
7. Widescreen and high frame rates.
8. In-game settings and easy installation.

Identify the smallest implementation experiment
that would test the recommended approach.

Explain which existing tools, libraries and
generated code could be reused.

Do not invent development timelines or claim
that experimental execution proves correctness.

SECURITY REQUIREMENTS:

- Never commit, publish or redistribute ROMs.
- Never commit proprietary extracted assets,
  disassembly or translated game code.
- Keep private ROM inputs outside Git.
- Treat the Destruction Derby ROM and installation
  as read-only inputs.
- Use isolated temporary workspaces.
- Preserve credential and network isolation.
- Avoid executing untrusted scripts without
  reviewing their behavior and dependencies.
- Never change GitHub repository visibility.
- Never delete historical project work.
- Never merge or publish a release.
- Do not weaken ROM confidentiality.

You may recommend relaxing certification
requirements for an experimental development
branch, but do not change them yet.

DELIVERABLES:

Produce a clear report containing:

1. Destruction Derby development methodology.
2. Verified findings from the local ROM.
3. Findings from the local Linux installation.
4. Tools and automation worth adopting.
5. Why our Mario Tennis project is slower.
6. A comparison of the three strategies.
7. Recommended development direction.
8. A concrete first-boot experiment.
9. Risks and owner decisions required.

Cite specific repository files, commits and
build results wherever possible.

Clearly distinguish verified facts,
developer claims and hypotheses.

Update the private session report and next
session handoff as appropriate.

Do not alter the existing implementation.
Do not start Session 95.

Do not collect or report token usage statistics.

BEGIN SESSION 94 INVESTIGATION.