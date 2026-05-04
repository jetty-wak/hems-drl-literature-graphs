# HEMS-DRL Literature Knowledge Graphs

Interactive knowledge graphs for a Master's thesis on **hierarchical decentralised Deep Reinforcement Learning (DRL) for demand response in Dutch low-voltage microgrids** (Energy and Environmental Sciences, University of Groningen).

These graphs map the **claim–evidence–source relationships** across the academic literature used in the thesis literature review (Chapters 2–4). They are extracted from published papers only; no thesis code, simulation data, or raw datasets are included here.

---

## What Is This?

Each graph view is a **static HTML visualisation** of a bipartite knowledge graph. Three node types appear:

| Colour | Type | Meaning |
|---|---|---|
| Blue | Claim | A statement made in the thesis, attributed to one or more sources |
| Teal | Concept | A research concept or theme the claim belongs to |
| Purple | Source | A published paper (BibTeX key + truncated title) |
| Amber | Evidence | A page-level quote or excerpt from a source that supports the claim |

Edges connect claims to the concepts they address and to the source pages that evidence them.

---

## Repository Layout

```
chapter2/   Claim–evidence graphs for Chapter 2: Literature Review
            (DRL, optimisation, smart-grid EMS, HEMS control, tariffs)

chapter3/   Claim–evidence graphs for Chapter 3: DRL Foundations
            (MDPs, SAC, actor-critic, exploration, action-space design)

chapter4/   Claim–evidence graphs for Chapter 4: Comparative Framework
            (benchmark fairness, oracle reference, KPI definitions)
```

Each chapter folder contains the same set of artefacts:

| File | Description |
|---|---|
| `INDEX.md` | Entry point — lists all lane graphs and cross-lane artefacts |
| `lane_01_scope_and_boundary.*` | Scope boundary + decentralised HEMS control lane |
| `lane_02_tariff_and_settlement.*` | Tariffs, settlement, and benchmark policy lane |
| `lane_03_physical_dynamics_and_control.*` | Physical dynamics + controller physiology lane |
| `lane_04_controller_architecture_and_safety.*` | Controller architecture + safety coordination lane |
| `lane_05_scaling_and_normalization.*` | Scaling + normalisation path lane |
| `lane_06_claim_evidence_governance.*` | Claim–evidence governance lane |
| `claim_evidence_graph.*` | Full cross-lane claim–evidence graph |
| `proposal_ready_compact_graph.*` | Compact 20–40-node summary graph |
| `gap_report.md` | Evidence gap report — claims with weak or missing source support |
| `manifest.json` | Machine-readable lane manifest |

Each lane is available in three formats: `.html` (open in any browser), `.json` (machine-readable), `.md` (plain text summary).

---

## Research Domain

The thesis investigates whether a DRL agent can manage a home energy system (solar PV + battery storage + flexible loads) as well as — or better than — classical MILP optimisation under realistic Dutch electricity market conditions.

Key topics covered in the graphs:

- Behind-the-meter HEMS control under dynamic and capacity tariffs
- Deep reinforcement learning for energy systems (SAC, PPO, DQN)
- MILP/MIQP optimisation as an oracle reference
- Battery state-of-charge dynamics and safety constraints
- Dutch low-voltage distribution grid congestion
- Demand response scheduling and flexibility quantification
- Benchmark fairness protocols for DRL vs optimisation comparisons

---

## How to Use

**View in browser:** Open any `.html` file directly — no server required.

**Load graph data:** Each `.json` file uses the schema:
```json
{
  "nodes": [{"id": "...", "label": "...", "subtitle": "...", "meta": {...}}],
  "edges": [{"source": "...", "target": "..."}]
}
```

**Read the gap report:** `gap_report.md` in each chapter lists claims where source evidence is weak, missing, or only partially supported.

---

## Citation

If you use these graphs in your own work, please cite the thesis when it is published (in progress, University of Groningen, 2026).

---

## Licence

Knowledge graph structure and claim summaries: © 2026 the thesis author. All rights reserved until publication.

Paper titles, BibTeX keys, and page-level quotes are from published third-party works cited under academic fair use.
