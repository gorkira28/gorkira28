# Hi, I’m Kira Gor, BDS, MPH

I’m a clinician-trained epidemiologist and healthcare data analyst who turns surveillance, clinical, observational, and geospatial data into clear, reproducible evidence for public-health decisions.

**[Explore my portfolio website](https://gorkira28.github.io/)** · [LinkedIn](https://www.linkedin.com/in/dr-kira-gor/) · [Email](mailto:gor.kira.28@gmail.com)

> Open to healthcare data analyst, epidemiologist, biostatistician, clinical data analyst, and related opportunities with employers able to support future U.S. work authorization.

## Featured analytics projects

### 1. Provisional Drug-Involved Overdose Signals — SAS + Python

**Decision question:** Which drug-involvement signals changed most in the latest comparable annual periods, and where did HHS regional patterns differ from the national direction?

- Analyzed 11,088 CDC/NCHS records across 12 drug categories, 10 HHS regions, and the U.S. aggregate
- Used non-overlapping annual snapshots to avoid treating heavily overlapping rolling periods as independent
- Built a Python acquisition, QA, trend-analysis, and visualization workflow with an independent SAS validation program
- Found broad national declines alongside emerging exceptions, including ketamine nationally and cocaine in Regions 8 and 9

**Tools:** SAS, Python, CDC/NCHS mortality surveillance, log-linear trends, QA/QC  
**View:** [Repository](https://github.com/gorkira28/provisional-overdose-drug-signals) · [Dashboard](https://github.com/gorkira28/provisional-overdose-drug-signals/blob/main/outputs/figures/overdose_drug_signal_dashboard.png)

### 2. Emergency Department Throughput — Python + DuckDB SQL

**Decision question:** Where do publicly reported emergency-department time measures indicate operational benchmarking priorities, and how does reporting completeness limit interpretation?

- Analyzed CMS Care Compare data for 4,658 facilities and six ED measures
- Built a reproducible Python acquisition workflow with date-stamped extracts and SHA-256 manifests
- Used DuckDB SQL for transformation, facility-level joins, and explicit QA checks
- Found a 154-minute median across 4,052 reporting hospitals and a substantial psychiatric-measure reporting gap

**Tools:** Python, DuckDB SQL, CMS Care Compare, bootstrap inference, healthcare operations, QA/QC  
**View:** [Repository](https://github.com/gorkira28/cms-ed-throughput-benchmarking) · [Dashboard](https://github.com/gorkira28/cms-ed-throughput-benchmarking/blob/main/outputs/figures/cms_ed_throughput_dashboard.png)

### 3. Clinical Trial Results Transparency — SAS + Python

**Decision question:** How often are summary results available for completed Phase 2–4 type 2 diabetes trials after allowing at least 12 months from primary completion?

- Analyzed 865 eligible ClinicalTrials.gov records from a reproducible API snapshot
- Built a Python acquisition, cohort-construction, statistical-analysis, QA, and visualization workflow
- Added an independent SAS validation program with statistical testing and logistic regression
- Found posted summary results for 52.0% of eligible trials, with clear limits on causal and legal interpretation

**Tools:** SAS, Python, ClinicalTrials.gov API, biostatistics, QA/QC  
**View:** [Repository](https://github.com/gorkira28/type-2-diabetes-trial-results-reporting) · [Dashboard](https://github.com/gorkira28/type-2-diabetes-trial-results-reporting/blob/main/outputs/figures/trial_results_transparency_dashboard.png)

### 4. Pertussis Surveillance Priorities — SQL + QGIS

**Decision question:** Where do high population-adjusted incidence and high operational case burden point to different surveillance priorities?

- Analyzed the CDC’s 2025 provisional pertussis report across 52 reporting jurisdictions
- Built a typed DuckDB SQL workflow with validation, ranking, threshold flags, and exportable results
- Prepared a QGIS-ready state join with explicit handling of New York State and New York City
- Reconciled jurisdiction records exactly to the reported national total of 28,783 cases

**Tools:** DuckDB SQL, QGIS, epidemiologic surveillance, QA/QC  
**View:** [Repository](https://github.com/gorkira28/pertussis-2025-surveillance-priorities) · [Dashboard](https://github.com/gorkira28/pertussis-2025-surveillance-priorities/blob/main/outputs/figures/pertussis_surveillance_dashboard.svg)

### 5. Hidden Hypertension — SAS + Python

**Decision question:** How large is the gap between measured hypertension and reported diagnosis awareness among U.S. adults?

- Conducted a complex-survey analysis of 7,938 adults in NHANES 2017–March 2020
- Used survey-weighted prevalence, Taylor confidence intervals, domain estimation, and survey logistic regression
- Implemented parallel SAS and Python workflows with validation and threshold-sensitivity checks
- Estimated that 39.8% of adults meeting the primary analytic proxy reported no prior diagnosis

**Tools:** SAS, Python, NHANES, complex-survey methods  
**View:** [Repository](https://github.com/gorkira28/nhanes-hypertension-awareness-gap)

### 6. Texas Diabetes Vulnerability Atlas — Python + SAS + GIS

**Decision question:** Where do diabetes burden and barriers to health overlap across Texas counties?

- Integrated CDC PLACES estimates with U.S. Census cartographic boundaries
- Built a transparent percentile-based composite using diabetes, obesity, inactivity, and insurance measures
- Included Spearman correlation, sensitivity analysis, data-quality checks, and GIS-ready outputs
- Preserved all 254 county boundaries and documented suppressed estimates

**Tools:** Python, SAS, QGIS/ArcGIS-compatible GeoJSON, spatial analysis  
**View:** [Repository](https://github.com/gorkira28/texas-diabetes-vulnerability-atlas) · [Portfolio case study](https://gorkira28.github.io/#work)

## Technical toolkit

- **Analysis:** SAS, R, Python, SQL, SPSS, Epi Info
- **Visualization and GIS:** ArcGIS, QGIS, Tableau, Power BI
- **Methods:** epidemiologic study design, regression, complex-survey analysis, propensity-score methods, machine learning, reproducible analysis, QA/QC
- **Data environments:** infectious-disease surveillance, clinical trials, observational research, REDCap, NEDSS

## Selected research

- First-author study of juvenile idiopathic arthritis, anxiety, and depression in 192,019 U.S. children and adolescents (2025)
- Co-author of a machine-learning study of juvenile idiopathic arthritis screening in 223,195 U.S. children, published in *Frontiers in Public Health* (2025)
- Co-author of a propensity-score-weighted study on asthma and juvenile idiopathic arthritis in *Pediatric Rheumatology* (2026)

## How I work

I prioritize transparent assumptions, reproducible workflows, careful data-quality checks, appropriate interpretation, and communication that distinguishes association from causation. All portfolio projects use public data and exclude PHI, confidential employer information, and proprietary Texas DSHS material.
