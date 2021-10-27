# PublicHealth490Z-Data-Challenge-2021
This is the Statistics Fall Data Challenge 2021 of Food Access Research done by group H (JInrui Zhou, Yikang Gong, Hongwei Shu, and Baitong Zhao) for Public Health 490Z in Fall 2021 at UMass Amherst.

We mainly use the “CA” sheet in the dataset and focus on “TractKids”, “TractSeniors”, “TractWhite”, “TractBlack”, “TractAsian”, “TractNHOPI”, “TractAIAN”, and “PovertyRate”, and probably “LowIncomeTracts”. We are aiming at the correlation between ages, races, and property rates to the chance of facing food insecurity.

Null hypothesis:
There is no relationship between ages, races, annual family incomes (below/at average/above the federal poverty rate), and food insecurity.

Alternative hypothesis:
Children (0-17) and seniors (65+) in families of different races (White, African American, Latino, Asian, Native Hawaiian and Other Pacific Islander, American Indian and Alaska Native, Other/Multiple race, Hispanic or Latino population) below/at average/above the federal poverty rate have a higher chance to face food insecurity and have a positive correlation with poverty rates in California.

Analysis plan:
Though the original data of races do not include different ages, since all our focused data are randomly sampled and with large sample size, we are treating each data set as independent and normal distributed variables and planning to find any linear correlations between ages, races, property rates, and chances of facing food insecurity. From the given data, we can get the mean, standard deviation, and variance of ages and annual family incomes within a group. For analysis, we plan to first analyze the situations about food insecurity that happen along with people’s ages in their families of different races. And then, from there, we want to figure out if a poverty rate, either below, at average, or above the federal standard in California, potentially causes a more serious problem in food insecurity within the communities. We can use multiple linear regression to find out the correlation between different age groups of different races, poverty rate, and food insecurity. After that, we can make a test to find the p-value. We can use p-value compared with α value. The result of the comparison will give us the conclusion of our hypothesis. To do the data analysis, we will be mainly using dylyr (select, filter, arrange, mutate, and summarize the given data), ggplot2 (plot graphs), tidyverse (data manipulation, exploration, and visualization), knitr (dynamic report generation), and caret (data splitting, pre-processing, feature selection, variable importance estimation) libraries.
