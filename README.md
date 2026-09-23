# Task 4: Data Storytelling & Statistical Validation

## ApexPlanet Data Analytics Internship

This repository contains my work for **Task 4 – Data Storytelling & Statistical Validation**, completed as part of the Data Analytics Internship at **ApexPlanet Software Pvt. Ltd.**

The objective of this task was to transform the analytical findings from the previous tasks into a clear business story and apply statistical hypothesis testing to validate a business question.

---

## Project Objective

The main objectives of Task 4 were to:

- Combine the findings from previous tasks into a clear data story
- Present important business KPIs and analytical insights
- Formulate a testable statistical hypothesis
- Perform an appropriate statistical test
- Interpret the p-value and confidence interval
- Translate statistical results into a business conclusion
- Develop a professional stakeholder presentation
- Provide practical business recommendations

---

## Project Files

This repository contains:

### `Task4_Statistical_Validation.ipynb`

Jupyter Notebook containing the statistical hypothesis test, calculations, visualizations, and interpretation.

### `Task4_Final_Presentation.pptx`

Final stakeholder presentation summarizing the complete analytical journey, major business findings, statistical validation, and recommendations.

### `Task4_Hypothesis_Testing_Summary.md`

Written summary of the hypothesis, statistical method, results, interpretation, and business conclusion.

### `README.md`

Documentation describing the Task 4 project, methodology, findings, and deliverables.

### `requirements.txt`

Python libraries required to run the statistical analysis notebook.

---

# Analysis Journey

Task 4 builds upon the work completed throughout the previous internship tasks.

## Task 1 – Data Immersion & Wrangling

The raw sales dataset was explored, cleaned, standardized, and transformed into an analysis-ready dataset.

The main activities included:

- Data profiling
- Missing-value analysis
- Duplicate detection
- Data-type validation
- Text standardization
- Date standardization
- Outlier analysis
- Feature engineering
- Data dictionary creation
- Clean dataset generation

---

## Task 2 – Exploratory Data Analysis & Business Intelligence

Exploratory Data Analysis and SQL were used to identify patterns, trends, relationships, and important business insights.

The analysis included:

- Descriptive statistics
- Univariate analysis
- SQL business queries
- Product analysis
- Customer analysis
- City analysis
- Monthly sales analysis
- Correlation analysis
- Business intelligence dashboarding

---

## Task 3 – Deep-Dive Analysis & Dashboarding

Core business KPIs were defined and customer segmentation was performed to better understand customer value and sales performance.

The deep-dive focused primarily on:

**Customer Segmentation & Sales Performance Analysis**

Customers were divided into:

- High Value
- Medium Value
- Low Value

Additional analysis was performed across:

- Products
- Product categories
- Cities
- Customers
- Monthly sales trends

---

## Task 4 – Data Storytelling & Statistical Validation

The findings from the previous analytical stages were combined into a structured business narrative.

A statistical hypothesis test was then performed to investigate whether an observed difference between customer groups was statistically significant.

---

# Core Business KPIs

The following KPIs summarize overall business performance:

| KPI | Result |
|---|---:|
| Total Revenue | ₹156,004,434.05 |
| Total Orders | 992 |
| Average Order Value | ₹157,262.53 |
| Unique Customers | 947 |
| Average Revenue per Customer | ₹164,735.41 |

These KPIs provide an overview of sales volume, customer activity, transaction value, and customer revenue contribution.

---

# Key Business Findings

## 1. Customer Segmentation

Customer segmentation was performed based on total customer revenue.

The **High Value** customer segment generated:

**₹81,219,576.59**

This represents approximately **52.1% of total business revenue**.

The High Value segment contained:

**246 unique customers**

This represents approximately **26% of the unique customer base**.

This indicates that a relatively small proportion of customers contributes a large share of total business revenue.

Therefore, retaining and developing relationships with High Value customers represents an important business opportunity.

---

## 2. Product Performance

The highest-performing product based on total revenue was:

**Laptop**

Total Laptop Revenue:

**₹30,215,273.25**

Laptop therefore represents an important contributor to overall sales performance.

---

## 3. Category Performance

The highest-performing product category was:

**Electronics**

