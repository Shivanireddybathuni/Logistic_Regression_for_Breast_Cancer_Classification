Hi Folks! I’m Shivani, currently pursuing my BCA from Nalanda Institute. I have a deep passion for data science and a strong grasp of machine learning algorithms. This project is part of my journey to explore and apply data science techniques to real-world problems. In this project, I developed a logistic regression model to predict the Progesterone Status in breast cancer patients.

Overview
This project involves building a logistic regression model to predict the Progesterone Status of breast cancer patients based on various clinical and demographic features. The dataset used for this project includes features such as age, race, marital status, tumor size, and other relevant clinical information.

Dataset
The dataset contains the following features:

Age: Age of the patient.
Race: Race of the patient.
Marital Status: Marital status of the patient.
T Stage: Tumor stage.
N Stage: Lymph node stage.
6th Stage: 6th edition AJCC stage.
Differentiate: Degree of differentiation of the tumor.
Grade: Tumor grade.
A Stage: Stage of cancer.
Tumor Size: Size of the tumor.
Estrogen Status: Estrogen receptor status.
Progesterone Status: Progesterone receptor status (Target variable).
Regional Node Examined: Number of regional lymph nodes examined.
Reginol Node Positive: Number of regional lymph nodes positive for cancer.
Survival Months: Survival time in months.
Status: Vital status of the patient.
Preprocessing
The dataset was cleaned and preprocessed to handle missing values and categorical variables.
The Progesterone Status was used as the dependent variable, and all other features were treated as independent variables.
Model
The model used is a Logistic Regression classifier. The dataset was split into 80% training and 20% testing sets.

Training and Evaluation
Training: The model was trained on the 80% training set.
Testing: The model was evaluated on the 20% testing set.
Metrics
The model was evaluated using the following metrics:

Accuracy: Overall accuracy of the model.
Precision, Recall, F1-Score: Detailed classification report.
Confusion Matrix: Visual representation of the model's performance.
Results
The logistic regression model performed well on the testing set, providing valuable insights into the relationship between the features and the Progesterone Status.
A confusion matrix was plotted to show the distribution of true positives, true negatives, false positives, and false negatives.
Feature Coefficients
The impact of each feature on the model's predictions was analyzed by examining the coefficients of the logistic regression model.
