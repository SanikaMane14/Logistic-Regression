Logistic Regression

Aim
To implement Logistic Regression for predicting whether a student will Pass or Fail based on academic performance and study-related features.

Dataset
The dataset contains 100 student records with the following attributes:
- Student ID
- Attendance Percentage
- Homework Percentage
- Midterm Score
- Study Hours Per Week
- Pass

Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab / Jupyter Notebook

Algorithm
Logistic Regression is a supervised machine learning classification algorithm used to predict a binary outcome such as Pass or Fail.

Features Used
attendance_pct
homework_pct
midterm_score
study_hours_per_week

Steps Performed
1. Import the required Python libraries.
2. Load the Pass-Fail dataset.
3. Display the first five records.
4. Check dataset information.
5. Check column names.
6. Check missing values.
7. Check duplicate values.
8. Select input features and target variable.
9. Split the dataset into training and testing data.
10. Train the Logistic Regression model.
11. Predict the test data.
12. Calculate accuracy.
13. Generate the confusion matrix.
14. Generate the classification report.
15. Predict the result for a new student.
16. Calculate prediction probability.
17. Display model coefficients.

Train-Test Split

The dataset is divided into:
- Training Data: 80 records
- Testing Data: 20 records

The experiment uses "test_size=0.20" and "random_state=42".

Results
The model achieved:

Accuracy: 1.0
Accuracy Percentage: 100.0%

The confusion matrix was:
[[8, 0],
 [0, 12]]

The classification report shows 1.00 precision, recall, and F1-score for both classes.

New Student Prediction

For a new student with:

Attendance = 85
Homework = 80
Midterm Score = 75
Study Hours/Week = 10

The model predicted:

Student will PASS

Author
Sanika Mane
