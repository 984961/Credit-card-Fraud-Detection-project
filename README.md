📊 Project Overview

Perform exploratory data analysis (EDA) on credit card transaction data.

Handle imbalanced dataset issues.

Explore key features that help in fraud detection.

Visualize patterns of fraudulent vs non-fraudulent transactions.

🛠 Technologies Used

Python

Pandas – data manipulation

NumPy – numerical computations

Matplotlib & Seaborn – data visualization

Scikit-learn – preprocessing, sampling techniques (SMOTE, Random Under-Sampling)

🚀 Features

Load and preprocess the credit card dataset.

Handle class imbalance using resampling techniques.

Generate statistical summaries for fraud vs non-fraud transactions.

Create visualizations:

Distribution of transaction amounts

Class imbalance plot

Feature correlations

Time vs fraud patterns

Identify which features contribute most to fraud detection.

📷 Sample Visualizations

Histogram of transaction amounts (fraud vs normal)

Heatmap of feature correlations

Pie chart of fraud vs non-fraud transactions

Boxplot of important features

Time-based transaction trends

✅ Results

Fraudulent transactions are very rare (<1%), making detection challenging.

Fraud transactions typically involve smaller transaction amounts compared to non-fraud.

Certain features show strong separation between fraud and normal cases.

Resampling techniques (like SMOTE) are crucial for balancing data before applying ML models.

📌 Future Work

Apply machine learning algorithms (Logistic Regression, Random Forest, XGBoost).

Compare models with ROC-AUC, Precision-Recall, and F1-score.

Build a real-time fraud detection system.

Deploy using Streamlit / Flask for interactive use.

🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.
