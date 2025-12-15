# Linear Regression on Szeged Weather Dataset

## 📌 Aim
To implement a Decision Tree Classifier to predict loan approval status using the **Loan_approval_data_2025.csv** dataset and visualize the decision-making process through a tree diagram.

## 📊 Dataset
https://www.kaggle.com/datasets/parthpatel2130/realistic-loan-approval-dataset-us-and-canada

## 🛠️ Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- KaggleHub

## ⚙️ Methodology
1. Downloaded dataset using KaggleHub
2. Loaded and preprocessed data
   - Removed unnecessary columns (customer_id)
   - Encoded categorical variables using one-hot encoding
   - Handled missing values
3. Defined:
   - **Target Variable:** loan_status
   - **Features:** All remaining attributes
4. Split data into training and testing sets (80:20 with stratification)
5. Trained a Decision Tree Classifier with:
   - Gini index
   - Controlled depth and minimum samples to avoid overfitting
6. Evaluated the model using:
   - Accuracy score
   - Confusion matrix
   - Classification report
7. Visualized the trained decision tree

## 📈 Results
Accuracy: 0.8295
[[3777  718]
 [ 987 4518]]
              precision    recall  f1-score   support

           0       0.79      0.84      0.82      4495
           1       0.86      0.82      0.84      5505

    accuracy                           0.83     10000
   macro avg       0.83      0.83      0.83     10000
weighted avg       0.83      0.83      0.83     10000


