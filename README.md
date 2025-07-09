---

# 📊 Advanced Data Science Analysis: Multicollinearity, Bivariate & Inferential Insights

This project provides practical, well-documented solutions to common yet advanced data science challenges. The focus is on diagnosing and solving multicollinearity, performing bivariate analysis, and conducting inferential statistical tests using Python.

---

## 📁 Repository Contents

### 1. [`Advanced Solutions For Multicollinearity.ipynb`](./Advanced%20Solutions%20For%20MultiColinearity.ipynb)

Tackles the issue of **multicollinearity** in regression modeling using:

* 📉 **Principal Component Analysis (PCA)**
* 🧩 **Ridge & Elastic Net Regression**
* 📊 **Partial Least Squares Regression (PLSR)**
* 🧠 **Feature Aggregation** for academic score variables

> Includes VIF calculation, interpretation, and comparison of multiple techniques.

---

### 2. [`Data_Science_Bivariate_Analysis.ipynb`](./Data_Science_Bivariate_Analysis.ipynb)

Explores **bivariate relationships** in a dataset using:

* 📈 **Covariance and Pearson Correlation**
* 🧮 **Variance Inflation Factor (VIF)**
* 🖼️ **Seaborn visualizations (Pairplot)**
* 🎯 Identification of weak and strong linear relationships between key predictors like `degree_p`, `etest_p`, `mba_p`, and target `salary`

---

### 3. [`Data_Science_Inferential Analysis_Question_Ans.ipynb`](./Data_Science_Inferential%20Analysis_Question_Ans.ipynb)

Solves a set of real-world inferential questions including:

* 🔍 **Hypothesis Testing (ANOVA, t-tests)** at 5% significance level
* 📊 **PDF calculations** for salary ranges
* 🧠 **Standardization (Z-scores)** of normal distribution
* 🧼 **Data Cleaning (NaN handling)** with justification for imputation
* 🔗 Investigation of factors affecting placement and salary

Each question is answered with:

* Code ✅
* Explanation 📘
* Statistical Justification 📏

---

## 🧰 Technologies Used

* **Python** (Pandas, NumPy, SciPy, Scikit-learn, Seaborn, Statsmodels)
* **Jupyter Notebooks** for code + documentation integration
* **Statistical Concepts**: Multicollinearity, Hypothesis Testing, Z-Scores, PDF
* **Visualization**: Pairplots, Correlation Heatmaps

---

## 📦 Dataset

* `PrePlacement.csv` and `Placement_Data_Full_Class.csv`
* Contains academic scores (`ssc_p`, `hsc_p`, `mba_p`), test results (`etest_p`), specialization, and placement details.

> Datasets are either uploaded locally or can be downloaded [here](https://drive.google.com/file/d/1hiR9XbTjMsNk_uA025w5nrw5LTBUDCEC/view?usp=sharing)

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/DataScience-MultiCollinearity-Inferential-Analysis.git
cd DataScience-MultiCollinearity-Inferential-Analysis
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Launch Jupyter Lab:

```bash
jupyter lab
```

---

## 🧠 Key Learnings

* How to **diagnose and fix multicollinearity** using statistical and ML techniques
* Differentiating **correlation vs. causation** in bivariate analysis
* Applying **real-world hypothesis testing** with business interpretation
* Handling **missing data responsibly**, especially in salary data
* Leveraging **visual analytics** to enhance interpretability

---



---

## 📄 License

This project is under the [MIT License](LICENSE).

---
