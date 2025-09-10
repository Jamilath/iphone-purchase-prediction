# iphone-purchase-prediction
A Decision Tree model to predict iPhone purchases based on Gender, Age, and Salary, built with Python and scikit-learn.
iPhone Purchase Prediction
Overview
This project builds a Decision Tree model to predict whether an individual will purchase an iPhone based on their Gender, Age, and Salary. The analysis includes Exploratory Data Analysis (EDA), data preprocessing, model training, and evaluation, implemented in Python using a Jupyter Notebook.
Purpose
The goal is to:

Analyze the dataset to identify patterns in iPhone purchase behavior.
Develop an interpretable machine learning model (Decision Tree) to predict purchases.
Showcase data science skills in Python, pandas, scikit-learn, and visualization for professional portfolios (e.g., resume, LinkedIn).

Methodology

Exploratory Data Analysis (EDA):
Visualized distributions of Gender, Age, and Salary using count plots, histograms, box plots, and scatter plots.
Analyzed correlations between numerical features (Age, Salary).
Identified class imbalance in the target variable (Purchase iPhone: 0 = No, 1 = Yes).


Data Preprocessing:
Encoded Gender using One-Hot Encoding.
Scaled numerical features (Age, Salary) with StandardScaler.
Split data into 80% training and 20% testing sets.


Modeling:
Trained a Decision Tree Classifier with hyperparameters (max_depth=5, min_samples_split=10).
Performed 5-fold cross-validation to ensure robust performance.


Evaluation:
Evaluated model using accuracy (~85–90%), confusion matrix, and classification report (precision, recall, F1-score).
Visualized feature importance and Decision Tree structure (text-based).



How to Run

Prerequisites:
Install Python 3.8+ and required libraries:pip install -r requirements.txt


Ensure iphone_purchase_records.csv is in the same directory as the notebook.


Run the Notebook:
Open iphone_purchase_analysis.ipynb in Jupyter Notebook:jupyter notebook


Run all cells to execute the analysis and generate visualizations.


View HTML Output:
Open iphone_purchase_analysis.html in a web browser for a static version with embedded plots.



Files

iphone_purchase_analysis.ipynb: Jupyter Notebook with the full analysis (EDA, modeling, evaluation).
iphone_purchase_analysis.html: HTML export of the notebook with embedded visualizations (e.g., confusion matrix, feature importance).
iphone_purchase_records.csv: Dataset containing Gender, Age, Salary, and Purchase iPhone columns.
requirements.txt: List of Python dependencies.
visualizations/: Folder containing saved plots (e.g., confusion_matrix.png, feature_importance.png).

Results

EDA Insights:
Purchasers (Purchase iPhone = 1) tend to be older (40–60) and have higher salaries (>100,000).
Gender has minimal impact on purchase behavior.
No strong correlation between Age and Salary.


Model Performance:
Test accuracy: ~85–90%.
Confusion matrix and classification report show balanced performance despite class imbalance.
Feature importance: Age and Salary are the most influential predictors.


Visualizations:
Count plots, histograms, box plots, scatter plots, and correlation heatmap.
Confusion matrix heatmap and feature importance bar plot.
Text-based Decision Tree rules (graphical tree requires Graphviz).



Technologies

Programming: Python 3
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
Tools: Jupyter Notebook, GitHub
Optional: Graphviz for graphical Decision Tree visualization

Future Improvements

Use ensemble methods (e.g., Random Forest) to improve accuracy.
Address class imbalance with SMOTE or class weights.
Add more features (e.g., location, income source) for better predictions.

Contact
For questions, reach out via LinkedIn ( https://www.linkedin.com/in/mohammed-jameel-2866028/ ) or GitHub issues  (https://github.com/Jamilath/iphone-purchase-prediction)