Total Electronics Revenue:

**₹57,359,364.21**

The strong performance of the Electronics category indicates its importance within the overall product portfolio.

---

## 4. Geographic Performance

The highest-revenue city was:

**Patna**

Total Patna Revenue:

**₹22,064,469.50**

Other strong-performing cities included Mumbai and Kolkata.

This geographic analysis helps identify important markets and areas where sales activity is concentrated.

---

## 5. Monthly Sales Performance

The strongest month in the dataset was:

**March 2025**

Total Revenue:

**₹14,972,050.97**

October 2025 and June 2025 were also among the strongest months.

This demonstrates that revenue performance varied across different periods of the year.

---

# Statistical Hypothesis Testing

## Business Question

The statistical analysis investigated the following question:

**Does average Total Sales differ significantly between male and female groups?**

---

## Hypotheses

### Null Hypothesis (H₀)

The mean Total Sales is the same for male and female groups.

### Alternative Hypothesis (H₁)

The mean Total Sales differs between male and female groups.

---

# Statistical Method

The analysis used:

**Welch's Independent-Samples t-test**

Welch's t-test was used to compare the mean Total Sales between the two independent groups without requiring the assumption of equal population variances.

The significance level was set to:

**α = 0.05**

The decision rule was:

- If `p-value < 0.05` → Reject H₀
- If `p-value ≥ 0.05` → Fail to reject H₀

---

# Statistical Results

The hypothesis test produced:

**p-value = 0.6171**

The calculated 95% confidence interval for the difference between the group means was approximately:

**₹-10,094.84 to ₹17,001.40**

Since:

**0.6171 > 0.05**

the analysis **failed to reject the null hypothesis**.

---

# Statistical Interpretation

At the 5% significance level, the available data does not provide sufficient statistical evidence that average Total Sales differs between the male and female groups.

The 95% confidence interval for the difference in means also includes zero, which is consistent with the hypothesis-test result.

This result should **not** be interpreted as proving that the two groups are identical.

Instead, it means that the available data does not provide sufficient statistical evidence to conclude that their mean Total Sales are different.

---

# Business Recommendations

Based on the complete analysis, the following business actions can be considered.

## 1. Prioritize High-Value Customer Retention

High Value customers generated approximately **52.1% of total revenue** while representing only about **26% of unique customers**.

The business should therefore prioritize retaining these customers through:

- Loyalty programs
- Personalized offers
- Targeted communication
- Strong customer service
- Customer retention initiatives

---

## 2. Develop Medium-Value Customers

Medium Value customers represent an opportunity for additional growth.

Strategies such as:

- Targeted promotions
- Cross-selling
- Product recommendations
- Personalized offers

may help increase their future contribution.

---

## 3. Focus on High-Performing Products

Laptop was the highest-performing product based on total revenue.

The business should monitor:

- Inventory availability
- Product demand
- Promotional opportunities
- Sales performance

for high-performing products.

---

## 4. Monitor Important Product Categories

Electronics was the highest-revenue category.

The business should monitor category-level performance when planning:

- Inventory
- Marketing
- Product availability
- Promotional activities

---

## 5. Monitor Geographic Markets

Patna, Mumbai, and Kolkata were among the strongest markets based on revenue.

These locations can be monitored closely while lower-performing markets can be investigated for possible growth opportunities.

---

## 6. Monitor Monthly Sales Trends

March 2025 was the highest-performing month in the dataset.

Tracking monthly changes in revenue can help support:

- Inventory planning
- Marketing activities
- Promotional planning
- Business performance monitoring

---

## 7. Use Statistical Evidence in Customer Analysis

The hypothesis test did not find sufficient evidence of a statistically significant difference in average Total Sales between male and female groups.

Therefore, gender-based sales strategies should not be justified by this statistical test alone.

Other customer characteristics and behavioral variables should also be considered when developing customer strategies.

---

# Data Storytelling

The final presentation combines the complete analytical journey into a business-oriented story.

The overall workflow was:

**Raw Data**

↓

**Data Cleaning & Preparation**

↓

**Exploratory Data Analysis**

↓

**SQL & Business Intelligence**

↓

**KPI Analysis**

