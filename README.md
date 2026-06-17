# Student-Mental-Health-and-Burnout
📊 Social Media Usage, Sleep & Mental Health Analysis
📌 Project Overview

This project explores the relationship between social media usage, sleep duration, academic level, and mental health indicators in students.
The goal is to identify behavioral patterns and statistical relationships that may help explain how digital habits correlate with wellbeing outcomes.

The analysis is performed using Python and focuses on exploratory data analysis (EDA), correlation studies, and subgroup comparisons.

🎯 Objectives
Analyze how daily social media usage relates to sleep duration
Investigate the relationship between sleep and mental health scores
Compare behavioral differences across academic levels and gender
Identify platform usage patterns among different student groups
Explore whether usage intensity is associated with wellbeing indicators
📂 Dataset
Source: Kaggle — Student Mental Health and Burnout Dataset
File used: Social_media_impact_on_life.csv
Records include:
Age, Gender, Academic Level, Country
Daily social media usage (hours)
Most used platform
Sleep duration (hours per night)
Mental health score
Self-reported academic impact
🧪 Methodology

The analysis includes:

Data loading via kagglehub
Data cleaning and filtering
Group-based segmentation (gender, academic level)
Correlation analysis
Data visualization using:
Seaborn
Matplotlib
Comparative subgroup analysis (high school focus)
📊 Key Findings
Social media usage shows a strong negative correlation with sleep duration (≈ -0.82)
Higher usage is also strongly associated with lower mental health scores (≈ -0.83)
Sleep duration is positively correlated with mental health (≈ 0.79–0.86)
These relationships remain consistent across full dataset and high school subgroup
Platform usage differs by gender, but overall usage intensity is the main driver of variation
🧠 Insights
Students with higher daily usage tend to sleep less and report lower mental health scores
High school students show the strongest concentration of high usage and lower sleep patterns
Gender differences in platform preference exist, but do not override overall behavioral trends
Observed differences in mental health across groups may be partially associated with usage intensity patterns
⚠️ Limitations
Correlation does not imply causation
Self-reported data may contain bias
External factors (stress, socioeconomic status, lifestyle) are not included
No predictive modeling or causal inference is performed
🚀 Future Work
Build regression or predictive models for mental health score estimation
Perform feature importance analysis
Test statistical significance of observed relationships
Extend analysis with time-series or longitudinal data if available
🛠️ Technologies Used
Python 3
Pandas
NumPy
Seaborn
Matplotlib
KaggleHubA Case a Study of the the Student Mental Health and Burnout Dataset from Kaggle to analyze the impact of social media platforms and time of sleep on students health score and Academic Level
