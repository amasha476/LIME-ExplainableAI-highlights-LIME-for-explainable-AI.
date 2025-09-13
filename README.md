# Explainable AI with LIME: Regression, Binary, and Multi-Class Classification

## Project Overview
This project demonstrates the application of **explainable AI (XAI)** techniques using **LIME (Local Interpretable Model-agnostic Explanations)** to generate explanations for model predictions across three different types of machine learning tasks:

1. **Regression** – Predicting continuous outcomes.
2. **Binary Classification** – Predicting two-class outcomes.
3. **Multi-Class Classification** – Predicting multiple class outcomes.

The project uses **three different datasets** to showcase how LIME can provide local, interpretable explanations for predictions made by models in diverse scenarios.

---

## Techniques and Tools
- **Programming Language:** Python
- **Machine Learning Models:** 
  - XGBoost (for regression)
  - Random Forest, XGBoost (for classification)
- **Explainability Library:** LIME (Local Interpretable Model-agnostic Explanations)
- **Data Processing Libraries:** Pandas, NumPy, Scikit-learn
- **Visualization:** Matplotlib, Seaborn

---

## Methodology / Steps
1. **Data Preparation**
   - Load and explore datasets.
   - Handle missing values, encoding categorical variables, and scaling features as necessary.

2. **Model Training**
   - Train models appropriate for each task:
     - Regression model for continuous outcomes.
     - Binary classification model for two-class predictions.
     - Multi-class classification model for multiple-class predictions.

3. **Prediction and Evaluation**
   - Evaluate model performance using metrics such as:
     - Regression: RMSE, MSE
     - Binary Classification: Accuracy, F1-Score, ROC-AUC
     - Multi-Class Classification: Accuracy, Confusion Matrix, F1-Score

4. **Explainable AI with LIME**
   - Apply **LIME** to generate local explanations for individual predictions.
   - Visualize feature contributions to understand how each feature impacts predictions.
   - Compare explanations across different datasets and tasks to identify key influencing features.

5. **Visualization**
   - Plot LIME explanations to make model decisions interpretable.
   - Highlight top features contributing to each prediction.

---

## Findings
- LIME effectively highlights the **most influential features** for predictions across all three tasks.
- Provides **interpretable insights** even for complex models like Random Forest and XGBoost.
- Reveals task-specific differences in feature importance:
  - Regression: Continuous features dominate.
  - Binary Classification: Certain categorical features strongly drive decisions.
  - Multi-Class Classification: Feature contributions vary across classes.

Some of the explanations are shown below.

Multi-Class Classification

<img width="932" height="747" alt="image" src="https://github.com/user-attachments/assets/31a0e9f6-a19d-48c6-a796-4164dc8599a6" />

Binary Classification

<img width="962" height="525" alt="image" src="https://github.com/user-attachments/assets/c9a68486-5e36-42e4-b4bc-a293842c1fbd" />

Regression

<img width="965" height="582" alt="image" src="https://github.com/user-attachments/assets/83654a8a-9a62-4fe4-a8a0-3ebe7b233cf1" />



---

## Importance of LIME
- Offers **local interpretability**, helping understand why a model made a specific prediction.
- Helps detect **bias or unexpected behavior** in models.
- Facilitates **trust and transparency** in AI systems, making them more explainable to non-technical stakeholders.
- Useful in **regulatory or ethical contexts** where explanations of AI decisions are required.

---

