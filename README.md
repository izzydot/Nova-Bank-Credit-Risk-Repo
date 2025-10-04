# Nova-Bank-Credit-Risk-Repo

# Credit Risk Analytics Report – Nova Bank

### Project Overview
Nova Bank, a financial institution operating across the USA, UK, and Canada, seeks to optimize its lending strategy by balancing accessibility with financial risk. This project analyzes borrower data to uncover patterns in loan defaults, identify high-risk groups, and recommend data-driven lending policies that are both fair and protective.

---

### Problem Statement
Nova Bank faces a dual challenge: approving loans to deserving customers while minimizing exposure to default risk. Overly lenient policies increase financial losses, while overly strict ones exclude viable borrowers. The bank needs a reliable framework to assess creditworthiness and predict loan outcomes.

---

### Business Questions Answered
- Which borrower groups are more likely to default?
- How do loan purpose, income, and credit history affect risk?
- What role do employment type and home ownership play in default behaviour?
- Are there geographic differences in repayment behaviour?
- Which loan grades and terms are safer or riskier?
- Can Nova Bank identify “safe” vs. “risky” borrower profiles?

---

### Tools & Methodology

- **Tools Used**:  
  - Power BI for interactive dashboard creation and data visualization  
  - DAX (Data Analysis Expressions) for calculated metrics and custom logic  
  - Data modelling features in Power BI for optimized performance and relational integrity  

- **Methodology**:
  - **Custom Bucketing**: Created custom columns using DAX to segment borrowers into meaningful groups (e.g., income brackets, credit history tiers, loan grades) for clearer analysis.
  - **Data Modelling**: Structured relationships between tables to enable smarter filtering, faster queries, and more dynamic visualizations.
  - **Data Cleaning & Imputation**:  
    - Checked for skewness in numerical distributions to guide imputation strategy.  
    - Replaced missing values in two key numerical columns using statistically informed methods to preserve data integrity.
  - **Segmentation & Comparative Analysis**: Explored default behaviour across demographics, loan intents, credit history, and geography.
  - **Visual Storytelling**: Used scatter plots, bar charts, pie charts, and line graphs to communicate insights clearly and intuitively.

---
### Dashboard

<img width="3399" height="6000" alt="Untitled (2900 x 5120 px)" src="https://github.com/user-attachments/assets/194d1964-efe1-44f7-9e31-81d16cc5b6bd" />





### Key Insights
- **Income vs. Default**: Default rates decrease significantly with higher income. Borrowers earning over $105K have a default rate of just 3%, compared to 22% for those under $30K.
- **Loan Grades**: Grade G loans show the highest default rates, indicating elevated risk.
- **Loan Purpose**: Debt consolidation and medical loans carry higher default risk than educational or vacation loans.
- **Employment & Education**: Full-time employees and college graduates borrow the most, but also show high LTI and DTI ratios—suggesting potential over-leverage.
- **Home Ownership**: Borrowers who own homes have lower default rates (~15%) compared to renters (~25%) or those with mortgages (~20%).
- **Credit History**: Better credit history correlates with higher income, older age, and lower default risk.
- **Geographic Trends**: Repayment behaviour varies across countries, with short-term loans generally performing better than long-term ones.

---

### Recommendations
1. **Refine Loan Approval Criteria**:
   - Tighten screening for Grade G loans and high DTI borrowers.
   - Prioritize applicants with strong credit history and stable income.

2. **Segment Lending Policies**:
   - Offer tailored interest rates and loan terms based on borrower risk profiles.
   - Consider incentives for home ownership or financial education.

3. **Monitor High-Risk Intents**:
   - Flag debt consolidation and medical loans for closer review or additional documentation.

4. **Use LTI/DTI as Early Warning Indicators**:
   - Integrate ratio thresholds into automated risk scoring systems.

5. **Geographic Strategy**:
   - Adjust loan terms based on regional repayment behaviour to optimize performance.


### Conclusion
This analysis equips Nova Bank with a data-driven understanding of borrower risk. By leveraging insights from income, loan purpose, credit history, and repayment behaviour, the bank can refine its lending strategy to be both inclusive and secure. Implementing targeted policies based on these findings will help Nova Bank reduce defaults, improve profitability, and serve its customers more responsibly.

