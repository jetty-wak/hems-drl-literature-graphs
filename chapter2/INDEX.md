# RP1 Knowledge Graph Views

This package provides RP1-specific focused graph views with proposal-friendly size and citation evidence depth.

## Focused Lane Subgraphs

- **Scope Boundary + Decentralised HEMS Control**
  - json: `docs/citation_verification/graph_views/lane_01_scope_and_boundary.json`
  - md: `docs/citation_verification/graph_views/lane_01_scope_and_boundary.md`
  - html: `docs/citation_verification/graph_views/lane_01_scope_and_boundary.html`
  - entries: `37`
- **Tariffs, Settlement, and Benchmark Policy**
  - json: `docs/citation_verification/graph_views/lane_02_tariff_and_settlement.json`
  - md: `docs/citation_verification/graph_views/lane_02_tariff_and_settlement.md`
  - html: `docs/citation_verification/graph_views/lane_02_tariff_and_settlement.html`
  - entries: `45`
- **Physical Dynamics + Controller Physiology**
  - json: `docs/citation_verification/graph_views/lane_03_physical_dynamics_and_control.json`
  - md: `docs/citation_verification/graph_views/lane_03_physical_dynamics_and_control.md`
  - html: `docs/citation_verification/graph_views/lane_03_physical_dynamics_and_control.html`
  - entries: `56`
- **Controller Architecture + Safety Coordination**
  - json: `docs/citation_verification/graph_views/lane_04_controller_architecture_and_safety.json`
  - md: `docs/citation_verification/graph_views/lane_04_controller_architecture_and_safety.md`
  - html: `docs/citation_verification/graph_views/lane_04_controller_architecture_and_safety.html`
  - entries: `42`
- **Scaling + Normalization Path**
  - json: `docs/citation_verification/graph_views/lane_05_scaling_and_normalization.json`
  - md: `docs/citation_verification/graph_views/lane_05_scaling_and_normalization.md`
  - html: `docs/citation_verification/graph_views/lane_05_scaling_and_normalization.html`
  - entries: `41`
- **Claim-Evidence Governance**
  - json: `docs/citation_verification/graph_views/lane_06_claim_evidence_governance.json`
  - md: `docs/citation_verification/graph_views/lane_06_claim_evidence_governance.md`
  - html: `docs/citation_verification/graph_views/lane_06_claim_evidence_governance.html`
  - entries: `0`

## Cross-Lane Artifacts

- claim-to-evidence graph: `docs/citation_verification/graph_views/claim_evidence_graph.json`
- proposal-ready compact graph: `docs/citation_verification/graph_views/proposal_ready_compact_graph.json`
- gap report: `docs/citation_verification/graph_views/gap_report.md`

## Heading Pattern Used (adapted to RP1)

- Create focused subgraphs by research lane.
- Build claim-to-evidence graph with page-level evidence nodes.
- Keep one proposal-ready compact graph (20-40 nodes target).
- Query graph for citation/source coverage gaps.

