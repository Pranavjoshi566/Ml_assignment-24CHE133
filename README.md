# Ml_assignment-24CHE133
This project uses the Kaggle “Student Performance” dataset (about 10,000 students: hours studied, previous scores, extracurricular activities, sleep hours, practice papers, and a Performance Index).  

Model 1 predicts the Performance Index ; Model 2 predicts whether a student does extracurricular activities (Yes/No).
I used Linear Regression for Model 1 and Logistic Regression for Model 2, both with an 80/20 train-test split after removing duplicate rows(127 duplicate rows where present) & no missing values were found.
I converted the Yes/No for extracurricular activities into 1/0 by using 'ONE HOT ENCODING'
Results: Linear Regression got an R² of 0.988 and an MSE of 4.31, so it predicts performance very accurately; Logistic Regression got an accuracy of 57.8%, only slightly better than guessing.
I learned that a simple linear model works very well when features relate directly to the target, while the same student data hardly predicts extracurricular participation, so a model is only as good as the signal in its features.
