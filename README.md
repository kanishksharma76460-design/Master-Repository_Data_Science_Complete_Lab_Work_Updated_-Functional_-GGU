# Master-Repository_Data_Science_Complete_Lab_Work_Updated_-Functional_-GGU
This repository contains all the source codes and readme file, with enhanced version of 6 lab works along with the 3 publication-ready projects.


# 📚 Master README – Data Science & Machine Learning Portfolio
**Author:** Kanishk Sharma  
**Batch:** Fall "A"  

---

## 🎯 Overview
This portfolio consolidates multiple labs and fun projects completed in Google Colab. Each project demonstrates a progression from **Python fundamentals** to **data analysis, visualization, machine learning models, and advanced applications** like recommendation systems and trackers.  

The README provides:
- **Objective & Dataset context**
- **Steps performed with code explanations**
- **Results & insights**
- **Reasoning behind choices**
- **Accountability for methods and outcomes**

---

## 📂 Projects

### 1. Lab 1 – Confusion Matrix & Regression Metrics

**Objective:** Implement evaluation metrics for classification and regression using Python. 

**Dataset:** Synthetic values (TP, FP, TN, FN, SSR, SSE).  

**Steps:**

- Calculated Accuracy, Precision, Recall, F1 Score with formulas.  
- Visualized metrics via bar chart.  
- Computed R², MSE, Cook’s Distance, and Linear Regression prediction.
-  
**Results:**
  
- Accuracy: 0.82, Precision: 0.86, Recall: 0.83, F1 Score: 0.84.  
- R² = 0.70 → model explains 70% variance.
- 
**Reasoning:** Metrics chosen to cover both classification and regression evaluation.
  
**Accountability:** Clear formulas ensure reproducibility.  

---

### 2. Lab 2 – Facebook Data Analysis

**Objective:** Compare CSV vs Excel formats, analyze Facebook dataset.  

**Dataset:** Facebook Friends data (715 rows).  

**Steps:**

- Loaded CSV and Excel, compared structure.  
- Examined columns, missing values, datatypes.  
- Generated descriptive statistics (mean, std, quartiles).  
- Visualized histograms for numeric columns.  
**Results:**
  
- Excel preserved formatting better; both contained consistent data.  
- Mean age ~24, photos highly skewed (max ~12k).  
**Reasoning:** Demonstrated importance of data source format.  
**Accountability:** Documented differences in headers and metadata.  

---

### 3. Lab 3 – NumPy & Visualization

**Objective:** Practice NumPy arrays and plotting.  

**Dataset:** Synthetic random data.  

**Steps:**

- Created arrays, reshaped, indexed.  
- Plotted histograms, sine/cosine, scatter plots.  
- Compared linear, power, exponential, logarithmic functions.  
**Results:**
  
- Histogram showed normal distribution.  
- Function plots highlighted growth differences.
- 
**Reasoning:** Built mathematical intuition for ML preprocessing.
  
**Accountability:** Code snippets reproducible in Colab.  

---

### 4. Lab 4 – German Credit Dataset

**Objective:** Predict credit response using Random Forest.  
**Dataset:** German Credit dataset (1000 rows, 23 columns).  

**Steps:**

- Cleaned missing values with mean imputation.  
- Dropped identifier columns.  
- Split train/test, trained Random Forest.
- 
**Results:**
  
- Accuracy printed in code output.  
- Classification report generated.
- 
**Reasoning:** Random Forest chosen for robustness with mixed features.
  
**Accountability:** Documented imputation strategy.  


### 5. Lab 5 – Student Performance Analysis

**Objective:** Analyze student grades and predict pass/fail.  

**Dataset:** Student Performance dataset (395 rows, 33 columns).  

**Steps:**

- EDA: histograms, boxplots, scatterplots, heatmap.  
- Feature engineering: pass/fail variable.  
- Models: Logistic Regression, Random Forest.
- 
**Results:**
  
- Logistic Regression Accuracy: ~0.95.
- 
- Random Forest Accuracy: ~0.91.
- 
**Insights:** Study time and absences strongly correlated with grades.
  
**Reasoning:** Logistic Regression chosen for interpretability. 

