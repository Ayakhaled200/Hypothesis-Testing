# **Hypothesis Testing - Data Simulation & Evaluation**

## **Project Overview**
This project focuses on simulating datasets using **two different approaches** from the `supermarket.csv` dataset:
1. **Independent Feature Simulation** – Generating data without considering correlations.
2. **Correlation-Preserved Simulation** – Generating data while maintaining feature relationships.

The project evaluates the quality of generated datasets using statistical tests to determine the best approach.

---

## **Approaches Used**
- **Independent Simulation:**  
  - Each feature is simulated separately based on its individual distribution.
  - Ignores dependencies between features.

- **Correlation-Preserved Simulation:**  
  - Uses statistical techniques to retain correlations.
  - Ensures more realistic data generation.

---

## **Statistical Tests Conducted**
- **Friedman Test:** Evaluates ranking differences between models.
- **Permutation Test:** Measures actual differences in model errors.
- **Repeated Measures ANOVA:** Tests for statistical significance (assumptions violated).
- **Wilcoxon Signed-Rank Test:** Assesses differences between paired models.
- **Bootstrap Test:** Compares errors across different models.

**Conclusion:** The **Permutation Test** provides the most reliable results for non-normal data.

---

## **Project Files**
- 📄 **``Null and Alternative hypotheses.ipynb`** – Jupyter Notebook for data simulation.
- 📊 **`benchmark_results.xlsx`** – Dataset.
- 📝 **`Null and Alternative hypotheses.docx`** – Report on hypothesis testing.

---

## **Author**
Aya Khaled
