# ESG Clauses
Clauses to include in the International Federation of Consulting Engineers (FIDIC) form of EPC contracts, obliging the contractor (and any subcontractors) to act sustainably in carrying out the works.

[Chancery Lane Project](https://chancerylaneproject.org/climate-clauses/net-zero-obligations-in-fidic-engineering-procurement-and-construction-epc-contracts/)
___
# Additional Clauses

## [4.25] Climate Obligations

### [4.25.1] The Contractor shall:

(a) measure and calculate its Projected Total Emissions and Actual Total Emissions for each Emissions Reporting Period in accordance with the GHG Protocol;

(b) engage an independent consultant appropriately qualified to provide climate impact assessment and emissions reporting services to verify the calculations in [4.25.1](a);

(c) provide an Annual Emissions Report to the {{employer}} no later than {{daysAfterReportingEnd}} (Business) Days after the end of each Emissions Reporting Period;

(d) Offset its Residual Emissions relating to performance of this Agreement for each{{#if annualReportingUsed}} financial year{{else}} Emissions Reporting Period{{/if}} within {{daysAfterPeriodEnd}} days of the end of such financial year/ Emissions Reporting Period;

(e) develop the Contract Target Plan within {{contractTargetPlanTimeframe}} of signing this Agreement and implement the Contract Target Plan by the Contract Target Date; and

(f) take all reasonable steps to reach its Net Zero Target.

### [4.25.2] Unless the {{employer}} otherwise consents, the Contractor will only enter into a Subcontract:

(a) with a Subcontractor who has set a Net Zero Target and specified a Contract Target; and 

(b) that includes a copy of this clause [4.25] and its related definitions.

***[Drafting note: This may need adjusting depending on the size and capability of subcontractors, as it may place an unfair burden on those lacking the resources to meet the reporting requirements. However, to appropriately set a Contract Target and for the Scope 3 Emissions of the entire chain to be properly assessed, this is necessary. This could be supported by providing funding to subcontractors (i.e. by extending the Employer Assistance clause) in order to decarbonise the supply chain.]***

### [4.25.3] If in any Emissions Reporting Period the Actual Total Emissions for that Emissions Reporting Period exceed the Projected Total Emissions for that Emissions Reporting Period/ Actual Total Emissions of the previous Emissions Reporting Period by more than {{emissionsAllowancePercentage}}%, the Contract Price payable to the Contractor or Subcontractor (as applicable) shall be reduced by {{reductionPercentage}}% per {{specifedUnit}} of CO2 that the Actual Total Emissions exceed the Projected Total Emissions up to {{premiumPortionCap}}% of the contract]. 

***[Drafting note: The first bracketed drafting option may be a disincentive to setting ambitious targets by encouraging the Contractor to overestimate their projected emissions, unless the Employer also evaluates the Projected Total Emissions value and provides a benefit for an ambitious value. A disincentive for exceeding the previous period's Actual Total Emissions may be preferable, since it encourages a reduction in emissions.]***

***[Drafting note: The disincentive should be proportionate to the failure, otherwise once the Contractor knows that it will not meet its targets it has no incentive to minimise such failure. This disincentive could be adjustable depending on the proportion of exceeded emissions (as in Ming's Clause) or a fixed figure payable to an environmental charity (as in Jessica's Clause or Owen's Clause). In relation to subcontracts, consider whether the reduction should be deducted per subcontractor or varied according to the value of the relevant Subcontract.]***

### [4.25.4 If the Contractor or Subcontractor (as applicable) fails to meet [any of its other obligations under this clause [4.25]]: 

***[Insert specific obligations that should attract a penalty for breach]***

{{fixedPenaltyFigure}} payable to an environmental charity {{nameOfCharity}}

***[could specify wallet address as source to expect transfers from to be validated]***
***[Insert disincentive or a list of disincentives applicable to different obligations].]***

***[Drafting note: If including this bracketed clause [4.25.4], disincentives should only be applicable to breach of those clauses that create sufficiently clear obligations so that what constitutes a breach is clear. For example, the achievement of the obligation to "take all reasonable steps to reach the Net Zero Target" would not be easy to objectively determine and implementing the Contract Plan may be similarly difficult to measure.]***

## Employer Assistance with Climate Obligations

The {{employer}} shall take reasonable steps to procure that the Contractor or Subcontractor (as applicable) is provided with appropriate training and/or resources to enable it to meet its obligations under Clause [4.25].

***[Drafting note: As explained above, this may need expanding to cover financial assistance to enable reporting by subcontractors.]***

ContractValue {{contractValue}}

Projected Total Emissions: {{projectedTotalEmissions}} tonnes of CO2

Residual Emissions:
cap equaling the premium portion of the contract

{{#if usingMingsClause}}proportion of exceeded emissions Ming's Clause{{else}}or a fixed figure payable to an environmental charity (as in Jessica's Clause or Owen's Clause).{{/if}} 

***[In relation to subcontracts, consider whether the reduction should be deducted per subcontractor or varied according to the value of the relevant Subcontract.]***

{{#if deductedPerSubcontractor}}amount is deducted per subcontractor{{/if}}


***[scores are unverified at the moment but could time restrict this]***

***[define the frequency that scores checked and if there is a time window allowed to restore the score. Could mandate verification at regular defined intervals e.g. annually. Could also look at an increasing threshold over time up to a certain level as companies are aiming towards net zero]***

Contract Value {{contractValue}}
Contractor Wallet {{contractorWalletAddress}}

# OpenESG Based Clauses

For the purposes of monitor ESG commitments, the Contractor or Subcontractor (as applicable) will agree to use the [OpenESG] (https://www.openesg.com/) register to measure their ESG Score. 

The url to validate will be {{websiteUrl}}

The Contractor or Subcontractor (as applicable) will agree to keep their OpenESG Score equal to or greater than the following values:

Committed ESG Scores
* {{#if verifiedScoreRequired}}The Score must be verified{{else}}The Score can be unverified{{/if}}
* Committed Environmental Score: {{environmentalScore}}
* Committed Governance Score: {{governanceScore}}
* Committed Social Score: {{socialScore}}

An allowance up to the following threshhold is permitted depending if the scores require verification.
* The permitted verified threshold is:{{verifiedThreshold}}%
* The permitted unverified threshold is:{{unverifiedThreshold}}%

If in any ESG Reporting Period the Actual Total ESG Scores for that ESG Reporting Period is lower than the Committed ESG Scores by more than the allowed threshold, the Contract Price payable to the Contractor shall be reduced by {{reductionPercentage}}% of the Contract Value. The value of the reduced figure is payable in {{penaltyCurrency}} to an environmental charity {{nameOfCharity}} at wallet address {{charityWalletAddress}}.