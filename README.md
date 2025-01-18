# Credit Card Fraud Detection

## Project Overview
Credit card fraud is a critical issue in financial systems, impacting security and trust. This project leverages machine learning techniques to develop a robust fraud detection system.

The project explores multiple algorithms, including:
- XGBoost
- LightGBM
- Random Forest
- Artificial Neural Networks (ANNs)

To handle the inherent class imbalance in fraud detection, we use **SMOTE** (Synthetic Minority Oversampling Technique).

## Key Features
- **Algorithms Evaluated:** XGBoost, CatBoost, LightGBM, Random Forest, ANN.
- **Metrics Used:** Accuracy, Precision, Recall, F1-Score, AUC-ROC.
- **Visualization Tools:** Heatmaps, Confusion Matrices, and Distribution Graphs.

## Dataset
The dataset is sourced from [Kaggle's Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud).

### Data Summary
- Total Transactions: 284,807
- Fraudulent Transactions: 492
- Features: Time, Amount, and PCA-transformed V1-V28.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/username/repo-name.git
   cd repo-name
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook ccfd.ipynb
   ```

## Results
The model comparison indicates the following:
- **Best Performing Model:** [Mention Model]
- **F1-Score:** [Value]
- **AUC-ROC:** [Value]

## File Structure
- `ccfd.ipynb`: Jupyter Notebook containing the source code.
- `Mini_Project_Report_22MP01_CreditCardFraudDetection.pdf`: Detailed project report.
- `README.md`: Overview and instructions.

## Future Work
- Real-time fraud detection system integration.
- Exploration of deep learning models for enhanced accuracy.

---

This repository represents the effort of leveraging modern machine learning techniques to address the growing challenge of credit card fraud detection. For any questions or contributions, feel free to raise an issue or submit a pull request.
