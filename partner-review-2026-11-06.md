# Partner review — 2026-11-06 (cobrajet302gt / Hermes)

Private working record. This file documents the Remote Play "voice" lane, which is private by
standing ruling (topology, sniff/capture posture, RP/DNS/cert lanes, island-derived roadmap stay
undisclosed unless explicitly approved). Nothing in the public venues describes this work yet.

## 1. Power-state oracle (the big one, free)
The RP discovery answer's HTTP status line distinguishes console power state, one UDP packet to
9302, no session, no credentials, no screen:
- `200 OK` = awake (full host report)
- `620 Server Standby` = rest mode (body still carries host fields)
- silence = the ~20 s transition window right after sleep entry
This closes the state-oracle gap that ranked #5 on the 2026-11-05 gap list. Tool:
`serve_kit/srch_state.py` (prints AWAKE/STANDBY/SILENCE).

## 2. Rest mode fully automated from the desk (loop verified twice)
- **Sleep** (needs a live session): chiaki keyboard dance `Ctrl+O` → `Return` (menu close,
  pre-focused) → `Return` (Sleep, pre-focused in the "Disconnect Session" dialog) = ctrl
  `GOTO_BED 0x50` + disconnect. Deterministic, keys-only (uinput chord mode), no Control Center
  navigation, no sign-in exposure. Replaces the failed CC bed-walk entirely.
- **Wake** (no session, no client): our own raw `WAKEUP` packet — verb exact per source grammar —
  with the real user-credential. Attributed: SRCH showed 620, packet sent, no TCP connect, 620 →
  200 within 15 s. One hand-built packet wakes the console.
- **Credential**: the vault regist key is stored as ASCII hex (`@ByteArray(<8 hex chars>` + NUL
  pad); user-credential = first 16 hex chars parsed base-16 (matches chiaki's discovery.h comment
  "regist key interpreted as hex" and its ≤8-byte wake guard). Values never published.

## 3. Listener census rows (rest-related)
- TCP 9295 stays OPEN in standby → plain connect can also wake (wake-on-connect second path).
- TCP 997 RSTs **even in rest** → the PS4/PPPwn-style sleeping request-port ear does not exist on
  PS5. Protocol-family diff; content is publish-safe in format terms if approval ever comes.
- Discovery responder accent (awake): verb case-sensitive, first line exact-match, body fields
  unvalidated (6-packet accent battery). Web door answers tables; native door answers boundaries.

## 4. Client program status (voice rungs)
Rung 1 (SRCH from our bytes) and rung 2 (WAKEUP attributed) are done. Next is **M1**: port
senkusha RSA-PSK handshake + ctrl login (protobuf) + takion/gkcrypt so we open our own session
with zero chiaki; then raw `GOTO_BED`/`GO_HOME`, then the remote-keyboard echo family
(console echoes typed text back over the wire = a printf channel that needs no cert and no screen).
Advisory-debate verdict 2026-11-06 22:1xZ: desk-only evening (PR #227 review posted, run-not-read,
gate proven green→red→green under tamper), M1 opens the next fresh session as headliner, PR1105
Guide-probe device load gets one hard 2-cycle budget in that same session.

## 5. Console posture
14.10 frozen, auto-update OFF, signed out (sign-in is consent-walled: it demands update
acceptance). Parked awake, sinkholed, all doors on the island verified through an 8-hour clean
soak; zero console settings touched; zero uncontrolled exposure all day.

## Method note
All claims above are bench-measured (raw packets, captures, screenshots) with tools under
`serve_kit/`; findings text banked at lab commit `1e75c09` (findings/rp-voice-2026-11-05/GRAMMAR.md).
Public venues carry none of the identity values (host-id, host-name, addresses) per standing rule.
