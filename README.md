# Data-Exploration
[Link to PDF (includes Visuals):](https://github.com/marspier/Data-Exploration/blob/main/Data%20Exploration.pdf) 

# Hospital Readmission Analysis 🏥
Overview
This project investigates the relationship between hospital readmissions (ReAdmis) and the initial admission status (initial_admin). The goal is to explore potential correlations between these two variables using statistical methods, which could help reduce readmissions, improve patient satisfaction, and reduce hospital penalties under the Medicare Hospital Readmissions Reduction Program.


# Research Question
Primary Question: Does the initial_admin variable correlate with readmissions (ReAdmis) in hospital patients?


# Benefit from Analysis
Patient Satisfaction: Identifying factors contributing to readmissions can improve patient care and satisfaction.
Hospital Revenue: Lowering readmission rates can help hospitals avoid Medicare penalties, leading to better financial outcomes.
Operational Efficiency: Understanding what influences readmissions can inform strategies to reduce unnecessary hospital readmissions.

# Data and Variables
# Dependent Variable:
- ReAdmis (Readmissions: categorical variable)
# Independent Variable:
- initial_admin (Initial admission status: categorical variable)
# Other Variables:
- Continuous: Income, Age
- Categorical: Complication_risk

# Analysis Methodology
A. Chi-Square Test
Justification: ReAdmis (readmissions) and initial_admin (admission status) are categorical variables, making the chi-square test appropriate for analyzing their potential correlation (GeeksforGeeks, 2020).

Test Result: The p-value was 0.143, which is greater than the 0.05 significance threshold. Thus, we cannot reject the null hypothesis, meaning there is no statistically significant correlation between the two variables.

# Univariate and Bivariate Analysis
Univariate Analysis:
Visualizations: Histograms and boxplots used to analyze the distribution of Age, Income, Initial_admin, and Complication_risk.
Income: Skewed distribution, with several outliers.
Age: Uniform distribution with no outliers.
Initial_admin: Most admissions were categorized as emergencies.
Complication_risk: Most patients had a medium complication risk.
# Bivariate Analysis:
Visualizations: Scatter plots, stacked bar charts, and boxplots.
Scatter plots: Showed no clear correlation between continuous variables and readmissions.
Stacked Bar Charts: Indicated a higher rate of readmissions among emergency admissions, but no clear cause-effect relationship was found.
Complication_risk: Similar trends, with medium risk categories showing slightly more readmissions.

# Limitations
Data Limitations: Lack of detailed information on the reasons for readmission and the time between admissions. Without these data points, a more in-depth analysis is not possible.
Statistical Significance: The p-value above 0.05 suggests that the analysis did not provide enough evidence to establish a strong correlation between initial admission and readmission.

# Recommendations
Further Analysis: To improve our understanding of readmissions, it’s recommended to explore other medical factors (e.g., chronic conditions like high blood pressure, arthritis) that might contribute to readmission rates.

# Conclusion
This analysis indicates no significant correlation between initial_admin and ReAdmis, based on the chi-square test results. Future analyses should consider additional variables, such as specific medical conditions or other factors that influence readmissions, to uncover actionable insights.
