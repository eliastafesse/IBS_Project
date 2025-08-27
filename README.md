This repository contains the R Markdown workflow and accompanying resources for the study:  
**"Prevalence and Predictors of Irritable Bowel Syndrome Among Ethiopian Medical Students."** by Elias Yeshitila, MD, MPhil.

[![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg


## Contents
- `IBS_analysis.Rmd`: Full analysis pipeline, figures and tables
- `ibs_data.csv`: Input dataset


## Instructions
1. Place `ibs_data.csv` in your working directory.
2. Open `IBS_analysis.Rmd` in RStudio.
3. Knit the document to produce a full reproducible report with tables and plots.

## Requirements
- Packages: `dplyr`, `openxlsx`, `lmtest`, `sandwich`, `broom`, `pROC`
- Exact R version and packages can be installed using 'renv::restore'.

## Contact
For any questions, contact **Elias Yeshitila** at ey270@cam.ac.uk.
