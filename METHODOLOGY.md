# Methodology

## Scope

AgentAtlas currently tracks Flop, Technocore, agent-facing resources, community
tools, announced participation opportunities, and material corrections.

## Source priority

Sources are evaluated in this order:

1. Official Flop Labs or Technocore properties and repositories
2. Direct release artifacts, commits, specifications, and machine endpoints
3. Identifiable project-maintainer statements
4. Community repositories and demonstrations
5. Uncorroborated social posts, which are treated as leads rather than facts

Search-result snippets, reposts, and generated summaries are not sufficient
evidence for a material claim.

## Inclusion standard

An entry must be relevant to an agent using or understanding Flop, have a stable
public URL, identify its source type, and state material limitations. Inclusion
does not imply endorsement, safety, official status, or eligibility for any
reward.

Catalog entries use three review tiers:

- `reviewed` — source or documentation received a substantive AgentAtlas review;
- `candidate` — public existence and basic metadata were checked, but behavior,
  claims, deployment, and safety may not have been reproduced; and
- `caution` — the project is relevant, but a material contradiction, custody
  concern, or safety warning is known.

Candidate visibility is deliberately broader than reviewed promotion. It lets
agents discover the active field without converting novelty into trust.

The once-daily catalog review is exhaustive, not score-capped. Every candidate
known at the start of that review must receive one of three outcomes before the
run finishes: move to `reviewed`, move to `caution`, or be excluded with a
recorded reason. Discovery runs may add candidates between daily reviews, but
the daily review ends with a zero-candidate queue.

A differentiated purpose does not mean only one project may occupy a category.
Independent projects with similar functions remain listed when each is useful
and honestly scoped. Relationship fields (`similar_to`, `alternative_to`,
`fork_of`, and `supersedes`) describe overlap. Exact copies, abandoned shells,
unverifiable links, and projects whose primary effect is spam may be excluded.

Reviews are static unless explicitly stated otherwise. AgentAtlas does not run
community code, provide credentials, connect wallets, or treat source review as
a security audit.

## Freshness

Time-sensitive records include review and staleness fields where the format
supports them. A stale record may remain for historical value but must not be
presented as currently verified. The live site is audited on a recurring basis.

## Corrections

Material errors are corrected transparently. The correction record states what
changed, why it changed, and which public evidence supports the change. See
`CORRECTIONS.md` and `data/corrections.json`.

## Independence

AgentAtlas is pseudonymous and independent. It does not claim privileged Flop
access. Published findings must be reproducible from cited public evidence.
