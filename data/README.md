# Data dictionary

All values were transcribed from the sources listed in the repository README. Percentages are as published; no value was recalculated.

## globocan2022-lip-oral-cavity-countries.csv

Countries with the most estimated new cases of lip and oral cavity cancer (ICD-10 C00 to C06) in 2022, both sexes.

| Column | Meaning |
|---|---|
| country | Country name |
| new_cases_2022 | Estimated new cases in 2022 |
| asr_incidence_per_100000 | Age-standardised incidence rate per 100,000 (world standard population) |
| source | Short source name |

## seer-oral-pharynx-stage-survival-2007-2013.csv

Invasive cancer of the oral cavity and pharynx, SEER 18 registry areas, diagnoses 2007 to 2013.

| Column | Meaning |
|---|---|
| stage | SEER summary stage at diagnosis |
| description | Plain-language meaning of the stage |
| share_of_cases_percent | Percent of cases diagnosed at this stage |
| five_year_relative_survival_percent | Five-year relative survival, percent |
| source | Short source name |

## kerala-trial-flow.csv

Participant flow of the Kerala cluster-randomised trial of oral visual screening, 1996 to 2004.

| Column | Meaning |
|---|---|
| arm | Intervention (screening rounds offered) or Control |
| stage | Point in the flow |
| count | Number of people |
| note | Percentage or condition as reported |
| source | Short source name |

## kerala-trial-mortality-rate-ratios.csv

Oral cancer mortality, intervention versus control clusters, intention-to-treat analysis.

| Column | Meaning |
|---|---|
| group | Participant group |
| rate_ratio | Mortality rate in the intervention group divided by the rate in the control group |
| ci95_low, ci95_high | 95 percent confidence interval of the rate ratio |
| deaths_intervention, deaths_control | Oral cancer deaths in each group (where reported) |
| rate_intervention_per_100000_py, rate_control_per_100000_py | Deaths per 100,000 person-years (where reported) |
| source | Short source name |
