# Data Analysis Portfolio
## About me 👋
📊 With over four years of experience in the land surveying and engineering industry, I've honed my analytical skills and attention to detail. In 2022, I made a deliberate career shift into the exciting realm of data analysis. Now, I'm eager to apply my technical expertise and analytical mindset to the dynamic data field.

🔍 **What I Bring to the Table**

In this repository, you'll find a collection of data analysis projects that reflect my journey and proficiency in this domain. These projects serve as a testament to my ability to:

- Collect and Acquire Data
- Clean and Preprocess Data 
- Analyze and Extract Insights
- Visualize and Communicate data insights

## Table of Contents
  - [About me]()
  - [Projects]
    - SBA loans analysis during pandemic
    - Cohort Analysis non-store online retail
    - Bikeshare company analysis to improve marketing strategies
    - Tableau --> [go to Tableau Dashboards](https://public.tableau.com/app/profile/felipe.jordan)

## Projects
### 📂 1. SBA loans analysis during the pandemic (2020-2021)
SQL Data Analysis | [**Full Documentation**](https://github.com/felipejordan95/SQL-for-Data-Analysis/blob/main/SBA_Loans_Analysis.sql) | [**Dashboard**](https://public.tableau.com/app/profile/felipe.jordan/viz/SBALoansAnalysis/Dash2)

📌 **Introduction**
The Small Business Administration (SBA) is a vital U.S. government agency tasked with supporting and assisting small businesses, particularly during challenging times such as the COVID-19 pandemic. This project delves into the extensive dataset of SBA loans issued during 2020-2021 to identify the industries that received a significant injection of funds. The goal is to gain insights into the economic impact of these loans on different sectors.

**Project Scope:**
This analysis focuses on SBA loans approved for small businesses in the United States during the COVID-19 pandemic period, spanning from January 2020 to December 2021.

**Key Findings:**

Loan Volume in 2021: In 2021, an astounding 11,244,186 loans were approved for small businesses in the United States, totaling a staggering $784,832,222,248 in financial assistance.

Top Lenders: Two prominent financial institutions, Bank of America and JPMorgan Chase Bank, played a pivotal role in providing financial support to small businesses during the pandemic. Bank of America granted loans amounting to $32,710,588,570, while JPMorgan Chase Bank extended $41,407,652,336 in loans.

Leading Sectors: The analysis reveals that three sectors stood out in terms of receiving the highest number of approved loans. These sectors are:

Construction: This industry received substantial financial support, underlining its significance in the economic recovery.
Health Care and Assistance: The healthcare sector also received a significant share of loans, reflecting the critical role it played during the pandemic.
Professional-Scientific-Technical Services: This sector, encompassing a wide range of professional services, also benefited greatly from SBA loans.

**Conclusion:**
The infusion of a substantial amount of capital into the U.S. economy through SBA loans played a pivotal role in supporting small businesses and sustaining various sectors during the challenging period of 2020-2021. The project's insights shed light on the industries that received the most financial assistance, illustrating the economic resilience and adaptability of small businesses during unprecedented times.

⚙️ **Tools** — SQL Server, Tableau
💻 **Skills** — Data Cleaning and Manipulation, Exploratory Data Analysis, Data Visualization

---
### 📂 2. Cohort Analysis non-store online retail
Customer Cohort Analysis | [**Full Documentation**](https://github.com/felipejordan95/SQL-for-Data-Analysis/blob/main/Cohort_Analysis.sql) | [**Dashboard**](https://public.tableau.com/app/profile/felipe.jordan/viz/CohortRetentionDash_16924073492000/CohortRetentionDash)

📌 **Introduction:** 
This project focuses on conducting a comprehensive cohort analysis of customer behavior for a UK-based and registered non-store online retail company. The company specializes in selling unique all-occasion gifts and caters to a customer base that includes many wholesalers. The dataset used in this analysis encompasses all transactions that occurred between 01/12/2010 and 09/12/2011.

**Project Scope:**
The primary objective of this analysis is to gain valuable insights into customer behavior and engagement over time using cohort analysis techniques. Specifically, we employ Time-based Cohort analysis, grouping customers by their initial engagement month (year-month), and calculating cohort indices to track customer behavior.

**Key Analytical Approaches:**

Cohort Analysis: Cohort analysis is a powerful tool for understanding customer behavior over time. In this project, we apply cohort analysis to segment customers based on their initial engagement month.

Cohort Index: We calculate the cohort index to determine the number of months that have passed since each customer's first engagement with the company. This index serves as a valuable metric for tracking customer retention and behavior over time.

Cohort Tables: To visualize the findings effectively, we pivot the data to create cohort tables. These tables provide insights into how customer behavior varies across different cohorts, allowing us to identify trends and patterns.

**Expected Insights:**

Customer Retention: We anticipate gaining insights into customer retention rates across different cohorts. Understanding how long customers stay engaged with the company can inform retention strategies.

Purchase Behavior: The cohort analysis will shed light on how customer purchase behavior changes over time. For example, we can identify whether customers tend to make repeat purchases or exhibit one-time purchase behavior.

Wholesaler Insights: Given that the company serves wholesalers, we may uncover patterns specific to this customer segment, such as bulk purchase behavior or seasonal variations.

Conclusion:
By applying cohort analysis to this transactional dataset, we aim to uncover valuable insights into customer behavior for the UK-based online retailer. These insights will enable the company to make data-driven decisions, refine marketing strategies, and enhance customer engagement, ultimately driving business growth and customer satisfaction. This project demonstrates your proficiency in utilizing data analysis techniques to extract actionable insights from real-world datasets.

⚙️ **Tools** — SQL Server, Tableau
💻 **Skills** — Cohort Analysis, Data Cleaning and Manipulation, Exploratory Data Analysis, Data Visualization

---
### 📂 3. Bikeshare company analysis to improve marketing strategies
R Programming | [**Full Documentation**](https://github.com/felipejordan95/R-Projects/blob/main/Cyclistic_Case_Study.Rmd)| [**Report**](https://github.com/felipejordan95/R-Projects/blob/main/Cyclistic_Case_Study.pdf)

📌 **Introduction:** 
This case study revolves around Cyclistic, a prominent bike-share company in Chicago. The director of Marketing at Cyclistic recognizes that the future success of the company hinges on maximizing the number of annual memberships. To achieve this, the marketing team aims to gain insights into the differences in bike usage patterns between casual riders and annual members. Armed with these insights, the marketing department plans to devise a new strategy to convert casual riders into annual members.

**Context:**
Cyclistic offers three options to its customers: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are categorized as casual riders, while those who opt for annual memberships are Cyclistic members. The finance department's analysis has shown that annual members are significantly more profitable than casual riders, making them a prime target for conversion.

**Analysis:**
This comprehensive analysis seeks to address the following key questions:

Usage Differences: How do annual members and casual riders use Cyclistic bikes differently? Are there distinct patterns in terms of ride frequency and duration?

Conversion Motivations: Why would casual riders be inclined to buy Cyclistic annual memberships? What factors might influence their decision to make this transition?

Digital Marketing Strategy: How can Cyclistic leverage digital media to encourage casual riders to become annual members? What targeted campaigns and engagement tactics can be employed?

**Key Findings:**
The analysis has revealed significant insights, including:

- Membership Disparity: Cyclistic boasts a notably larger number of annual members compared to casual riders. However, the average ride length for casual riders is considerably higher, suggesting they tend to take longer trips.

- Weekly Ride Patterns: There are discernible differences in riding patterns. Annual members predominantly use the service on weekdays, possibly for commuting purposes, whereas casual riders exhibit higher ride numbers on weekends.

- Ride Duration: The average trip duration for casual members is consistently higher, particularly on weekends, indicating leisurely use. Annual members maintain a relatively stable average trip duration throughout the week.

**Recommendations:**
- Based on the findings, here are strategic recommendations for Cyclistic:

- Targeted Weekend Campaigns: Launch targeted weekend campaigns aimed at encouraging weekend riders to become annual members. Special promotions and discounts designed for weekend riders may be particularly effective in converting them.

- Member Conversion Strategy: Highlight the benefits of annual membership, including cost savings, exclusive features, and priority bike availability. Utilize digital media to clearly communicate these advantages to casual riders.

- Customer Engagement: Engage casual riders through digital media by providing valuable content such as biking tips, local routes, and Cyclistic service information. Building a sense of community and loyalty can enhance their willingness to consider annual memberships.

- Weekday Promotions: To retain and attract more annual members, offer weekday promotions or incentives, such as discounts on annual memberships, for those who frequently use the service during weekdays. This can drive weekday usage among annual members.

⚙️ **Tools** — SQL, Rstudio
💻 **Skills** — Classification, Data Cleaning and Manipulation, Exploratory Data Analysis, Correlation Analysis, Data VisualizationModeling, Model Evaluation

---

## Education
### Degrees
BACHELOR OF ENVIRONMENTAL ENGINEERING – EPN – Quito, Ecuador 	September 2019
Majors: Statistical Analysis, Technical Proficiency, Critical Thinking 

### Certificates
GOOGLE DATA ANALYTICS PROFESSIONAL CERTIFICATE – Google 	September 2023
Majors: Data cleaning, analysis & visualization (spreadsheets, SQL, R programming, Tableau)

## Contact 
- LinkedIn: [Felipe Jordan](https://www.linkedin.com/in/felipejordan/)
- Email: felipejordan95@gmail.com
    
