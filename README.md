# Hi, I’m Kira Gor, BDS, MPH

I’m a clinician-trained epidemiologist and healthcare data analyst who turns surveillance, clinical, observational, and geospatial data into clear, reproducible evidence for public-health decisions.

**[Explore my portfolio website](https://gorkira28.github.io/)** · [LinkedIn](https://www.linkedin.com/in/dr-kira-gor/) · [Email](mailto:gor.kira.28@gmail.com)

> Open to healthcare data analyst, epidemiologist, biostatistician, clinical data analyst, and related opportunities with employers able to support future U.S. work authorization.

## Featured analytics projects

### 1. CMS Birthing-Friendly Designation Density — DuckDB SQL + Python + GIS

**Decision question:** Where is the CMS Birthing-Friendly designation most sparse after accounting for the population of women ages 15–44?

- Joined the July 2026 CMS Hospital General Information release to Census Vintage 2025 age/sex estimates
- Built a typed DuckDB SQL cleaning layer, exact Poisson intervals, automated QA, and QGIS-ready GeoJSON
- Identified 2,256 designated hospitals across the 50 states and Washington, D.C., or 3.33 per 100,000 women ages 15–44
- Found state density ranging from 2.01 in Nevada to 9.08 in Wyoming while explicitly separating structural designation from clinical safety and geographic access

**Tools:** DuckDB SQL, Python, GeoPandas, QGIS-ready GIS, CMS, Census, QA/QC

**View:** [Repository](https://github.com/gorkira28/cms-birthing-friendly-access) · [Portfolio case study](https://gorkira28.github.io/#work)

### 2. County Behavioral Health Priority Signals — DuckDB SQL + Python + GIS

**Decision question:** Where do model-based county estimates suggest that behavioral-health need and insurance barriers overlap strongly enough to justify deeper local review?

- Ranked diagnosed depression, frequent mental distress, and lack-of-insurance estimates for 2,956 counties with complete CDC PLACES inputs
- Built an auditable equal-weight percentile score in DuckDB SQL and joined it to Census county boundaries
- Exported tested CSV, GeoJSON, GeoPackage, QGIS style, and publication-ready visual outputs
- Identified 296 counties in the highest signal decile while explicitly separating planning triage from causal inference or program evaluation

**Tools:** DuckDB SQL, Python, CDC PLACES, GeoPandas, QGIS-ready GIS, QA/QC

**View:** [Repository](https://github.com/gorkira28/cdc-places-behavioral-health-priorities) · [Portfolio case study](https://gorkira28.github.io/#work)

### 3. CKD Awareness Gap Among Adults With Diabetes — SAS + Python

**Decision question:** How much laboratory-defined CKD is detectable among U.S. adults with diagnosed diabetes, and how often do affected adults report awareness of kidney disease?

- Integrated five CDC/NCHS NHANES files with survey weights, strata, and PSUs
- Derived race-free CKD-EPI 2021 eGFR and combined it with urine albumin-creatinine ratio
- Built a complete SAS survey workflow with an independently executed Python validation analysis
- Estimated analytic CKD in 39.3% of adults with diagnosed diabetes and an 82.0% reported-awareness gap among those with diabetes and CKD

**Tools:** SAS, Python, NHANES, complex-survey analysis, CKD-EPI 2021, QA/QC

**View:** [Repository](https://github.com/gorkira28/nhanes-diabetes-ckd-awareness-gap) · [Portfolio case study](https://gorkira28.github.io/#work)

### 4. Nursing Home Staffing and Quality Signals — R + DuckDB SQL

**Decision question:** Do staffing capacity and nursing-staff turnover align with low CMS overall ratings after facility and market context are considered?

- Analyzed 14,690 active nursing homes in the August 2026 CMS Provider Information file
- Built an auditable DuckDB SQL transformation layer, Python QA and statistical cross-check, and independent R replication workflow
- Fit a multivariable logistic model adjusting for occupancy, case mix, bed count, ownership, and state
- Found a 54.7% low-rating share in the lowest adjusted-staffing quartile versus 23.6% in the highest, with explicit noncausal interpretation

**Tools:** R, DuckDB SQL, Python, CMS Care Compare, logistic regression, QA/QC

**View:** [Repository](https://github.com/gorkira28/cms-nursing-home-staffing-quality-gap) · [Portfolio case study](https://gorkira28.github.io/#work)

### 5. Provisional Drug-Involved Overdose Signals — SAS + Python

**Decision question:** Which drug-involvement signals changed most in the latest comparable annual periods, and where did HHS regional patterns differ from the national direction?

- Analyzed 11,088 CDC/NCHS records across 12 drug categories, 10 HHS regions, and the U.S. aggregate
- Used non-overlapping annual snapshots to avoid treating heavily overlapping rolling periods as independent
- Built a Python acquisition, QA, trend-analysis, and visualization workflow with an independent SAS validation program
- Found broad national declines alongside emerging exceptions, including ketamine nationally and cocaine in Regions 8 and 9

**Tools:** SAS, Python, CDC/NCHS mortality surveillance, log-linear trends, QA/QC  
**View:** [Repository](https://github.com/gorkira28/provisional-overdose-drug-signals) · [Dashboard](https://github.com/gorkira28/provisional-overdose-drug-signals/blob/main/outputs/figures/overdose_drug_signal_dashboard.png)

### 6. Emergency Department Throughput — SAS + Python + DuckDB SQL

**Decision question:** Where do publicly reported emergency-department time measures indicate operational benchmarking priorities, and how does reporting completeness limit interpretation?

- Analyzed CMS Care Compare data for 4,658 facilities and six ED measures
- Built a reproducible Python acquisition workflow with date-stamped extracts and SHA-256 manifests
- Used DuckDB SQL for transformation, facility-level joins, and explicit QA checks
- Added a substantive SAS workflow for typed import, validation, grouped analysis, reporting, and Python cross-checks
- Found a 69-minute median difference between very-high- and low-volume ED groups (95% bootstrap CI: 65–75)

**Tools:** SAS, Python, DuckDB SQL, CMS Care Compare, bootstrap inference, healthcare operations, QA/QC<br>
**View:** [Repository](https://github.com/gorkira28/cms-ed-throughput-benchmarking) · [Dashboard](https://github.com/gorkira28/cms-ed-throughput-benchmarking/blob/main/outputs/figures/cms_ed_throughput_dashboard.png)

### 7. Clinical Trial Results Transparency — SAS + Python

**Decision question:** How often are summary results available for completed Phase 2–4 type 2 diabetes trials after allowing at least 12 months from primary completion?

- Analyzed 865 eligible ClinicalTrials.gov records from a reproducible API snapshot
- Built a Python acquisition, cohort-construction, statistical-analysis, QA, and visualization workflow
- Added an independent SAS validation program with statistical testing and logistic regression
- Found posted summary results for 52.0% of eligible trials, with clear limits on causal and legal interpretation

**Tools:** SAS, Python, ClinicalTrials.gov API, biostatistics, QA/QC  
**View:** [Repository](https://github.com/gorkira28/type-2-diabetes-trial-results-reporting) · [Dashboard](https://github.com/gorkira28/type-2-diabetes-trial-results-reporting/blob/main/outputs/figures/trial_results_transparency_dashboard.png)

### 8. Pertussis Surveillance Priorities — SQL + QGIS

**Decision question:** Where do high population-adjusted incidence and high operational case burden point to different surveillance priorities?

- Analyzed the CDC’s 2025 provisional pertussis report across 52 reporting jurisdictions
- Built a typed DuckDB SQL workflow with validation, ranking, threshold flags, and exportable results
- Prepared a QGIS-ready state join with explicit handling of New York State and New York City
- Reconciled jurisdiction records exactly to the reported national total of 28,783 cases

**Tools:** DuckDB SQL, QGIS, epidemiologic surveillance, QA/QC  
**View:** [Repository](https://github.com/gorkira28/pertussis-2025-surveillance-priorities) · [Dashboard](https://github.com/gorkira28/pertussis-2025-surveillance-priorities/blob/main/outputs/figures/pertussis_surveillance_dashboard.svg)

### 9. Hidden Hypertension — SAS + Python

**Decision question:** How large is the gap between measured hypertension and reported diagnosis awareness among U.S. adults?

- Conducted a complex-survey analysis of 7,938 adults in NHANES 2017–March 2020
- Used survey-weighted prevalence, Taylor confidence intervals, domain estimation, and survey logistic regression
- Implemented parallel SAS and Python workflows with validation and threshold-sensitivity checks
- Estimated that 39.8% of adults meeting the primary analytic proxy reported no prior diagnosis

**Tools:** SAS, Python, NHANES, complex-survey methods  
**View:** [Repository](https://github.com/gorkira28/nhanes-hypertension-awareness-gap)

### 10. Texas Diabetes Vulnerability Atlas — Python + SAS + GIS

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
