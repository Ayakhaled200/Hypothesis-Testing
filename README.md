# **Hypothesis Testing - Data Simulation & Evaluation**

## **Project Overview**
This project focuses on simulating datasets using **two different approaches** from the `benchmark_results.xlsx` dataset:
1. **Independent Feature Simulation** – Generating data without considering correlations.
2. **Correlation-Preserved Simulation** – Generating data while maintaining feature relationships.

The project evaluates the quality of generated datasets using statistical tests to determine the best approach.

---

## **Approaches Used**
### **1️⃣ Independent Simulation (Column-wise Distribution Generation)**
- Each feature is simulated separately based on its individual distribution.
- Ignores dependencies between features.
- Provides a **better match for individual distributions** but fails to capture feature relationships.

### **2️⃣ Correlation-Preserved Simulation (Copula-Based Generation)**
- Uses statistical techniques to retain correlations.
- Ensures **more realistic data generation** by preserving feature dependencies.

---

## **Statistical Tests Conducted**
- **Friedman Test:** Evaluates ranking differences between models.
- **Permutation Test:** Measures actual differences in model errors.
- **Repeated Measures ANOVA:** Tests for statistical significance (**assumptions violated**).
- **Wilcoxon Signed-Rank Test:** Assesses differences between paired models.
- **Bootstrap Test:** Compares errors across different models.

**Conclusion:**  
✔ The **Permutation Test** provides the most reliable results for non-normal data.  
✔ Independent generation fails to capture relationships, while correlation-preserved simulation **better reflects real-world data**.  

---

## **Project Files**
- 📊 **`benchmark_results.xlsx`** – Original dataset used for simulation and testing.  
- 📄 **`Null and Alternative hypotheses.ipynb`** – Jupyter Notebook for hypothesis testing and data analysis.  
- 📝 **`Null and Alternative hypotheses.docx`** – Report detailing hypothesis testing and findings.  

