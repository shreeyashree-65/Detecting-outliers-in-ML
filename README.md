# Outlier Detection on Wine Quality Dataset

This project explores and compares multiple **outlier detection techniques** applied to the **Wine Quality Dataset** to identify anomalous data points that may affect model performance and data analysis.

---

## 📌 Project Objective

- Detect outliers using **statistical and machine learning methods**
- Compare traditional methods with unsupervised ML-based techniques
- Understand how different approaches behave on the same dataset

---

## 📊 Dataset

- **Dataset:** Wine Quality Dataset  
- **Features:** Physicochemical properties of wine (e.g., acidity, alcohol, sulphates)
- **Target (not used for detection):** Wine quality score

---

## 🛠️ Outlier Detection Methods Implemented

1. **Z-Score Method**
   - Identifies outliers based on standard deviation from the mean
   - Assumes approximately normal distribution

2. **IQR (Interquartile Range) Method**
   - Uses Q1 and Q3 to detect extreme values
   - Robust to skewed distributions

3. **Isolation Forest**
   - Tree-based unsupervised algorithm
   - Isolates anomalies instead of profiling normal data

4. **Local Outlier Factor (LOF)**
   - Density-based method
   - Detects points that have significantly lower density than neighbors

---

## ⚙️ Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn (for visualization)

---

## 📈 Key Learnings

- Different outlier detection methods flag **different data points**
- Statistical methods are simple but distribution-sensitive
- ML-based methods (Isolation Forest, LOF) capture **complex patterns**
- Outlier detection is highly context-dependent
