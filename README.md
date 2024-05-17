# Medical-Dataset
Medical Dataset Analysis
Overview
This project focuses on the analysis of a medical dataset containing information about patients' health metrics and test results. The dataset was collected from [data source], and it includes various features such as age, gender, heart rate, blood pressure, blood sugar levels, and cardiac enzyme levels. The goal of this analysis is to explore the relationships between different health metrics and diagnose potential heart conditions based on the provided data.

Data Source
The dataset used in this project is sourced from [data source]. It consists of [number of samples] samples and [number of features] features. Each sample represents a patient, and the features include:

Age: Age of the patient.
Gender: Gender of the patient (1 for male, 0 for female).
Heart rate: Resting heart rate of the patient (beats per minute).
Systolic blood pressure: The upper number in blood pressure measurement (mmHg).
Diastolic blood pressure: The lower number in blood pressure measurement (mmHg).
Blood sugar: Fasting blood sugar level of the patient (mg/dL).
CK-MB: Creatine kinase-MB enzyme level (ng/mL).
Troponin: Troponin enzyme level (ng/mL).
Result: Binary outcome indicating the presence (1) or absence (0) of a heart condition.
Data Cleaning and Preprocessing
Prior to analysis, the dataset underwent cleaning and preprocessing steps, including:

Handling missing values.
Encoding categorical variables.
Feature scaling.
Removing outliers.
Analysis and Modeling
The analysis involves exploring the relationships between different health metrics and the presence of heart conditions. Various machine learning models, including logistic regression and random forest, were trained and evaluated to predict the presence of heart conditions based on the provided features. Model performance metrics such as accuracy, precision, recall, and F1-score were computed to assess the effectiveness of each model.

Results
The analysis revealed significant correlations between certain health metrics and the presence of heart conditions. For example, older age, higher blood pressure, and elevated cardiac enzyme levels were associated with an increased risk of heart conditions. The random forest model outperformed other models, achieving an accuracy of [accuracy score] on the test dataset.

Technologies Used
Python
Pandas
NumPy
Scikit-learn
Getting Started
To run the analysis locally, follow these steps:

Clone the repository to your local machine.
Install the required dependencies listed in the requirements.txt file.
Run the Jupyter Notebook medical_dataset_analysis.ipynb to reproduce the analysis.
Contributing
Contributions to this project are welcome. If you have any suggestions or improvements, feel free to open an issue or create a pull request.

Contact
For inquiries or feedback regarding the project, please contact [Jeyhun] at [jeyhun.aliyevv01@gmail.com].

License
This project is licensed under the [MIT ] License - see the LICENSE file for details.

