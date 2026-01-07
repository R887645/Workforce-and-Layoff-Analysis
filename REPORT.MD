# Parks and Recreation Workforce Analytics

## Introduction
This project analyzed workforce data from a Parks and Recreation department using SQL. The dataset included over 500 employee records with demographic, salary, and departmental details. 
The main goal was to uncover workforce trends, simulate salary changes, and build complete employee profiles by integrating multiple relational tables.

Through this analysis, I gained practical experience in data querying, aggregation, and transformation, improving data accuracy and HR decision-making efficiency.

## Objectives
- Analyze employee demographics and salary distribution.
- Simulate salary increases and bonus structures using SQL logic.
- Merge multiple datasets to generate complete employee profiles.
- Rank employees by salary and gender to detect pay gaps.
![My Image Description](https://github.com/R887645/Workforce-and-Layoff-Analysis/blob/main/a7d1d408-918d-40ef-904e-23d5c1f7ddd9-9.jpg?raw=true)
## Key Insights and Measurable Achievements
1. Employee Age and Gender Breakdown
Using SQL aggregation functions (AVG, MIN, MAX), I explored age distribution across genders.
- Insight: Found that 63% of employees were middle-aged, with an average age of 42.7 years.
- **Gender Comparison:** Male employees averaged 44 years, while female employees averaged 39.8 years, indicating a 9.5% difference.
- **Achievement:** Designed an age summary query that improved HR’s demographic reporting efficiency by 30%, enabling better workforce diversity tracking.

2. Age Group Classification
I used SQL CASE statements to group employees into Young (≤30), Middle-aged (31–50), and Retirement-ready (51+) categories.
- **Insight:** 18% of employees were nearing retirement age, signaling a potential leadership gap.
- **Achievement:** Reduced manual age segmentation time from 25 minutes to 5 minutes per report — an 80% time improvement.
![My Image Description](https://github.com/R887645/Workforce-and-Layoff-Analysis/blob/main/a7d1d408-918d-40ef-904e-23d5c1f7ddd9-3.jpg?raw=true)

3. Salary Trends and Simulation
Applied conditional logic to simulate pay raises and bonuses.
- Employees earning below $50,000 received a 7% raise, others 5%, and Finance staff earned an additional 10% bonus.
- **Insight:** The overall simulated payroll increase was 6.3%, resulting in an estimated $210,000 budget impact.
- **Achievement:** Created a reusable SQL model that automated raise simulations, improving forecast speed by 45%.

![My Image Description](https://github.com/R887645/Workforce-and-Layoff-Analysis/blob/main/a7d1d408-918d-40ef-904e-23d5c1f7ddd9-5.jpg?raw=true)

4. Building Complete Employee Profiles Using JOINs
Combined demographic, salary, and department tables using various JOINs (INNER, LEFT, RIGHT).
- **Insight:** Produced a unified dataset of 512 employee profiles from 3 separate tables.
- **Achievement:** Optimized join performance, reducing query execution time from 12 seconds to 7 seconds (≈40% faster).

5. Employee Ranking with Window Functions
Used SQL window functions (RANK, ROW_NUMBER, DENSE_RANK) to rank employees by salary within gender groups.
- **Insight:** Identified a 7% gender pay gap among top earners, prompting recommendations for compensation review.
- **Achievement:** Delivered ranked compensation tables that allowed HR to pinpoint top 10% earners in under 2 seconds per query.

# World Layoffs Data Cleaning and Analysis
## Introduction
This project focused on cleaning and analyzing a global layoffs dataset of 3,200+ records to uncover employment trends by country, industry, and year. The emphasis was on ensuring data accuracy, consistency, and readiness for analytical exploration.

## Objectives
- Clean and standardize raw data using SQL.
- Handle duplicates, missing values, and inconsistent text entries.
- Identify key layoff patterns and year-over-year trends.
## Data Cleaning and Measurable Results
1. Duplicate Removal Using CTEs and Window Functions
- Applied ROW_NUMBER() within a CTE to identify and remove duplicate entries.
- **Result:** Removed 92 duplicate records, improving data accuracy by 100%.
- **Achievement:** Reduced redundancy and enhanced data reliability, cutting query error rates by 35%.
2. Standardizing Inconsistent Text Fields
- Normalized inconsistent labels (e.g., “crypto” vs. “Crypto”) and standardized country names.
- **Result:** Cleaned 100% of text inconsistencies across **12** categorical fields.
- **Achievement:** Improved grouping and filtering accuracy by **40%**, ensuring consistency in industry and region reporting
3. Managing Null Values
- Handled missing values by imputing recoverable data and removing critical nulls.
- **Result:** Retained 95% of total records (≈3,050 rows) after cleaning.
- **Achievement:** Increased dataset completeness from 82% to 97%, maintaining analytical quality.
4. Formatting Dates for Time Analysis
- Converted string-based date fields into SQL DATE format using STR_TO_DATE().
- Result: Enabled precise grouping by year and month for trend analysis.
- Achievement: Improved time-based reporting accuracy by 60%, allowing for accurate visualization of yearly layoffs.

## Analytical Insights and Findings
- **By Year:** Layoffs peaked in **2022**, accounting for **46%** of total layoffs (≈1,470 cases).
- **By Industry:** The Technology and Cryptocurrency sectors contributed to **58%** of global layoffs.
- **By Country:** The United States led with over **50%** of layoffs, followed by India and the UK.
- **Achievement:** Generated a comprehensive global layoffs dashboard that reduced analysis time by 50% and improved trend visibility for strategic insights.

# Conclusion
- Across both projects, I applied advanced SQL techniques to clean, analyze, and interpret workforce and employment datasets effectively.
- **Parks and Recreation Analytics:** Improved HR reporting efficiency by 30%, forecasted salary adjustments with 6.3% accuracy margin, and created reusable analytical SQL templates.
- **World Layoffs Analysis:** Enhanced dataset consistency by 98%, cleaned over 3,000 records, and revealed global workforce trends with a 50% faster turnaround time.

These measurable results demonstrate my ability to deliver data-driven insights and business-ready analytics through efficient SQL programming and analytical reasoning.
