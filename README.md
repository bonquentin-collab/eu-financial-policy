# EU Financial Policy — Claude Code multi-agent pipeline

A pipeline for developing genuinely creative, well-grounded reform proposals on EU financial regulation — built so that the creative step (`policy-innovator`) never floats free of the legal, micro-financial, macro-financial, comparative, and political-feasibility fact base, and never survives unchallenged.

## Architecture

```
.claude/
  agents/
    current-regulation-analyst.md  → state of the law: text, legislative history, transposition, evaluations
    micro-financial-analyst.md     → firm/transaction-level mechanics and incentive effects
    macro-financial-analyst.md     → systemic effects, macroprudential stability, CMU objectives
    benchmarking-analyst.md        → international comparison (US, UK, and other relevant markets)
    stakeholder-mapper.md          → initial position mapping, then a feasibility-check round
    policy-innovator.md            → the creative agent — proposals framed against adjacent EU frameworks
    impact-assessment-auditor.md   → Better Regulation stress-test, round-based exchange with policy-innovator
    legal-drafter.md               → optional, on-request only — recitals and articles for approved proposals
  commands/
    eu-financial-policy.md         → orchestrates the full sequence, including both round-based exchanges
policy/                            → generated fact-base briefs, proposals, and debate transcripts
```

## Why this split

- **Five independent fact-base agents run first**, in parallel where the runtime allows it: legal state, micro mechanics, macro/systemic effects, international benchmarking, stakeholder positions. `policy-innovator` is only ever invoked once all five have reported, and is required to visibly ground every proposal in specific findings from them — not float free of the fact base.
- **The creative step is explicitly instructed to look for cross-framework synergy** (InvestEU, EuVECA, ELTIF 2.0, GBER, CMU Action Plan, Solvency II/LTEI, CRR/CRD, Listing Act, etc.), not just amend the one instrument in isolation — this is where most of the actual value of a good EU reform proposal tends to sit.
- **Two separate adversarial rounds, not one.** `impact-assessment-auditor` checks regulatory soundness (subsidiarity, proportionality, cost-benefit, coherence with the acquis) in the spirit of an actual Regulatory Scrutiny Board review. Only proposals that survive that get a second, different kind of stress test from `stakeholder-mapper`: not "is this good policy" but "will this survive the actual politics." A proposal can be well-designed and still politically dead on arrival — these are genuinely different questions and conflating them produces proposals that are naive about either substance or feasibility.
- **`legal-drafter` is opt-in, not automatic.** Drafting legislative text is a distinct, higher-commitment step from developing and stress-testing a proposal; it only runs on request, and only on proposals that already passed the impact-assessment round.

## Installation

1. Copy `.claude/` to your project root (or `~/.claude/` for global use) — safe to install alongside the other packs, agent names are distinct.
2. Run Claude Code in that folder.
3. Type `/eu-financial-policy` and name the regulation/directive/topic, or run it bare and answer the scoping question first.

## Notes

- Default output language is French unless you specify otherwise (matches the other packs' default).
- The parallel step in step 2 of the command is a real Claude Code capability — the five fact-base agents don't depend on each other, so invoking them together rather than strictly sequentially is both faster and doesn't cost analytical quality.
- Like the other packs, the adversarial agents here are themselves LLMs — a genuine stress test, more rigorous than a single self-review pass, but not equivalent to an actual Regulatory Scrutiny Board opinion or a real stakeholder consultation.
