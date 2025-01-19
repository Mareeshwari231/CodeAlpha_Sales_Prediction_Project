**Sales Prediction Using Python**
**Project Overview**
This project focuses on predicting sales based on advertising budgets allocated to TV, radio, and newspaper channels. Multiple regression models are utilized, including Linear Regression, Lasso, Ridge, and Random Forest, to analyze and forecast sales, providing actionable insights for marketing strategies.

**Key Features**
Data Exploration and Visualization: Analyze the dataset using descriptive statistics, correlation heatmaps, and pair plots.
Feature Engineering: Interaction features like TV_Radio and TV_Newspaper are added to enhance model performance.
Model Training and Evaluation: Train multiple regression models and evaluate them using metrics such as R² Score, Mean Squared Error (MSE), and Mean Absolute Error (MAE).
Advanced Techniques: Comparison of models (Linear Regression, Lasso, Ridge, and Random Forest) to identify the best-performing model.
Heatmap of Coefficients: Visualize feature importance in the Linear Regression model.
**Technologies Used**
Programming Languagee: Python
**Libraries:**
NumPy and Pandas (Data Manipulation)
Scikit-learn (Machine Learning Models)
Seaborn and Matplotlib (Data Visualization)
**Dataset Details**
Columns:
TV: Advertising budget for TV.
Radio: Advertising budget for Radio.
Newspaper: Advertising budget for Newspaper.
Sales: Actual sales (Target variable).
Source: A CSV file containing historical advertising and sales data.
Steps in the Project
Data Preprocessing:

Load the dataset and remove unnecessary columns.
Handle data types and scale the features for better performance.
Exploratory Data Analysis (EDA):

Correlation heatmap to identify relationships between features.
Sales distribution histogram.
Pair plots for feature interaction analysis.
Feature Engineering:

Created interaction terms (TV_Radio and TV_Newspaper) to capture combined effects of features.
**Model Training:**

Models used: Linear Regression, Lasso, Ridge, Random Forest.
Each model is trained on scaled data for consistency.
**Model Evaluation:**

Metrics: R² Score, MSE, and MAE.
Random Forest showed strong performance due to its ability to capture non-linear relationships.
Visualization:

Coefficients heatmap for Linear Regression.
Correlation heatmap and feature analysis plots.
Sample Results
Random Forest Model Evaluation:

R² Score: 0.97 (Example)
Mean Squared Error: 2.45
Mean Absolute Error: 1.31
Heatmap of Coefficients: Visualizes the contribution of each feature in predicting sales.
**
Future Enhancements**
Deploy the best-performing model as a web application.
Experiment with ensemble techniques like Gradient Boosting or XGBoost.
Use cross-validation to improve model generalization.
Include additional features such as regional or seasonal data.
This project serves as a practical application of machine learning in the domain of marketing analytics, enabling businesses to optimize advertising budgets and maximize sales outcomes.