↓

**Customer Segmentation**

↓

**Dashboarding**

↓

**Statistical Hypothesis Testing**

↓

**Business Insights**

↓

**Business Recommendations**

This structure demonstrates how raw transactional data can be transformed into useful business information through a complete analytics workflow.

---

# Final Presentation

The final stakeholder presentation is available in:

`Task4_Final_Presentation.pptx`

The presentation covers:

- Business objective
- Analysis journey
- Core business KPIs
- Customer segmentation
- Product performance
- Category performance
- Geographic performance
- Key business findings
- Statistical hypothesis testing
- Statistical interpretation
- Business recommendations
- Final call to action

---

# Tools & Technologies

The following tools and technologies were used during this project:

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook
- Statistical Analysis
- Hypothesis Testing
- Data Visualization
- Microsoft PowerPoint / LibreOffice Impress
- Git
- GitHub

---

# Python Libraries

The main Python libraries used in the project were:

```text
pandas
numpy
matplotlib
scipy
openpyxl
jupyter
ipykernel
```

---

# Key Skills Demonstrated

This project demonstrates practical experience in:

### Data Analysis

- Data exploration
- Business-oriented analysis
- Analytical interpretation
- KPI evaluation

### Statistical Analysis

- Formulating null and alternative hypotheses
- Selecting an appropriate statistical test
- Welch's independent-samples t-test
- p-value interpretation
- Confidence interval interpretation
- Statistical decision-making
- Translating statistical results into business conclusions

### Business Analytics

- KPI analysis
- Customer segmentation
- Customer-value analysis
- Product performance analysis
- Category performance analysis
- Geographic analysis
- Monthly trend analysis

### Data Visualization

- Business charts
- KPI visualization
- Dashboard interpretation
- Presentation-ready visualizations

### Data Storytelling

- Transforming analytical findings into a structured narrative
- Presenting technical results in business-friendly language
- Connecting analysis with business objectives
- Communicating limitations appropriately

### Business Communication

- Stakeholder presentation
- Business recommendations
- Professional analytical reporting
- Communicating statistical findings clearly

### Technical Skills

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook
- Git
- GitHub

---

# Conclusion

Task 4 brought together the analytical work completed throughout the internship and transformed it into a structured, business-oriented data story.

The complete project progressed from raw data cleaning and exploratory analysis to SQL, business intelligence, KPI development, customer segmentation, dashboarding, statistical validation, and business recommendations.

The business generated total revenue of **₹156,004,434.05** from **992 unique orders** and **947 unique customers**, with an Average Order Value of **₹157,262.53**.

One of the most important findings from the customer segmentation analysis was that **High Value customers generated approximately 52.1% of total revenue while representing only about 26% of unique customers**.

This demonstrates the importance of identifying and retaining customers who make a disproportionately large contribution to overall business revenue.

The analysis also identified:

- **Laptop** as the highest-performing product with **₹30,215,273.25** in revenue.
- **Electronics** as the highest-performing category with **₹57,359,364.21** in revenue.
- **Patna** as the highest-revenue city with **₹22,064,469.50** in revenue.
- **March 2025** as the strongest month with **₹14,972,050.97** in revenue.

Statistical validation was then used to investigate whether average Total Sales differed between male and female groups.

Welch's independent-samples t-test produced a **p-value of 0.6171**.

Since the p-value was greater than the significance level of **0.05**, the analysis **failed to reject the null hypothesis**.

The 95% confidence interval for the difference between the group means was approximately **₹-10,094.84 to ₹17,001.40**, which includes zero and is consistent with the hypothesis-test result.

Therefore, the available data did not provide sufficient statistical evidence of a difference in average Total Sales between the male and female groups.

Overall, Task 4 demonstrates how descriptive analysis, customer segmentation, business intelligence, statistical testing, and data storytelling can work together to transform transaction-level data into meaningful business insights.

The project also highlights the importance of not only identifying patterns in data, but validating findings statistically, interpreting results carefully, communicating limitations, and translating analytical evidence into practical business recommendations.

---

# Author

**Soumyadeep Das**

Data Analytics Intern  
**ApexPlanet Software Pvt. Ltd.**
