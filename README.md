# National-Poll-on-Healthy-Aging-NPHA-
https://archive.ics.uci.edu/dataset/936/national+poll+on+healthy+aging+(npha)

This is a subset of the NPHA dataset filtered down to develop and validate machine learning algorithms for predicting 
the number of doctors a survey respondent sees in a year. This dataset’s records represent seniors who responded to the 
NPHA survey.

## For what purpose was the dataset created?
The National Poll on Healthy Aging dataset was created to gather insights on the health, healthcare, and health policy 
issues affecting Americans aged 50 and older. By focusing on the perspectives of older adults and their caregivers, 
the University of Michigan aimed to inform the public, healthcare providers, policymakers, and advocates about the 
various aspects of aging. This includes topics like health insurance, household composition, sleep issues, dental care, 
prescription medications, and caregiving, thereby providing a comprehensive understanding of the health-related needs 
and concerns of the older population.

## Who funded the creation of the dataset?
The dataset was funded by AARP and Michigan Medicine, the University of Michigan's academic medical centre.

## What do the instances in this dataset represent?
Each row represents a survey respondent.

## Does the dataset contain data that might be considered sensitive in any way?
Yes. There is information about race/ethnicity, gender, age.

## Was there any data preprocessing performed?
For this subset of the original NPHA dataset we chose 14 features related to health and sleep to use for the prediction 
task. We then removed all survey respondents with missing responses for any of the chosen features.

## Has Missing Values?
No