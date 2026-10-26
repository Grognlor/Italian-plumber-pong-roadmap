# Session 44 owner prompt

**Authentic — visibly redacted.** Derived from the owner-supplied text attachment,
preserved privately byte-for-byte with source, size, hash and independent reread
provenance. Marked spans withhold private paths, checksums and retained evidence.
Remaining wording and order are preserved. This is the issued prompt; the diary
records the actual outcome.

```text
RECOMMENDED CODEX MODEL: GPT-6.1 (if available)
REASONING EFFORT: HIGH

ITALIAN PLUMBER PONG — SESSION 44 MASTER PROMPT
ONE BOUNDED TARGET: OWNER-SUPPLIED NEC VR4300 SDR PRIMARY-SOURCE INTAKE AND GATED SEMANTIC COMPARISON

You are Codex working on the private Italian Plumber Pong N64 native-recompilation feasibility project. The owner explicitly authorizes this Session 44 task, subject to the boundaries below. Read the entire prompt before acting. This is NOT authorization to execute original game code, inspect a new ROM, build a game harness, fetch dependencies, publish game assets, or expand the investigation.

OWNER-SUPPLIED PRIMARY REFERENCE (NOW LOCALLY AVAILABLE)
Exact path: [REDACTED: LOCAL REFERENCE PATH]
Expected SHA-256: [REDACTED: REFERENCE CHECKSUM]
Expected document: NEC VR4300/VR4305/VR4310 64-Bit Microprocessor User's Manual, U10504EJ7V0UMJ1, seventh edition, August 2000.
Candidate SDR section: printed pages 498–500. Verify actual printed/PDF page mapping yourself. Do not assume the page numbers, title, edition, applicability, or contents without examining the authenticated file.

OWNER AUTHORIZATION FOR THIS SESSION
1. Read and hash ONLY the exact manual file above for primary-source verification; use relevant sections of that PDF for SDR, endianness, address/byte lanes, memory operations, exception/alignment rules, and any needed definitions. The file must remain unchanged and outside Git. You may create narrowly scoped private notes/excerpts in the new restricted archive, subject to source copyright and no public reproduction.
2. [REDACTED: PRIVATE RETAINED INPUT CONTEXT] This is not permission to inspect or re-read original ROM/reference images, expand to new game code, or acquire additional proprietary evidence. If evidence is absent, stop rather than substitute new reads.
3. Compare independently derived guest SDR semantics against the pinned N64Recomp ABI 3 implementation ONLY AFTER primary-source authenticity, applicability, and operand gates pass. Synthetic-only test proposals or narrow synthetic tests are permitted when safely supported by the existing test workflow. Do not change the pinned tool, patch stack, generated original code, original-game runtime, or ABI without a new owner decision.
4. Perform existing approved baseline verification, private preservation, report/status/handoff updates and normal reviewed GitHub publication using existing workflows and approvals. Public docs may report redacted findings and bibliographic references, but MUST NOT include the full PDF, private paths, game words/addresses/operands/hashes, disassembly, generated game code, ROM data, or private evidence.
5. No external manual retrieval is necessary or authorized. Do not attempt web access, alternate mirrors, dependency downloads, or network-policy workarounds. Existing GitHub workflow remains subject to normal tool approvals.

PROJECT CONTEXT AND HARD BOUNDARIES
[REDACTED: PRIVATE CHECKOUT, TOOLCHAIN AND HISTORICAL EVIDENCE CONTEXT]

MANDATORY PREFLIGHT (BEFORE NEW SEMANTIC CLAIMS)
[REDACTED: PRIVATE REQUIRED READING]
B. Confirm correct private origin/branch/upstream, clean checkout, no unreviewed outgoing commits, expected working roots, path aliases, ownership and permissions. If dirty or unexpected, preserve evidence and stop for a decision.
C. Record declared Codex sandbox/approval/network configuration and distinguish it from independently verified enforcement. Workspace-write/on-request/restricted network declaration is not proof that network is blocked. Actual network enforcement may remain UNKNOWN. Never weaken controls or request broad elevation to continue.
D. Reverify existing explicit prior archive inventories, detached anchors and selected input identities without new ROM analysis. Preserve old seals unmodified. Use a new persistent restricted Session 44 archive directory (umask 077, mode 0700), a harmless create/read/delete access test, and a detached manifest/anchor outside the sealed tree. One local copy is NOT a verified independent backup.
E. Capture this exact owner prompt with provenance, bytes, length and SHA-256, without normalization; independently reread for equality. If exact prompt attachment is unavailable, record the limitation honestly and do not invent an exact-byte receipt.
F. Verify the manual exists at the exact path, is a regular readable PDF, and SHA-256 matches [REDACTED: REFERENCE CHECKSUM]. If absent/mismatched, STOP with a precise remediation request. Do not silently use a substitute. Record source as owner-supplied local copy, not as a Codex download. Hash the file without modifying it. Confirm document cover, publisher, identifier, edition/date, table of contents, relevant SDR pages, and cross-referenced definitions. Note that matching a known owner-provided hash proves byte identity to the supplied copy, not cryptographic publisher authenticity; assess provenance explicitly.
G. Verify pinned N64Recomp source/submodules/patch ordering/ABI and dependency inventory with existing procedures, no fetches or repins. Run standard/full 108-test baseline and both synthetic generator fixtures where approved; report exact PASS/FAIL/SKIPPED/BLOCKED/UNKNOWN, not assumed outcomes. Honor existing verification sequence.

ONE EVIDENCE INVESTIGATION — STRICT ORDER
1. Build a falsifiable acceptance matrix BEFORE semantic inspection: (i) exact PDF hash/identity, (ii) manufacturer-authored content and applicability to retained VR4300 instruction/endianness, (iii) complete SDR instruction definition and referenced endian/byte-lane/memory/fault rules, (iv) verified retained actual base operand and relevant alignment from explicitly inventoried Session 41/42 evidence, (v) independent guest byte-write and architectural read effects, (vi) host helper source comparison, (vii) optional synthetic validation, (viii) P1 remaining readiness gates. Each has evidence and stop conditions.
2. Independently transcribe/derive the relevant SDR semantic rules from the manual. Distinguish big-endian guest SDR from little-endian cases. State byte lanes and masks for each low-three-bit effective-address alignment 0..7, which bytes of the 64-bit source register are selected, which guest memory bytes change, and the defined architectural memory read/merge behavior. Include alignment, address, exception, and fault rules with precise manual page/section references. If the manual does not define a required detail, label UNKNOWN; do not use emulator implementations, helper source, or model recollection as the guest oracle. Differentiate architectural effects from physical bus/cache transactions and from implementation-specific optimized native memory reads.
[REDACTED: PRIVATE OPERAND APPLICATION DETAILS]
[REDACTED: PRIVATE PINNED HELPER COMPARISON REQUIREMENTS]
5. If safe and useful, add/run narrowly scoped synthetic-only regression tests in existing approved test locations, with no proprietary data, original game code, original generation, original build or execution. Do not alter production helper/toolchain as a shortcut. If code/test changes would exceed the bounded objective, write a proposal instead and request owner authorization.
[REDACTED: PRIVATE READINESS AND DEFERRED EVIDENCE DETAILS]

TIME AND FAILURE LIMITS
Maximum 15 bounded investigation rounds, 20 minutes of focused investigation, 3 failed attempts at any blocker, 300 seconds per individual process. Stop at the FIRST material missing source/authenticity/applicability/semantic/operand gate; do not spend the remainder on speculative substitutes. Baseline verification, preservation and reporting may proceed under established procedures, with clear separation from investigation limits.

SECURITY, COPYRIGHT AND PUBLICATION
No ROM/image/new game asset reads; no original-game function generation, compilation, validation or execution; no startup/gameplay claims. No dependency or public-document downloads. No broad file search through private data; use explicit inventories and approved paths. No new external account/access changes, permissions broadening, sandbox weakening, main merge, force push, release or media production. Never publish proprietary code/data, game addresses, instruction words, ROM hashes, private paths, private evidence or PDF bytes. Public documentation should cite manual title/document/edition and relevant printed pages only; paraphrase semantics, do not reproduce large copyrighted tables/sections. Treat exact reference checksum as non-secret if appropriate, but do not publish it without public-document review. Do not add the manual to Git, Git LFS, Actions artifacts, or CI. Review complete public files and Git diff before commit/push; verify actual remote bytes. GitHub actions subject to existing approvals. Keep the public roadmap issue #2 under milestone 2 open and all eight milestones open unless evidence truly changes status. Do not claim CI green without observing a relevant run.

SESSION 44 DELIVERABLES
- A clear Session 44 report, source/provenance receipt, exact manual hash verification, cover/edition/section/page citations, acceptance matrix with PASS/FAIL/BLOCKED/UNKNOWN, independently derived guest SDR byte/read effects or precise blocker, and strictly gated host comparison findings.
- Explicit P1 readiness table, no inflated progress, current test/fixture receipts, unchanged or carefully justified synthetic-only tests, exact pinned-toolchain verification and declared-vs-observed security controls.
- New restricted sealed private archive with complete explicit relative-path/size/SHA-256 inventory, detached manifest/anchor, independent post-seal verification, and exact prompt provenance. Do not modify older seals; distinguish snapshot timing from later mutable Git/CI receipts.
- Updated [REDACTED: PRIVATE STATUS DOCUMENT PATH], [REDACTED: PRIVATE HANDOFF DOCUMENT PATH] (one concrete bounded Session 45 target depending on outcome), public redacted prompt/index/newest-first diary and approved public roadmap/issue notes where established. Follow repo workflows, complete full-file redaction and remote-byte review, and report publication/CI truthfully.
- Final concise owner-facing summary: what was verified, what remains UNKNOWN/BLOCKED, tests/fixtures, whether P1 is ready (likely not until all independent gates close), security/archival status, commit/push/CI observations, and exactly what owner decision or evidence is needed next.

SUCCESS MEANS closing the primary-source SDR gate honestly and, if justified, reaching a defensible bounded semantic comparison. It does NOT mean making Mario Tennis run this session. If any prerequisite fails, preserve a useful, reproducible BLOCKED result rather than forcing progress.
```
