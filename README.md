**House Price Prediction Through Machine Learning**


Description
This project focuses on predicting house prices using various machine learning techniques. The notebook explores, preprocesses, and models a dataset of housing prices, demonstrating step-by-step feature selection and model building. The objective is to develop a robust prediction model that can estimate house prices accurately based on selected features.

**Dataset**
The dataset used for this project includes the following details about houses:


Numerical variables: Square meters, number of floors, number of rooms, and basement area.
Categorical variables: City codes, whether the house has a yard, pool, or storage room.
Target variable: House price.
Data preprocessing included handling outliers, transforming price variables for better readability, and updating the dataset.

Note: the data used is machine generated not real data



**Steps in the Project**
Exploratory Data Analysis (EDA):

Statistical summaries and visualizations.
Identification of outliers in variables.
Examination of binary variables (e.g., hasYard, hasPool, isNewBuilt) and their impact on price.
Feature Engineering and Selection:

Correlation analysis to identify significant predictors.
Random Forest Regressor for feature importance ranking.
LASSO regression for regularization-based feature selection.
Sequential feature selection for identifying the optimal feature set.
Final Selected Features:

SquareMeters, floors, hasPool, hasYard, and cityPartRange.
Model Building:

**Linear Regression**
Additional models (to be specified, e.g., Random Forest, Gradient Boosting, etc.).
Model Evaluation:

Performance metrics like RMSE, MAE, and R-squared.
Cross-validation to ensure robustness.
Libraries Used
This project utilizes the following Python libraries:

Data Analysis: pandas, numpy
Visualization: matplotlib, seaborn
Machine Learning: scikit-learn

****How to Run****
Clone this repository:
bash
Copy code
git clone https://github.com/yourusername/House-Price-Prediction.git
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Open the notebook:
bash
Copy code
jupyter notebook House_Price_Prediction.ipynb
Follow the steps in the notebook to preprocess data, train models, and evaluate results.
Results
The best-performing model was based on features like SquareMeters, floors, and hasPool. Results showed strong predictive accuracy (details available in the notebook).

Future Work
Integrating additional machine learning algorithms.
Incorporating more features from external data sources.
Enhancing the preprocessing pipeline.



**Author**
Sadaqat Ghafoorzai
For questions or suggestions, feel free to reach out!

