# Happiness-Factors
Statistical analysis of World Happiness Report 2018 – exploring the leading factors for happiness across countries.


This project aims to identify key determinants of happiness across nations, emphasizing the importance of exploring what drives life satisfaction. We examine a variety of potential predictors, including GDP per capita, social support, freedom to make life choices, generosity, and measures of corruption such as CPI scores.
We employ statistical tools such as correlation analysis, hypothesis testing, and regression modeling to uncover relationships between these predictors and reported happiness (Ladder score).

Our goal is not only to apply these techniques in an educational setting but also to provide insights that may be relevant for policymakers, migration researchers, and those studying global well-being trends.

Data Description
Source: World Happiness Report, Kaggle
Number of countries: 156
Year Used: 2020 (filtered from full dataset)
Data Origin: Survey-based happiness ratings and national statistics compiled by the World Happiness Report.
Features: Ladder score (0–10), GDP per capita (logged), Social support, Healthy life expectancy, Freedom to make life choices, 
Generosity, Perceptions of corruption

Preprocessing Steps:
Replaced missing Social support values for certain years with averages from adjacent years (for intermediate steps).

3. Analysis Outline
Exploratory Data Analysis (EDA)
Descriptive statistics and visual summaries.
Normality Testing
Shapiro–Wilk and Kolmogorov–Smirnov tests.
Histograms and Q–Q plots.
Correlation Analysis
Spearman correlation matrix.
Hypothesis Testing
Mann–Whitney U test for comparing high vs. low factor groups.
Regression Analysis
Multiple linear regression model.
Extended Analysis
PCA and factor analysis for dimensionality reduction.
Misery Index (inflation + unemployment) comparison.
