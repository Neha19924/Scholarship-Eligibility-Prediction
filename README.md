# 🎓 Scholarship Prediction using PySpark

This project uses PySpark MLlib to build a machine learning model that predicts whether a student is eligible for a scholarship based on academic performance and other factors.

## 📌 Project Overview

The goal of this project is to:

Process student data using PySpark
Create a new target variable (Scholarship)
Train a Decision Tree Classifier
Evaluate model performance using accuracy, precision, and recall
Visualize feature importance and prediction results
## 📂 Dataset

The dataset contains student-related information such as:

### Gender
### Parental Support
### Extracurricular Activities
### Previous Grade
### Study Hours per Week
### Attendance Rate
### Final Grade

A new column Scholarship is created based on:

Scholarship = 1 if:
    FinalGrade >= 75 AND ParentalSupport == "High"
Else:
    Scholarship = 0
## ⚙️ Technologies Used
### Python 🐍
### PySpark
### Spark MLlib
### Matplotlib
### Pandas
## 🧠 Machine Learning Pipeline

The pipeline includes:

### Data Cleaning
### Removing null values
### Feature Engineering
### Creating target variable (Scholarship)
### Categorical Encoding
### StringIndexer for:
### Gender
### Parental Support
### Extracurricular Activities
### Feature Vector Creation
### Using VectorAssembler
### Model Training
### Decision Tree Classifier
### Train-Test Split
### 80% Training
### 20% Testing
## 📊 Model Evaluation

The model is evaluated using:

Accuracy
Precision (Weighted)
Recall (Weighted)

Example output:

Accuracy: 0.XX
Precision: 0.XX
Recall: 0.XX
## 📈 Visualizations

The project includes multiple visualizations:

1. Feature Importance
Shows which features influence the prediction the most
2. Scholarship Distribution
Bar chart of eligible vs non-eligible students
3. Actual vs Predicted Comparison
Compares model predictions with actual values
## ▶️ How to Run
Install dependencies:
pip install pyspark matplotlib pandas
Start Spark session (handled in script)
Update dataset path:
"C:/Users/Neha/Desktop/student_performance_updated_1000.csv"
Run the script:
python your_script_name.py
## 📌 Notes
Ensure Apache Spark is properly installed and configured
Dataset path should be updated based on your system
Remove the stray character a in the plotting section to avoid errors
## 🚀 Future Improvements
Try other models (Random Forest, Logistic Regression)
Perform hyperparameter tuning
Handle class imbalance
Deploy as a web application
## 👩‍💻 Author

Neha
