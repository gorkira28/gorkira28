# Hi, I’m Kira Gor, BDS, MPH

I’m a clinician-trained epidemiologist and healthcare data analyst who turns surveillance, clinical, observational, regulatory, and geospatial data into clear, reproducible evidence for public-health decisions.

**[Explore my complete portfolio](https://gorkira28.github.io/)** · [LinkedIn](https://www.linkedin.com/in/dr-kira-gor/) · [Email](mailto:gor.kira.28@gmail.com)

> Open to healthcare data analyst, epidemiologist, biostatistician, clinical data analyst, and related opportunities with employers able to support future U.S. work authorization.

## Featured analytics projects

### 1. FDA Medical-Device Recall Response Timelines — SAS + Python + DuckDB SQL

**Decision question:** How much time elapsed between firm initiation of a medical-device recall and publication in an FDA Enforcement Report?

- Analyzed 11,005 recall records initiated during 2022–2025
- Built a reproducible openFDA acquisition pipeline, typed DuckDB SQL layer, Python analysis, and automated QA
- Found median initiation-to-report times of 48 days for Class I, 50 for Class II, and 62 for Class III records
- Distinguished a statistically detectable class difference from its small practical effect size (epsilon-squared = 0.011)
- Added a substantive SAS validation program with explicit rank, tie-correction, effect-size, reporting, and cross-software comparison steps

**Tools:** SAS, Python, DuckDB SQL, openFDA, nonparametric statistics, regulatory data, QA/QC  
**View:** [Repository](https://github.com/gorkira28/fda-device-recall-response-timelines) · [Portfolio case study](https://gorkira28.github.io/#work)

### 2. RESP-NET Age-Specific Respiratory Hospitalization Burden — SAS + Python

**Decision question:** Which age groups carried the greatest cumulative hospitalization burden from COVID-19, influenza, and RSV during the 2025–26 respiratory season?

- Analyzed 53 weeks of CDC RESP-NET observed cumulative rates across three viruses and 11 age groups
- Found the highest combined rates among adults aged 85+ and infants younger than 1 year
- Showed that RSV accounted for 71% of the infant rate while influenza dominated most older age groups
- Reconciled the component series to CDC’s separately published combined series

**Tools:** SAS, Python, CDC RESP-NET, surveillance epidemiology, QA/QC  
**View:** [Repository](https://github.com/gorkira28/resp-net-age-hospitalization-burden) · [Portfolio case study](https://gorkira28.github.io/#work)

### 3. Emergency Department Throughput Benchmarking — SAS + Python + DuckDB SQL

**Decision question:** Where do publicly reported emergency-department time measures indicate operational benchmarking priorities?

- Analyzed CMS Care Compare data for 4,658 facilities and six ED measures
- Used DuckDB SQL for transformation, facility joins, and explicit QA checks
- Added a substantive SAS workflow for import, validation, grouped analysis, and reporting
- Found a 69-minute median difference between very-high- and low-volume ED groups (95% bootstrap CI: 65–75)

**Tools:** SAS, Python, DuckDB SQL, CMS Care Compare, bootstrap inference, QA/QC  
**View:** [Repository](https://github.com/gorkira28/cms-ed-throughput-benchmarking) · [Dashboard](https://github.com/gorkira28/cms-ed-throughput-benchmarking/blob/main/outputs/figures/cms_ed_throughput_dashboard.png)

### 4. CKD Awareness Gap Among Adults With Diabetes — SAS + Python

**Decision question:** How much laboratory-defined CKD is detectable among U.S. adults with diagnosed diabetes, and how often do affected adults report awareness?

- Integrated five CDC/NCHS NHANES files with survey weights, strata, and PSUs
- Derived race-free CKD-EPI 2021 eGFR and combined it with urine albumin-creatinine ratio
- Built a complete SAS survey workflow with an independently executed Python validation analysis
- Estimated analytic CKD in 39.3% of adults with diagnosed diabetes and an 82.0% awareness gap among those with diabetes and CKD

**Tools:** SAS, Python, NHANES, complex-survey analysis, CKD-EPI 2021, QA/QC  
**View:** [Repository](https://github.com/gorkira28/nhanes-diabetes-ckd-awareness-gap) · [Portfolio case study](https://gorkira28.github.io/#work)

### 5. Nursing Home Staffing and Quality Signals — R + DuckDB SQL

**Decision question:** Do staffing capacity and nursing-staff turnover align with low CMS overall ratings after facility and market context are considered?

- Analyzed 14,690 active nursing homes in CMS Care Compare data
- Fit a multivariable logistic model adjusting for occupancy, case mix, bed count, ownership, and state
- Found a 54.7% low-rating share in the lowest adjusted-staffing quartile versus 23.6% in the highest
- Kept interpretation explicitly associational rather than causal

**Tools:** R, DuckDB SQL, Python, CMS Care Compare, logistic regression, QA/QC  
**View:** [Repository](https://github.com/gorkira28/cms-nursing-home-staffing-quality-gap) · [Portfolio case study](https://gorkira28.github.io/#work)

### 6. Pertussis Surveillance Priorities — DuckDB SQL + QGIS

**Decision question:** Where do high population-adjusted incidence and high operational case burden point to different surveillance priorities?

- Analyzed CDC’s 2025 provisional pertussis report across 52 reporting jurisdictions
- Built a typed DuckDB SQL workflow with validation, ranking, and threshold flags
- Prepared a QGIS-ready state join with explicit handling of New York State and New York City
- Reconciled jurisdiction records exactly to the reported national total of 28,783 cases

**Tools:** DuckDB SQL, QGIS, infectious-disease surveillance, QA/QC  
**View:** [Repository](https://github.com/gorkira28/pertussis-2025-surveillance-priorities) · [Dashboard](https://github.com/gorkira28/pertussis-2025-surveillance-priorities/blob/main/outputs/figures/pertussis_surveillance_dashboard.svg)

## Technical toolkit

- **Analysis:** SAS, R, Python, SQL, SPSS, Epi Info
- **Visualization and GIS:** ArcGIS, QGIS, Tableau, Power BI
- **Methods:** epidemiologic study design, regression, complex-survey analysis, propensity-score methods, nonparametric statistics, reproducible analysis, QA/QC
- **Data environments:** infectious-disease surveillance, clinical trials, observational research, regulatory data, REDCap, NEDSS

## Selected research

- First-author study of juvenile idiopathic arthritis, anxiety, and depression in 192,019 U.S. children and adolescents (2025)
- Co-author of a machine-learning study of juvenile idiopathic arthritis screening in 223,195 U.S. children, published in *Frontiers in Public Health* (2025)
- Co-author of a propensity-score-weighted study on asthma and juvenile idiopathic arthritis in *Pediatric Rheumatology* (2026)

## How I work

I prioritize transparent assumptions, reproducible workflows, careful data-quality checks, appropriate interpretation, and communication that distinguishes association from causation. All portfolio projects use public data and exclude PHI, confidential employer information, and proprietary Texas DSHS material.
