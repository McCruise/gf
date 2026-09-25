We are asking for approval for the continued use of GMI0184, the Standard Initial Margin Model, version 2.8.2, within SCB AG. The model is used to calculate posted and collected initial margin in line with the ISDA SIMM methodology.
As part of the country assessment, we reviewed the Group validation outcome, the model’s local use, the relevant limitations, the compensating controls and the latest performance monitoring results. Overall, the model has been assessed as Acceptable, which is aligned with the Group Model Validation conclusion.
There are no material weaknesses or identified concerns. There is one immaterial issue related to the use of HistSim VaR for benchmarking and backtesting for equity products, but there is already a remediation plan in place, with a target closure date of 30 September 2026.
The known model limitations and the related compensating controls have also been assessed for SCB AG. These are mainly covered through quarterly monitoring, daily backtesting, stress testing and risk-not-in-SIMM assessments. The recent monitoring results have remained within the relevant thresholds.
These points, including the open issue and the compensating controls, were already discussed at the Model Risk Forum. As the model is rated RR3, ERC approval is required, so today we are requesting approval for its continued use.




Thank you, Magdalena. I will briefly cover the independent validation outcome, the issues relevant to SCB AG, the monitoring results and the final reviewer assessment.

The Group validation was a targeted review of the migration of the Aggregation and Margining model from Active Pivot to Cortex. The underlying methodology had been validated previously, while this review focused on whether the model was correctly reimplemented in Cortex. The Group validation outcome was Conditionally Acceptable, and the proposed SCB AG outcome is aligned with that assessment.

In terms of validation findings, there is one material issue, four identified concerns and two immaterial issues relevant to the assessment.

The material issue is GAME-104046, concerning residual trade-count mismatches between the source systems and Cortex across OTC, repo and ETD portfolios. Most causes have been identified, but some residual mismatches still require resolution or verification in production. The remediation has been submitted and the issue is currently under closure review by GMV.

The four identified concerns relate to the treatment of foreign-currency collateral, the treatment of dynamic initial margin, trades missing from TDS, and NaN MtM values in Cortex and Front Office valuation outputs. Remediation activities and monitoring have been defined. The current target dates are November 2026 for the foreign-currency collateral issue, December 2026 for dynamic initial margin and missing trades, and January 2027 for the NaN MtM issue.

There are also two immaterial issues: illiquid-position identification and minor implementation defects in the Limit batch. Both are currently under closure review. I have not gone into further detail because they were assessed as immaterial.

Moving to monitoring, the latest quarterly backtesting relates to the Active Pivot implementation and was previously presented to the Committee. At trade level, 95.4% of the Anderson–Darling results were Green. All FX swaps were Green, and no FX forwards received a Red outcome.

At portfolio level, three representative SCB AG portfolios were tested. Two received Green outcomes under both the Anderson–Darling and Cramér–von Mises tests. One portfolio received an Amber outcome, but this was caused by exposure overestimation. The result therefore indicates conservative performance rather than an underestimation of counterparty exposure. For AG, the Anderson–Darling result is particularly relevant because it places greater weight on the tails and is more aligned with PFE monitoring.

These monitoring results provide historical performance evidence for the Active Pivot implementation. The Cortex implementation is supported separately by the migration validation and parallel-run testing.

The model retains a materiality rating of 4 and an uncertainty rating of D, resulting in an overall model risk rating of RR4.

Based on the Group validation, the documented controls and the monitoring evidence, the proposed SCB AG assessment is Conditionally Acceptable for the Other Traded Risk use case, in line with GMV’s conclusion. No additional country-specific issues were identified through this attestation.
