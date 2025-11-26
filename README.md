# Skin Disorder Classification Using Machine Learning

A comprehensive machine learning approach for diagnosing dermatological conditions using clinical features.

---

## Project Summary

This project presents a complete end-to-end machine learning pipeline designed to classify various dermatological conditions using structured clinical data.
It emphasizes not only model development, but also **robust data preprocessing**, **interpretability**, and **analytical documentation**, aligning with academic and professional standards.

---

## Dataset Description

* **Dataset Name:** Dermatology Dataset
* **Total Samples:** 366
* **Features:** 34 clinical attributes
* **Target:** 6 dermatology disease classes
* **Problem Type:** Multi-Class Classification

The dataset captures various clinical indicators used by dermatologists for diagnosis, making this a clinically relevant classification task.

---

## Data Preprocessing

The preprocessing pipeline includes:

* **Missing Value Imputation**

  * Numerical features → Median
  * Categorical features → Mode

* **Label Encoding** for categorical variables

* **Data Integrity Checks**

* **Train-Test Split** ensuring balanced evaluation

This prepares the dataset for reliable and reproducible analytics.

---

## Exploratory Data Analysis (EDA)

A structured EDA was performed to derive meaningful insights:

### 🔹 Class Distribution

Revealed slight imbalance across disease categories.

### 🔹 Feature Distribution

Histograms highlighted diverse data patterns, including skewed and uniform distributions.

### 🔹 Correlation Heatmap

Showed moderate correlations among certain attributes, with no severe multicollinearity.

### Key EDA Insights

* Dataset is suitable for both linear and non-linear algorithms.
* Some features have potential diagnostic significance due to their correlation patterns.
* Distribution differences suggest models like Random Forest and SVM will outperform linear approaches.

---

## Machine Learning Models

Four classification algorithms were implemented:

| Model                      | Category             | Observations                                            |
| -------------------------- | -------------------- | ------------------------------------------------------- |
| **Logistic Regression**    | Linear               | Baseline model; limited by non-linearity in data        |
| **K-Nearest Neighbors**    | Distance-based       | Performance sensitive to scaling and neighborhood size  |
| **Support Vector Machine** | Kernel-based         | Strong performance; handles complex decision boundaries |
| **Random Forest**          | Ensemble, Non-linear | ⭐ Best overall accuracy and stability                   |

---

## Model Evaluation

Models were compared using accuracy and additional evaluation metrics.
A consolidated comparison table helps identify the most effective classifier.

### Best Performing Model: **Random Forest**

Random Forest demonstrated superior performance due to its ability to:

* Model non-linear patterns
* Capture complex feature interactions
* Resist overfitting
* Handle high-dimensional data effectively

---

## Conclusion

This study successfully demonstrates how machine learning can be applied to dermatology using structured clinical datasets.
Through systematic preprocessing, EDA, model experimentation, and performance comparison, the Random Forest classifier emerged as the most reliable model.

The project showcases the importance of:

* Feature understanding
* Algorithm selection
* Model interpretability
* Analytical documentation

---

## Limitations

* Limited dataset size (366 samples) affects scalability
* Minor class imbalance may influence certain metrics
* Hyperparameter tuning was not extensively performed

---

## Future Enhancements

To increase robustness and real-world applicability:

* Apply **SMOTE** or class-weight adjustments to handle imbalance
* Conduct **GridSearchCV** for hyperparameter optimization
* Explore **XGBoost**, **LightGBM**, or **Neural Networks**
* Build an interactive **Streamlit/Flask web application** for prediction
* Incorporate **explainable AI** techniques (SHAP, LIME)
* Include dermatologists’ clinical interpretations for domain validation

---

## Reflection

This project reinforced the idea that impactful machine learning is not only about running algorithms, but also about:

* Understanding data behavior
* Communicating analytical findings
* Presenting results with clarity and professionalism

The structured approach taken here transforms the notebook from simple code execution into a comprehensive analytical report.

---

## Technologies & Tools

* **Python 3**
* **Pandas**, **NumPy**
* **Scikit-learn**
* **Matplotlib**, **Seaborn**
* **Jupyter Notebook / Google Colab**

---

## Contributors

* **Nandhakumar V**
* **Suvaathii E**
* **Rehana Sultana**
* **Swetha R**

---
