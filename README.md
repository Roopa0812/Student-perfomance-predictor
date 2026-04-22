# 🎓 Student Performance Predictor

A machine learning project that predicts student academic performance (`GradeClass`) based on behavioral, academic, and demographic factors such as study time, absences, parental support, and GPA.

---

## 📌 Project Overview

This project demonstrates a complete **end-to-end machine learning pipeline** to analyze student data and predict performance levels. It focuses on identifying key factors that influence academic success and provides insights that can be used for early intervention.

---

## 🚀 Features

* 📊 Exploratory Data Analysis (EDA) with visualizations
* 🧹 Data cleaning and preprocessing
* 🔤 Categorical encoding & feature transformation
* ⚖️ Feature scaling using StandardScaler
* 🤖 Multiple ML models:

  * Random Forest Classifier
  * Logistic Regression
  * Support Vector Machine (SVM)
* 📈 Model evaluation using:

  * Accuracy Score
  * Confusion Matrix
  * Classification Report
* 🔍 Feature impact analysis

---

## 🗂️ Dataset Description

The dataset includes the following features:

| Feature           | Description                            |
| ----------------- | -------------------------------------- |
| Age               | Student age                            |
| Gender            | Male/Female                            |
| Ethnicity         | Student background                     |
| ParentalEducation | Parent education level                 |
| StudyTimeWeekly   | Weekly study hours                     |
| Absences          | Number of absences                     |
| Tutoring          | Whether student receives tutoring      |
| ParentalSupport   | Level of parental involvement          |
| Extracurricular   | Participation in activities            |
| Sports            | Sports involvement                     |
| Music             | Music participation                    |
| Volunteering      | Volunteering activities                |
| GPA               | Grade Point Average                    |
| GradeClass        | Target variable (performance category) |

---

## ⚙️ Tech Stack

* 🐍 Python
* 📦 Libraries:

  * pandas
  * numpy
  * matplotlib
  * seaborn
  * scikit-learn

---

## 🔄 Machine Learning Workflow

1. **Data Collection & Loading**
2. **Data Cleaning**

   * Removed missing values
   * Checked duplicates
3. **Exploratory Data Analysis**

   * Correlation heatmaps
   * Distribution & boxplots
4. **Data Preprocessing**

   * Encoding categorical variables
   * Feature scaling
5. **Model Training**

   * Random Forest
   * Logistic Regression
   * SVM
6. **Model Evaluation**

   * Accuracy, Precision, Recall, F1-score
   * Confusion Matrix

---

## 📊 Results

| Model               | Accuracy |
| ------------------- | -------- |
| Random Forest       | XX%      |
| Logistic Regression | XX%      |
| SVM                 | XX%      |

✅ **Random Forest performed best** in terms of overall accuracy and stability.

---

## 🔍 Sample Prediction

**Input:**

* StudyTimeWeekly: 10 hours
* Absences: 2
* ParentalSupport: High

➡️ **Predicted Output:** High Performance

---

## 🧠 Key Insights

* 📈 Higher study time strongly improves performance
* ❌ Increased absences negatively affect grades
* 👨‍👩‍👧 Parental support has a positive impact
* 🎯 GPA is a strong indicator of performance

---

## 🌍 Real-World Impact

This project demonstrates how machine learning can be applied in education to:

* Identify at-risk students early
* Help teachers provide targeted support
* Improve student outcomes through data-driven decisions

---

## ⚡ Challenges Faced

* Handling categorical data using encoding techniques
* Ensuring proper feature scaling for models like SVM
* Comparing multiple models effectively
* Avoiding overfitting and ensuring generalization

---

## ▶️ How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/student-performance-predictor.git
```

2. Navigate to the project folder:

```bash
cd student-performance-predictor
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the notebook:

```bash
jupyter notebook
```

---

## 📁 Project Structure

```
📦 student-performance-predictor
 ┣ 📜 STU_PERFORMANCE.ipynb
 ┣ 📜 README.md
 ┣ 📜 requirements.txt
 ┗ 📂 dataset
```

---

## 🔮 Future Scope

* 🌐 Deploy as a Streamlit web application
* ⚙️ Hyperparameter tuning (GridSearchCV)
* 📊 Interactive dashboards
* 🤖 Advanced models (XGBoost, Neural Networks)
* 📉 Feature importance visualization

---

## 🎥 Demo

*(Add screenshots or demo link here for better visualization)*

Example:
![Confusion Matrix](images/confusion_matrix.png)

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👩‍💻 Author

**Roopa Reddy**
B.Tech - Computing & Data Science
Aspiring Data Scientist | AI & Cloud Enthusiast

---

⭐ If you found this project useful, consider giving it a star!
