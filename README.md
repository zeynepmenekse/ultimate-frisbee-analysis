# Ultimate Frisbee Training Performance Analysis

## Project Overview
This project aims to analyze the impact of various physiological, nutritional, and psychological factors on my catching and throwing performance during ultimate frisbee training sessions. By using a structured dataset and Python-based data analysis, the project investigates which variables most significantly influence training success, with the goal of improving future performance through actionable insights.

## Research Question
How do multiple physical, nutritional, and psychological attributes collectively affect my catching and throwing performance during ultimate frisbee training sessions?

## Hypothesis
**H₀ (Null Hypothesis):** There is no significant relationship between the attributes in the dataset and my training performance.

**H₁ (Alternative Hypothesis):** There is a significant relationship between one or more attributes and my performance. This includes factors such as sleep quality, caffeine intake, mood, protein, carbohydrates, and training difficulty.

## Dataset Description
The dataset includes manually recorded data from multiple ultimate frisbee training sessions. It contains 10 attributes:

| Attribute             | Description                                      |
|-----------------------|--------------------------------------------------|
| Date                  | Date of training session                         |
| Sleep Hours           | Number of hours slept before training            |
| Sleep Quality         | Self-rated sleep quality (scale: 1-10)           |
| Caffeine (mg)         | Caffeine intake on training day                  |
| Mood (1-10)           | Overall mood/stress rating before training       |
| Training Difficulty   | Self-rated difficulty of training (scale: 1-10)  |
| Protein (g)           | Protein intake (g) on training day               |
| Carbohydrates (g)     | Carbohydrate intake (g) on training day          |
| Body Weight (kg)      | Weight on the day of training                    |
| CatchThrow_Percentage | Main performance metric (%)                     |

## Data Processing & Analysis Plan

### Data Cleaning
- Convert date formats
- Normalize numeric columns (mg, grams, percentages)
- Fill missing values with mean or interpolated data

### Exploratory Data Analysis (EDA)
- **Correlation Heatmap:** Visualize overall attribute relationships
- **Boxplots:** Examine impact of sleep quality and mood on performance
- **Scatter Plots:** Visualize trends between caffeine/protein/carbs and performance
- **Trend Line Visualization:** Plot performance over time vs. weight

### Statistical Analysis
- **Pearson Correlation Tests**: Evaluate significance of individual variables
- **Regression Analysis**: 
  - Simple Linear Regression (e.g., each variable → Catch %)
  - Polynomial Regression where needed (e.g., non-linear variables)
- **Hypothesis Testing**:
  - Check p-values for regression coefficients
  - Accept/reject null hypothesis based on significance level (α = 0.05)

## Key Analytical Objectives
- Identify which individual or combined variables significantly impact performance
- Evaluate non-correlating variables for control comparison
- Explore both linear and non-linear patterns among attributes

## Tools & Technologies Used
- **Python** (Pandas, Matplotlib, Seaborn, Statsmodels)
- **Excel** for preliminary data entry and structure

## Conclusion (to be written after full analysis)
To be completed with insights from the final regression and visualization results.


