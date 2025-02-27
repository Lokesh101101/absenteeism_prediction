# 🏢 Employee Absenteeism Prediction
 The project aims to analyze an employee absenteeism dataset  to understand patterns, reasons, and predict future absences using Machine Learning models.

### 📝 Project Description:
 
Briefly state the project's objective: To analyze employee absenteeism data, identify patterns and reasons, predict future absences, and optimize workforce management.
Mention the use of Python for data preprocessing and analysis.
Highlight the focus on actionable insights, including demographic patterns, absence reasons, duration prediction, and risk identification.

### 📜 Table of Contents:

- Installation
- Data
- Methodology
- Key Findings
- Models

### 📌 Installation:

List required Python libraries (e.g., Pandas, Scikit-learn, NumPy).
Provide instructions on how to install them (e.g., using pip install).
### 📌 Data:

Describe the dataset used (source, columns, etc.).
Explain data preprocessing steps (cleaning, handling missing values, feature engineering).
Mention any data transformations or encodings applied.
### 📌 Methodology:

### Exploratory Data Analysis (EDA):
Describe the analysis of absenteeism patterns across demographics.
Outline the methods used to identify frequent reasons for absences.
### Predictive Modeling:
Explain the approach used to predict the duration of absences.
Detail the classification models used to identify employees at risk of high absenteeism.
Clustering:
Describe the clustering models used to group employees with similar absenteeism patterns.
### 📌 Key Findings:

Summarize the main insights gained from EDA.
Present the results of the predictive models (accuracy, precision, recall, etc.).
Describe the identified employee clusters and their characteristics.
List the employees that were identified as high risk.
### 📌 Models:

- Detail the classification models used.
- Detail the clustering models used.
- Explain the parameters used.

### 🤖 Simple linear vs. Multilinear Regression Model
|Model |	R2 | MSE | MAE | RMSE |
| ------ | ------ | ------ | ------ | ------ |
| Simple Linear | .008 | .90 | .44 | .94 |
| Multilinear 	| .08	| .83 |	.42 |	.91 |

### 🤖 Logistic Regression vs. K Nearest Neighbor Model
|Model |	Accuracy | Precision | Recall | F1 Score|
| ------ | ------ | ------ | ------ | ------ |
| Logistic Regression | 79.7% | 80% | 87.7% | 84% |
| K Nearest Neighbor 	| 73.6%	| 72.9% |	90% |	80.5% |

### 🤖 KMeans Clustering Model
|Model |	Silhouette | Calinski Harabasz  | Davies Bouldin |
| ------ | ------- | ------- | ------- |
| KMeans | 19.5% | 68.7 | 1.91 |

