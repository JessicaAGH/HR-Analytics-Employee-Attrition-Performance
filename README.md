# 📊 HR Analytics: Employee Attrition & Performance Analysis
## 📌 Project Description

Employee turnover is one of the most critical challenges organizations face today. This project analyzes employee attrition and performance trends to uncover the key factors influencing turnover, satisfaction, and productivity.
Using data-driven insights, the analysis identifies patterns in employee behavior, compensation, work environment, and performance ratings to help HR departments make strategic, evidence-based decisions.


## 🎯 Project Goals

- Identify the primary factors contributing to employee attrition.  
- Analyze the relationship between performance ratings and employee turnover.  
- Evaluate the impact of salary, job role, and department on retentio.  
- Measure employee satisfaction and engagement levels.  
- Provide actionable recommendations to improve retention and workforce performance.  


## 🗂 Data Sources

- Internal HR employee dataset (anonymized company data).  
- Employee demographic information (age, gender, marital status).  
- Job-related data (department, role, years at company, promotion history).  
- Compensation details (monthly income, salary hike %).  
- Performance ratings and satisfaction scores.  

(Kaggle dataset)


## 🛠 Tools & Technologies Used

- Microsoft Excel – Data cleaning and preliminary analysis.  
- Power BI – Interactive dashboard creation and data visualization.  
- Data Modeling & DAX – KPI calculations and dynamic measures.  
- Pivot Tables & Charts – Trend and comparative analysis.  


## 📊 Overview

The main story derived from the IBM HR Analytics dataset is a critical, multi-faceted problem of preventable employee attrition, driven primarily by high-stress work factors and a lack of long-term financial incentives.
The overall attrition rate of 16.12% suggests a consistent drain on human capital. However, the data reveals that this loss is highly concentrated among specific groups:

- High-Churn Roles: Laboratory Technicians and Sales Executives bear the brunt of the turnover.  
- Lack of Investment: Employees without stock options are disproportionately leaving.  
- Burnout: Those who work mandatory OverTime and report poor Work-Life Balance are the most likely to exit.  
- Mid-Career Flight: The highest volume of leavers are Single employees in the 26-35 age bracket, often those with low tenure in the company, indicating a failure to retain talent shortly after their initial investment period.  

The dashboard's primary objective is to pinpoint the exact demographics, job conditions, and tenure levels where the company is most vulnerable, allowing management to deploy targeted retention programs rather than broad, expensive, and ineffective solutions.


## 💡 Key Insights
The dashboard focuses on three highly correlated factors—Dempographics, Work&Life Balance, Career Progression—to provide a granular view of the attrition problem.

### ✨Factors:
#### 1) Demographics Factors

Key Demographics Insights:
       
- Age: Nearly (38.4%) of all employees who left are in the less than 30 age group, suggesting a significant turnover issue among early-to-mid career professionals. The 30-39 group is also highly represented, accounting for (37.55%).   
         
- Gender and Marital Status: Over half (50.6%) of the employees who left are Single.This group is far more likely to leave than the married or divorced groups and also Male employees represent a slightly larger share.  
         
- Distance From Home: Employees living (0-5Miles) from the office account for the largest single group of those who left (36.7%), indicating that proximity does not appear to be a deterrent to attrition.  
         
- Education Level: Employees with a Bachelor's degree (41.7%) are the most common education level among those who left.  


#### 2) Work & Life Balance Factors

Key Work & Life Insights:
      
- OverTime: A clear majority (53.6%) of employees who left were working OverTime. This is the highest single category across all factors and suggests that mandated overtime is a critical driver of attrition.  

- Job Role: The most vulnerable roles are Laboratory Technicians (26.2%), followed closely by Sales Executives (24.1%) and Research Scientists (19.8%).  

- Work-Life Balance (WLB): The highest count of attrition is in the "High (3)" WLB category (53.6%), which, while not the worst rating, suggests that for employees who are leaving, 'High' is still not enough. The lowest WLB rating, Low (1), accounts for (10.5%) of the turnover.  

- Environment Satisfaction: The largest group of leavers (30.4%) had Low (1) Environment Satisfaction, confirming that an unsatisfactory working environment is a major contributor to turnover.  

- Job Satisfaction: The highest number of leavers rated their satisfaction as High (3) (30.8%), followed closely by Low (1) (27.8%). This bimodal distribution suggests two groups of leavers: those who are truly unhappy (Low/Medium) and those who are satisfied but are leaving for better external opportunities (High/Very High), possibly due to low salary or lack of promotion/incentive.  

- Stock Options: A vast majority (65.0%) of employees who left had Stock Option Level Low, suggesting that the lack of ownership or long-term incentive is a strong factor in their decision to leave.  

   
#### 4) Career Progression

