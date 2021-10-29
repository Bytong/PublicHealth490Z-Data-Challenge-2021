# PublicHealth490Z-Data-Challenge-2021
This is the Statistics Fall Data Challenge 2021 of Food Access Research done by group H for Public Health 490Z in Fall 2021 at UMass Amherst as a course project.

We mainly use the “CA” sheet in the dataset and focus on "lahunv1", "lahunv1share", "tractHUNV", "HUNVFlag", "lahunv1", "lahunv1share", "lahunv10", "lahunv10share", "lasnap1", "lasnap1share", "lasnap10", "lasnap10share", and "tractSNAP". We aim to correlate the total count of housing units without a vehicle in tract and the total count of housing units receiving Supplemental Nutrition Assistance Program(SNAP) benefits in tract along with the group of low income communities to the change of facing food insecurity. All the datasets are available here: https://thisisstatistics.org/

**Null hypothesis:**
There is no relationship between access to vehicle, receiving SNAP and the change of facing food insecurity

**Alternative hypothesis:**
Family in California who have no access to vehicle or reciving SNAP has a lower change of facing food insecurity.

**Analysis plan:**
We are treating each data set as independent and normal distributed variables and planning to find any linear correlations between access to vehicle and reciving SNAP and chances of facing food insecurity. AS for the binomial data set, we will analyze the percentage of "0" and "1" to serve as background information. 

From the given data, we can get the mean, standard deviation, and variance of ages and annual family incomes within a group. For analysis, we plan to first analyze the situations about food insecurity that happen along with people’s ages in their families of different races. And then, from there, we want to figure out if a poverty rate, either below, at average, or above the federal standard in California, potentially causes a more serious problem in food insecurity within the communities. 

We can use multiple linear regression to find out the correlation between access to vehicle, receiving SNAP and food insecurity. After that, we can make a test to find the p-value. We can use p-value compared with α (0.05) value. The result of the comparison will give us the conclusion of our hypothesis. To do the data analysis, we will be mainly using dylyr (select, filter, arrange, mutate, and summarize the given data), ggplot2 (plot graphs), tidyverse (data manipulation, exploration, and visualization), knitr (dynamic report generation), and caret (data splitting, pre-processing, feature selection, variable importance estimation) libraries.
