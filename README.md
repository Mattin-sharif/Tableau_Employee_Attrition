# Human Resource Attrition Analysis Report

![image](https://github.com/user-attachments/assets/ff5fffbd-638b-4df6-8148-4a8aba166cd1)

## Introduction / Background

### The Problem and Its Importance 

In a highly competitive pharmaceutical industry, being a key stakeholder, the company confronts an alarming issue of high attrition ratio affecting the competitive edge to the company. This pattern of high attrition rate, if left un-attended, will not only impact operations but will also impact long-term strategy. Addressing this issue is significant to retain institutional knowledge, and operational excellence (Chatzoudes and Chatzoglou, 2022).

**Literature-Based Support**

Staff turnover is researched in literature previously highlighting the complexity of the problem. Many researchers have pointed out the different causes of turnover from individual job satisfaction to the compensation of the broader cultural and market changing dynamics. This report will highlights the main issues to analyses with pre-existing HR theories and practices. According to  (Shet et al., 2021) identified certain aspects inducing the successful implementation of data analytics in human resource management, which are vital for practicing HR analytics within organization furthermore, (Raza et al., 2022) highlight the importance of improving factors like monthly income, hourly rate, job level, and age to overcome employee attrition.

**Analytical Approach and Challenges** 

To tackle this issue CRISP-DM methodology was incorporated with an exploratory data analysis by leveraging advance visualization tool to identify key areas leading to attrition and the potential solution based on demographic, behavioural and performance feature. The challenges revolve around the complexity of data and its interpretation for a human centric actionable insight alongside ethical data handling and reporting standards requirements.  

**Audience and Objectives** 
The primary audience of the attrition analysis will be the decision makers of the pharmaceutical company. For this specific audience, the report is attached to certain objectives:  
1.	To identify leading factors contributing to high attrition rate. 
2.	To translate data-driven insights into actionable insights, enabling strategic actions against potential turnover. 
3.	Proposing recommendation to retain existing skilled employees and highlight areas that focus on for future talent acquisition.
 
![image](https://github.com/user-attachments/assets/e8750d0e-3a2e-437f-b8cd-0edbdf8ac795)
 
Figure 1: Flow of the EDA analysis report to investigate Attritions

## Methodology

An exploratory data analysis (EDA) is executed using Tableau to drive actionable insights to investigate high attrition rate in the pharmaceutical company. The main focus is to leverage the visualization capabilities of tableau to uncover the trends, patterns and relationships in the data (Afzal et al., 2020)  

### Data quality and processing: 
The integrity of data analysis process depends on the quality of data (Zhu, 2022). The initial step of the EDA involving careful assessment of the dataset was employed to remove potential data quality issues resulting in the false interpretation of the data. Data was initially screened in Excel for any data anomalies and inconsistencies. With a total of 1467 observations with 35 variables including target variable. The issues in the dataset were in; department, age, total working years & date of birth. For instance, minimum age was 7, departments were divided with in same category, total working years were 94 and date of birth had a missing value.  
![image](https://github.com/user-attachments/assets/ce517602-aa41-4ab9-8255-fd1740105133)

Figure 2: Calculated field to fix outlier
![image](https://github.com/user-attachments/assets/4492ef5e-7073-4898-b049-eb0a1e3536d6)

Figure 3: Calculated field to merge department category
![image](https://github.com/user-attachments/assets/17a8920e-b762-4202-a6e2-0f554bc06ed2)

Figure 4: Calculated field to merge department category
![image](https://github.com/user-attachments/assets/9cb14dda-63df-422f-8964-c00a34845c49)
 
Figure 5: Calculated field to fix outlier

### Data transformation for visualizations:  

Data binning techniques were leveraged to convert the numerical data of Age into meaningful categorical data to see the trends within certain age brackets. Furthermore, to convert the numerical values in the data for categorical features, data categorization techniques were incorporated to make the data more intuitive and interpretable in the visual context. Multiple calculated fields were created in tableau. As exhibited in the figures in Appendix.

#### Exploratory data analysis:  

Furthermore, after optimizing the quality for accuracy and clarity, the focus shifted to exploratory data analysis using Tableau, chosen for its advance visualization capabilities and interactive dash-boarding functionality (Orji et al., 2022) to get in depth examination and interpretation of Human resource data related to employee attrition. 

The Exploratory data analysis process was conducted in a following way (Rao et al., 2021): 
1.	Attrition overview visualization:  
2.	Demographic analysis
3.	Satisfaction and compensation analysis
4.	Department and role-based analysis
5.	Training impact analysis

### Dashboard design for decision makers 
A strategic technique z-pattern layout ensuring the flow of information from left to right and top to the bottom was incorporated, making the flow of information in such a way that user can dive into the granularity of the data using interactive filter. This technique not only allowed stakeholders to engage dynamically but also to explore data in a user-friendly way to get insights about their area of interest. 
The outcome of exploratory data analysis using Advance visualization tool provides what segment of the employee but also provided insights into why, such as employee satisfaction score and the compensation patterns. 

### Findings
Total Employees, Attrition, and Attrition Rate Visualization: 
Text tables are used to highlight Total number of employees including, both current and former, total number of employees who are attritioned, along with the percentage of employees who are attritioned. Aggregated data shown of company overall figures without data slicing and filters for data represented numerically. Three different calculated fields were created (Khan, 2021). 

![image](https://github.com/user-attachments/assets/ca7a9a69-9889-4040-864e-8c10f0f49867)

Figure 6: Important KPI’s

The company has a total employee count of 1467 employees. Among them 19.15% got attritioned indicating one in five employees leaving the company making a significant challenge for the company which requires strategic actions.
Satisfaction analysis 
Average Job Satisfaction Score/ Average Environment Satisfaction Score/ Average Relationship satisfaction Score: 
![image](https://github.com/user-attachments/assets/43fabd04-04f6-4b7b-8c59-788d63567a61)
 
Figure 7: Average Job Satisfaction Score – former vs current employees.
![image](https://github.com/user-attachments/assets/ec3259b4-b636-490c-8f2a-40ef8cf9ea59)

Figure 8: Average Job Satisfaction Score – former vs current employees.
![image](https://github.com/user-attachments/assets/c61fc889-546d-48c0-afce-3083371bf99d)

Figure 9: Average Job Satisfaction Score – former vs current employees.


Bar charts were used to illustrate the average job satisfaction score, average environment satisfaction score and average relationship satisfaction score between current and former employees based on attrition column.
Average scores are colour coded and labelled differently based on attrition to easily identify current (green) and former employees (grey). Two different calculated fields are made for each visualization based on the Attrition category and then aggregated the measure on average value. 
The visualization shows that current employees have an average job satisfaction score of 2.7, slightly higher than the employee who left with an average 2.5. Similarly, like job satisfaction, the current average value of environmental satisfaction is 2.7 which is again slightly higher than the former employee value of 2.5. These trends highlight the importance of these KPI’s while formulating retention strategies (Bakker & Demerouti, 2021).

**Compensation analysis:** 

Average Monthly Salary and Average salary Hike Visualization: 
![image](https://github.com/user-attachments/assets/bf3b2415-888c-47ed-961e-0ea9d3919f70)
 
Figure 10: Average Monthly salary – former vs current employees.
![image](https://github.com/user-attachments/assets/98e69652-4675-4bd9-b3a1-6cdad4d7fdd3)
 
Figure 11: Average Salary Hike– former vs current employees.

In the satisfaction analysis, the chart exhibits a noticeable difference between the average salary of the current and former employee, with current employee earning an average of $6835 compared to $5154 for former employee putting compensation as a main driver of high attrition rate in the company. Whereas average salary hike values for the former (15.12%) and current employee (15.23%) is the same making it not a standalone factor leading to attrition. Based on the compensation metrics it is clear that competitive compensation can lead to lower attrition furthermore supported by the findings of (Chatzoudes and Chatzoglou, 2022).
  
**Department and role-based analysis:** 
![image](https://github.com/user-attachments/assets/0b4e6752-7bc6-407e-9dec-979c101f98c2)

Figure 12: Department and role-based analysis

A table to investigate the distribution of attritions across different departments and more specifically job roles within the departments. Departments and job roles are used as labels and attrition column is used for applying the filter to include only the attritions from the employee data. 
The visualizations exhibit the highest attrition in the sales executives (101) from the sales department followed by lab technicians (62) in R&D department. This will assist the managers in identifying targeted retention strategies. 

**Training impact analysis:** 
The trend line it investigates the relationship of number of training session attended by an employee last year by their attritions. Data was segmented on training sessions and points were marked properly across the line. The trend line shows a decrease in attrition with an increasing number of training sessions. This highlights the importance of professional development to decrease attrition rate among employees (Murugan et al., 2011).  
  
**Demographic analysis:** 
Attrition by Gender Visualization: 
![image](https://github.com/user-attachments/assets/e374bc2a-424e-4251-b7c6-c3610aeb8556)

Figure 13: Attrition by Gender Visualization

Pie chart was used to represent both genders. Overall, more male (172) Attrition compared to female (109). It should be investigated further to see if the proportion of males is higher in the company. 
Age Group Attrition Visualization: 
![image](https://github.com/user-attachments/assets/2ae6c254-6ce2-4db3-8030-89611765f0ac)

Figure 14: Age Group Attrition Visualization

The bar chart was used to effectively differentiate between Attrition counts across different age groups based on the calculated field for data transformation. Employees were segmented into age brackets. Findings demonstrate that the majority of attrition is occurring in the 26-35 yeas age bracket making this age bracket at high risk of Attrition. There is a significant decrease in Attrition as age bracket progresses which may indicate that young people are more inclined to leaving for their rapid career progression or higher education.  
  
Attrition Based on Income Visualization: 
![image](https://github.com/user-attachments/assets/89a9d7bb-e95b-4ebd-8c78-93a2df4364a4)

Figure 15: Attrition Based on Income Visualization

Income brackets serve as the slicing criteria for this bar chart to effectively differentiate between the numbers of employees leaving at different income levels. Attrition numbers by income bracket help in analysing the influence of pay scales on employee Attrition. The visualization demonstrates a significant and high attrition number is lower income category (2k-4k) with 61 attritions. Followed by a decreasing trend moving up the income bracket. So company needs to revise their compensation structure to stay competitive in the market (Murugan et al., 2011).
  
Attrition Based on Commute Distance Visualization: 
![image](https://github.com/user-attachments/assets/685028d7-0dc4-4830-b915-33bb7fff3614)
 
Figure 16: Attrition Based on Commute Distance Visualization

The attrition numbers are categorized by commute distance and visualized by bar charts. There was a high attrition rate among employees having less compute distance (0-5 miles), with 103 leaving the company and similar trend seen in people having high commute distance (20 miles above), with 64 attritions.  
  

Impact of Travel on Attrition Visualization:
![image](https://github.com/user-attachments/assets/29cf43c9-b8a3-4093-bd19-17a7238a39d7)
  
Figure 17: Impact of Travel on Attrition Visualization

The bar graph shows how the employees who rarely travel have a significant and high Attrition count of 189 employees in comparison to the employees who travel frequently, indicating a decreased level of engagement in employees who rarely travel. Furthermore, backed by (KM, 2020)
   

## Dashboard:   

### Dashboard Design Explanation: 
![image](https://github.com/user-attachments/assets/e8b016d2-ead0-4a5e-8811-817b30f1aa83)

Figure 18: Human resource Attrition analysis - Dashboard 

Dashboard displays the leading information starting from the top. The key metrics regarding the total attritions, and attrition rate at the top convey the severity of the issue and set the stage for further analysis. 
Stakeholders are engaged throughout and given a big picture around the problem and then drilling down further based on the interactive filters according to demographic, behavioural, performance metrics to get actionable insights regarding human resource attrition data. 
Overall, the charts and figures are arranged in a logical format. The dashboard also identifies the potential solution to overcome high attrition rate based on the trend in the training sessions in the last year (Afzal et al., 2021). 
  
## Summary of Findings: 

Overall, there is a minimal difference between the satisfaction scores, current employees having slightly higher average satisfaction score, suggesting additional support to other factors to determine high Attrition rate. Compensation Analysis appears to be a significant driving factor, with a clear difference between the current and former employees of 30%.  
The demographic of Attrition suggests the younger people and male specifically are at elevated risk of leaving the company. Moreover, the department sections pinpoint the specific areas experiencing higher employee attrition, where targeted interventions and custom strategies can be most effective.  

Furthermore, training analysis identified the general trend in the data forming a relationship with Attrition, suggesting that greater number of training secessions can lead to lower attrition rate. 
This multifaceted analysis provided a broader image of attrition problems, equipping the leadership at the company with actionable insights to formulate their employee retention strategies. 

## Recommendations and Discussion
### Recommendations:
To Reduce Attrition: 
1.	Competitive Compensation Structure: The data presented a significant and clear difference in the average monthly salary of current and former employees making it a crucial factor leading to Attrition. It is suggested that the company revise their compensation packages for specific job roles. It was established through research papers as well that compensation is critical for employee retention (Raza et al., 2022). 
2.	Targeted Retention Strategies: With higher Attrition in certain departments, job roles, and age groups, targeted employee retentions strategies should be employed which evolves around career development, job specific benefits, and reward systems to meet the competitive industry standards and to increase the overall job satisfaction score (Raza et al., 2022).
3.	Training and Development: seeing an unusual increase in attritions who received moderate amount of training it can be established that the company should evaluate their training program to check the effectiveness of their training program. To better meet the needs and expectations of their current employee but overall, more training sessions can lead to more engagement, hence lower Attrition (Km, 2020)
4.	Travel Opportunities: formulate strategies for employee rotation to other job roles to create more opportunities for business travel for the people who rarely travel. This will reduce their job satisfaction and overall, less desire to explore new job opportunities. 
  
### To Follow Up Work: 
In future advance statistical techniques can be employed to build a predictive model to predict employee risk of getting attritioned so effective talent acquisition strategies can be employed promptly to replace the resource based on their predicted risk score  (Raza et al., 2022). This advanced attrition predictive model can leverage advanced data analytics and supervised machine learning techniques.  
However, figuring out the accuracy of the model will be a challenge as accuracy depends on the quality and completeness of the data, this can lead to misinterpretation of data. 




## Reference

Afzal, S., C Rajmohan, Manish Kesarwani, Mehta, S. and Patel, H. (2021). Data Readiness Report. doi:https://doi.org/10.1109/smds53860.2021.00016.
Bakker, A.B. and Demerouti, E. (2017). Job Demands–resources theory: Taking Stock and Looking forward. Journal of Occupational Health Psychology, 22(3), pp.273–285.
Chatzoudes, D. and Chatzoglou, P. (2022). Factors Affecting Employee Retention: Proposing an Original Conceptual Framework. International Journal of Economics and Business Administration, X(Issue 1), pp.49–76. doi:https://doi.org/10.35808/ijeba/748.
Jain, P.K., Jain, M. and Pamula, R. (2020). Explaining and predicting employees’ attrition: a machine learning approach. SN Applied Sciences, 2(4). doi:https://doi.org/10.1007/s42452-020-2519-4.
Khan, U. (2021). Effect of Employee Retention on Organizational Performance. Journal of Entrepreneurship, Management, and Innovation, 2(1), pp.52–66. doi:https://doi.org/10.52633/jemi.v2i1.47.
KM, R.K. (2020). Employee Retention – Challenges and Realities Faced by Corporates for New Recruits as well as Existing Employees. Ushus Journal of Business Management, 19(4), pp.75–93. doi:https://doi.org/10.12725/ujbm.53.6.
Murugan, Dr.J.S.V. and Murugan, S.B. (2011). Employee Attrition And Retention In Private Insurance Sector A HRM Challenge. Indian Journal of Applied Research, 1(5), pp.115–117. doi:https://doi.org/10.15373/2249555x/feb2012/43.
Orji, Ugochukwu.E., Ukwandu, E., Obianuju, Ezugwu.A., Ezema, Modesta.E., Ugwuishiwu, Chikaodili.H. and Egbugha, Malachi.C. (2022). Visual Exploratory Data Analysis of the Covid-19 Pandemic in Nigeria: Two Years after the Outbreak. [online] IEEE Xplore. doi:https://doi.org/10.1109/ITED56637.2022.10051529.
Rao, A.S., Vardhan, B.V. and Shaik, H. (2021). Role of Exploratory Data Analysis in Data Science. [online] IEEE Xplore. doi:https://doi.org/10.1109/ICCES51350.2021.9488986.
Raza, A., Munir, K., Almutairi, M., Younas, F. and Fareed, M.M.S. (2022). Predicting Employee Attrition Using Machine Learning Approaches. Applied Sciences, 12(13), p.6424. doi:https://doi.org/10.3390/app12136424.
Shet, Sateesh.V., Poddar, T., Wamba Samuel, F. and Dwivedi, Y.K. (2021). Examining the determinants of successful adoption of data analytics in human resource management – A framework for implications. Journal of Business Research, 131, pp.311–326. doi:https://doi.org/10.1016/j.jbusres.2021.03.054.
Zhang, X., Pablos, P.O. de and Zhou, Z. (2013). Effect of knowledge sharing visibility on incentive-based relationship in Electronic Knowledge Management Systems: An empirical investigation. Computers in Human Behavior, 29(2), pp.307–313. doi:https://doi.org/10.1016/j.chb.2012.01.029.
Zhu, H. (2022). A Course on Data Quality in Analytics. Proceedings of the 53rd ACM Technical Symposium on Computer Science Education V. 2. doi:https://doi.org/10.1145/3478432.3499100.

