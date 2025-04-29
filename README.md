# Elevate-Labs-Task-4
# 🧠 Breast Cancer Classification with Logistic Regression

## 📌 Objective
Build a binary classifier using **Logistic Regression** to detect whether a tumor is **malignant** or **benign**, using the **Breast Cancer Wisconsin Dataset**.

---

## 📊 Dataset Summary
- **Source**: Breast Cancer Wisconsin Diagnostic Dataset
- **Target Column**: `diagnosis`  
  - M (Malignant) → `1`  
  - B (Benign) → `0`

---

## ⚙️ Tasks Performed

### 1. Data Preprocessing
- Dropped irrelevant columns: `id`, `Unnamed: 32`
- Converted categorical diagnosis labels (`M`, `B`) into numerical values (`1`, `0`)
- Standardized features using `StandardScaler`

### 2. Model Building
- Split data into train/test (80/20)
- Trained Logistic Regression using `sklearn.linear_model.LogisticRegression`

### 3. Model Evaluation
- **Confusion Matrix**
- **Precision, Recall, F1-score**
- **ROC-AUC Score & ROC Curve**
- Compared results with different probability thresholds (e.g., 0.3)

### 4. Threshold Tuning
- Explored performance when changing classification threshold
- Demonstrated effect of probability cut-off on predictions

### 5. Sigmoid Function
- Explained how logistic regression converts raw outputs into probabilities:
  \[
  \text{sigmoid}(z) = \frac{1}{1 + e^{-z}}
  \]

---

## 🛠️ Tools Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 📈 How to Run
1. Install requirements:  
   `pip install pandas numpy matplotlib scikit-learn`
2. Run the Jupyter Notebook:  
   `Task4_Logistic_Regression.ipynb`
3. Update the dataset path if needed:  
   `"E:\\Elevate labs internship\\data.csv"`

---

## 📚 Outcome
Achieved strong performance using logistic regression. ROC-AUC score and classification metrics show good predictive ability for binary classification.

---

> 🔍 **Note**: Logistic Regression is effective for interpretable, fast binary classification problems like medical diagnosis.
