# Elevate_Labs_Task-4
# 🧠 Task 4: Binary Classification using Logistic Regression

## 📌 Internship: AI & ML Internship - Elevate Labs (MSME - Govt. of India)

## ✅ Objective
Build a **binary classifier** using **Logistic Regression** to predict whether a tumor is malignant or benign based on the Breast Cancer Wisconsin dataset.

---

## 📂 Dataset
- **Name**: Breast Cancer Wisconsin (Diagnostic) Data Set  
- **Source**: [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Target Column**: `diagnosis` (M = Malignant, B = Benign)
- **Classes**: Binary (1 = Malignant, 0 = Benign)

---

## 🔧 Tools & Libraries Used
- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🚀 Steps Performed

1. **Data Loading & Exploration**  
   - Loaded dataset using `pandas`
   - Explored data structure, missing values, and class distribution

2. **Data Preprocessing**  
   - Dropped unnecessary columns (`id`, `Unnamed: 32`)
   - Converted target `diagnosis` to binary (M → 1, B → 0)
   - Split into training and test sets
   - Standardized features using `StandardScaler`

3. **Model Training**  
   - Trained a Logistic Regression model using Scikit-learn

4. **Model Evaluation**  
   - Evaluated model using:
     - Confusion Matrix
     - Precision, Recall, F1-score
     - ROC Curve and AUC Score

5. **Sigmoid Function & Threshold Tuning**  
   - Explained and plotted sigmoid curve
   - Modified classification threshold and analyzed the effect

---

## 📈 Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **ROC-AUC Score**

---

## 📊 Visualizations

- Countplot of class distribution
- Confusion Matrix heatmap
- ROC Curve
- Sigmoid Function plot

---

## 🧠 Key Learnings

- Fundamentals of **binary classification**
- Working of **logistic regression** and **sigmoid function**
- Importance of **threshold tuning**
- Using **evaluation metrics** to assess model performance

---

## 🙋‍♂️ Author

- **Name**: Tharuneshvar 
- **Email**: tharuneshvar24@gmail.com

> _(Replace with your actual name and email before submitting)_

---

## 📝 How to Run

1. Open the provided Jupyter Notebook / Colab notebook.
2. Upload the `data.csv` file from the Breast Cancer dataset.
3. Run each cell step-by-step to see the full analysis and results.

---

## 📎 Note
This project is a part of Task 4 from the AI & ML Internship under the guidance of Elevate Labs, Ministry of MSME, Govt. of India.
