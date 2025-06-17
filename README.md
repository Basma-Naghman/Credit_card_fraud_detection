🕵️ Credit Card Fraud Detection
This project applies machine learning techniques to detect fraudulent credit card transactions using a publicly available dataset. The dataset is highly imbalanced, and the aim is to build a predictive model that can accurately identify fraud cases while minimizing false positives.

📁 Project Structure
Credit_card_fraud_detection.ipynb: The core notebook that includes data loading, preprocessing, model training, evaluation, and visualization.

📊 Dataset
Source: The dataset contains transactions made by European credit cardholders in September 2013.

Features:

28 anonymized principal components (V1–V28)

Time, Amount

Class: 1 for fraud, 0 for normal

Note: The dataset is highly imbalanced (fraud cases make up ~0.17%).

🛠️ Tools & Libraries
Python

Jupyter Notebook

pandas, numpy

matplotlib, seaborn

scikit-learn (Logistic Regression)

🔍 Workflow Summary
Data Preprocessing

Missing value check

Scaling features like Amount and Time

Handling imbalance using methods like under-sampling or SMOTE


Modeling

Logistic Regression


Evaluation using accuracy

Model Evaluation



📈 Results
The best performing model balances recall (to catch fraud cases) and precision (to avoid false alarms).

Metrics used: accuracy_score

⚠️ Challenges
Handling class imbalance

Avoiding overfitting on small fraud cases

Choosing the right threshold for classification

📌 Conclusion
Machine learning can significantly assist in detecting fraudulent transactions when paired with appropriate techniques to handle class imbalance and feature scaling. This project demonstrates a basic pipeline that can be adapted for real-world applications with further tuning and larger datasets.

