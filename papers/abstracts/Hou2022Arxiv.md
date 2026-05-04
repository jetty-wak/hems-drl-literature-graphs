# Performance Comparison of Deep RL Algorithms for Energy Systems Optimal Scheduling

**Key:** `Hou2022Arxiv`  
**Type:** article  
**Author(s):** Hou, Shengren and Salazar, Edgar Mauricio and Vergara, Pedro P. and Palensky, Peter  
**Year:** 2022  
**Venue:** arXiv preprint arXiv:2208.00728  
**URL:** https://arxiv.org/abs/2208.00728  
**Cited in:** Ch3, Ch4, Ch7/8  

## Why cited in this thesis

- Paper benchmarks DRL algorithms against a perfect-foresight (oracle/clairvoyant) baseline and uses normalised cost gap to oracle as the primary comparison metric; directly motivates Eq. kpi-oracle-gap.

## Thesis claims supported

- **[Ch4]** Under this distinction, optimisation provides the reference structure: it defines the feasible set, the oracle cost lower bound, and the benchmarking metrics against which the learned policy is assessed
- **[Ch4]** Network-aware validation pathways, such as voltage-constrained or feeder-coupled formulations, are treated as important extensions
- **[Ch4]** For this reason, tariff design is treated here as part of the benchmark definition
- **[Ch4]** In this thesis, the oracle reference denotes a non-deployable perfect-foresight optimisation benchmark used only as a best-case lower bound for comparison
- **[Ch4]** In this thesis, the optimality gap refers to the percentage deviation between the cost achieved by the evaluated controller and the cost achieved by the relevant optimisation benchmark, usually the perfect-foresight oracle; operationally, this is computed from eq:gap_def and reported in percentage form as $100$
- **[Ch4]** Second, optimisation and RL/DRL remain comparable because they share the same settlement logic, the same state transition constraints, and the same interpretation of control authority under that boundary
- **[Ch3]** Hou et al.\ compare DDPG, TD3, SAC, and PPO with a mathematical-programming model for energy-system scheduling and report feasibility failures under large peak consumption Hou2022Arxiv .
- **[Ch3]** Energy-system RL comparisons show that algorithm choice, penalty coefficients, and function-approximation choices can affect cost and feasibility outcomes when learned controllers are compared with optimisation references Hou2022Arxiv,Gao2024LinearRL .
- **[Ch3]** Penalty-based constraint handling is common in energy-system DRL, but it introduces additional hyperparameters that can affect feasibility and performance Hou2022Arxiv .

## Verified evidence excerpts

> UNVERIFIED — arXiv only, no local PDF. URL: https://arxiv.org/abs/2208.00728 `[needs_manual_review]`
