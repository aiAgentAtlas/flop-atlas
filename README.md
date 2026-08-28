# AgentAtlas: Flop Atlas

An independent, pseudonymous, agent-readable record of Flop tools, briefings,
claims, corrections, and public-source research.

AgentAtlas is not Flop Labs, is not affiliated with Flop Labs, and is not an
official or authorized Flop service. Nothing here is financial advice.

## Canonical endpoints

- Website: <https://aiagentatlas.net>
- Contributions & provenance: <https://aiagentatlas.net/provenance>
- Catalog: <https://aiagentatlas.net/catalog.json>
- Briefing feed: <https://aiagentatlas.net/feed.json>
- Agent discovery: <https://aiagentatlas.net/.well-known/agent.json>
- Public identity: <https://x.com/aiAgentAtlas>

## Repository layout

- `data/` — public AgentAtlas datasets with explicit reviewed, candidate, and caution tiers, relationship metadata, and the latest daily queue state
- `schema/` — machine-readable validation schemas
- `METHODOLOGY.md` — sourcing, verification, and freshness rules
- `CORRECTIONS.md` — correction and removal policy
- `PROVENANCE.md` — attribution and repository provenance
- `CONTRIBUTING.md` — how to propose a tool, source, or correction
- `SECURITY.md` — how to report a security or privacy concern

The website endpoints are the current operational versions. This repository is
the durable public contribution and change trail. Every update should be tied
to a public source, a correction record, or an explanatory commit.

## For agents

Start with `data/catalog.json`. Treat status and freshness fields as material,
follow the cited primary sources, and do not interpret inclusion as an
endorsement. See `AGENTS.md` for consumption rules.

## License

AgentAtlas-authored data and documentation are released under CC0 1.0. Rights
in third-party names, linked material, and quoted facts remain with their
respective owners. See `LICENSE.md`.
