# Customer Churn Analysis (EDA with Statistical Validation)

## 📌 Project Overview
This project analyzes customer churn using Exploratory Data Analysis (EDA) with **statistical hypothesis testing**. 
It goes beyond visual exploration to validate findings using Chi-square tests and t-tests.

## 🛠️ Tools Used
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- SciPy (statistical tests)
- Sklearn (PCA)

## 🔍 EDA Workflow
1. Data Cleaning & Exploration
2. Univariate Analysis (distributions)
3. Bivariate Analysis (numerical vs categorical vs target)
4. Multivariate Analysis (correlations)
5. Statistical Tests (Chi-square, T-test, ANOVA)
6. Insights & Recommendations

## 📊 Key Statistical Findings
- Chi-Squared Contingency Test:
    - Churn Depends Significantlly on Partner(p_Value: 3.97379757451591e-36)
    - Churn Depends Significantlly on Dependents(p_Value: 2.0196592017051303e-42)
    - Churn Depends Significantlly on MultipleLines(p_Value: 0.0035679273999811405)
    - Churn Depends Significantlly on InternetService(p_Value: 5.831198962237274e-159)
    - Churn Depends Significantlly on OnlineSecurity(p_Value: 1.4006867477839222e-184)
    - Churn Depends Significantlly on OnlineBackup(p_Value: 7.776099238804965e-131)
    - Churn Depends Significantlly on DeviceProtection(p_Value: 1.9593887862403176e-121)
    - Churn Depends Significantlly on TechSupport(p_Value: 7.407807748843711e-180)
    - Churn Depends Significantlly on StreamingTV(p_Value: 1.324641113169159e-81)
    - Churn Depends Significantlly on StreamingMovies(p_Value: 5.353560421401324e-82)
    - Churn Depends Significantlly on Contract(p_Value: 7.326182186265472e-257)
    - Churn Depends Significantlly on PaperlessBilling(p_Value: 8.236203353962564e-58)
    - Churn Depends Significantlly on PaymentMethod(p_Value: 1.4263098511063342e-139) 

- T Test:
    - Significant difference in tenure between Churned and Non-Churned Users (p Value: 9.437650217574845e-207).
    - Significant difference in MonthlyCharges between Churned and Non-Churned Users (p Value: 6.760843117980302e-60).
    - Significant difference in TotalCharges between Churned and Non-Churned Users (p Value: 4.876865689694505e-64).

## ✅ Business Recommendations
- I noticed customers in the middle range of tenure seem to leave more. Maybe the company can try some offers or rewards for people around 6–24 months so they don’t drop out.
- Most people are on month-to-month contracts, and churn is higher there. If the company gives some small discounts or benefits for yearly contracts, it might keep customers longer.
- Customers with higher monthly charges seem to churn more. Maybe giving them better value or flexible plans could help.
- Add-on services like Online Security, Backup, and Tech Support are linked with lower churn. It might be good to promote these together as bundles.
- Many new customers leave quickly (low tenure). So better onboarding, like welcome guides or early support, could help them stick around.
- Payment method also matters. I saw that people using electronic checks churn more. If the company motivates them to use auto-pay (credit card or bank), churn might reduce.
- Fiber optic users pay more and seem more engaged. Maybe DSL customers can be encouraged to upgrade to fiber with some offers.
- Customers with dependents or multiple lines may behave differently. The company can think about family or group plans for them.
- Streaming users pay more but also churn sometimes. Maybe giving them special streaming bundles or free trials could keep them happy.
- Many don’t have tech support, and churn is higher for them. Even a basic free support option could make them feel more cared for.

---

## 🚀 How to Run This Project
1. Clone this repository or download the files.
2. Install dependencies (preferably in a virtual environment):

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn scipy
   ```

3. Open the notebook:

   ```bash
   jupyter notebook CustomerChurn_EDA.ipynb
   ```

4. Run cells step by step to reproduce the analysis and plots.

---

## 📌 Author
- Prepared by **Shailya Gandhi**(https://www.linkedin.com/in/shailya-gandhi-b395a953/)
- This project is intended as a professional portfolio piece showcasing **EDA skills for Data Analytics / Data Science** roles.
