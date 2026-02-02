# Sampling Assignment - Credit Card Fraud Dataset

## Objective
This assignment demonstrates the importance of sampling techniques in handling highly imbalanced datasets and evaluates how different sampling strategies affect machine learning model performance.

---

## Dataset
Credit Card Fraud Dataset (`Creditcard_data.csv`)

The dataset is highly imbalanced:
- Class 0 → Normal Transactions
- Class 1 → Fraud Transactions

---

## Sampling Techniques Used

1. **Random Oversampling**
2. **Random Undersampling**
3. **SMOTE (Synthetic Minority Oversampling Technique)**
4. **ADASYN**
5. **SMOTE + Tomek Links**

These techniques were selected from the imbalance handling strategies reference link provided in the assignment.

---

## Machine Learning Models Used

- **M1** Logistic Regression  
- **M2** Decision Tree  
- **M3** Random Forest  
- **M4** K-Nearest Neighbors  
- **M5** Support Vector Machine  

---

## Results

The accuracy of each model under different sampling techniques is stored in:

📌 `Accuracy_Table.csv`

---

## Conclusion

Each model performs differently depending on the sampling strategy.
The best sampling technique for each model is printed at the end of the notebook execution.

---

## How to Run

1. Install dependencies:

```bash
pip install -r requirements.txt
```
2. Run the notebook:

Sampling_Assignment.ipynb
