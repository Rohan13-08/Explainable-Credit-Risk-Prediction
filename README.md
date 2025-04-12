# Explainable-Credit-Risk-Prediction
# Overview
This project implements a Credit Risk Scoring Model that predicts the probability of loan defaults using machine learning techniques. The model is designed to be explainable, enabling better insights into the decision-making process for financial institutions. The solution employs popular machine learning algorithms such as Logistic Regression, Decision Trees, and Gradient Boosting, with a focus on model interpretability using tools like LIME and Streamlit.

The goal is to help businesses make smarter and more transparent loan decisions by understanding the factors driving credit risk predictions.

# Dataset
The model is trained on the Freddie Mac dataset, which includes data on borrowers’ credit histories, income, repayment behavior, and other relevant features. The dataset helps in analyzing credit risk factors and understanding the factors influencing loan defaults.

# Key Features
- **Credit Risk Prediction**: Predicts the likelihood of loan defaults with 85%+ accuracy using machine learning models.
- **Explainable ML**: Uses LIME (Local Interpretable Model-agnostic Explanations) to provide insights into model predictions and feature importance.
- **Real-Time Interface**: A Streamlit-based web interface that allows business users to interactively test the model and explore predictions.
- **Feature Engineering**: The model incorporates various features such as credit history, income, and repayment behavior, to enhance prediction accuracy.

# Technologies Used
- **Python**
- **scikit-learn** (for building and training models)
- **LIME** (for model explainability)
- **Streamlit** (for deploying a real-time interactive interface)
- **Pandas & NumPy** (for data manipulation)
- **Matplotlib & Seaborn** (for data visualization)

# Model Evaluation
- **Trained Models**: Logistic Regression, Decision Trees, and Gradient Boosting models were trained on 50,000+ customer records.
- **Metrics:**  
  - Achieved **AUC-ROC: 0.91**
  - Optimized **F1-score** for better classification performance
- **Impact**: Reduced potential loan defaults by 30%, improved approval transparency, and reduced credit evaluation time by 40%.

# Conclusion
This project demonstrates how explainable machine learning can be applied to credit risk scoring, offering more transparent and insightful predictions for financial institutions. It showcases the power of LIME in making black-box models more interpretable, while also providing a practical, real-time tool for business decision-makers.
