 # 🤱Nigeria Maternal Birth Outcome Analysis
An end-to-end healthcare data analytics project focused on evaluating maternal and neonatal health indicators, birth outcomes, and delivery facility care across Nigerian regions. This project leverages Excel (Power Query & Pivot Tables) for ETL and exploratory analysis, and Power BI for interactive reporting and business intelligence.

# 📑 Executive Summary
​Maternal and neonatal healthcare delivery remains a critical priority in Nigeria. This project analyzes a dataset of 25,000+ maternal health records across all 36 Nigerian states and the Federal Capital Territory (FCT). By profiling clinical risk factors, antenatal care (ANC) attendance, delivery facilities, and geographic outcomes, this study provides actionable insights to help healthcare administrators, policymakers, and public health organizations optimize interventions and reduce maternal and neonatal mortality.

# ​🛠 Tech Stack & Tools Used
​Data Processing & ETL: Microsoft Excel (Power Query)
​Exploratory Data Analysis (EDA): Excel Pivot Tables & Formulas
​Data Visualization & Analytics: Power BI (DAX, Interactive Dashboarding)
​Documentation & Version Control: Markdown / GitHub

# ​⚙️ Project Architecture & Data Workflow
​1. Data Cleaning & Transformation (Power Query / Excel)
​Handling Missing & Invalid Data: Filtered duplicate records, removed non-standard data entries, and standardized missing values across clinical metrics.

## ​Feature Engineering & Categorization:
​ANC Category: Grouped ANC visits into Inadequate (<4 visits), Moderate (4–7 visits), and Adequate (\ge 8 visits).
​Blood Pressure Classification: Categorized Systolic and Diastolic readings into Normal, Elevated, Hypertension Stage 1, and Stage 2.
​Age Group Binning: Categorized patient ages into actionable demographic groups (Young, Mature, Advanced Maternal Age).
​Low Birth Weight Classification: Flagged infants with birth weight < 2.5\text{ kg} as Low Birth Weight.
​Data Validation: Applied date format consistency checks and validated data types across numerical, categorical, and geographical attributes.

​## 2. Exploratory Data Analysis (Excel Pivot Tables)
​Investigated relationships between clinical pre-conditions (Anaemia, Hypertension, Malaria) and adverse maternal outcomes.
​Evaluated how antenatal care (ANC) attendance influences birth weight outcomes and neonatal survival.
​Assessed clinical outcomes across different delivery facility types (Public Hospitals, Primary Health Centres, Private Hospitals, Teaching Hospitals, and Maternity Centres).
​Analyzed maternal risk across demographic tiers (Age Groups, Residence Types, and Marital Status).

## ​3. Business Intelligence & Dashboard Development (Power BI)
​Engineered custom DAX measures for key healthcare KPIs.
​Visualized state-by-state geographic distribution of adverse maternal outcomes.
​Designed interactive slicers for dynamic filtering by Year, Region, and Age Group.

# ​📊 Key Insights & Analytical Findings
## ​1. Core Healthcare KPIs (National Overview)
​Skilled Birth Attendance Rate (SBA): 66.2% of deliveries were attended by qualified healthcare personnel.

​Inadequate ANC Rate: 42.2% of pregnant women received inadequate antenatal care (<4 visits).
​Adverse Neonatal Outcome Rate: 3.7% of recorded births experienced adverse neonatal outcomes.

​Adverse Maternal Outcome Rate: 1.4% of deliveries resulted in adverse maternal outcomes.

## ​2. Birth Weight & Antenatal Care (ANC) Dynamics
​85.6% of babies recorded normal birth weights, while 14.4% exhibited Low Birth Weight (<2.5\text{ kg}).

​There is a direct inverse correlation between ANC attendance and low birth weight; mothers with inadequate ANC visits were significantly more likely to give birth to low birth weight infants.

​Monthly ANC visits remained steady across the calendar year, hovering between 7,000 and 9,000 visits per month.

​## 3. Delivery Facility Performance & Complications
​Public Hospitals recorded the highest volume of adverse maternal outcomes (119 cases), followed by Primary Health Centres (82 cases) and Private Hospitals (78 cases).
​Complication Profile:
​No Complication: 15,759 cases (~63%)
​Low Birth Weight: 3,467 cases
​Gestational Anaemia: 1,944 cases
​Prolonged Labour: 1,721 cases
​Pre-Eclampsia: 1,209 cases

## ​4. Geographic Risk Hotspots
​Top States by Adverse Maternal Outcomes:
​Ondo State: 16 adverse cases
​Edo State: 14 adverse cases
​Imo State: 14 adverse cases
​Gombe State: 13 adverse cases
​Kano State: 13 adverse cases

# ​💡 Strategic Recommendations
​Based on the quantitative insights uncovered during the analysis, four core strategic interventions are recommended:

​Targeted Healthcare Intervention in High-Risk States

​Prioritize public health funding, medical equipment, and clinical specialist deployments to states exhibiting the highest adverse outcome rates (e.g., Ondo, Edo, Imo, Gombe, and Kano).

​Capacity Building for Primary Health Centres (PHCs)

## ​Since Primary Health Centres handle a substantial volume of deliveries and complication cases, upgrading PHC diagnostic tools, emergency referral transport, and staff training will significantly reduce adverse outcomes before hospital arrival.

​## Community Outreach for Early ANC Enrollment

​Implement community-based sensitization campaigns to tackle the 42.2% inadequate ANC rate. Educating mothers on completing at least 4 to 8 ANC visits will directly reduce low birth weight and undetected hypertensive complications.

​## Mandatory High-Risk Screening Protocols

​Establish routine clinical screening protocols for Gestational Anaemia and Pre-Eclampsia at all antenatal clinic visits to ensure early medical management and prevent emergency labour complications
