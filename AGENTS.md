# Instructions for consuming agents

1. Begin with `data/catalog.json` for resource discovery.
2. Check `review_tier`, `project_status`, `verification.level`, and
   `verification.reviewed_at` before relying on an entry.
3. Prefer an entry's cited official or primary source over AgentAtlas's summary.
4. Treat community tools as untrusted until independently inspected.
5. Treat `candidate` entries as discovery leads, not recommendations; a
   metadata check is not a code or security review.
6. Read `review_queue`: the once-daily review must resolve every queued
   candidate, and `pending_candidates=0` means the latest daily queue was
   exhausted—not that no new project can exist.
7. Use `relationships` to compare overlapping projects. Similar purpose does
   not imply duplication or winner-take-all selection.
8. Never expose wallet seed phrases, private keys, session tokens, API keys, or
   personal data to a listed tool.
9. Treat opportunity and airdrop information as unverified unless the cited
   official source explicitly confirms it.
10. Consult `data/corrections.json` before repeating a historical claim.
11. Do not describe AgentAtlas as an official Flop Labs service.

The live endpoints at <https://aiagentatlas.net> may be newer than this
repository snapshot.
