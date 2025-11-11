Machine Learning for Cyberattack Prediction on Social Media


This project leverages machine learning to detect malicious activities on social media platforms using behavioral and contextual data. It aims to support businesses in reducing cybersecurity risks, preventing fraudulent ads, and safeguarding brand reputation.
The system analyzes user interactions, device details, authentication methods, and domain reputations to classify activities as benign or malicious.

👥 Authors

Group 8 — 
Prakshi Agrawal B2025034
Radhika Agrawal B2025038
Ishita Vyas B2025023

🎯 Objectives

Build an ML model to classify social media interactions as malicious or safe.
Improve cybersecurity decision-making for businesses.
Ensure reproducibility, transparency, and technical rigor following IEEE guidelines.

🧠 Key Insights

Dataset: 5,000 simulated user interactions from Kaggle.

Models Implemented:
Logistic Regression
Random Forest
XGBoost
Best Model: Random Forest
Accuracy: 93.7%
Recall: 0.9455

📊 Files in This Repository

crime through social media.csv	Cleaned dataset (5,000 interactions).
eda.ipynb	Exploratory Data Analysis (EDA) and visualization of dataset features.
Final_EDA.ipynb	Final version of EDA with preprocessing steps.
final model.ipynb	Model building, training, and evaluation notebook.
main.ipynb	Integrated final pipeline including validation protocol, metrics, and results.

⚙️ Methodology

Data Preprocessing:

Handled missing and imbalanced data.

Encoded categorical variables and normalized numeric ones.

Model Training:

Used stratified 80/20 train-test split (seed = 42).

Tuned hyperparameters with 5-fold cross-validation.

Evaluation Metrics:

Accuracy, Precision, Recall, F1-Score, ROC-AUC.

Confusion Matrix analysis for true/false positives & negatives.

🧩 Business Impact

Identifies suspicious social media interactions in real-time.

Helps marketing and security teams flag fraudulent ads and phishing links.

Reduces reputational damage and financial loss.

🚀 How to Reproduce

Clone this repository:

git clone https://github.com/PRAKSHI18/Machine-Learning-for-Cyberattack-Prediction-on-Social-Media.git


🏫 Acknowledgment

Special thanks to Prof. Suman Sanyal for guidance and feedback.
We also acknowledge Goa Institute of Management for resources and academic support.
