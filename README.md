# LinearRegression
Preprocessing data, analysis and Regression Algorithm Implementation.

# California Housing Price Prediction

This project predicts house prices in California using machine learning. It covers data cleaning, data analysis, and a comparison of 4 different prediction models.

#To make sure our machine learning models perform accurately, we cleaned the data using these steps:
* **Checking for Errors:** We verified that there are no missing fields or duplicate rows in the data.
* **Scaling Features:** We leveled the population field so that big numbers do not overwhelm smaller numbers (like income).

#Tested four different algorithms to see which one predicts house prices best:
 **Linear Regression:** Fits a simple straight line through the data. It is fast and very easy to explain.
*   **Decision Tree Regressor:** Works like a flowchart by asking simple "yes/no" questions to group houses by price.
*   **Random Forest Regressor:** Combines a large group of decision trees together and averages their scores to prevent mistakes.
*   **Gradient Boosting Regressor:** Builds a chain of trees where each new tree fixes the mistakes made by the last one.

Then evaluated our models using standard scores like MSE, MAE, R2, RMSE
