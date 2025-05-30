# Ultimate Frisbee Training Performance Analysis

**Author**: [Your Name]  
**Course**: [Course Name]  
**Instructor**: [Professor's Name]  
**Date**: [Submission Date]

---

## Abstract

This study explores the relationship between daily lifestyle factors and athletic performance in ultimate frisbee training sessions. Over several weeks, data was collected on sleep habits, nutritional intake, psychological states, and training difficulty to assess their impact on the catch/throw performance metric. Using Python-based statistical analysis and visualization, this project identifies key variables influencing performance and proposes a framework for evidence-based athletic optimization.

---

## 1. Introduction

Ultimate frisbee requires a blend of stamina, coordination, and mental focus. Performance outcomes such as the catch/throw percentage are influenced by both training and daily lifestyle. This project aims to quantify the impact of behaviors—like sleep, mood, and caffeine intake—on ultimate frisbee outcomes using data science tools.

Motivated by personal athletic goals and academic training in data analysis, this study integrates real-world performance tracking with structured statistical methodology.

---

## 2. Methodology

### 2.1 Data Collection

Data was manually recorded after each of 20 training sessions. Attributes include:

- `Sleep Hours`  
- `Sleep Quality (1–10)`  
- `Caffeine (mg)`  
- `Mood (1–10)`  
- `Training Difficulty (1–10)`  
- `Protein (g)`  
- `Carbohydrates (g)`  
- `Body Weight (kg)`  
- `CatchThrow_Percentage` (Target)

### 2.2 Data Cleaning and Preprocessing

- Converted date values
- Ensured all values were numeric
- Imputed missing values using column means (none found)

### 2.3 Tools Used

- **Python**: Language for data processing  
- **Pandas**: Dataset manipulation  
- **Seaborn & Matplotlib**: Visualization  
- **Statsmodels & SciPy**: Statistical analysis

---

## 3. Exploratory Data Analysis (EDA)

### Correlation Insights

| Variable              | Correlation with Catch/Throw % |
|-----------------------|-------------------------------|
| Mood (1–10)           | ~ **0.78** (strong)           |
| Sleep Quality         | ~ 0.63                        |
| Sleep Hours           | ~ 0.55                        |
| Caffeine (mg)         | ~ 0.18 (weak)                 |
| Body Weight, Nutrition| Negligible/insignificant      |

### Visual Observations

- **Mood**: Clear upward trend (higher mood → higher performance)
- **Sleep**: Longer/higher quality sleep linked to better results
- **Caffeine**: No consistent effect observed
- **Body Weight**: No evident impact on catch/throw performance

---

## 4. Statistical Modeling

### 4.1 OLS Regression: Sleep Hours

- **R²**: 0.404  
- **p-value**: 0.0046  
- Indicates a statistically significant relationship between sleep and performance.

### 4.2 Hypothesis Testing

- **H₀**: Lifestyle attributes have no effect on performance  
- **H₁**: At least one attribute significantly impacts performance  

Pearson correlation and regression testing reject H₀ for **mood** and **sleep** variables (p < 0.05).

---

## 5. Discussion

This analysis finds **mood** and **sleep-related factors** to be the strongest predictors of ultimate frisbee performance. Caffeine and dietary metrics did not show consistent or significant effects.

### Limitations

- Small dataset (n = 20 sessions)
- Subjective variables (e.g., mood, sleep quality)
- Untracked factors: weather, team dynamics, session duration

---

## 6. Conclusion & Future Work

This project confirms that **psychological state and rest** are key contributors to athletic performance. It offers actionable insight into how optimizing recovery and mental well-being can yield better training outcomes.

### Future Directions

- Collect larger, long-term datasets  
- Add biometric data (e.g., heart rate, readiness)  
- Experiment with polynomial and ML-based modeling  
- Include session metadata (weather, time of day, location)