**Accountability:** Confusion matrix validated predictions.  

---

### 6. Lab 6 – Titanic Survival Prediction

**Objective:** Compare ML models on Titanic dataset.

**Dataset:** Titanic train/test sets.  

**Steps:**

- Cleaned missing values, encoded categorical features.  
- Scaled numerical features.  
- Models: Logistic Regression, Decision Tree, KNN.
- 
**Results:**
  
- Logistic Regression: ~0.53, Decision Tree: ~0.54, KNN: ~0.47.
-  
- Visualized accuracies with bar and line charts.
- 
**Insights:** Decision Tree slightly outperformed others.
    
**Reasoning:** Multiple models compared to highlight trade-offs.
  
**Accountability:** Explained KeyError when dropping non-existent “Cabin”.  


### 7. PCA Classification Activity

**Objective:** Apply PCA to Wine dataset and compare accuracy.  

**Dataset:** Wine dataset (scikit-learn).  

**Steps:**

- Standardized features.  
- Trained KNN before and after PCA.  
- Compared accuracy and explained variance.
  
**Results:**
  
- Accuracy before PCA: 0.96.  
- Accuracy after PCA: 0.98.  
- Explained variance ratio: [0.36, 0.18].
- 
**Insights:** PCA preserved most variance while reducing dimensionality.
    
**Reasoning:** PCA chosen to demonstrate dimensionality reduction.
  
**Accountability:** Balanced discussion of accuracy vs variance.  


### 8. Dynamic Titanic Survival Lab

**Objective:** Advanced Titanic survival prediction with multiple models.

**Dataset:** Titanic train/test CSVs.  

**Steps:**

- Cleaned, encoded, scaled features.  
- Models: KNN, Logistic Regression, Decision Tree.  
- Evaluated with accuracy, classification report, confusion matrix.  
- Visualized coefficients and feature importance.
-  
**Results:**
  
- Comparative accuracy table generated.  
- Feature importance highlighted Age, Fare, Embarked.
- 
**Insights:** Logistic Regression coefficients provided interpretability; Decision Tree showed feature hierarchy.
   
**Reasoning:** Multiple models ensure robustness.  

**Accountability:** Alignment of train/test columns documented.  



### 9. Fun Project – Guess Game ML

**Objective:** Apply ML models to synthetic Guess Game dataset.  

**Dataset:** Synthetic guesses (1–100).  

**Steps:**
- Generated dataset with outcomes (too low, too high, correct).  
- Trained Logistic Regression, Decision Tree, KNN.  
- Compared accuracies with bar chart.
-  
**Results:**  
- Logistic Regression: 0.995, Decision Tree: 1.0, KNN: 0.995.
- 
**Insights:** Decision Tree achieved perfect accuracy.
  
**Reasoning:** Demonstrated ML in playful context.  

**Accountability:** Synthetic dataset documented.  



### 10. Fun Project – To-Do List Tracker
**Objective:** Build CLI-based task tracker.  
**Dataset:** Tasks stored in text file.  
**Steps:**
- Functions for add, remove, mark complete, save/load.  
- Menu-driven interface.
-  
**Results:**  
- Tasks persisted across sessions.
- 
**Insights:** Demonstrated file I/O and state management.
  
**Reasoning:** CLI chosen for simplicity.  

**Accountability:** Error handling for malformed lines.  



### 11. Fun Project – Expense Tracker
**Objective:** Build CLI-based expense tracker.  
**Dataset:** Expenses stored in text file. 

**Steps:**
- Functions for add, delete, category analysis, save/load.  
- Menu-driven interface.
- 
**Results:**  
- Expenses categorized and summarized.  
**Insights:** Category analysis highlighted spending patterns.  
**Reasoning:** CLI chosen for portability.  
**Accountability:** Input validation for amounts.  



##  Final Conclusion
This portfolio demonstrates:
- **Progression from fundamentals to advanced ML.**
- **Strong coding accountability** with documented errors and fixes.  
- **Insights and reasoning** for every project.  
- **Professional polish** with reproducible workflows.  

**Kanishk Sharma (Fall "A" batch)** has showcased mastery in **Python, NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn**, and applied them across diverse datasets and problem statements.  



