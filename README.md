# Project-BreastCancer
“Survival Analytics: Charting the Course of Breast Cancer Progression”

Team Members:
•	Stephanie Santiago 
•	Molleigh Hughes 
•	Hidy Vengalil 
•	Tasha Christensen 
•	Miranda Smith

Project Overview

 Breast Cancer is the second most common cancer in women in the United States. It is about 30% of the new cancers detected in women each year. According to the American Cancer Society, the average risk for a woman in the United States to develop breast cancer is 13%. (The American Cancer Society, 2023)
 
In this project, we are looking into various factors in women’s lives that can affect the outcomes of breast cancer. The relationships we selected to study are:

1.	Is menopausal status correlated with recurrence?
2.	Is there any correlation between menopause and the number of months survived?
3.	Is menopausal status correlated with metastasis?
4.	Is marital status related to the number of months survived after diagnosis?
5.	Are positive nodes correlated to months survived?

Data Sources

1.	https://www.kaggle.com/datasets/reihanenamdari/breast-cancer

2.	https://datahub.io/machine-learning/breast-cancer#resource-breast-cancer

Data Preparation

	Two datasets were selected from the data sources as .csv files. Python Pandas is used to clean up the datasets. The columns of interest were selected from both data frames and concatenated together.


Analysis and Visualizations

	The tools used are, Pandas, SciPy, NumPy, Matplotlib, and Seaborn
Menopause VS Recurrence

![image](https://github.com/molleighH/Project-BreastCancer-/assets/25726099/f119ae9d-0c9a-41c0-98a5-f8a67acb7b51)
	
 
The Chi-square test of independence was conducted to determine if there was a significant association between the two categorical variables. The Chi-square statistic (52.869106353110936) is relatively large, indicating a greater deviation from what we would expect if the variables were independent.
The p-value (3.308410754095632e-12) is extremely small, suggesting a significant association between the two variables.

Menopause Vs Survival

 ![image](https://github.com/molleighH/Project-BreastCancer-/assets/25726099/c92150c8-64ab-4ead-a701-16a921bfabfe)

 
![image](https://github.com/molleighH/Project-BreastCancer-/assets/25726099/35c6d43c-4c40-4bd0-8abe-d5b02da5c9e6)

 
Menopause Vs Metastasis


![image](https://github.com/molleighH/Project-BreastCancer-/assets/25726099/7cf15c5f-94fd-4f5e-a503-1c22ba687585)

 
Marital Status Vs Survival 

![image](https://github.com/molleighH/Project-BreastCancer-/assets/25726099/4c5adaaa-ff81-43e9-b105-a5edcfa0eadd)


Positive Nodes Vs Survival

![image](https://github.com/molleighH/Project-BreastCancer-/assets/25726099/f5242d8d-0dc8-4ef0-a42b-2a6d4bcf670b)

Age, Survival, and Recurrence

![image](https://github.com/molleighH/Project-BreastCancer-/assets/25726099/320ab864-5f6e-4206-9582-b6ec2634be30)


Conclusion


Our analysis shows that the months of survival after diagnosis are related to marital status and the presence of lymph node involvement. The metastasis to remote areas is correlated to menopausal status and age. We need to explore more datasets to get more conclusive results

References

1. The American Cancer Society. (2023, Sept 14). How common is breast cancer? Retrieved from https://www.cancer.org/: https://www.cancer.org/cancer/types/breast-cancer/about/how-common-is-breast-cancer.html
2. Surveillance, Epidemiology, and End Results; (SEER)., N. C. I. (2019, January 18). SEER Breast Cancer Data. Retrieved October 2023,.
3. Zwitter , M., & Soklic, M. (2014, April 6). Breast Cancer Data. Retrieved October 2023,. 



