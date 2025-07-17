# 📊 Customer Churn Analysis & Prediction Dashboard

## 📝 Overview

This project provides a complete **data-driven solution** to analyze and predict customer churn for a telecom company. It integrates **SQL**, **Power BI**, and **machine learning (Python)** to extract valuable business insights and empower decision-making for customer retention strategies.



## 🔧 Tools & Technologies Used

- **SQL** – Data extraction, transformation, and cleaning  
- **Power BI** – Interactive dashboards, KPIs, drill-down analysis  
- **Python (Scikit-learn)** – Churn prediction using machine learning  
- **Random Forest Classifier** – Predictive modeling algorithm  
- **Evaluation Metrics** – Accuracy, Precision, Recall, ROC-AUC



## 🚀 Project Workflow

1. **Data Extraction and Preparation**  
   - Used SQL to extract and clean telecom customer data.
   - Connected Power BI directly to the SQL database for auto-refresh and live data sync.

2. **Exploratory Data Analysis (EDA)**  
   - Performed detailed visual analysis using Power BI on:
     - Demographics (gender, age)
     - Service usage
     - Tenure groups
     - Contract and billing behavior

3. **Machine Learning (Python)**  
   - Built a **Random Forest** model to predict customer churn using historical trends.
   - Evaluated the model using classification metrics: **Accuracy**, **Precision**, **Recall**, and **ROC-AUC**.
   - Output predictions were integrated back into Power BI for end-to-end insight delivery.

4. **Dashboard Design**  
   - Created an interactive **Power BI** dashboard with:
     - Custom KPIs
     - State-wise and contract-wise drill-downs
     - Churn prediction profiles
     - Filters by marital status, age group, tenure, etc.


## 🔍 Key Insights

- 🔸 **Churn Rate is 27%**, indicating over a quarter of the customer base is at risk.
- 🔸 **Month-to-month contracts** show the highest churn (47%) – lock-in plans can help reduce it.
- 🔸 **Customers >50 years** churn more (32%) – potential focus for retention plans.
- 🔸 **Jammu & Kashmir** has the highest state-wise churn at **57%** – regional targeting needed.
- 🔸 **Mailed Check payments** lead to higher churn (38%) – promote digital payments.
- 🔸 **Customers with multiple services** like Internet and Phone Service churn more – review bundle pricing or satisfaction.
- 🔸 **355 out of 378 predicted churners** are on **Month-to-month contracts** – high-risk group identified.
- 🔸 High churn predicted in **Uttar Pradesh, Maharashtra, and Tamil Nadu** – prioritize customer care there.


## 📈 Dashboard Overview

### ✅ Summary Page

![Summary Page](./Dashboard%20Screenshots/Summary%20Page.png)

#### 📌 KPIs:
- **Total Customers:** 6,418  
- **New Joiners:** 411  
- **Total Churn:** 1,732  
- **Churn Rate:** 27%

#### 📊 Visual Insights:

- **Churn by Gender**  
  - Male churn: 64%  
  - Female churn: 36%

- **Churn by Age Group**  
  - Age >50 group has the highest churn (32%)  
  - Age <20 has the lowest

- **Churn by State (Top 5)**  
  - Jammu & Kashmir: 57%  
  - Assam: 38%  
  - Jharkhand: 35%  
  - Chhattisgarh: 31%  
  - Delhi: 30%

- **Churn by Payment Method**  
  - Mailed check: 38%  
  - Bank withdrawal: 34%  
  - Credit card: only 15%

- **Churn by Contract Type**  
  - Month-to-month: 47%  
  - One year: 11%  
  - Two years: 3%

- **Churn by Internet Type**  
  - Fiber Optic: 41%  
  - DSL: 19%  
  - No Internet: 8%

- **Churn by Services**  
  Customers using the following services have **higher churn**:  
  - Internet Service (78%)  
  - Online Security (44%)  
  - Paperless Billing (76%)  
  - Phone Service (90%)  
  - Multiple Lines (42%)

- **Churn Categories**  
  - Competitor: 761  
  - Attitude: 301  
  - Dissatisfaction: 300  
  - Price: 196  
  - Other: 174  


### 🔮 Prediction Page

![Prediction Page](./Dashboard%20Screenshots/Prediction%20Page.png)

#### 🧠 Predicted Churners: `378` customers

#### 🧍 Gender Breakdown:
- Female: 246
- Male: 132

#### 💍 Marital Status:
- Not Married: 193  
- Married: 185

#### 🧓 Age Group:
- Highest churn risk in middle-aged groups

#### 💳 Payment Method:
- Credit Card: 192  
- Bank Withdrawal: 150  
- Mailed Check: 36

#### 📅 Tenure Group:
- Highest churn prediction in:
  - >24 months: 106
  - 6–12 months: 90

#### 📜 Contract Type:
- Month-to-month: 355
- One year: 17
- Two years: 6

#### 🗺️ Top States by Predicted Churn:
- Uttar Pradesh: 44  
- Maharashtra: 40  
- Tamil Nadu: 37  
- Karnataka: 29  
- Andhra Pradesh: 24  

#### 🧾 Customers at Risk Table:
- Displays customer ID, monthly charge, number of referrals, and total charges for the top predicted churners. Helps the retention team plan outreach.
---

## 📂 Repository Contents

| File / Folder                       | Description                                                  |
|------------------------------------|--------------------------------------------------------------|
| `Customer Churn Analysis Power BI.pbit` | Power BI dashboard template                                 |
| `Customer Churn Prediction.ipynb`  | Python notebook with Random Forest model and evaluation      |
| `Dashboard Screenshots/`           | Contains screenshots of Power BI dashboards                  |
| `README.md`                        | Full project documentation                                   |



## 🎯 Business Impact

- Enables proactive retention campaigns  
- Provides clear segmentation of high-risk customers  
- Improves service bundling strategies  
- Offers real-time insights to leadership teams



## 🧑‍💻 Author

**Shivangi Vaish**  
Customer Churn Analysis | Power BI | SQL | Machine Learning  
GitHub: [vaish-shivangi](https://github.com/vaish-shivangi)



