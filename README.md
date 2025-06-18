# marketing-mix-modeling
Full marketing analytics project in R using OLS and LASSO regression with ad spend optimization.

# 📈 Marketing Mix Modeling: Optimizing Ad Spend for Sales Growth

An end-to-end marketing analytics project using R, OLS, and LASSO regression to explore how YouTube, Facebook, and Newspaper ad budgets impact sales — and simulate the best way to allocate ad spend.

---

## 📖 Overview

This project showcases a complete analytical pipeline for **Marketing Mix Modeling** using real-world data. We examine how advertising spend across YouTube, Facebook, and Newspapers affects product sales. The goal is to determine the most effective budget allocations using both traditional regression (OLS) and regularized models (LASSO), followed by data-driven budget optimization.

---

## 📊 Dataset Description

- **Name:** `marketing`
- **Source:** [`datarium` R package](https://cran.r-project.org/web/packages/datarium/index.html)
- **Type:** Simulated marketing data, often used for regression and causal modeling tutorials

### 🧾 Variables

| Variable         | Description                                 |
|------------------|---------------------------------------------|
| `youtube`        | YouTube advertising spend (in thousands $)  |
| `facebook`       | Facebook advertising spend (in thousands $) |
| `newspaper`      | Newspaper advertising spend (in thousands $)|
| `sales`          | Product sales (in thousands of units)       |

---

## 🎯 Project Objectives

- Explore relationships between ad spend and sales
- Log-transform and scale features for modeling
- Fit and evaluate OLS and LASSO models
- Compare model performance (R², RMSE)
- Simulate ad budget optimization with LASSO
- Deliver plots, tables, and insights for stakeholders

---

## 🧠 Methodology

1. **Data Cleaning & EDA** (zero checks, boxplots, pairplots)
2. **Feature Engineering** (log-transform, scaling, interaction terms)
3. **Modeling**:
   - OLS regression
   - LASSO regression with cross-validation
4. **Performance Evaluation**:
   - R² and RMSE on test set
   - Coefficient comparison (OLS vs LASSO)
5. **Budget Optimization**:
   - Simulated heatmaps
   - Optimal allocation under a fixed budget
6. **Output Delivery**:
   - Visuals, CSVs, and polished `.Rmd`

---

## 📂 Folder Structure


---

## 🖼️ Key Visuals

- 📊 Side-by-side coefficient plot (OLS vs LASSO)
- 🔥 Heatmap of predicted sales by spend level
- 🎯 Optimal spend allocation curve
- 🧪 Residuals and model diagnostics

---

## ▶️ How to Run

1. Clone the repository or download the folder  
2. Open `marketing_mix_modeling.Rmd` in **RStudio**
3. Run the document chunk-by-chunk to:
   - View plots and diagnostics
   - Save outputs to `/plots` and `/tables`
4. Review final visualizations in the `plots/` folder
5. Use `tables/` for summary metrics and reporting

---

## 📁 Outputs

- 📁 **Plots:** Exploratory graphs, diagnostics, coefficient visuals, budget optimization heatmaps
- 📁 **Tables:** Model performance comparisons, OLS/LASSO coefficients, simulation results

---

## 👤 Author

**Victor King**  
M.S. in Sport Analytics, Syracuse University (2025)  
🔗 [LinkedIn](https://linkedin.com/in/victormking)  
💻 [GitHub](https://github.com/victormking)  
📝 [Portfolio](https://victormking.github.io/portfolio-site)  

---

