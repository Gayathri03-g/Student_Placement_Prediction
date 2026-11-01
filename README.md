# 🎓 Student Placement Prediction using Machine Learning

### Predicting Student Placement Outcomes Using a Decision Tree Classifier

## 📌 Project Overview

This project demonstrates a beginner-level Machine Learning classification model that predicts whether a student is likely to get placed based on academic performance, technical skills, projects, internships, certifications, and DSA scores.

The project uses Python and Scikit-learn to build, train, test, and evaluate a Decision Tree Classification model.

The objective was to understand the fundamental Machine Learning workflow and apply theoretical concepts through practical implementation.

## 🎯 Project Objective

To develop a Machine Learning model that classifies students into two categories:

- **1 – Placed**
- **0 – Not Placed**

The model uses student-related academic and skill-based attributes to generate placement predictions.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Dataset creation and manipulation |
| Scikit-learn | Machine Learning implementation |
| Decision Tree | Classification algorithm |
| Jupyter Notebook / Google Colab | Development environment |

## 📊 Dataset Description

A manually created dataset containing **30 student records** was used for this project.

### Input Features

| Feature | Description |
|---|---|
| CGPA | Student's academic performance |
| Skills | Technical skill score |
| Projects | Number of completed projects |
| Internships | Number of internships |
| Certifications | Number of certifications |
| DSA_Score | Data Structures and Algorithms score |

### Target Variable

`Placed`

- `1` – Student is placed.
- `0` – Student is not placed.

**Note:** This is a small demonstration dataset created for learning purposes, not a real-world placement dataset.

## ⚙️ Machine Learning Workflow

1. Import the required Python libraries.
2. Create the student dataset using Pandas.
3. Convert the dataset into a DataFrame.
4. Select input features (X).
5. Define the target variable (y).
6. Split the dataset into training and testing sets.
7. Create a Decision Tree Classifier.
8. Train the model using training data.
9. Test the model using unseen test data.
10. Evaluate the model using accuracy score.
11. Generate predictions for new student records.

## 🤖 Model Implementation

**Algorithm:** Decision Tree Classifier

The dataset was divided using an 80:20 train-test split.

- Training records: 24
- Testing records: 6
- Random state: 42

The model was trained using:

`model.fit(X_train, y_train)`

Predictions were generated using:

`model.predict(X_test)`

## 📈 Model Performance

The model achieved the following result:

| Evaluation Metric | Result |
|---|---:|
| Test Accuracy | **83.33%** |
| Correct Predictions | 5 |
| Total Test Records | 6 |

The accuracy was calculated using Scikit-learn's `accuracy_score()`.

## 🔍 Sample Predictions

The trained model was also tested using two new student records.

**Example 1:**

- CGPA: 8.5
- Skills: 0
- Projects: 0
- Internships: 0
- Certifications: 0
- DSA Score: 22

Prediction: **Not Placed (0)**

**Example 2:**

- CGPA: 8.81
- Skills: 10
- Projects: 5
- Internships: 4
- Certifications: 5
- DSA Score: 76

Prediction: **Placed (1)**

## 📚 Key Learnings

Through this project, I gained practical understanding of:

- Creating and manipulating datasets using Pandas.
- Understanding features and target variables.
- Splitting datasets into training and testing data.
- Implementing a Decision Tree Classifier.
- Training and testing a Machine Learning model.
- Evaluating model performance using accuracy.
- Generating predictions for new input data.

## 🚀 Future Improvements

- Work with larger, real-world placement datasets.
- Explore additional classification algorithms.
- Perform feature engineering and data preprocessing.
- Evaluate models using precision, recall, F1-score and confusion matrices.
- Apply cross-validation and hyperparameter tuning.
- Develop a simple web application for interactive predictions.

## 👩‍💻 Author

**Gayathri Vadla**

B.Tech – Computer Science and Engineering (AI & ML)

Interested in Python, Machine Learning, Artificial Intelligence, and Data Science.

## ⭐ Acknowledgement

This project marks one of my first practical steps into Machine Learning. It helped me connect Python programming and data handling concepts with the fundamentals of predictive modelling.

**Learning by building, improving with every project! 🌱**
