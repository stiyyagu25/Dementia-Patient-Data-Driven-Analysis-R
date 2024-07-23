## A Data-Driven Approach to Defining Risk-Adjusted Coding Specificity Metrics for a Large U.S. Dementia Patient Cohort

## Citation
Richardson, K.; Penumaka, S.; Smoot, J.; Panaganti, M.R.; Chinta, I.R.; Guduri, D.P.; Tiyyagura, S.R.; Martin, J.; Korvink, M.; Gunn, L.H. A Data-Driven Approach to Defining Risk-Adjusted Coding Specificity Metrics for a Large U.S. Dementia Patient Cohort. Healthcare 2024, 12, 983. https://doi.org/10.3390/healthcare12100983

## Abstract
Medical coding impacts patient care quality, payor reimbursement, and system reliability through the precision of patient information documentation. This study presents a data-driven approach to define risk-adjusted coding specificity metrics using a large dataset of U.S. dementia patient records. The aim is to provide a novel risk-adjusted metric to estimate dementia ICD-10 coding specificity by facility upon adjusting for commonly available facility- and patient-level characteristics.

## Key Findings
- Developed logistic regression models using patient and facility characteristics to explain the coding specificity of principal and secondary diagnoses of dementia.
- Produced a two-step approach allowing for flexible clustering of patient-level outcomes.
- Identified facilities that over- or under-specify dementia diagnoses against healthcare industry standards.

## Methodology
The study uses de-identified data sourced and provided by Premier, Inc.'s private database, consisting of nearly 500,000 unique inpatient hospitalization records of individuals diagnosed with dementia and discharged in 2022. Detailed statistical analyses were conducted to identify associations between patient- and facility-level characteristics and the specificity of dementia diagnoses.

## License
This project is licensed under the terms and conditions of the Creative Commons Attribution (CC BY) license. See the [LICENSE](https://creativecommons.org/licenses/by/4.0/) file for details.

## Dependencies
The project requires the following R packages:
- readr: Package used to read datasets in different formats into R
- questionr: Package used to calculate odds ratios (ORs) - we may or may not use it, as we may use something different for ORs
- stringr: Package used to manipulate strings of characters, such as extracting substrings/components of strings
- vtable: Package used to create and visualize professional-looking tables of results
- ggplot2: Package used for a large number of high-quality visualizations
- usmap: Package used as the template for spatial visualizations of US states
- pROC: Package used to calculate the area under the curve (AUC) for logistic regression to assess the model fit to the data
- poisbinom: Package used to calculate facility-specific metrics for our project
- plyr: Package used to map values to descriptions (function mapvalues)

## Authors
- Kaylla Richardson (UNC Charlotte)
- Sankari Penumaka (UNC Charlotte)
- Jaleesa Smoot (UNC Charlotte)
- Mansi Reddy Panaganti (UNC Charlotte)
- Indu Radha Chinta (UNC Charlotte)
- Devi Priya Guduri (UNC Charlotte)
- Sucharitha Reddy Tiyyagura (UNC Charlotte)
- John Martin (Premier, Inc.)
- Michael Korvink (Premier, Inc.)
- Laura H. Gunn (UNC Charlotte, Imperial College London)





