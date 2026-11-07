# Partner review — 2026-11-02

Evaluation by the research partner's agent (Hermes, running on the partner's
rig "Hal"; GitHub: cobrajet302gt). This is the assistant-side evaluation of
the partner, kept separate and labeled, per repo convention. It is NOT
perg's text and does not enter any verbatim record.

## What was done

Reviewed the single rewritten public-release commit `19e2436` (author
Kickazzman, 2026-11-01 12:23:08 -0500; GitHub push 2026-11-01T17:23:19Z).
The remote was force-updated over the previous 2-commit private history
(`bd68dd9` + `492285c`), which this agent still held locally; both trees
(old private and new public) were expanded byte-for-byte into scratch dirs
and compared independently of perg's tooling. GitHub API confirms repo
visibility is now PUBLIC. `partner-review-2026-11-01.md` (this agent's
prior review) is absent from the public tree and history; a copy is kept
by the partner outside the repo (3435 bytes, sha256 6f61dffc...e7a34,
matching that commit's recorded hash).

## What was verified (programmatic, exact)

1. MANIFEST.sha256: 15 entries, 0 duplicate filenames; recomputed all 15
   SHA-256 values against the public tree: 15/15 match; manifest-to-tree
   bijection exact (15 tree files excl. MANIFEST; none unlisted, none
   phantom).
2. RECORD.md table: all 13 rows fully verified. Every published SHA-256
   matches the recomputed public-tree hash; every stated byte size
   matches; every original SHA-256 matches the recomputed hash from the
   preserved pre-rewrite private tree — a complete original→published
   provenance chain, including the four changed files (README 44299d6e...
   -> 60acdbb4..., 1726->1790 B; use-map-full-content 1e971e2f... ->
   6074952e..., 282962->282966 B; RECORD.md -> 4b8288a9...; REDACTION-LOG
   -> 0190ac1c...).
3. Redaction is minimal and structure-neutral: use-map-full-content.md
   differs from its original by exactly 1 line (--host 127.0.0.1 ->
   [REDACTED-IP], +4 B, matching the size claim); entry-ID set identical
   old vs new (408 = 408 by this agent's line-start heuristic; symmetric
   difference empty).
4. Redaction claims hold: 0 quad-shaped strings remain anywhere in the
   public tree; [REDACTED-IP] marker counts RECORD.md 3, REDACTION-LOG.md
   10, use-map-full-content.md 1 — matching the addendum's file list. The
   claim that the only removed matches were loopback + documented fixture
   quads is confirmed against the private tree, whose full quad inventory
   was exactly {127.0.0.1, 0.0.0.0, 1.1.1.1, 1.2.3.4, 10.0.0.1,
   192.168.0.1, 255.255.255.255, 8.8.8.8}. No other dotted quad existed.
5. "No AI-conversation content": 0 hits for transcript/turn markers across
   all 15 public files. Consistent.
6. Counts: theories-full-inventory 228 distinct TH ids, contiguous 1..228,
   no duplicates (README's "228-entry" claim holds). use-map-index meta
   arithmetic exact: class totals 126+61+141+83+14 = 425 =
   map_total_entries; avoid_entries_total = AVOID class = 83. Citation
   counts recomputed from the JSON itself, all four exact:
   unique_entries_cited_total 135, operational_entries_cited 94 (U/B/E),
   reference_entries_cited 3 (R-S03, R-S04, R-S05),
   avoid_entries_cited_in_avoid_lists 42.
7. History claim "private history (2 commits) preserved in a bundle": the
   preserved local history is exactly 2 commits, matching (the bundle
   itself is on perg's machine and not independently checkable here).

## Questions / observations (partner's evaluation, labeled)

1. The blanket sweep rewrote prose that describes the redaction policy,
   producing self-contradictions: RECORD.md now reads "Loopback addresses
   ([REDACTED-IP], [REDACTED-IP]) are retained" immediately next to an
   addendum saying loopback was redacted; REDACTION-LOG.md's original
   section still says loopback and the six fixture quads "are retained /
   are kept" while each value is now literally [REDACTED-IP]; and "No
   redactions were made in this repo." still stands one line above the
   addendum that logs redactions. Also "127.x" (not quad-shaped) was
   replaced, exceeding the addendum's own stated "quad-shaped" scope.
   Cosmetic/audit-clarity only — no data integrity issue. Two clarifying
   sentences would settle it.
2. Carried from 2026-11-01, still open: meta.reference_entries_total = 135
   vs map_classes.REFERENCE = 141 (six-entry drift, or an unstated second
   definition).
3. The 425 total is not reproducible from the published file by
   independent regex grammars (this agent's best: 413 distinct ID tokens
   anywhere, 408 line-start). The prior pass verified 425 under perg's
   header grammar, and the file is unchanged structurally since, so 425
   stands — but use-map-regen-check.py, the named guard, is still not in
   the repo, so the PASS claim remains single-ended.
4. Visibility flipped private -> public by owner order. That is perg's
   call alone and stands. Flagging two mechanical consequences: this very
   file now sits in a public tree (perg has stated partner reviews are
   excluded from the public release, so the next pass will need to decide
   its status), and the partner's standing assumption that vault content
   stays private is structurally inverted for future passes.
5. male-donor-shortlist.html was hash-verified but content-audited only
   for structure, not breeding-advice correctness (out of scope).

## What is NOT claimed

- Research content was not re-derived or fact-checked; only provenance
  hashes, counts, structure, and redaction claims were verified.
- Original files at /home/hatch/... were not inspected at source;
  original hashes are verified against the preserved private git tree,
  itself first verified from a fresh clone on 2026-11-01.
- The owner's-machine bundle and regen-check.py PASS results are not
  claimed verified.
- 425 is not claimed wrong — only not reproducible by the agent's quick
  grammars.
- Nothing was edited in perg's files or the map; this file is the only
  write. No publication decisions were made by the partner; perg's
  release of the repo is perg's own act.

## Verification of this file

This file's byte size and SHA-256 are recorded in its commit message, so
either end can byte-check it against their own clone. Delivered 2026-11-02
by push from cobrajet302gt.
