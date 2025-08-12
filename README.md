# Happiness-Factors
<p align="center">
  <img src="WHR.png" alt="Leading Factors for Happiness Across Countries" width="800">
</p>

Statistical analysis of World Happiness Report 2018 – exploring the leading factors for happiness across countries.
<br>
## 1. Introduction-
This project aims to identify key determinants of happiness across nations, emphasizing the importance of exploring what drives life satisfaction and overall well-being. The variables examined include GDP per capita, social support, freedom to make life choices, generosity, and measures of corruption such as CPI scores. The statistical tools used—such as correlation analysis, hypothesis testing, and regression modeling—help uncover relationships between these predictors and reported happiness (Ladder score).
The goal is to apply these techniques in an academic statistics course setting, demonstrating the use of statistical theory in real-world data analysis, while also providing insights into global well-being, migration patterns, and governmental policy..

## 2. Data Description and Preparation <br>
Source: [World Happiness Report, Kaggle](https://www.kaggle.com/datasets/unsdsn/world-happiness)<br>
Number of countries: 156<br>
Year Used: 2020 (filtered from full dataset)<br>
Origin: Survey-based happiness ratings and national statistics compiled by the World Happiness Report.<br>
Features:
Ladder score (0–10)
GDP per capita (logged)
Social support
Healthy life expectancy
Freedom to make life choices
Generosity
Perceptions of corruption<br>
Preprocessing Steps:
Adding missing values for certain countries with averages from adjacent countries.

## 3. Analysis Outline<br>

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
Extended Analysis;
PCA and factor analysis for dimensionality reduction.
Misery Index (inflation + unemployment) comparison.

## 4. How to Run
### Option 1 — Google Colab (Recommended)
1. Open the Colab notebook [here](https://colab.research.google.com/drive/14bz7YD4RXYYlYRbUVWQpK0Bq6p7faByL?usp=sharing).
2. Go to File → Save a copy in Drive to create your own editable version.
3. Download the dataset from [this link](https://github.com/Yafit23/Happiness-Factors/blob/main/WH2018DATA.csv) and upload it to the Colab session.
4. Run all cells in order to reproduce the analysis.


### Option 2 — Local Execution (Run On Your Computer)
1. **Download or clone** this repository from [here](https://github.com/Yafit23/Happiness-Factors.git).

    ```bash
    git clone https://github.com/Yafit23/Happiness-Factors.git
    cd Happiness-Factors
    pip install -r requirements.txt
    jupyter notebook
    ```

2. Open the `.ipynb` file and run all cells.

## 5. Dependencies

python>=3.8<br>
pandas<br>
numpy<br>
matplotlib<br>
seaborn<br>
scipy<br>
statsmodels<br>
scikit-learn<br>

## Authors
Yafit  — <yafitd352@gmail.com>

