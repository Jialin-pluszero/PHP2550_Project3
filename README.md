# PHP2550_Project3

## Description
This project is a collaboration with Dr. Jon Steingrimsson in the Biostatistics Department and focuses on evaluating a performance of a perdiction model in a different population than it was originally developed and /or evaluated in. Prediction models are often developed from samples in source populations, however, models cannot be directly applied to the target population since datasets are typically not random sample from the target population, even distributions of observed variables are totally different between source and target populations. Consequently, models built using the data from source population are not applicable to the target population so that model performance evaluation in the source population cannot perfectly reflect performance in the target population unless using tailored prediction models as an attractive alternative to evaluate performance in the target population to achieve transportability tasks. In many cases, both covariates and outcome are available in source populations, whereas only covariates are available in target populations without prior information about outcomes. Under the lack of outcomes in target populations, we tailor prediction models given outcomes information from the source population and assess performance of models for datasets with covariates only. This study aimed to see if the prediction model can be generalized to the other target population by looking at the Brier scores from the transportability analysis, conducted a simulation study when individual level datasets are not available for transportability, and evaluated performance of Brier risk scores.

## Data Privacy
Data used in this project provided by the Institution is confidential and proprietary information, whcih can only be shared with the instructor, students, and TA of the course. Data Privacy Agreement is entered by the signed student participating in PHP 2550 Practical Data Analysis, represented by Alice Paul.

## Environment Version Information
- tidyverse_1.3.2
- riskCommunicator_1.0.1
- dplyr_2.2.1
- tableone_0.13.2
- mice_3.15.0
- fitdistrplus_1.1-8
- MASS_7.3-57
- data.table_1.14.2
- kableExtra_1.3.4
- logspline_2.1.21
  
## Guideline for this repository
In this github repo, you can find a pdf report inside `Report` folder along with the corresponding R markdown file inside `Codes` folder. Due to concision of public report, we did not choose to include all analysis in the report. You can find the full R makrdown report file inside `Codes` folder. All images and tables in the public report can be found in `Images` and `Tables` folders. All the required packages and version information can be found in this README file.
