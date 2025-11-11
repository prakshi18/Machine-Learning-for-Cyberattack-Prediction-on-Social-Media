Machine Learning for Cyberattack Prediction on Social Media


This project leverages machine learning to detect malicious activities on social media platforms using behavioral and contextual data. It aims to support businesses in reducing cybersecurity risks, preventing fraudulent ads, and safeguarding brand reputation.

The system analyzes user interactions, device details, authentication methods, and domain reputations to classify activities as benign or malicious.

👥 Authors

Group 8 — Goa Institute of Management
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

ROC-AUC: 0.976

Recall: 0.9455

📊 Files in This Repository
File	Description
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

git clone https://github.com/<your-username>/MLBA_Cyberattack_Prediction.git
cd MLBA_Cyberattack_Prediction


Install dependencies:

pip install -r requirements.txt


Run the main script or notebooks:

jupyter notebook main.ipynb


or

python mlba_main.py --seed 42 --split 0.8

📈 Results Summary
Model	Accuracy	Precision	Recall	F1-Score	ROC-AUC
Random Forest	0.937	0.786	0.945	0.858	0.976
Logistic Regression	0.896	0.738	0.752	0.745	0.953
XGBoost	0.927	0.795	0.861	0.827	0.973
🧮 Future Work

Real-time streaming and drift monitoring.

Expanded dataset across multiple social media platforms.

Deployment using Flask or FastAPI.

Publishing a public GitHub repository with a make reproduce command.

🏫 Acknowledgment

Special thanks to Prof. Suman Sanyal for guidance and feedback.
We also acknowledge Goa Institute of Management for resources and academic support.
