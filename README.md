# tech-wellness-python-analysis
Python analysis of a 5,000-participant Kaggle dataset examining links between technology use and mental/physical wellness. Uses correlation analysis and machine learning (linear/logistic regression, SVM) to analyze screen time, sleep, social media, and lifestyle data.

## Objective

- Explore relationships between screen time, social media use, and wellness indicators (stress, anxiety, depression, sleep, healthy eating)
- Quantify correlations between digital habits and mental health outcomes
- Build predictive models to test strength of these relationships
- Translate findings into practical recommendations for tech companies, employers, and wellness apps

## Key Findings

**1. Screen time and mental health**
Daily screen time strongly correlates with weekly anxiety and depression, and moderately with stress. A linear regression model performed well (RMSE 1.36 vs. mean 5.04, range 10), confirming a strong relationship. Suggests social platforms (e.g. Meta, Reddit) should consider screen-time limiting features for user wellbeing.

**2. Screen time and sleep**
Daily screen time strongly negatively correlates with sleep duration and quality. Regression again performed well (RMSE 1.45), reinforcing the relationship. Suggests high-screen-exposure industries (e.g. healthcare) may benefit from sleep education programs.

**3. Social media and healthy habits**
Social media use negatively correlates with healthy eating and wellness app usage. Logistic regression models were weak (accuracy 0.63 and 0.57) — expected, since ~86% of the dataset's responses are continuous rather than categorical. Suggests social platforms could promote nutrition tips and wellness apps (e.g. Calm, Fitbit) despite the weaker classification fit.

## Methodology

- Data manipulation: NumPy, Pandas (Series, DataFrame)
- Visualization: Matplotlib, Seaborn
- Modeling: Scikit-learn — Linear Regression, Logistic Regression, Support Vector Machines
- Correlation analysis between technology use variables and wellness indicators

## Files

- `Tech Use and Stress Wellness.ipynb` — full analysis: data cleaning, correlation analysis, and modeling

## Screenshots

<img width="1152" height="648" alt="scrntime-stresslvl" src="https://github.com/user-attachments/assets/292667a7-9cff-4548-b583-21aca1e712b9" />
<img width="1476" height="702" alt="socmed-wellness" src="https://github.com/user-attachments/assets/c71d832b-1824-4565-907b-e6366393fb14" />
<img width="1152" height="866" alt="accuracy-scores" src="https://github.com/user-attachments/assets/f31054e7-8eb5-4c1b-937a-a9c77806bed7" />

## Attribution

Individual project
