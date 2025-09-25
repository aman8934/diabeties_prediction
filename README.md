# diabeties_prediction
Use of SVM Classifier and improving recall score 


🩺 Diabetes Prediction using SVM Classifier

This project uses a Support Vector Machine (SVM) classifier to predict whether a person has diabetes based on medical attributes. The dataset used is the Pima Indians Diabetes Dataset.

📂 Project Overview

Preprocesses the dataset (handling duplicates, scaling features).

Splits the data into training and test sets.

Trains an SVM with a linear kernel on standardized data.

Evaluates the model using accuracy, precision, and recall.

Builds a predictive system where you can input patient data and get a prediction.

⚙️ Technologies Used

Python 🐍

NumPy, Pandas

Matplotlib, Seaborn (for visualization)

Scikit-learn (SVM, train/test split, metrics, StandardScaler)

📊 Dataset

The dataset is diabetes.csv (Pima Indians Diabetes Database).

Features include: pregnancies, glucose level, blood pressure, skin thickness, insulin, BMI, diabetes pedigree function, age.

Target: Outcome (1 → Diabetic, 0 → Non-Diabetic).



Recall Improvement Attempts

Since recall is very important for medical predictions, I experimented with different techniques to improve the recall score of the SVM classifier:

Decision Threshold Adjustment

Changed the classification threshold on the SVM decision function to classify more patients as positive.

Kernel Variations

Tested different kernels (linear, rbf) to check if non-linear decision boundaries improve recall.

(In this project, these changes did not significantly improve recall, but they are important steps in model evaluation and understanding trade-offs between precision and recall.)
