# Safe exploration in continuous action spaces

**Key:** `Dalal2018`  
**Type:** misc  
**Author(s):** Dalal, Gal and others  
**Year:** 2018  
**Cited in:** Ch2, Ch3, Ch7/8  

## Why cited in this thesis

- Paper introduces safety constraints as hard binary predicates in continuous action-space RL; motivates V_hard as a post-hoc binary per-step constraint violation count and the infeasibility criterion.
- Paper frames safety as a conjunction of hard constraints that must ALL be satisfied for an episode to be considered safe; motivates the AND-conjunction structure of Eq. kpi-feasibility.

## Thesis claims supported

- **[Ch2]** Explicit projection methods enforce feasibility at every step
- **[Ch3]** Hard constraints require a different treatment: the controller must either be prevented from executing infeasible actions through projection or trained within a constrained formulation that exposes feasibility explicitly
- **[Ch3]** Soft objectives can be represented through reward shaping
- **[Ch3]** Dalal et al.\ describe an action-correction safety layer for continuous action spaces Dalal2018 .
- **[Ch3]** Safety-layer work illustrates the alternative of modifying continuous actions through an action-correction formulation before execution Dalal2018 .

## Verified evidence excerpts

> UNVERIFIED — arXiv only. URL: https://arxiv.org/abs/1801.08757. Earlier code had WRONG arXiv ID (1809.05078). Fixed 2026-04-18. `[needs_manual_review]`

> UNVERIFIED — arXiv only. See row 15. `[needs_manual_review]`
