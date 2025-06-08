# 🧠 Breast Cancer Detection using Support Vector Machines (SVM)

This project applies Support Vector Machines (SVM) to the Breast Cancer Wisconsin dataset to classify tumors as benign or malignant. The project explores both linear and non-linear classification using Scikit-learn, and includes visualization, hyperparameter tuning, and performance evaluation.

---

## 📌 Task Objectives

- Use SVMs for linear and non-linear classification.
- Visualize decision boundaries using PCA-reduced 2D data.
- Tune SVM hyperparameters (`C`, `gamma`) using GridSearchCV.
- Evaluate model performance with accuracy, confusion matrix, and classification report.
- Analyze learning curve and support vectors.

---

## 🧰 Tools & Libraries

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Dataset

**Source:** [UCI ML Repository - Breast Cancer Wisconsin Dataset](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic))  
**File Used:** `breast-cancer.csv`  
**Features:** Mean, standard error, and worst-case values for 30 cell nuclei features.  
**Target:** `diagnosis` (M = Malignant, B = Benign)

---

## 🔍 Project Steps

1. **Data Preprocessing**
   - Dropped ID column
   - Label encoded target (`M=1`, `B=0`)
   - Standardized features

2. **Model Training**
   - Trained SVM with:
     - Linear kernel
     - RBF kernel

3. **Evaluation**
   - Accuracy comparison
   - Confusion matrices
   - Classification reports

4. **Visualization**
   - PCA-reduced 2D visualization
   - Decision boundaries
   - Support vectors

5. **Tuning**
   - Used `GridSearchCV` to tune `C` and `gamma`
   - Best Accuracy: ~97.89%

6. **Advanced**
   - Learning Curve plot to understand generalization

---

## 📊 Results

| Model       | Accuracy |
|-------------|----------|
| SVM Linear  | ~95.6%   |
| SVM RBF     | ~97.4%   |
| RBF (Tuned) | ~97.9%   |

---

## 📌 How to Run

1. Clone the repository or download the notebook:
   ```bash
   git clone https://github.com/your-username/svm-breast-cancer.git
