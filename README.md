# 🛡️ Insurance Portfolio Analytics Dashboard | Power BI Project

<div align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![CSV](https://img.shields.io/badge/CSV-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

**A comprehensive Power BI dashboard for insurance portfolio management, premium tracking, and ROI analysis**

[Features](#-key-features) • [Dashboard Views](#-dashboard-overview) • [Data Model](#-data-architecture) • [Contact](#-contact)

### 🌐 [**View Live Interactive Report**](https://app.powerbi.com/groups/3ad17ba2-818f-4f61-8c2b-34f46bb00b8d/reports/60a99caa-ecaf-4a4a-ae8e-639a661747ac/004d6a2a3d56b8b90ad0?experience=power-bi)
💡 **Feel free to explore the `.pbix` file and adapt it to your own customer datasets!**

</div>

---

## 📊 Project Overview

This Power BI project delivers an end-to-end insurance portfolio analytics solution for insurance companies and financial institutions. The dashboard tracks **7,299 active policies** worth **₹39,096.58M in total premium amount** with comprehensive insights into premium collections, policy performance, maturity tracking, and agent productivity.

### 🎯 Business Objectives

- **Premium Management**: Track premium amounts, payments, and payables across policies
- **ROI Analysis**: Calculate and visualize annualized returns on investment
- **Agent Performance**: Monitor sales agent productivity and commission tracking
- **Portfolio Health**: Analyze policy distribution by type, tenure, and geography
- **Maturity Tracking**: Forecast maturity amounts and payment schedules
- **Customer Insights**: Understand policyholder demographics and behavior
- **Underwriting Analytics**: Track underwriting expenses and profitability

---

## ✨ Key Features

### 📈 Advanced Analytics
- **Real-time KPI Monitoring** - Track Number of Policies, Annual Premium, Total Premium Amount, Premium Paid/Payable
- **ROI Calculations** - Annualized ROI analysis by year, tenure, and policy type
- **Maturity Forecasting** - Predict future payouts and payment schedules
- **Agent Hierarchy Tracking** - Zonal Manager → Regional Manager → Sales Agent analytics
- **Multi-dimensional Analysis** - Analyze by State, Policy Type, Year, Occupation, and more

### 🎨 Interactive Visualizations
- Premium trend analysis with year-over-year comparisons
- Geographic distribution across Indian states
- Policy type and protection plan breakdowns
- Agent performance rankings
- Underwriting expense analysis
- Maturity amount projections
- Payment frequency distributions

### 🔍 Comprehensive Filtering
- State-wise filtering (all Indian states)
- Policy type selection (Endowment, Whole, Universal)
- Policy name filtering (ULIP Growth, Jeevan Saral, Life Growth, etc.)
- Sales agent multi-select
- Year-based filtering (2016-2025)
- Occupation-based segmentation
- Dynamic slicers for custom analysis

---

## 🖥️ Dashboard Overview

### 1️⃣ Active Policies Overview
The main dashboard provides a comprehensive view of the active insurance portfolio:

**Key Metrics Displayed:**
- 📋 **No of Policies**: **7,299** active policies
- 💰 **Total Annual Premium**: **₹2,161.60M** 
- 💵 **Total Premium Amount**: **₹39,096.58M**
- ✅ **Total Premium Paid**: **₹10,686.35M** (27.33%)
- ⏳ **Total Premium Payable**: **₹28,410.24M** (72.67%)
- 💼 **Underwriting Expense**: **₹38.66M**

**Visualizations Include:**
- 📊 **Underwriting Expense by Policy Type**: Endowment (33.58%), Whole (33.24%), Universal (33.18%)
- 🏆 **Underwriting Expense by Policy Name**: ULIP Growth (32.73%), Jeevan Saral (24.07%), Life Growth (18.5%)
- 👥 **Underwriting Expense by Sales Agent**: Performance tracking of top agents (Baiju Singh, Divij Malhotra, Biju Issac, etc.)
- 🗺️ **Underwriting Expense by State**: Geographic distribution across Delhi, Uttar Pradesh, Sikkim, Haryana, etc.
- 👔 **Underwriting Expense by Occupation**: Distribution across professions (Ecologist, Pharmacologist, Administrator, etc.)
- 📅 **Underwriting Expense by Year**: Trend analysis from 2016 to 2024

---

### 2️⃣ Premium & ROI Analysis
Detailed analysis of premium amounts and return on investment:

**Premium Trend Analysis:**
- 📈 **Total Premium Amount, Maturity Amount and Annualized ROI by Year**
  - Year-wise comparison from 2016 to 2024
  - Maturity amount projections
  - ROI percentages ranging from 3.21% to 14.05%
  - 2018 showed highest ROI at 7.71%

**Future Projections:**
- 🔮 **Total Annual Premium, Sum Assured and ROI by Maturity Year**
  - Projections from 2035 to 2050
  - Coverage amount forecasting
  - Long-term ROI analysis
  - Tenure-based segmentation (20-year and 25-year policies)

**Key Insights:**
- Strong premium growth trajectory
- Consistent maturity amount projections
- ROI variations by policy vintage and type
- Coverage amount trends over time

---

### 3️⃣ Payment Bucket Analysis
Focused view on payment schedules and future obligations:

**Payment Metrics:**
- 💰 **% Premium Payable**: **29.61%** of total
- ✅ **% Premium Paid**: **70.39%** of total
- 📊 **Total Annual Premium**: **₹313.51M**
- 💵 **Total Premium Amount**: **₹3,338.85M**
- ✔️ **Total Premium Paid**: **₹2,350.20M**
- ⏰ **Total Premium Payable**: **₹988.65M**

**Visualizations:**
- 📅 **Premium Paid, Payable and Maturity Amount by Year** (2025-2030)
  - Detailed payment timeline
  - Maturity amount forecasting
  - ROI percentages by maturity year
  - Payment bucket: Payable in 5 Years

- 👥 **Premium Analysis by Sales Agent**
  - Agent-wise breakdown: Divij Malhotra, Baiju Singh, Biju Issac, Sara Chatterjee, Ravi Chandran, Kartik Sunder
  - Premium paid vs payable tracking
  - Maturity amount by agent

---

### 4️⃣ Hierarchical Agent Performance
Organizational structure and performance tracking:

**Agent Hierarchy:**
```
Zonal Manager → Regional Manager → Sales Agent
```

**Performance Tracking:**
- 🏢 **Zonal Manager Level**: Lakshmi Iyer, Rohit Kapoor
- 📊 **Regional Manager Level**: Ravi Menon, Ananya Sharma, Naveen Verma, Arindam Ghosh
- 👤 **Sales Agent Level**: 22 active agents across all states

**Key Metrics per Agent:**
- Total Annual Premium generated
- Total Premium Amount
- Total Premium Paid
- Total Premium Payable
- Underwriting expenses

**Top Performing Agents:**
1. **Baiju Singh**: ₹631.7M annual premium
2. **Divij Malhotra**: ₹488.2M annual premium
3. **Sara Chatterjee**: ₹391.1M annual premium
4. **Kartik Sunder**: ₹318.6M annual premium
5. **Ravi Chandran**: ₹330.3M annual premium

---

### 5️⃣ Detailed Policy Table
Granular policy-level information with comprehensive data:

**Policy Details Include:**
- 🆔 Customer ID and Policy Holder Name
- ⏱️ Tenure (Years) - ranging from 10 to 25 years
- 💳 Premium Duration and Payment Frequency (Monthly, Quarterly, Annually)
- 💰 Premium Amount per payment
- 📊 Total Annual Premium
- 💵 Total Premium Amount over policy lifetime
- ✅ Total Premium Paid to date
- ⏳ Total Premium Payable remaining
- 📧 Contact information and state details

**Advanced Features:**
- Sortable columns for custom analysis
- Search and filter capabilities across all fields
- Export functionality for further analysis
- Real-time data refresh

**Sample Policy Data:**
- CUST-100128 (Anika Ranganathan): 20-year tenure, ₹96,625 monthly premium, ₹2.32Cr total amount
- CUST-101521 (Hunar Iyer): 20-year tenure, ₹79,476 monthly premium, ₹1.91Cr total amount
- CUST-102502 (Sara Lalla): Multiple policies with varying tenures and payment structures

---

## 🛠️ Data Architecture

### Data Model Schema
```
├── FCT_Insurance_Policy_Table (Fact Table)
│   ├── Policy Number (Primary Key)
│   ├── Customer ID (Foreign Key)
│   ├── Sum Assured/Coverage Amount
│   ├── Premium Amount
│   ├── Payment Frequency
│   ├── Underwriting Expenses
│   ├── Sales Agent Code (Foreign Key)
│   ├── Policy Type Code (Foreign Key)
│   └── Policy Status
│
├── DM_Customer_Detail_Table (Dimension)
│   ├── Customer ID (Primary Key)
│   ├── Policy Holder Name
│   ├── Gender
│   ├── Age at Entry / Current Age
│   ├── Occupation
│   ├── Smoker Status
│   ├── Nationality
│   └── State
│
├── DM_Insurance_Agent_Table (Dimension)
│   ├── Agent Code (Primary Key)
│   ├── Sales Agent Name
│   ├── Agent Email
│   └── State
│
├── DM_Regional_Manager (Dimension)
│   ├── RM ID (Primary Key)
│   ├── Regional Manager Name
│   └── Regional Manager Email
│
├── DM_Zonal_Manager (Dimension)
│   ├── Zonal Manager ID (Primary Key)
│   ├── Zonal Manager Name
│   └── Zonal Manager Email
│
├── DM_Policy_Type (Dimension)
│   ├── Policy Type Code (Primary Key)
│   ├── Policy Type (Endowment, Whole, Universal)
│   └── Number
│
└── DM_Policy_Protection_Plan (Dimension)
    ├── Policy Code (Primary Key)
    ├── Policy Name
    └── Policy Type Code (Foreign Key)
```

### Star Schema Design
- **Fact Table**: FCT_Insurance_Policy_Table (7,299 records)
- **Dimension Tables**: 6 dimension tables for comprehensive analysis
- **Relationships**: One-to-many relationships from dimensions to fact table
- **Calculated Columns**: Tenure dates, payment buckets, ROI calculations

---

## 📐 Key Measures & DAX Calculations

### Core KPIs
```dax
No of Policies = COUNTROWS(FCT_Insurance_Policy_Table)

Total Annual Premium = SUM(FCT_Insurance_Policy_Table[Annual Premium])

Total Premium Amount = SUM(FCT_Insurance_Policy_Table[Total Premium Amount])

Total Premium Paid = SUM(FCT_Insurance_Policy_Table[Premium Paid])

Total Premium Payable = SUM(FCT_Insurance_Policy_Table[Premium Payable])

Underwriting Expense = SUM(FCT_Insurance_Policy_Table[Underwriting Expenses])
```

### Advanced Calculations
```dax
% Premium Paid = 
DIVIDE(
    [Total Premium Paid],
    [Total Premium Amount],
    0
)

% Premium Payable = 
DIVIDE(
    [Total Premium Payable],
    [Total Premium Amount],
    0
)

Annualized ROI (%) = 
DIVIDE(
    ([Maturity Amount] - [Total Premium Amount]) / [Tenure (Years)],
    [Total Premium Amount],
    0
) * 100

Maturity Amount = 
[Total Premium Amount] + 
([Total Premium Amount] * [Tenure (Years)] * [ROI Rate])
```

### Time Intelligence
```dax
YoY Premium Growth = 
VAR CurrentYear = [Total Annual Premium]
VAR PreviousYear = 
    CALCULATE(
        [Total Annual Premium],
        DATEADD(DateTable[Date], -1, YEAR)
    )
RETURN
    DIVIDE(CurrentYear - PreviousYear, PreviousYear, 0)

Payment Bucket = 
SWITCH(
    TRUE(),
    [Years to Maturity] <= 5, "Payable in 5 Years",
    [Years to Maturity] <= 10, "Payable in 6-10 Years",
    "Payable in 10+ Years"
)
```

---

## 📊 Key Performance Indicators (KPIs)

| Metric | Value | Coverage |
|--------|-------|----------|
| 📋 Total Policies | 7,299 | Active policies |
| 💰 Total Annual Premium | ₹2,161.60M | Annual recurring revenue |
| 💵 Total Premium Amount | ₹39,096.58M | Lifetime premium value |
| ✅ Total Premium Paid | ₹10,686.35M | 27.33% collected |
| ⏳ Total Premium Payable | ₹28,410.24M | 72.67% outstanding |
| 💼 Underwriting Expense | ₹38.66M | Operating costs |
| 📈 Avg ROI | 7.5% - 12.5% | Annual returns |
| 👥 Active Agents | 22 | Sales force |

---

## 🗺️ Geographic Coverage

### States Covered (India)
- 🏛️ **North**: Delhi, Uttar Pradesh, Haryana, Chandigarh, Uttarakhand, Himachal Pradesh
- 🏔️ **East**: Sikkim, West Bengal, Bihar, Jharkhand, Assam, Orissa
- 🌴 **South**: Tamilnadu, Karnataka, Telangana, Andhra Pradesh, Kerala
- 🏜️ **West**: Rajasthan, Madhya Pradesh, Gujarat, Goa, Maharashtra

### Top Performing States by Premium
1. **Delhi**: Highest underwriting expenses and policy concentration
2. **Uttar Pradesh**: Strong market presence
3. **Tamilnadu**: South region leader
4. **Maharashtra**: Western region powerhouse
5. **Karnataka**: Growing market share

---

## 🔍 Use Cases

### For Insurance Executives
- Monitor overall portfolio health and growth
- Track premium collection efficiency
- Analyze ROI across policy types and vintages
- Make strategic decisions on product mix

### For Sales Managers
- Evaluate agent performance and productivity
- Identify top performers and training needs
- Optimize territory allocation
- Track commission and incentive metrics

### For Actuaries
- Analyze underwriting expense ratios
- Calculate and forecast maturity obligations
- Assess risk by occupation and demographics
- Model premium pricing strategies

### For Operations Teams
- Track payment schedules and follow-ups
- Manage policy renewals and lapses
- Monitor customer service metrics
- Ensure compliance with regulatory requirements

### For Financial Analysts
- Calculate portfolio ROI and profitability
- Forecast cash flows and maturity payments
- Analyze premium vs. payout ratios
- Assess investment performance

---

## 🎓 Learning Outcomes

This project demonstrates proficiency in:
- ✅ **Power BI Dashboard Development** - Complex multi-page reports
- ✅ **DAX (Data Analysis Expressions)** - Advanced calculations and measures
- ✅ **Data Modeling** - Star schema with 6 dimension tables
- ✅ **Insurance Domain Knowledge** - Premium, ROI, underwriting concepts
- ✅ **KPI Definition and Tracking** - Financial and operational metrics
- ✅ **Hierarchical Data Analysis** - Zonal → Regional → Agent structure
- ✅ **Time Intelligence** - Year-over-year and maturity forecasting
- ✅ **Interactive Visualization Design** - Filters, slicers, drill-throughs
- ✅ **Financial Analytics** - ROI calculations, premium tracking

---

## 📊 Policy Type Distribution

### Endowment Policy (33.58%)
- Traditional savings cum protection plan
- Maturity benefit + death benefit
- Fixed premium and tenure

### Whole Life Policy (33.24%)
- Lifetime coverage
- Cash value accumulation
- Premium payment flexibility

### Universal Life Policy (33.18%)
- Flexible premiums and death benefits
- Investment component
- Market-linked returns

### Popular Policy Names
1. **ULIP Growth** - 32.73% of underwriting expenses
2. **Jeevan Saral** - 24.07% of underwriting expenses
3. **Life Growth Plan** - 18.5% of underwriting expenses
4. **Additional plans** - 24.7% combined

---

## 📧 Contact

**Project Maintainer**: Uttam Kumar Biswal

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/https://www.linkedin.com/in/uttam-kumar-biswal-752a10120)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/u77am)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:uttam.biswal047@gmail.com)

---

## ⭐ Show Your Support

If you find this project helpful, please consider giving it a ⭐ star on GitHub!

---

## 🙏 Acknowledgments

- **Trusecure Insurance** for providing the dataset structure
- **Power BI Community** for best practices and inspiration
- **Insurance domain experts** for business knowledge validation
- **Data Team**: Ajith Sinha, Rohit Kapoor, Prasad Rao, Rahul Das for data management
- **Management Team**: Lakshmi Iyer, Rohit Kapoor, Ananya Sharma, Ravi Menon, Naveen Verma, Arindam Ghosh

---

## 📚 Related Resources

- [Power BI Documentation](https://docs.microsoft.com/en-us/power-bi/)
- [DAX Guide](https://dax.guide/)
- [Insurance Analytics Best Practices](https://www.insurancejournal.com/)
- [Financial Modeling Resources](https://www.wallstreetprep.com/)

---

<div align="center">

**Made with ❤️ and Power BI**

*Empowering Insurance Companies with Data-Driven Insights*

*Last Updated: February 2026*

</div>
