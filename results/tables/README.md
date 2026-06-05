

## GLP1_FAERS_Results.xlsx

Signal detection results from FDA-FAERS 2025 pharmacovigilance analysis  
of GLP-1 receptor agonists across 82,558 adverse event reports.

---

##  Sheet Summary

### 1. Semaglutide_Signals
- **28 significant signals** detected for Semaglutide (OZEMPIC, WEGOVY, RYBELSUS)
- Strongest signal: **Optic Ischaemic Neuropathy** (ROR = 124.88) — vision loss risk
- Other critical signals: Impaired Gastric Emptying (ROR = 51.53), Ileus (ROR = 27.59), Pancreatitis (ROR = 8.70)
- Predominantly **systemic and serious ADEs**

### 2. Tirzepatide_Signals
- **24 significant signals** detected for Tirzepatide (MOUNJARO, ZEPBOUND)
- Strongest signal: **Therapeutic Response Changed** (ROR = 71.04) — drug efficacy concern
- Highest frequency signal: **Incorrect Dose Administered** (n = 11,583, ROR = 16.94) — pen device usability issue
- Predominantly **device and injection-related ADEs**

### 3. All_GLP1_ADEs
- Complete ADE frequency table across all 82,558 GLP-1 cases
- Top ADE: Incorrect Dose Administered (11,790 reports)
- Covers 194,868 total adverse event records

### 4. Outcomes
- Hospitalisation is the most common serious outcome for both drugs
- Death, Disability, and Life-Threatening outcomes also documented
- Total outcome records: 31,270

### 5. Demographics
- Majority of reporters in the **41–60 age group**
- Female reporters predominate — consistent with GLP-1 prescribing patterns

---

##  Column Definitions

| Column | Description |
|---|---|
| `ADE` | Adverse Drug Event (MedDRA Preferred Term) |
| `n` | Number of reports for this drug-ADE pair |
| `PRR` | Proportional Reporting Ratio |
| `ROR` | Reporting Odds Ratio |
| `ROR_95CI_low` | Lower bound of 95% Confidence Interval |
| `ROR_95CI_high` | Upper bound of 95% Confidence Interval |
| `Chi2` | Chi-square statistic |
| `p_value` | p-value of association |
| `SIGNAL` | 🚨 YES = PRR ≥ 2, Chi² ≥ 4, n ≥ 3 |


