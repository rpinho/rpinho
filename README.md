# Ricardo Pinho

Data engineer with a PhD in computational biology. I use AI agents, mostly Claude Code and Codex, on open science problems and publish the code and the results. Results are unrefereed unless a paper says otherwise.

## AI for Science

One hub per field. Each collects the work, the code and the references it builds on.

- **Biology:** [ai-biology](https://github.com/rpinho/ai-biology), protein design, the Arc Virtual Cell and Virtual Embryo challenges, open drug-target discovery, and refereed bug reports on scientists' published software.
  - [virtual-cell-challenge](https://github.com/rpinho/virtual-cell-challenge): pipeline and local evaluation harness for the Arc Virtual Cell Challenge 2026. Final entry submitted, scores pending.
  - [Virtual Embryo Challenge](https://virtualembryo.ai): competing now. The reusable parts are public in [virtual-embryo-community](https://github.com/rpinho/virtual-embryo-community): a stage-window checker for atlas sample sheets, and a best-of-k selection tutorial.
  - [adaptyv-challenges](https://github.com/rpinho/adaptyv-challenges): entries to the Adaptyv/Anthropic protein design competition, challenges 3 to 5.
  - [louis](https://github.com/rpinho/louis): pick an autoimmune disease and get trust-ranked CD4+ T-cell drug targets from a genome-scale Perturb-seq screen.
  - [autoregulation](https://github.com/rpinho/autoregulation): gene regulatory network stability analysis, code from my PhD (Feldman lab, Stanford).
- **Math:** [math-certificates](https://github.com/rpinho/math-certificates), an index of explicit, exactly checked bounds on open optimization constants. Each entry states its verification level: AI review only, an independent checker, or Lean.
  - Six of these are merged into Terence Tao's [optimization-constants table](https://github.com/teorth/optimizationproblems): C86 ≤ 1.8117251, C82 < 0.2534449, and C68, C42, C44 and C70. [Eighteen more pull requests are open](https://github.com/teorth/optimizationproblems/pulls?q=is%3Apr+author%3Arpinho), several of them improving the merged ones.
  - Public postings on Hexagon: [C86](https://hexagonmath.org/2610.00425), [C82](https://hexagonmath.org/2610.00426) and [Korenblum's c2](https://hexagonmath.org/2610.00399), plus later bounds for [C44](https://hexagonmath.org/2610.00694), [C86](https://hexagonmath.org/2610.00695) and [C68](https://hexagonmath.org/2610.00696).
- **Physics:** [ai-physics](https://github.com/rpinho/ai-physics), certified bounds on published results, exact checks with independent referees, and bug reports on physics software.
- **Astronomy:** [planet-hunt](https://github.com/rpinho/planet-hunt), AI agents searching NASA TESS data for small planets. Four candidate-planet research notes submitted to RNAAS, all four corrected after a re-audit.

## Learning

- [family-learning-games](https://github.com/rpinho/family-learning-games): 13 self-hosted learning games and an illustrated story book that writes a new chapter every night, in one hub.

## Agents and tools

- [rstack](https://github.com/rpinho/rstack): the stack I run research agents on. A research harness with checks against overfitting, stalled work and unapproved outreach; a file-based knowledge base the agents maintain; and the guards, scheduled jobs and lints that keep it honest, with tests. Point Claude Code or Codex at it to install.
- [sentinel](https://github.com/rpinho/sentinel): two-stage incident detector for open-source repos, built with Codex.
- [prediction-market-mm](https://github.com/rpinho/prediction-market-mm): a passive market maker for the Orderbook Prediction Market Challenge, plus the harness used to tune it.
