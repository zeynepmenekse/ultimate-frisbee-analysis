# ultimate-frisbee-analysis
# Ultimate Frisbee Training Performance Analysis

## Project Overview
This project aims to analyze the impact of various factors on my throwing accuracy and catching percentage during ultimate frisbee training sessions. The primary goal is to identify how different physical, physiological, and psychological factors influence my performance and use the insights to improve my game.

## Research Question
How do sleep quality, caffeine intake, resting heart rate, and psychological state affect my throwing accuracy and catching percentage in ultimate frisbee training sessions?

## Hypothesis
**H₀ (Null Hypothesis):** There is no significant relationship between the measured factors (sleep, caffeine, heart rate, and psychological state) and my training performance.  
**H₁ (Alternative Hypothesis):** There is a significant relationship between the measured factors and my performance. Specifically:
- Better sleep correlates with higher accuracy and catch percentage.
- Higher caffeine intake may improve alertness but could also lead to jitteriness, negatively affecting accuracy.
- Increased resting heart rate (indicator of stress or fatigue) may correlate with lower performance.
- Higher stress levels due to academic or relational factors may decrease performance.

## Data Collection Plan

**Training Schedule:**  
Sessions occur three times per week: Monday, Wednesday, and Friday (each lasting 3 hours). The same training environment and drills will be maintained to ensure consistency.

**Collected Data:**

**Tools & APIs Used:**
- Google Sheets or Notion for manual data logging
- Samsung Health / Apple Health for resting heart rate & sleep tracking
- Mood Tracking Apps: Daylio, Moodfit, Baseline for psychological state tracking
- Excel / Python (Pandas, Matplotlib, Seaborn, Scikit-Learn) for data analysis & visualization

## Data Processing & Analysis

**Data Cleaning:**
- Convert timestamps to appropriate formats.
- Handle missing values.
- Normalize caffeine intake units.

**Feature Engineering:**
- Compute catching percentage and throwing accuracy.
- Create "stress level difference" between pre- and post-training stress.
- Categorize sleep duration into Short (≤4h), Normal (5-7h), Optimal (8h+).

**Exploratory Data Analysis (EDA):**
- Histograms: Distribution of throwing accuracy, catching percentage.
- Boxplots: Relationship between sleep, caffeine intake, and performance.
- Scatter plots: Correlations between resting heart rate, mood, and performance.

**Statistical Analysis & Machine Learning:**
- **Correlation Analysis:** Checking relationships between variables.
- **Regression Models:**
  - Linear Regression: Predicting throwing accuracy based on sleep, caffeine, and stress.
  - Decision Tree & Random Forest: Identifying the most influential factors.
- **Clustering:** Grouping performance patterns under different conditions.
