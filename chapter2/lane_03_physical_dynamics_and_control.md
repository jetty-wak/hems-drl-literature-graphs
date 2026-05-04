# Physical Dynamics + Controller Physiology

Battery/SoC dynamics, control behavior, and feasibility physics.

## Summary

- Source entries scanned: `56`
- Node count: `72`
- Edge count: `122`
- Concepts: `8`
- Claims: `24`
- Sources: `16`
- Evidence nodes (page-level): `24`

## Page-Level Evidence Node Contract

- source document
- page number
- matched concept
- short evidence note
- confidence/status

## Evidence Preview

- `evidence:11:3` | page `3` | verdict `partial` | confidence `high`
  - source: `E:\RP1\RP1_main\docs\hub\papers\Theme_05_Battery_Storage_EV\054_Steering_the_adoption_of_battery_storage_through_electricity_tariff_design.pdf`
  - note: The passage addresses tariff design's impact on battery storage adoption, but the claim is about battery operation strategy. Adoption and operational design are related but dist...
- `evidence:12:9` | page `9` | verdict `partial` | confidence `medium`
  - source: `E:\RP1\RP1_main\docs\hub\papers\Theme_05_Battery_Storage_EV\054_Steering_the_adoption_of_battery_storage_through_electricity_tariff_design.pdf`
  - note: The passage discusses tariff design mechanisms (block capacity pricing, real-time energy pricing) affecting battery storage behavior, which relates to the claim's core concept....
- `evidence:13:3` | page `3` | verdict `partial` | confidence `high`
  - source: `E:\RP1\RP1_main\docs\LITERATURE_REVIEW_battery_scheduling_dynamic_tariffs_papers\Theme_A_MILP_Optimization_Approaches_for_Battery_Scheduling\A6_Optimal_Sizing_and_Energy_Scheduling_of_Photovoltaic-Battery_Systems_Under_Different_Tariff_Structures.pdf`
  - note: Passage shows tariff structures affect economic viability of battery operations, supporting that tariffs change operational outcomes. However, it doesn't directly address how ta...
- `evidence:14:132` | page `132` | verdict `partial` | confidence `high`
  - source: `E:\RP1\RP1_main\docs\citation_verification\recovered_pdfs\from_root_staging\Norouzi2025_Farshid_Norouzi_Final.pdf`
  - note: Passage shows tariff regimes (dynamic pricing) affect battery control strategy selection (RL vs GA behavior differs under peak pricing), supporting the claim's core idea but not...
- `evidence:15:2` | page `2` | verdict `supported` | confidence `high`
  - source: `E:\RP1\RP1_main\docs\LITERATURE_REVIEW_battery_scheduling_dynamic_tariffs_papers\Theme_A_MILP_Optimization_Approaches_for_Battery_Scheduling\A6_Optimal_Sizing_and_Energy_Scheduling_of_Photovoltaic-Battery_Systems_Under_Different_Tariff_Structures.pdf`
  - note: The passage directly supports the claim by demonstrating that comparing multiple tariff structures (TOU and demand tariffs) in residential EMS studies yields more informative re...
- `evidence:17:285` | page `285` | verdict `partial` | confidence `high`
  - source: `E:\RP1\RP1_main\docs\hub\papers\Theme_12_Energy_Policy_Markets\001_Regulation_of_Energy_Markets_Economic_Mechanisms_and_Policy_Evaluation.pdf`
  - note: Passage addresses distributed decision-making by multiple firms in energy markets and competitive supply dynamics, but doesn't explicitly discuss investment and dispatch decisio...
- `evidence:19:3` | page `3` | verdict `partial` | confidence `high`
  - source: `E:\RP1\RP1_main\docs\citation_verification\recovered_pdfs\Gorrasi2024_Comparison_of_market_designs_ensuring_network_integrity_in_low_voltage_distribution_systems_with_high_DER_penetration.pdf`
  - note: The passage discusses Dynamic Operating Envelopes as a mechanism to address low-voltage network constraints, supporting the claim that congestion is treated as an explicit const...
- `evidence:1:164` | page `164` | verdict `partial` | confidence `high`
  - source: `E:\RP1\RP1_main\docs\citation_verification\recovered_pdfs\hoogsteen2017cyber_A_Cyber_Physical_Systems_Perspective_on_Decentralized_Energy_Management.pdf`
  - note: The passage confirms that different tools vary in key technical dimensions (energy carriers, timestep size, control systems, optimization methods), supporting the need for expli...
- `evidence:20:8` | page `8` | verdict `partial` | confidence `high`
  - source: `E:\RP1\RP1_main\docs\hub\papers\Theme_02_MARL_Cooperative_Multi_Agent\007_A_novel_user_centric_decentralized_multi_objective_energy_management_system_for_.pdf`
  - note: Passage confirms congestion is treated as an objective function in energy management systems, supporting the claim that congestion receives explicit treatment. However, it doesn...
- `evidence:21:none` | page `n/a` | verdict `n/a` | confidence `n/a`
  - source: `n/a`
  - note: 
