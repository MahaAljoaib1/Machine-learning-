# Assignment 6 – ARTI 308  
## Decision Tree & Random Forest

This assignment focuses on building and evaluating classification models using a loan dataset (`loan_data.csv`).

---

## Objectives

- Explore and understand the dataset  
- Convert categorical data using encoding (dummy variables)  
- Split data into training and testing sets  
- Train a Decision Tree model  
- Train a Random Forest model  
- Evaluate models using classification report and confusion matrix  
- Compare performance between models  

---

## Models Used

- Decision Tree Classifier  
- Random Forest Classifier  

---

## Key Observations

- The dataset is imbalanced (more class 0 than class 1)  
- Both models perform well on class 0  
- Both models struggle with class 1 (low recall due to class imbalance)  
- Random Forest accuracy ≈ 85% vs Decision Tree ≈ 73%  
- Random Forest performs better overall than Decision Tree  

---

## Tools Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## Files Included

- `Assignment6_DecisionTree_RandomForest.ipynb`  
- `loan_data.csv`  
