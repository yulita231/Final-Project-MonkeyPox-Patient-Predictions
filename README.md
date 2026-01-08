# 🦠 Mpox Early Detection & Risk Factor Identification

### 🏆 Context
Final Project for **ITS Hackathon [2025]**.
* Status: Participant*
![Bukti Sertifikat](sertifikat_its.png)

## 📌 Problem Statement
The spread of **Mpox (Monkeypox)** requires fast and accurate screening tools. However, early symptoms are often confused with other diseases, leading to delayed diagnosis and higher transmission rates.

## 🎯 Solution
We developed a Machine Learning model to:
1.  **Predict** the probability of a patient being positive for Mpox.
2.  **Identify** the most critical symptoms (Feature Importance) that distinguish Mpox from other conditions.

## 🛠 Tech Stack
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn 
* **Algorithms Compared:** Logistic Regression, Decision Tree, Random Forest, SVM
* **Champion Model:** Gradient Boosting Classifier (Selected for best performance).
* **Visualization:** Matplotlib, Seaborn

## 📊 Key Findings (Risk Factors)
Based on our model analysis, the top 3 strongest indicators of Mpox are:
1.  **HIV infection**
2.  **Rectal Pain** 
3.  **penile Oedema**.
*(Sesuaikan dengan temuan datamu ya!)*

## 📊 Model Performance Evaluation
We trained 5 different algorithms (Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, SVM).

**Champion Model: Gradient Boosting Classifier** 🏆
This model achieved the best balance between Accuracy and Recall, which is critical for disease screening.

* **Accuracy:** **65.92%** (Highest among all models)
* **Recall (Positive Case):** **0.71**
    * *Why this matters:* A high recall score (0.71) means the model is effective at catching positive Mpox cases, minimizing the risk of undiagnosed patients spreading the virus.
* **Precision (Positive Case):** **0.74**

**Comparison:**
* Gradient Boosting outperformed Decision Trees (+4.4%) and Random Forest (+3.1%) in accuracy, proving its capability to handle complex medical data patterns better than standard tree-based models.

## 🚀 How to Run
1. Clone this repository.
2. Install requirements: `pip install -r requirements.txt`
3. Run the notebook/app.

**Experimental Conclusion:** Based on a comparative evaluation of five machine learning algorithms, the Gradient Boosting Classifier was determined to be the best model for this monkeypox early detection project.

This model excelled with an accuracy of **65.92%** and, more importantly, recorded the highest recall score of 0.71 in the positive class. 
The high recall value indicates that this model has the best sensitivity in detecting infected patients, thus minimizing the risk of false negatives (undetected positive patients), which are very dangerous in the context of a spreading outbreak.

**Recommended Use:** This model is recommended as a first-layer screening tool to prioritize high-risk patients for immediate medical examination.
