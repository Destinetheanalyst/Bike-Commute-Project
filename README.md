# Bike Commuters Analysis

### Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning/preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#results/findings)
- [Limitations](#limitations)

### Project Overview
---

This data analysis project aim to provide insights into the Bike usage analysis of a company over staffs. By analyzing various aspects of the analysis , we seek to identify trends, make data driven recommendations, and gain a deeper understanding of the of the company's performance.

![Bike Sales](https://github.com/user-attachments/assets/684acab9-abc4-41fc-a53d-2e066cc1afc2)


### Data Source
---

Bike Analysis: The primary dataset used for this analysis is the "Bike Commuters.xlsx" file, containig detailed information about each staff in the company.

### Tools
---

- Excel - Data Cleaning
 -[Download_here](https://microsoft.com)
- Excel - Data Analysis
- PowerBi - Data visualization and Creating Reports
 -[Download_here](https://microsoft.com/powerbi)


 ### Data Cleaning/Preparation
 ---

  In the initial data preparation phase, we performed the following tasks:
  1. Data loading and inspection.
  2. Handling missing values.
  3. Data cleaning and formatting.

  
  ### Exploratory Data Analysis
  ---

  EDA involved exploring the Bike Commuters data to answer key questions, such as:

  - Total number of commuters?
  - Total number of bike commuters?
  - Total Male and Female and their percentage?
  - Average Age of staff?
  - Total number of bike commuters by Continent?
  - Total number of bike commuters by commuter distance?

### Data Analysis
---

Include some functions used to analyze 
```Excel
=TRIM(F2:F1001)

=COUNT(A2:A1001)

=IF(L2>54,"Old Age",IF(L2>=31,"Middle Age",IF(L2<31,"Adolecent","Invalid")))
```

### Results/Findings
---

The analysis results are summarized as follows:
1. The total number of commuters.
2. The total number of Male and Female commuters and their percentages.
3. The Average of commuters.
4. The total number of commuters per continent.
5. The total number of commuters per Age range.
6. The total number of commuters per commuter distance.

### Limitations
---

I had to remove all zero values from age column because they would affected the accuracy of my conclusions from the analysis.

