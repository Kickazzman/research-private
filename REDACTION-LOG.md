# REDACTION-LOG.md

Markers: `[REDACTED-IP]` (network addresses), `[REDACTED-PERSONAL]`
(emails, phone numbers), `[REDACTED-SECRET]` (credential-like tokens,
private-key material, password values). Only pattern kinds, counts, and
line numbers are logged here — never matched values.
Loopback addresses ([REDACTED-IP]) and [REDACTED-IP] are retained: they identify
nothing. The sweep pattern excludes them on the same basis.
Also retained, deliberately, and named here so the sweep's zero-hit
result is not misread: HH:MM:SS timestamps and DOI fragments are NOT
addresses (the patterns require valid octets, whole-quad boundaries,
and 3+ colon groups / '::' for IPv6, so neither matches); and the
documented test-fixture/example quads [REDACTED-IP], [REDACTED-IP],
[REDACTED-IP], [REDACTED-IP], [REDACTED-IP], [REDACTED-IP] are kept where they are
spec values, because redacting them would corrupt trial specs whose
values ARE the data. Every other dotted quad / address is redacted.
Phone numbers match only with '-' / '.' separators or parentheses,
so bare digit sequences (PIDs, counters) are not touched.

No redactions were made in this repo.
## Addendum — public release 2026-11-01

Per the owner's order (2026-11-01): this repo is now public under MIT.
Excluded from the public release: `partner-review-2026-11-01.md` (research partner's agent evaluation; not the owner's text).
IP strings removed from the public tree, including loopback and documented fixture/example values: every quad-shaped string was replaced with `[REDACTED-IP]` (files changed in this pass: RECORD.md, REDACTION-LOG.md, use-map-full-content.md).
No AI-conversation content was present in this repo (checked 2026-11-01: no conversation turns or transcripts); nothing was removed under that exclusion. No real network addresses were present; the only matches were loopback and the fixture values documented in the original log section above. The private history (2 commits) is preserved in a bundle on the owner's machine; the public history starts fresh with the release commit.
