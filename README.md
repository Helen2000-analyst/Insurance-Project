# Port-Harcourt Insurance Company Project

### Table of Contents.

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning or Preparation](#data-cleaning-or-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results or Findings](#results-or-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

  
### Project Overview

This data analysis project aim to provide insight into the insurance of the people over the past years. It is also to find out if medical claims made by people who smoke are greater than those who don’t,to examine that the BMI of females are different from that of males,to find out if smoking habit of customers depend on their region, to examine if BMI of women with no children, one child, and two children are the same.

### Data Sources 

Insurance data: The primary dataset used for this analysis is the "Insrance-company-data.csv" containing detailed information about each persons in the company insurace file.

### Tools

- Excel- Data Cleaning
    - [Download here](https://microsoft.com)
- SQL- Data Analysis
    - [Download here](https://MySQLWorkbench.com)
- Power Bi- Creating Reports
    - [Download here](https://powerBI.com)
 
  ### Data Cleaning or Preparation

  in the initial data preparation phase, the following task was performed:
  1. Data Loading and inspections.
  2. Handling Missing Values.
  3. Data Cleaning and Formatting.
 
### Exploratory Data Analysis

EDA involves exploring the insurance data to answer ket questions, such as:

- What is the sum total of the children in the regions?
- What is the sum of regions available in the insurance company?
- What are the sum of smokers and non-smokers in the regions?
- What is sum of BMI of children in the regions?

### Data Analysis

```sql
SELECT * FROM table1
WHERE cond = 2;
```

### Results or Findings

These data analysis results show several key insights: 
1. Sex Distribution: These dataset has a balanced representation of females and males.
2. Age Distribution: A higher percentage of populations falls within the younger age groups (20–30 and 30-40) with the noticeable difference in the older  age group (40-50 and 50-60).
3. Charges Distribution: The majority of charges are relatively low with a few instances of very high charges, indicating a right-skewed distribution.
4. BMI Distribution: Most individuals have BMI values near the average, with an higher portion of the population having a BMI close to 30.
5. Number of Children and Smokers Status: There are no much difference in the number of children between smokers and non smokers.
6. Relationship Between BMI and  Charges: There are positive correlation between BMI and Medical charges, with higher BMI values generally associated with higher Medical charges while lower BMI values generally associated with lower medical charges.
7. Regional Differences in Smoking Behavior: The Southeast region has a higher proportion of non-smokers while the Southwest region has a lowest proportion of non-smokers.
8. Sex and BMI: Both males and females have similar average.
9. Age, BMI and Children: Medical charges tends to increase with age, there is variability in charges based on children.
10. Sex, Charges, and Smokers Status: Smokers tends to have a higher charges compared to smokers regardless of the sex.

### Recommendations

Based on these analysis, here are some recommendations:
  - Healthcare Planning: Focus on preventive healthcare measures for younger age groups, as they constitute the majority of the population.
  - BMI Management: Implementing programs to manage BMI and promote healthy lifestyle, as higher BMI values are associated with higher medical charges.
  - Gender-Specific Health Programs: Ensure that health programs are inclusive and address the needs of both females and males equally. 
  - Family Health Programs: Consider family health programs that address the needs of individuals with varying numbers of children.
  - Targeted interventions: Develop targeted interventions for regions with higher smoking rates such as the southwest region.


### Limitations

I had to remove all zero values from the age and bmi columns because they would have affected the accuracy of my conclusions from the analysis. There are still a few outliers but even after the omissions even then we can still see that there is a positive correlations between both age of the children and bmi charges of the children.




