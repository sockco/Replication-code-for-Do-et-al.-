# Replication-code-for-Do-et-al.-
Friendship diversity, contact frequency, and perspective-taking among college students

Dataset DOI: 10.5061/dryad.fn2z34vbn

Description of the data and file structure

Our analytic sample consists of undergraduate students at a large American West Coast public research university participating in a multicohort, longitudinal study of undergraduate student experiences. All matriculating students received a study invitation at the beginning of the Fall quarter, with respondents opting in and providing reports on close friendship ties and completing perspective-taking assessments. Respondents received $20 Amazon gift cards for their participation. Participants include first year, transfer junior, and continuing junior undergraduate students who consented to participate, with our sample consisting of Fall 2023 and Fall 2025 cohort respondents. Survey data are also paired with university administrative data to examine students’ background information.

Files and variables

File: 2.__No_Friends__replication_data.csv

Description: 

Variables

replication_id: Arbitrarily assigned student ID number

Avg_Score: Perspective-taking score

race_diversity_gs_norm: Friend network racial diversity (normalized Gini–Simpson index)

ses_diversity_gs_norm: Friend network socioeconomic diversity (normalized Gini–Simpson index)

pol_diversity_gs_norm: Friend network political diversity (normalized Gini–Simpson index)

gender_diversity_gs_norm: Friend network gender diversity (normalized Gini–Simpson index)

total_interaction_exposure: Continuous measure of weekly contact frequency across reported friends

replication_id: Arbitrarily assigned student ID number

Avg_Score: Perspective-taking score

race_diversity_gs_norm: Friend network racial diversity (normalized Gini–Simpson index)

ses_diversity_gs_norm: Friend network socioeconomic diversity (normalized Gini–Simpson index)

pol_diversity_gs_norm: Friend network political diversity (normalized Gini–Simpson index)

gender_diversity_gs_norm: Friend network gender diversity (normalized Gini–Simpson index)

total_interaction_exposure: Total estimated weekly contact frequency across reported friends

race_outgroup_exposure: Total estimated weekly contact frequency with racially different friends

ses_outgroup_exposure: Total estimated weekly contact frequency with socioeconomically different friends

pol_outgroup_exposure: Total estimated weekly contact frequency with politically different friends

gender_outgroup_exposure: Total estimated weekly contact frequency with gender-different friends

respondents_race: Respondent race/ethnicity

gender_num: Respondent gender

age_cohort: Respondent age

mother_edu_years: Mother’s educational attainment, measured in approximate years of education

hs_gpa_num: Respondent high school GPA

Form: Perspective-taking instrument form

Code/software

All data preparation and statistical analyses were conducted using R version 4.5.1 (2025-06-13) on Windows 11. The replication dataset is provided in CSV format and can be viewed using R or any software capable of reading CSV files.

The analysis was conducted using the following R packages: dplyr (1.1.4), readr (2.1.6), ggplot2 (4.0.0), marginaleffects (0.32.0), ggeffects (2.3.2), tidyr (1.3.1), scales (1.4.0), parameters (0.28.3), and modelsummary (2.6.0).

The accompanying R script performs data preparation, descriptive analyses, variable construction, statistical modeling, and visualization. The deposited replication dataset contains the variables necessary to reproduce the reported analyses, including pre-constructed normalized Gini–Simpson network diversity indices. The script estimates the linear regression models and associated subgroup and interaction analyses and generates descriptive statistics and model results.

Access information

Data was derived from the following sources:

Arum, Richard, Jacquelynne S. Eccles, Jutta Heckhausen, Gabe Avakian Orona, Luise von Keyserlingk, Christopher M. Wegemer, Charles E. (Ted) Wright, and Katsumi Yamaguchi-Pedroza. 2021. “A Framework for Measuring Undergraduate Learning and Growth.” Change: The Magazine of Higher Learning 53(6): 51–59. This article describes the University of California, Irvine’s Next Generation Undergraduate Success Measurement Project, from which the data used in this study were derived.

