
# Plotting_Matplotlib_Seaborn_Assignment_1

Project Title: Fuel Efficiency Analysis and Prediction
Objective:
The goal of this project is to analyze a fuel efficiency dataset and predict key outcomes, such as GHG (Greenhouse Gas) Score, by selecting relevant features while avoiding multicollinearity and removing irrelevant columns. The focus is on optimizing feature selection for better model performance and interpretability.

Feature Selection Process:
Multicollinearity Removal:

Used a correlation matrix and heatmap to identify highly correlated features.
For highly correlated pairs of features, the feature with a weaker correlation to the target variable (GHG Score) was removed.

Dropped columns that provide no meaningful predictive information, such as id, year, pv2, and pv4, based on domain knowledge.

Final Selected Features:
Displacement
City Fuel Efficiency
Highway Fuel Efficiency
FE Score
CO2 Emissions (dropped in favor of FE Score due to multicollinearity).
How to Run the Project:
Load the dataset and apply the feature selection process.
Train using the selected features to predict the GHG Score or other relevant outcomes from the dataset.
Evaluate model performance based on predictive accuracy.

Conclusion:
By eliminating highly collinear and irrelevant features, the model is streamlined for better performance. The selected features provide the most relevant information for predicting fuel efficiency and related outcomes, such as the GHG Score.
