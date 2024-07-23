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

This include some functions used to analyze 
```Excel
=TRIM(F2:F1001)

=COUNT(A2:A1001)

=IF(L2>54,"Old Age",IF(L2>=31,"Middle Age",IF(L2<31,"Adolecent","Invalid")))
```



### Results/Findings
---

The analysis results are summarized as follows:
1. The total number of commuters is 1000.
2. The total number off bike owners is 481, which makes up 48% of total commuters.
3. There are 753 cars owners
4. The total number of Male is 511, with 51%.
5. The total number of Female is 489, with 49%.
6. The Average Age of commuters is 44.
7. The total number of commuters per continent.
   - There are 508 bike commuters in North America,which makes of 50.8% of commuters.
   - There are 300 bike commuters in Europe, which makes up 30% of commmuters.
   - There are 192 bike commuters in Pacific, which makes up 19.2% of commuters.
8. The total number of bike owners per Age range.
  - The Middle age are the most bike owners. They have a total of 383 bikes.
  - The Old age has a total of 59 bikes.
  - The adolecent has a total of 39 bikes and they own the least amount of bikes.
   
9. The total number of bike owners per commuter distance.
 - Commuter that travel 0-1 miles have the most bikes. They have a total of 200 bikes, while commuters that travels 10+ have the least numberof bikes. They have a total of 33 bikes
    



### Limitations
---

I had to remove all zero values from age column because they would affected the accuracy of my conclusions from the analysis.