- `evidence:22:5` | page `5` | verdict `partial` | confidence `high`
  - source: `E:\RP1\RP1_main\docs\citation_verification\recovered_pdfs\Gorrasi2024_Comparison_of_market_designs_ensuring_network_integrity_in_low_voltage_distribution_systems_with_high_DER_penetration.pdf`
  - note: The passage addresses network integrity constraints and market design, but doesn't explicitly discuss separating price responsiveness from network enforcement or their distinct...
- `evidence:23:none` | page `n/a` | verdict `n/a` | confidence `n/a`
  - source: `n/a`
  - note: 
- `evidence:2:none` | page `n/a` | verdict `n/a` | confidence `n/a`
  - source: `n/a`
  - note: 
- `evidence:30:2` | page `2` | verdict `supported` | confidence `high`
  - source: `E:\RP1\RP1_main\docs\hub\papers\Theme_04_Building_Energy_HVAC\033_Optimisation_algorithms_used_in_home_energy_management_systems_A_review.pdf`
  - note: The passage directly confirms that contemporary HEMS integrate PV and battery storage to improve distributed-resource use and reduce energy expenses, matching the thesis claim's...
- `evidence:35:8` | page `8` | verdict `partial` | confidence `high`
  - source: `E:\RP1\RP1_main\docs\citation_verification\recovered_pdfs\Gorrasi2024_Comparison_of_market_designs_ensuring_network_integrity_in_low_voltage_distribution_systems_with_high_DER_penetration.pdf`
  - note: The passage addresses network constraints in market designs and mentions network admissible limits, supporting the claim's focus on explicit network representation. However, it...
- `evidence:36:12` | page `12` | verdict `partial` | confidence `high`
  - source: `E:\RP1\RP1_main\docs\hub\papers\Theme_02_MARL_Cooperative_Multi_Agent\007_A_novel_user_centric_decentralized_multi_objective_energy_management_system_for_.pdf`
  - note: Passage addresses congestion constraints in energy systems and coordination mechanisms, supporting the claim's mention of congestion limits and coordination. However, it focuses...
- `evidence:3:3` | page `3` | verdict `partial` | confidence `medium`
  - source: `E:\RP1\RP1_main\docs\hub\papers\Theme_01_DRL_SAC_Policy_Optimization\016_Deep_reinforcement_learning_based_multi_objective_energy_management_system_for_m.pdf`
  - note: Passage addresses reward function definition in DRL optimization context, supporting the claim's emphasis on explicit KPI/objective definitions. However, it doesn't cover bounda...
- `evidence:40:1` | page `1` | verdict `partial` | confidence `high`
  - source: `E:\RP1\RP1_main\docs\hub\papers\Theme_04_Building_Energy_HVAC\008_A_hybrid_heuristic_reinforcement_learning_based_real_time_control_model_for_resi.pdf`
  - note: The passage addresses cost minimization for prosumers with PV-battery systems, directly supporting the 'cost' aspect of the claim. However, it does not explicitly mention self-c...
- `evidence:43:1` | page `1` | verdict `partial` | confidence `medium`
  - source: `E:\RP1\RP1_main\docs\hub\papers\Theme_04_Building_Energy_HVAC\008_A_hybrid_heuristic_reinforcement_learning_based_real_time_control_model_for_resi.pdf`
  - note: The passage addresses behind-the-meter battery control and cost minimization, which aligns with the claim's action set and import cost objective. However, the passage doesn't ex...
- `evidence:44:2` | page `2` | verdict `partial` | confidence `medium`
  - source: `E:\RP1\RP1_main\docs\citation_verification\recovered_pdfs\Watari2021_Multi-time_scale_energy_management_framework_for_smart_PV_systems_mixing_fast_and_slow_dynamics.pdf`
  - note: Passage discusses real-time information's role in control decisions but focuses on control approach choice rather than information availability's importance relative to system b...
- `evidence:46:5` | page `5` | verdict `partial` | confidence `high`
  - source: `E:\RP1\RP1_main\docs\citation_verification\recovered_pdfs\Watari2021_Multi-time_scale_energy_management_framework_for_smart_PV_systems_mixing_fast_and_slow_dynamics.pdf`
  - note: Passage demonstrates explicit specification of operating constraints and scheduling parameters for appliances, supporting the claim's point about stated constraints and schedule...
- `evidence:47:3` | page `3` | verdict `partial` | confidence `high`
  - source: `E:\RP1\RP1_main\docs\citation_verification\recovered_pdfs\Watari2021_Multi-time_scale_energy_management_framework_for_smart_PV_systems_mixing_fast_and_slow_dynamics.pdf`
  - note: The passage confirms that MPC uses PV forecasts and iterates schedules, supporting the claim's core mechanism. However, it doesn't explicitly demonstrate that degraded forecasts...
- `evidence:48:8` | page `8` | verdict `partial` | confidence `high`
  - source: `E:\RP1\RP1_main\docs\citation_verification\recovered_pdfs\Arvanitidis2025_Comprehensive_assessment_of_deep_reinforcement_learning_approaches_for_economic_dispatch_in_nuclear_driven_microgrids.pdf`
  - note: Passage demonstrates one specific instance of domain expertise requirement (heat input curve for cost function), supporting the claim's core point about expertise needs for mode...
- `evidence:4:none` | page `n/a` | verdict `n/a` | confidence `n/a`
  - source: `n/a`
  - note: 
