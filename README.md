# Data-Mining-Techniques
## Exploring Socio-Economic Patterns in Adult Census Income for Informed Decision-Making

## Project Overview
This project explores socio-economic patterns in U.S. adult income based on census data. Using various machine learning models, we aim to analyze demographic and employment-related factors to predict income levels, specifically distinguishing between individuals earning above or below $50,000 annually. The insights generated can assist in informed decision-making around socio-economic issues, workforce management, and economic policy.

## Project Structure
** Data Collection: U.S. Census data from 1994 with attributes including age, education, occupation, work class, marital status, etc.
** Preprocessing: Handling missing values, encoding categorical data, normalizing features, and removing outliers.
** Feature Engineering: Creation of additional relevant features and conversion of categorical features to numerical representations.
** Modeling: Support Vector Machines (SVM), Random Forest, and Gradient Boosting are utilized for predictive modeling.
** Evaluation: Models are evaluated using accuracy, precision, recall, and F1-score to compare performance.

## Installation and Requirements
Python 3.x
** Required Libraries:
pandas for data manipulation and cleaning
numpy for numerical operations
matplotlib and seaborn for visualizations
scikit-learn for machine learning model training and evaluation

## Usage
Load Data: The dataset can be loaded from a CSV file, containing socio-economic attributes.
Preprocess Data: The preprocessing script handles missing values, encodes categorical data, and scales numerical values.
Train Models: Execute the script to train SVM, Random Forest, and Gradient Boosting classifiers.
Evaluate Models: Review the model outputs in terms of accuracy and classification reports.

## Key Steps
Data Preprocessing: Includes handling missing values, encoding, and scaling.
Feature Engineering: Transformation of categorical data and removal of redundant features.
Training & Testing: Model training and evaluation with cross-validation.
Visualization: Use of histograms, bar charts, and pair plots for Exploratory Data Analysis (EDA).

## Results
The Gradient Boosting Classifier demonstrated the highest accuracy at 85.67%, followed by SVM and Random Forest, confirming the model’s superior capacity in distinguishing income levels.

 ## Architecture diagram of the project workflow:

                 +-------------------------------+
                |                               |
                |      Census Income Dataset     |
                |                               |
                +---------------+---------------+
                                |
                                v
                  +-------------------------+
                  |                         |
                  |     Data Preprocessing  |
                  |                         |
                  | - Handle missing values |
                  | - Encode categorical    |
                  |   variables            |
                  | - Scale numerical data  |
                  |                         |
                  +-----------+-------------+
                                |
                                v
                  +-------------------------+
                  |                         |
                  |  Exploratory Data       |
                  |  Analysis (EDA)         |
                  |                         |
                  | - Visualization         |
                  | - Identify patterns     |
                  |   & relationships       |
                  |                         |
                  +-----------+-------------+
                                |
                                v
                  +-------------------------+
                  |                         |
                  |   Feature Engineering   |
                  |                         |
                  | - Extract key features  |
                  | - Transform data        |
                  |                         |
                  +-----------+-------------+
                                |
                                v
                  +-------------------------+
                  |                         |
                  |  Model Training         |
                  |                         |
                  | - Train SVM, Random     |
                  |   Forest, Gradient      |
                  |   Boosting              |
                  |                         |
                  +-----------+-------------+
                                |
                                v
                  +-------------------------+
                  |                         |
                  |   Model Evaluation      |
                  |                         |
                  | - Accuracy, Precision,  |
                  |   Recall, F1-Score      |
                  | - Compare model         |
                  |   performance           |
                  |                         |
                  +-----------+-------------+
                                |
                                v
                  +-------------------------+
                  |                         |
                  |   Results & Insights    |
                  |                         |
                  | - Visualize outcomes    |
                  | - Summarize socio-      |
                  |   economic patterns     |
                  |                         |
                  +-------------------------+
