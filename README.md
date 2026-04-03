# Student Performance Factors Analysis

This project investigates the multifaceted variables that influence student exam scores. By analyzing habits, socioeconomic factors, and school environments, this study identifies the primary drivers of academic success and compares the predictive effectiveness of different machine learning models.

## Project Overview
The goal of this research is to move beyond simple correlations and determine which factors—ranging from study habits to parental involvement—most significantly impact performance. The findings provide actionable insights for educators to develop targeted interventions.

## Dataset Highlights
The analysis utilizes a comprehensive dataset covering several key attributes:
* **Academic Habits:** Hours studied per week, attendance percentage, and previous scores.
* **Environmental Factors:** Parental involvement, access to resources, and teacher quality.
* **Personal Wellbeing:** Sleep hours and physical activity.
* **Socioeconomics:** Family income, parental education level, and internet access.

## Methodology
1. **Exploratory Data Analysis (EDA):** Visualized distributions and identified strong correlations between lifestyle choices and grades.
2. **Feature Importance:** Ranked attributes to find the "heavy hitters" in predicting success.
3. **Model Benchmarking:** Compared Linear Regression against Gradient Boosting to determine the best fit for this specific numerical data.

## Key Findings and Statistics
The analysis revealed that simple, consistent habits often outweigh complex socioeconomic variables in predicting immediate exam outcomes.

### Model Comparison
| Model | Performance Note |
| :--- | :--- |
| **Linear Regression** | **Best Fit:** Highest accuracy for this dataset. |
| **Gradient Boosting** | Good performance, but slightly less precise than LR. |

### Significant Factors
| Factor | Impact Level |
| :--- | :--- |
| **Attendance** | Very High |
| **Hours Studied** | High |
| **Sleep Hours** | Significant |
| **Previous Scores** | High Predictor |

## Final Conclusion
The research concludes that students who prioritize **high attendance**, **consistent study hours**, and **sufficient sleep** are statistically more likely to achieve superior scores. Linear Regression proved to be the most reliable model for predicting these outcomes, making it a valuable tool for identifying students who may need additional support.

## Technologies Used
* **Languages:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook
