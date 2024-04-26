DESCRIPTION OF THE PROJECT

Background
The dataset in question is a component of the textbook "Introduction to Statistical Learning."


Hyperlink to dataset: https://www.statlearning.com/resources-python


Goal
Our objective is to construct a predictive model to determine whether a patient has Heart Disease or not. Additionally, we aim to minimize Type I error, meaning we want to avoid misclassifying a patient as not having Heart Disease when they actually do. Therefore, the metric we prioritize for optimizing the models is recall.


Data Dictionary

Age: Age of the patient in years

Sex: Gender of the patient. 0: Female 1: Male

CP (Chest Pain Type): Type of chest pain experienced by the patient.

Trestbps (Resting Blood Pressure): Resting blood pressure of the patient in mm Hg on admission to the hospital.

Chol (Serum Cholesterol Level): Serum cholesterol level of the patient in mg/dl.

Fbs (Fasting Blood Sugar): Fasting blood sugar > 120 mg/dl. 0: False 1: True

Restecg (Resting Electrocardiographic Results): Resting electrocardiographic results.

Thalach (Maximum Heart Rate Achieved): Maximum heart rate achieved by the patient during exercise.

Exang (Exercise Induced Angina): Exercise-induced angina. 0: No 1: Yes

Oldpeak (ST Depression Induced by Exercise Relative to Rest): ST depression induced by exercise relative to rest.

Slope: The slope of the peak exercise ST segment.

CA (Number of Major Vessels Colored by Flourosopy): Number of major vessels colored by fluoroscopy. 0 to 3: Number of vessels

Thal (Thalassemia): Thalassemia.

AHD: Presence of heart disease.


Jupyter Notebooks
Inspect the Jupyter Notebooks in order:

In "B1) Preprocessing_and_EDA", ee conducted a comprehensive examination and preprocessing of the dataset. This involved transforming categorical variables, addressing missing data, and managing outliers and high-leverage points. Additionally, we analyzed variable distributions in detail.

To deepen our exploration, we utilized various visualization techniques such as boxplots and correlation matrices. These visualizations allowed us to visualize relationships within the data and identify underlying patterns.

Finally, we split the dataset to facilitate model evaluation and validation.

From Notebooks B2 to B9, we implemented several methods to address the problem. The methods used include:

B2) Logistic Regression

B3) Linear Discriminant Analysis

B4) Quadratic Discriminant Analysis

B5) K-Nearest Neighbors

B6) Gaussian Naive Bayes

B7) Random Forest Classifier

B8) Support Vector Classifier

B9) XGBOOST

Lastly, in "C) Results_and_Conclusions", we compare model performance metrics and identify the most accurate prediction method.

Note 1: Scaling
The dataset underwent scaling prior to the application of any method.

Note 2: Optimization of models
For every model optimized through the GridSearchCV method, we determined the values of hyperparameters to be examined by referring to literature, articles, and also sought assistance from ChatGPT.

Note 3: Updates
In the future, we may consider incorporating additional methods.
