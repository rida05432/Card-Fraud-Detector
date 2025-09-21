# 💳 Credit Card Fraud Detection

This project tackles **credit card fraud detection** using Machine Learning with **Scikit-Learn** and **Snap ML**.  
The dataset is highly imbalanced (~0.172% fraud), so the project focuses on handling class imbalance while maintaining high recall on fraudulent transactions.

---

## 🚀 Features
- Preprocessing and standardization of transaction data.  
- Handles **class imbalance** using resampling techniques.  
- Compares **Decision Tree** and **SVM** classifiers.  
- Benchmarks **Snap ML** vs. **Scikit-Learn** for performance and training speed.  
- Evaluates results with **ROC-AUC, Precision, Recall, and F1-score**.  

---

## 🛠 Tech Stack
- **Python**  
- **Jupyter Notebook**  
- **Pandas / NumPy** – data preprocessing  
- **Scikit-learn** – ML training & evaluation  
- **Snap ML** – accelerated ML on structured data  

---

## 📊 Results
- **Snap ML** delivers **faster training** compared to Scikit-Learn.  
- Achieved **strong ROC-AUC performance** while improving recall on the fraud class.  
- Reduced false negatives, which are critical in fraud detection.  

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/rida05432/credit-card-fraud-detector.git
   cd credit-card-fraud-detector
