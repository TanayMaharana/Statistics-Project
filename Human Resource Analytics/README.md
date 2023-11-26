# Employee Satisfaction and Productivity Analysis

## Overview

This repository contains the code and documentation for a comprehensive analysis of HR data aimed at enhancing employee satisfaction and productivity within a multinational corporation (MNC). The project focuses on exploring patterns, extremes, and associations within the collected data, leveraging probability and distribution concepts.

## Problem Statement

The primary goal is to optimize the working environment and productivity of employees. The analysis involves understanding outliers, patterns, and correlations within the dataset to formulate strategies for improvement.

## Dataset Overview

1. **EmployeeId:** System-generated employee ID.
2. **Hrs:** Average daily working hours per employee.
3. **Rating:** Organization-assigned rating with four categories: Outstanding, Excellent, Satisfactory, and Unsatisfactory.
4. **EmployeeSatisfaction:** Employee-rated satisfaction score out of 10.

## Observations

### Working Hours Distribution

- The majority of working hours cluster around 8 to 14, indicating outliers on the higher and lower sides.

### Rating Distribution

- Excellent ratings have the highest frequency, followed by outstanding and unsatisfactory.
- Most employees give satisfaction scores of 6 or 7, suggesting a need to improve work-life balance.

### Employee Satisfaction vs. Working Hours

- Employees tend to give higher satisfaction scores with lower average working hours.

## Probability Distribution and Confidence Level

- Probability that 2 out of 10 employees are rated outstanding: 18.18%
- Probability that at least 3 out of 10 employees are rated outstanding: 6.11%
- Probability that at least 7 out of 10 employees are rated outstanding or excellent: 95.08%
- Probability that none out of 10 employees are rated unsatisfactory: 38.71%
- Probability that an employee will provide less than 9 hours of service: 10.81%
- Probability that an employee will provide 11 to 14 hours of service: 0.48%
- Confidence interval for 95% confidence level for Hrs variable: (10.98, 11.28)

## Insights and Recommendation:
### 1. High Working Hours: Throughout the analysis, we have witnessed that the organisation somehow rewards the employees working for a high number of hours within the organisation. This could actually be counterproductive as the employees tend to slow and sluggish after a certain point. 

#### Here the recommendation that could be provided is estimating the hours of service that will be needed in a project beforehand for proper allocation of manpower. Higher working hours should be reserved for extreme deadlines or until and unless absolutely necessary.
![output](https://github.com/TanayMaharana/Statistics-Project/assets/105596561/a1698c9a-66d1-473d-bcc4-e2eb4f228a95)


### 2. Work life balance: In our analysis, we have also witnessed that the highest frequency is for Excellent rating where employees tend to provide a good amount of working hours in general. This management should focus on better work life balance which means these scales should be estimated based on individual performances and their impact on the project rather than on the number of hours of service provided. 
![output2](https://github.com/TanayMaharana/Statistics-Project/assets/105596561/c0739a3d-8ee1-4d7d-837f-7fd204021990)


#### By addressing these challenges and capitalising on the insights drawn from the data, we believe the organisation can significantly enhance the experience of the employees working within the organisation which should be reflected in their satisfaction score down the road.

## Conclusion

By leveraging insights from this analysis, the organization can develop targeted strategies to create a more employee-friendly environment, thereby improving satisfaction and productivity.