Key Work & Life Insights:
   
- Average Monthly Income vs. Years at Company: Average monthly income generally increases with years at the company for those who leave, suggesting that even higher-paid, longer-tenured employees eventually leave, though the bulk of the attrition occurs at lower tenure levels (Years 0-10). The highest average income is seen at the highest tenure levels, indicating that when very experienced employees leave, they are generally high earners.

- Years Since Last Promotion: Shows a U-shaped relationship with attrition. The highest attrition appears among employees with 0 years since last promotion (46.4%), suggesting instability among newly promoted or never-promoted employees. Attrition decreases to its lowest in the 4–6 year range, then rises again for employees with 7+ years, indicating frustration from long-term stagnation.

- Salary: Shows (47.6%) of all attrition (113 out of 237 leavers) occurs among employees earning less than $4,000 per month. This is clear evidence that the company has a foundational issue with compensation for the majority of its workforce, particularly in the entry and mid-low levels.

- Years with Current Manager: Follows a clear downward trend. Employees with 0–1 year under their current manager show the highest attrition (~35.9%), while those with 5–8 years or 9+ years under the same manager show the lowest turnover. Manager continuity strongly contributes to retention.  



## 📣 Insights and Recommendations: Data-Backed Solutions
Based on the quantitative analysis, the company should implement the following targeted, data-backed solutions to strategically reduce the current high-risk attrition rate.

### 📍 Recommendation 1: Address Critical Compensation Gaps and Enhance Financial Commitment
Insight: 47.6% of leavers earn less than $4,000 per month, and 65.0% have Stock Option Level 0. Low compensation combined with a lack of long-term incentive is driving a massive talent flight.
📈Actionable Solutions:  
Immediate Salary Bump for High-Risk Roles: Conduct an emergency compensation review focused solely on Laboratory Technicians and Research Scientists (low-income roles). Implement immediate, targeted salary adjustments to bring the average income of these roles above the $5,000 threshold, thus neutralizing the primary attrition driver.
Tiered Stock Grant Program (The "Golden Handcuff"): Roll out a mandatory Level 1 stock option grant for all employees after 2 years of service. This provides a financial stake that vests over the following 3 years, creating a strong retention incentive right before the high-risk 3-5 year tenure mark.
___________________________________________________________________________________________________________________________________________________________________________________________________________________
### 📍 Recommendation 2: Standardize and Accelerate Career Progression Pathways
Insight: Attrition peaks sharply 1-2 years after the last promotion, and high-tenure Sales Executives leave, indicating stagnation in their current title.
📈Actionable Solutions:  
Mandatory Career Path Check-in: Within 18 months of any employee’s last promotion, the manager must conduct a formal "Next Step Planning" session. This session must result in documented, measurable goals designed for the next promotion, ensuring the employee sees a tangible future at the company.
Senior Specialist Titles: For high-performing Sales Executives or Research Scientists who cannot be promoted to management (Job Level 3+), create a non-managerial title track (e.g., "Principal Sales Specialist" or "Senior Staff Researcher") that comes with a Job Level increase (Job Level 3) and corresponding salary raise. This retains their technical expertise while rewarding tenure and eliminating the perception of stagnation.
___________________________________________________________________________________________________________________________________________________________________________________________________________________
### 📍 Recommendation 3: Improve Managerial Effectiveness in Early Tenure
Insight: 70% of leavers depart within the first three years of working with their current manager, with the highest volume occurring between 0 and 3 years. This indicates a failure in initial managerial support.
📈Actionable Solutions:  
"First Year Retention" Metric for Managers: Implement a formal performance metric for all managers based on the retention rate of their direct reports during the employee's first 12 months. Poor performance on this metric should require mandatory retraining in coaching, feedback, and performance management.
Mandatory 90-Day Check-ins: Formalize quarterly one-on-one sessions during the first year of a new manager-employee relationship. These check-ins must specifically address Work-Life Balance, Job Satisfaction, and Career Alignment to proactively identify and resolve issues before they lead to turnover.

____________________________________________________________________________________________________________________________________________________________________________


## 💼 Business Impact

This dashboard enables:
- Clear visibility into profitability drivers  
- Faster executive-level decision-making  
- Identification of cost inefficiencies  
- Data-backed growth strategy development  

The project demonstrates advanced Power BI skills, including DAX calculations, time intelligence modeling, data architecture design, and business-focused analytics.



## 🏁 Final Note

This project demonstrates how HR data can be transformed into actionable business intelligence. By identifying key drivers of attrition and performance trends, organizations can proactively improve employee engagement, reduce turnover costs, and enhance overall workforce productivity.
The analysis highlights the power of data analytics in supporting strategic HR decision-making.

 
