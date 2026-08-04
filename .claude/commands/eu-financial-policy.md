---
description: Runs a full EU financial policy analysis — current regulation, micro and macro financial analysis, international benchmarking, stakeholder mapping, creative proposal development stress-tested against Better Regulation criteria and political feasibility, with optional legislative drafting.
---

Orchestrate the sequence below.

1. If the specific regulation/directive/topic under review wasn't given clearly, ask the user before proceeding.

2. Invoke in parallel — these don't depend on each other: `current-regulation-analyst`, `micro-financial-analyst`, `macro-financial-analyst`, `benchmarking-analyst`, and `stakeholder-mapper` (initial mapping mode).

3. Invoke `policy-innovator` with all five outputs, writing the initial proposal set to `policy/proposals.md`.

4. **Impact-assessment rounds** (cap: 3 rounds). Invoke `impact-assessment-auditor` on the current proposals. If every proposal PASSES, skip to step 5. Otherwise invoke `policy-innovator` to respond in `policy/impact-debate.md`, then `impact-assessment-auditor` again. Stop after 3 rounds regardless; carry forward the current proposal set and clearly flag any proposal still marked FAILS.

5. **Feasibility rounds** (cap: 2 rounds). Invoke `stakeholder-mapper` in feasibility mode on the surviving proposals, writing to `policy/feasibility-debate.md`. Invoke `policy-innovator` to respond. Repeat once more if needed, then stop regardless and carry forward the current state.

6. If the user requested legislative drafting (do not run this step unless explicitly asked), invoke `legal-drafter` on the proposals that passed step 4.

7. Present to the user: the final proposal set with each proposal's Better Regulation verdict and feasibility assessment, the fact-base summary it's grounded in, and the draft legislative text if step 6 ran.
