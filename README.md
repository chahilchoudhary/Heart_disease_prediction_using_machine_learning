# Heart_disease_prediction_using_machine_learning

Overview
The primary aim of this project is to harness the power of machine learning to predict the likelihood of a person having heart disease based on various health metrics. Early prediction of cardiovascular diseases can lead to better management and timely interventions, potentially saving lives.

Dataset
The dataset used in this project consists of several parameters that are considered risk factors for heart disease, including:

Age
Sex
Chest pain type
Blood pressure
Cholesterol level
Fasting blood sugar
Electrocardiographic results
Maximum heart rate achieved
Exercise-induced angina
ST depression induced by exercise relative to rest
Peak exercise ST segment
Number of major vessels colored by fluoroscopy
Thalassemia type
The target variable is binary: 0 (no presence of heart disease) and 1 (presence of heart disease).

Methodology
Data Preprocessing: Before feeding the data into a machine learning model, we've ensured that it's clean, free from any inconsistencies, and is appropriately scaled.

Feature Selection: Not all features are equally informative. We've used various feature selection techniques to choose the most relevant parameters.

Model Building: Several machine learning algorithms, such as Logistic Regression, Decision Trees, Random Forests, and Gradient Boosting, were explored to find the model with the best performance.

Evaluation: Models were evaluated based on accuracy, precision, recall, and the area under the ROC curve to ensure that they not only predict accurately but also minimize false positives and negatives.

Deployment: The best-performing model has been deployed as a web application where users can input their health metrics and get a prediction instantly.
