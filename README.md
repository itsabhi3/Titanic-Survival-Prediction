# Titanic-Survival-Prediction
# Images Screenhot
<img width="753" height="516" alt="Screenshot 2026-06-23 113437" src="https://github.com/user-attachments/assets/fcb64e31-a683-4d2d-b987-94876bd5bfbf" />
<img width="797" height="587" alt="Screenshot 2026-06-23 113624" src="https://github.com/user-attachments/assets/e56ed5d9-9b26-44e2-a7b8-58d8ef96484e" />
<img width="763" height="578" alt="Screenshot 2026-06-23 113638" src="https://github.com/user-attachments/assets/45e7d0a7-9f73-4518-8495-bd2d29a35cee" />
<img width="755" height="587" alt="Screenshot 2026-06-23 113649" src="https://github.com/user-attachments/assets/d01c3130-ae32-4cba-adea-0abac26a06ce" />
<img width="977" height="773" alt="Screenshot 2026-06-23 113705" src="https://github.com/user-attachments/assets/45156f5c-71bc-4326-9044-9c3993a52b1a" />
<img width="1012" height="515" alt="Screenshot 2026-06-23 113720" src="https://github.com/user-attachments/assets/9221dcef-48ca-4322-8d95-64809e16c63a" />
<img width="688" height="757" alt="Screenshot 2026-06-23 113817" src="https://github.com/user-attachments/assets/c737d83c-fd19-4634-93c1-2daa7551aff7" />
<img width="1026" height="503" alt="Screenshot 2026-06-23 121959" src="https://github.com/user-attachments/assets/a5a44ec3-7803-445d-9fca-acbedc8dcd56" />


------------------------------📌 Project Overview------------------------------------------

This project predicts passenger survival in the Titanic disaster using machine learning (Logistic Regression) on a cleaned dataset.

.

----------------------------------📂 Dataset Columns-------------------------------------

Dataset contains the following features:

survived (Target: 0 = Not Survived, 1 = Survived)
pclass (Passenger class)
sex (Gender)
age (Age of passenger)
sibsp (Siblings/Spouses aboard)
parch (Parents/Children aboard)
fare (Ticket fare)
adult_male
alone
who_man
who_woman
embarked_Q
embarked_S


--------------------------------🧹 Data Cleaning---------------------------------------
Missing values handled in age column
Categorical values converted into numerical format
Data prepared for model training


-------------------------📊 Exploratory Data Analysis (EDA)-----------------------------

Visual analysis performed using Seaborn and Matplotlib:

Survival distribution
Sex vs Survival
Pclass vs Survival
Age distribution
Relationship between features using heatmap


=---------------------------🤖 Model-----------------------------------
Logistic Regression model used
Model trained on cleaned dataset
Used for binary classification (survived / not survived)


--------------------------📈 Model Performance-----------------------------

The Logistic Regression model was evaluated using different metrics:

Accuracy: 0.83 (83%)
Precision: 0.81
Recall: 0.74
F1 Score: 0.77 (class 1)
Classification Report
Class 0 (Not Survived): Precision 0.84, Recall 0.89, F1-score 0.87
Class 1 (Survived): Precision 0.81, Recall 0.74, F1-score 0.77
Confusion Matrix
[[98 12]
 [18 51]]

--------------------------------🔍 Summary------------------------------

Model achieved around 83% accuracy
It performs better in predicting non-survived passengers (Class 0)
Prediction for survived passengers (Class 1) can still be improved

------------------------------------🧰 Tools Used-----------------------------

Python, Pandas, NumPy, Matplotlib, Seaborn

👨‍💻 Author
Abhishek Dhakad
