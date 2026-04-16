# Data Analytics Internship - Task 4: Predictive Modeling

## **Project Overview**
The final phase of the internship involved building a predictive engine to forecast transaction values (`Total Spent`). This project demonstrates the transition from descriptive analytics to predictive machine learning.

## **Analytical Workflow**
1.  **Preprocessing:** Applied Label Encoding to categorical features (Category, Payment Method, etc.).
2.  **Model Selection:** Tested Linear Regression as a baseline.
3.  **Optimization:** Implemented a Random Forest Regressor to capture non-linear relationships in the dataset.

## **Model Performance Results**
| Metric | Linear Regression | Random Forest (Optimized) |
| :--- | :--- | :--- |
| **R-squared (R2)** | 0.8742 | **0.9596** |
| **Mean Absolute Error (MAE)** | - | **$23.94** |

## **Final Insights**
The high R2 score of **0.9596** indicates that the model is extremely reliable. The business can now use this tool to simulate different sales scenarios, helping to optimize inventory levels and prepare for high-revenue periods like the January surge discovered in Task 2.
