This project aims to analyze and model the dataset provided in the Kaggle competition "Who is the real winner?" using various machine learning techniques. The primary objective is to predict the education level of election winners based on multiple features such as assets, liabilities, criminal cases, and other demographic details.

Methodology
Data Preprocessing:

Currency Conversion: Standardized 'Total Assets' and 'Liabilities' fields to numerical format in Indian Rupees.
Encoding Categorical Variables: Transformed categorical variables like 'Party', 'State', and 'Education' into numerical codes.
Exploratory Data Analysis (EDA):

Analyzed the distribution and relationships of features such as education levels, criminal cases, and asset values.
Identified patterns and correlations to inform predictive modeling.
Model Preparation:

Data Splitting: Divided the dataset into training and testing sets.
Feature Selection: Selected key features influencing the outcome based on domain knowledge and iterative testing.
Experimentation:

Tested several machine learning models including SVM, KNN, Decision Tree, and Random Forest.
Utilized cross-validation and F1-score as the primary performance metric.
Insights:

Higher education levels tend to correlate with higher asset values and fewer criminal cases.
The distribution of criminal cases and financial disclosures provides significant information for predicting education levels.
Results
The models were evaluated using the F1-score, considering the imbalanced nature of the dataset. Due to a technical error during the final submission, the leaderboard ranking could not be finalized within the competition deadline.

References
The project methodology and analysis were informed by various sources, including datasets from the Election Commission of India and literature on machine learning and data analysis.
