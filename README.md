<h1 align="center">
<u>Breast Cancer Model Comparison</u>
</h1>

---

# 📌 Problem Statement

- Breast cancer is one of the most common cancers worldwide.
- Early detection is crucial for improving treatment outcomes and survival rates.
- Manual diagnosis can be challenging and time-consuming.
- Machine learning techniques can assist in accurately classifying tumors.
- This project aims to classify breast tumors as *Benign* or *Malignant*.
- Multiple classification algorithms are compared to identify the best-performing model.

---

# 📂 Dataset Description

### Dataset Name
Breast Cancer Wisconsin Diagnostic Dataset

### Dataset Characteristics

- Total Instances: *569*
- Total Features: *30*
- Classes: *2*
  - Malignant (Cancerous)
  - Benign (Non-Cancerous)
- Type: *Binary Classification*

### Dataset Source

https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic)

### Target Variable

| Value | Diagnosis |
|---------|------------|
| 0 | Malignant |
| 1 | Benign |

---

# 🔗 GitHub Repository Link

Add your repository link here.

Example:
https://github.com/ranijoy3-alt/Breast-Cancer-Model-Comparison


---

# 🤖 Models Used

The following Machine Learning classification models were implemented:

1. Logistic Regression
2. Decision Tree Classifier
3. K-Nearest Neighbors (KNN)
4. Gaussian Naive Bayes
5. Support Vector Machine (SVM)

---

# 📊 Model Comparison Table


<img width="1239" height="204" alt="image" src="https://github.com/user-attachments/assets/455a5f4c-7ac6-4b33-9f63-7e6dff07d101" />


---

# 📝 Model Performance Observations

| ML Model | Observation |
|-----------|-------------|
| Logistic Regression | Produced strong classification performance with high accuracy and precision. |
| Decision Tree | Easy to interpret but may overfit the dataset. |
| KNN | Performed well with good recall and classification capability. |
| Naive Bayes | Fast and efficient, providing competitive results. |
| Support Vector Machine | Achieved the best overall performance with high accuracy and AUC. |
| Overall Winner | Support Vector Machine (SVM) |

---
# 🏆 Results and Best Model Observation

## Best Metrics Achieved

- *Highest Accuracy:* Logistic Regression and SVM (0.9825)
- *Highest AUC:* Logistic Regression (0.9954)
- *Highest Precision:* Logistic Regression and SVM (0.9861)
- *Highest Recall:* Logistic Regression and SVM (0.9861)
- *Highest F1 Score:* Logistic Regression and SVM (0.9861)
- *Highest MCC Score:* Logistic Regression and SVM (0.9623)


Accuracy alone should not be used to select the best model.
Precision and Recall help evaluate classification trade-offs.
F1 Score provides a balance between Precision and Recall.
MCC is a robust metric for evaluating binary classification performance.
Based on the overall evaluation metrics, especially F1 Score and MCC, the best-performing models are [Logistic Regression and SVM]

# 📈 Evaluation Metrics

The following metrics were used to evaluate model performance:

- Accuracy
- AUC (Area Under Curve)
- Precision
- Recall
- F1 Score
- Matthews Correlation Coefficient (MCC)

---

# 🚀 Streamlit Application Features

✅ Dataset Upload Option (CSV)

✅ Model Selection Dropdown

✅ Evaluation Metrics Display

✅ Accuracy Comparison Chart

✅ Performance Metrics Visualization

✅ Best Model Identification

✅ Interactive Dashboard

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Streamlit

---

# 📁 Repository Structure

text
Breast-Cancer/
│
├── app.py
├── breast_cancer_dataset.csv
├── requirements.txt
├── README.md
└── Ml2.ipynb


---

# ▶️ Installation

Install the required packages:

bash
pip install -r requirements.txt


Run the Streamlit application:

bash
streamlit run app.py


---

# 🌐 Live Streamlit Application

Add your Streamlit URL here.
https://breast-cancer-model-comparison-vnwju89msgjvpnjwzzm3nz.streamlit.app/



---

# 🎯 Conclusion

This project applied Machine Learning to classify breast tumors as benign or malignant using the Breast Cancer Wisconsin Diagnostic Dataset. Five models (Logistic Regression, Decision Tree, K-Nearest Neighbors, Gaussian Naive Bayes and Support Vector Machine) were trained on the same data and compared using Accuracy, AUC, Precision, Recall, F1 Score and Matthews Correlation Coefficient (MCC). Logistic Regression and SVM gave the strongest results, both reaching an accuracy of 0.9825 and an MCC of 0.9623, with Logistic Regression slightly ahead on AUC (0.9954 against 0.9950). The Decision Tree was the weakest model (accuracy 0.9123, MCC 0.8174), while KNN and Naive Bayes performed well but below the top two. The Streamlit application lets users choose a model and view its evaluation metrics in an interactive dashboard. Overall, the results show that well-scaled classical models can classify tumors very reliably and can support early breast cancer diagnosis.
