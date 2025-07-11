# Customer Sign-Up Behavior & Data Quality Audit

## Project Overview
This project analyzes customer sign-up behavior and conducts a comprehensive data quality audit for Rapid Scale, a fast-growing SaaS company. The analysis supports Monthly Business Review (MBR) meetings by providing actionable insights to optimize marketing campaigns and user engagement workflows.

## Business Context
The Marketing and Onboarding teams need data-driven insights to:
- Identify data quality issues affecting business decisions
- Understand customer acquisition patterns and preferences
- Optimize marketing campaigns and engagement strategies
- Improve user onboarding experiences

## Dataset
**Primary Dataset:** `customer_signups.csv` (300 records)
- Customer demographics and sign-up information
- Acquisition sources and regional data
- Plan selections and marketing preferences

**Secondary Dataset:** `support_tickets.csv` (123 records)
- Support ticket data for customer service analysis
- Ticket resolution tracking

## Key Findings

### Data Quality Issues
- **11.3%** missing email addresses
- **10%** missing regional data
- **1 duplicate** customer record removed
- Inconsistent formatting in categorical variables

### Customer Acquisition Insights
- **YouTube** is the top acquisition source (58 signups)
- **Premium plan** most popular (99 customers)
- **Young adults (20-35)** represent 62% of customer base
- **44%** overall marketing opt-in rate

### Support Performance
- **77%** ticket resolution rate
- **Pro plan** users generate most support tickets (47)
- **40 customers** contacted support within 2 weeks of signup

## Business Questions Answered
1. **Top acquisition source last month:** Google (7 signups in October 2024)
2. **Region with data quality issues:** North region (10 missing emails, 4 missing sources)
3. **Marketing opt-in by age:** Older users less likely to opt-in (44% vs 49% for middle-aged)
4. **Most popular plan:** Premium, primarily chosen by young adults (57 customers)
5. **Support-heavy plan:** Pro plan users most likely to contact support

## Tools & Technologies
- **Python** - Data analysis and manipulation
- **Pandas** - Data cleaning and aggregation
- **Matplotlib/Seaborn** - Data visualization
- **Jupyter Notebook** - Interactive analysis environment

## Project Structure
```
├── customer_signups.csv          # Primary dataset
├── support_tickets.csv           # Support ticket data
├── rapid_scale.ipynb    # Main analysis notebook
├── Customer Sign-Up Behaviour.pdf            # Business report (1500 words)
└── README.md                     # Project documentation
```

## Key Recommendations
1. **Focus marketing efforts** on YouTube and Google channels
2. **Implement data validation** for North region signups
3. **Develop enhanced onboarding** for Pro plan users
4. **Target middle-aged demographics** for marketing campaigns

## Skills Demonstrated
- Data cleaning and standardization
- Exploratory data analysis
- Business intelligence reporting
- Data visualization
- Statistical analysis
- Problem-solving with missing/inconsistent data

## How to Run
1. Clone the repository
2. Install required packages: `pip install pandas matplotlib seaborn numpy`
3. Open `rapid_scale_analysis.ipynb` in Jupyter Notebook
4. Run all cells to reproduce the analysis

## Author
**Ujwal Neethipudi** - Data Analyst  
Analysis Date: July 10, 2025

---
