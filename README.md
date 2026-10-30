# Orrin Chen

MEng student in Industrial Engineering (Mechanical & Industrial Engineering) at the University of Toronto, focusing on agent systems, RL post-training, applied ML, and quantitative research / operations research. Seeking 2027 new-grad roles.

## Selected projects

- **[Sandbox](https://github.com/OrrinChen/Sandbox)**: Sandboxed tool-use agent evaluation harness with typed tools, JSONL traces, deterministic validators, replay, and regression gates. In a recorded offline, fixture-backed study (64 tasks, 320 runs), final-answer-only grading overestimated validated correctness by 56.2 percentage points, and validators caught 180 silent failures. An Agentic RL extension is scaffolded; its held-out model results are not yet run.
- **[multimodal_FEE](https://github.com/OrrinChen/multimodal_FEE)**: Financial Evidence Engine for claim-level verification: claim decomposition, evidence retrieval, numeric reconciliation, and validator-gated verdicts. On 60 due-diligence tasks over a constructed 320-document corpus, full-engine verdict accuracy was 83.3% vs. 66.7% for BM25 (research evaluation, not live SEC-scale accuracy).
- **[LLM_heuristic](https://github.com/OrrinChen/LLM_heuristic)**: Sandboxed LLM-guided program search for OR heuristics (bin packing, routing) with static validation, subprocess isolation, and archives. Search covers 3 benchmarks and 15 held-out slices, with no claim of universal dominance over classical OR baselines.
- **[PortfolioOS](https://github.com/OrrinChen/PortfolioOS)**: Audit-ready platform for portfolio rebalance, scenario analysis, execution simulation, TCA, and alpha research. Recorded event-aware `revision_1m` study (external US WRDS methodological benchmark): rank-IC t-statistic ~3.61 (backtest-based, no live trading).
- **[Chip-Placement](https://github.com/OrrinChen/Chip-Placement)**: Graph placement engine comparing masked PPO and simulated annealing on chip netlists, with a frozen linear wirelength proxy. Proxy Spearman 0.9008 within design and 0.3859 across designs; 0 DRC violations on the Ariane reference-flow check (reference floorplan, not an RL placement).

## Focus areas

Tool-using agent evaluation, RL and post-training (PPO, GRPO, SFT), retrieval and evidence verification, portfolio and execution research, and combinatorial optimization.

## Links

- GitHub: https://github.com/OrrinChen
- LinkedIn: https://www.linkedin.com/in/orrin-chen-1b4b59255/
