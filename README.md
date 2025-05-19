# Credit-Card-Fraud-Detection
In an era where digital transactions are the norm, detecting fraudulent activity swiftly and accurately is critical. In this project, I tackled the challenge of identifying fraudulent credit card transactions using machine learning, where the stakes are high and the data is imbalanced.

Understanding the Problem
The dataset provided consisted of anonymized credit card transactions made by European cardholders. It was highly imbalanced — with fraudulent transactions making up only a tiny fraction of all entries. Recognizing the challenge, I began by thoroughly exploring and understanding the data.

Exploratory Data Analysis (EDA)
To uncover hidden patterns and anomalies, I conducted detailed EDA. I examined the distribution of each feature, studied correlations, and highlighted the severe class imbalance. Visualizations helped in understanding how fraudulent and non-fraudulent transactions differed subtly.

Data Preprocessing
Given the class imbalance, I applied Random UnderSampling to balance the dataset. I scaled features using StandardScaler to normalize them — a crucial step for algorithms sensitive to feature magnitude.

Model Building
I trained multiple classification models, including:

Logistic Regression

K-Nearest Neighbors

Decision Tree

Random Forest

XGBoost

Each model was evaluated using precision, recall, F1-score, and confusion matrices, with particular focus on recall, as missing a fraudulent transaction is more costly than flagging a legitimate one.

Performance Evaluation
Among the models, XGBoost and Random Forest stood out, showing strong performance in identifying fraudulent transactions with minimal false negatives. I visualized ROC curves and feature importance to further interpret the models.

Conclusion
Through this project, I built a robust pipeline to detect credit card fraud, balancing precision and recall in a highly skewed dataset. This solution provides a foundation for real-world implementation where fraud detection systems must act swiftly and accurately.

