# churn-analysis
A data analysis project to understand and reduce customer churn through data-driven insights and visualizations using Python and Power BI.

![Screenshot 2025-06-01 185836](https://github.com/user-attachments/assets/3c00e7ba-410d-4fe7-b8e9-4fa68c2504f7)

## Tools Used
- Python (pandas, matplotlib, seaborn)
- Power BI
- Data Cleaning & Feature Engineering
- Categorical Mapping & Grouping

## Workflow Overview
1. **Data Cleaning & Preprocessing**  
   - Handled missing values and formatted categorical variables  
   - Engineered new features (e.g. binary flags for services, billing types)  

2. **Exploratory Data Analysis (EDA)**  
   - Explored churn patterns based on tenure, monthly charges, and services  
   - Visualized key metrics and segment-based churn behaviors  

3. **Power BI Dashboard Development**  
   - Multi-page dashboard with KPIs, charts, and customer-level drilldowns  
   - Created dynamic visuals for deeper business understanding  

## Visualizations
- Distribution plots of **MonthlyCharges** and **Tenure** by churn status 
- Matrix chart of churn rate by **internet & phone service combinations**  
- 100% stacked bar chart for **customer types by churn**  
- KPI tiles (e.g., churn rate, average tenure)  
- Funnel chart & conditionally formatted customer tables
  
![Screenshot 2025-06-01 190009](https://github.com/user-attachments/assets/17e5f9cd-cf5b-4fea-92ec-0f9c07f7ae3c)

## Key Insights
- **Senior citizens without dependents/partners** have higher churn risk  
- **Fiber Optic users without add-on services** tend to churn more  
- **Short tenure and high charges** strongly correlate with churn  
- **Paperless billing** users are more likely to churn — potential digital gap  

## Business Recommendations
- Offer **personalized retention plans** to high-risk segments  
- Promote **service bundles** to improve perceived value  
- Launch **onboarding incentives** for new users  
- Test **hybrid billing options** for digitally hesitant customers  

## Report & Deliverables
- Executive-level report with a structured narrative:  
  **Empirical Finding → Analytical Insight → Business Recommendation**  
- Power BI Dashboard for stakeholder use  

## Repository Contents
- `dataset/` – Dataset, raw and processed
- `notebooks/` – Python data preprocessing & EDA scripts  
- `dashboard/` – Power BI `.pbix` file  
- `report/` – Summary report (PDF)
- `README.md` – Project overview

## Kaggle Link
https://www.kaggle.com/code/cindyvv/telco-churn-analysis-who-s-leaving-and-why/

## Author
**Cindy Valerie**  
[https://www.linkedin.com/in/cindyvv/] | [cindyvalerieev@gmail.com]

