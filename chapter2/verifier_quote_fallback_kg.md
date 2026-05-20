# Verifier Quote + Fallback Trace KG (Chapter 2)

Generated: 2026-05-14T13:22:17+02:00

## Coverage

- records: `195`
- records with quote_text: `90`
- records with needs_manual_review=true: `3`
- parsed verifier log files: `9`
- total fallback batches captured: `81`

## Inputs

- `docs/citation_verification/ch2_full_verifier_run_20260510.err.log`
- `docs/citation_verification/ch2_full_verifier_run_20260510.out.log`
- `docs/citation_verification/verify_ch2_live_20260505.log`
- `docs/citation_verification/verify_ch2_live_20260505_full_post_tightening.log`
- `docs/citation_verification/verify_ch2_live_20260505_post_tightening.log`
- `docs/citation_verification/verify_ch2_post_tightening_final_77.log`
- `docs/citation_verification/verify_ch2_post_tightening_full_run.log`
- `docs/citation_verification/verify_ch2_post_tightening_table_cleanup.log`
- `docs/citation_verification/verify_ch2_targeted_top10_20260505.log`

## Sample Trace Rows

- row `1` key `Benalcazar2024` verdict `partial` conf `high` fallback_batches `0`
  - quote_page: `4`
  - quote: The formulation of the optimization component ensures the effective utilization of the PV-battery sy
- row `2` key `Rezaeimozafar2024` verdict `partial` conf `high` fallback_batches `0`
  - quote_page: `1`
  - quote: An RL-based BESS control that minimizes electricity costs for prosumers.
- row `3` key `Watari2021` verdict `partial` conf `high` fallback_batches `1`
  - quote_page: `5`
  - quote: Each shiftable appliance is characterized by four parameters [40]: (1) its operating time, (2) its c
- row `4` key `Milis2018` verdict `partial` conf `high` fallback_batches `0`
  - quote_page: `3`
  - quote: In order to investigate the impact of electricity tariff design on the adoption of battery storage,
- row `4` key `liDeepReinforcementLearning2023Full` verdict `partial` conf `high` fallback_batches `0`
  - quote_page: `23`
  - quote: this section reviews the applications of DRL for the optimal dispatch issues in SG operations, and the reviewed methods are summarized along with the references in Tables 2–4.
- row `5` key `Li2023ProcIEEE` verdict `partial` conf `high` fallback_batches `0`
  - quote_page: `23`
  - quote: In conclusion, this section reviews the applications of DRL for the optimal dispatch issues in SG operations, and the reviewed methods are summarized along with the references in Tables 2–4.
- row `5` key `Milis2018` verdict `partial` conf `high` fallback_batches `1`
  - quote_page: `6`
  - quote: throughout the year in scenario C, as the system tries to exploit any price arbitrage opportunities
- row `6` key `Talent_2018` verdict `supported` conf `high` fallback_batches `0`
  - quote_page: `2`
  - quote: there is a benefit in storing cheap electricity generated from a PV system to offset energy consumpt
- row `6` key `Varghese2025` verdict `` conf `` fallback_batches `0`
  - quote_page: `n/a`
  - quote: 
- row `7` key `Milis2018` verdict `partial` conf `medium` fallback_batches `3`
  - quote_page: `9`
  - quote: the effect of two policy interventions is studied: (i) block capacity pricing and (ii) the combinati
- row `7` key `Watari2021` verdict `` conf `` fallback_batches `0`
  - quote_page: `n/a`
  - quote: 
- row `8` key `Milis2018` verdict `` conf `` fallback_batches `0`
  - quote_page: `n/a`
  - quote: 
- row `8` key `Talent_2018` verdict `partial` conf `high` fallback_batches `1`
  - quote_page: `11`
  - quote: The battery under demand tariff optimisation typically retains a higher SOC in the morning, up until
- row `9` key `Milis2018` verdict `` conf `` fallback_batches `0`
  - quote_page: `n/a`
  - quote: 
- row `9` key `Norouzi2025` verdict `partial` conf `high` fallback_batches `6`
  - quote_page: `103`
  - quote: Given the significant impact of the battery's capital and replacement costs on the NPC, it is crucia
- row `10` key `Talent_2018` verdict `partial` conf `high` fallback_batches `0`
  - quote_page: `2`
  - quote: the method developed in this research study can be used to compare the sizing and energy scheduling
- row `11` key `Milis2018` verdict `` conf `` fallback_batches `0`
  - quote_page: `n/a`
  - quote: 
- row `11` key `Norouzi2025` verdict `partial` conf `high` fallback_batches `0`
  - quote_page: `94`
  - quote: The designed integrated optimisation with a rule-based EMS is applied to the assumed pricing scenari
- row `12` key `Talent_2018` verdict `` conf `` fallback_batches `0`
  - quote_page: `n/a`
  - quote: 
- row `12` key `mulderRegulationEnergyMarkets2020` verdict `partial` conf `high` fallback_batches `1`
  - quote_page: `118`
  - quote: Agents can switch to other suppliers or consumers without any cost
- row `13` key `Norouzi2025` verdict `` conf `` fallback_batches `0`
  - quote_page: `n/a`
  - quote: 
- row `13` key `Talent_2018` verdict `partial` conf `high` fallback_batches `0`
  - quote_page: `2`
  - quote: the method developed in this research study can be used to compare the sizing and energy scheduling
- row `14` key `Norouzi2025` verdict `supported` conf `high` fallback_batches `0`
  - quote_page: `43`
  - quote: To address the lack of incentive, dynamic pricing is proposed and implemented in some countries (e.g
- row `14` key `Talent_2018` verdict `` conf `` fallback_batches `0`
  - quote_page: `n/a`
  - quote: 
- row `15` key `Gorrasi2024` verdict `partial` conf `high` fallback_batches `0`
  - quote_page: `3`
  - quote: In addressing the limitations of static limits, the concept of Dynamic Operating Envelopes (DOEs) ha
- row `15` key `Norouzi2025` verdict `` conf `` fallback_batches `0`
  - quote_page: `n/a`
  - quote: 
- row `16` key `Ahmadi2025` verdict `partial` conf `high` fallback_batches `0`
  - quote_page: `8`
  - quote: weighting factors ω and ω, k ∈ {1,2,…,n} for CO2, electricity cost, self-consumption, and congestion
- row `16` key `mulderRegulationEnergyMarkets2020` verdict `` conf `` fallback_batches `0`
  - quote_page: `n/a`
  - quote: 
- row `17` key `Khorram2020` verdict `partial` conf `medium` fallback_batches `1`
  - quote_page: `5`
  - quote: Adding constraints by scenarios that are considering user comfort, might be limited the power reduct
- row `17` key `Talent_2018` verdict `` conf `` fallback_batches `0`
  - quote_page: `n/a`
  - quote: 

## Graph Semantics

- `claim -> source` via `cited_by`
- `source -> evidence` via `supported_by`
- `claim -> trace` via `searched_with`
- `trace -> evidence` via `selected_quote`

