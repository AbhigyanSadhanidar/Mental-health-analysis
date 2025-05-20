MENTAL HEALTH ANALYSIS 
This project analyzes a mental health dataset to explore relationships between various social, personal, and psychological factors and their impact on the likelihood of seeking treatment. It includes steps from data access and cleaning to visualizations and statistical insights.

Accessing the Data~
The dataset used is: Mental Health Dataset.csv

Data Cleaning & Organization~
1.Missing Value Treatment: Filled missing values in self_employed with 'No'.
Verified and removed duplicate entries.

#Standardization:
Converted inconsistent cases in Gender, Country, and Occupation to title case.
Cleaned care_options values ('Not sure' → 'Unsure').
Converted Days_Indoors into an ordered categorical variable for meaningful sorting.

Exploratory Data Analysis (EDA)~
#Key Observations:
1. Occupation Distribution: Most respondents come from IT and healthcare.
2. Country Distribution: Majority are from the US and India.
3. Treatment Rates: A significant portion of respondents have sought treatment.
4. Days Indoors: Many reported being indoors for more than 2 months.
5. Grouped Insights: Treatment vs Occupation: Varies by profession — IT workers had higher treatment rates.
6. Mental Health History by Country: Varies across regions, e.g., higher in Western countries.


Visual Representations~
1. Univariate & Bivariate Plots: 
![alt text](image.png)
2. Bar Chart: Occupation and country distribution.
![alt text](image-8.png)
3. Pie Chart: Treatment status.
![alt text](image-7.png)
4. Categorical Plots: Family history, stress levels, and mood swings vs treatment status.
![alt text](image-9.png)
5. Stacked Bars: Treatment rates by occupation.
![alt text](image-10.png)
6. Count Plots: Days Indoors vs treatment.
![alt text](image-11.png)


Conclusion & Impact Analysis~
Key Findings:
1. Family History and Growing Stress are statistically significant predictors of whether a person seeks mental health treatment.
2. Prolonged Days Indoors (especially >2 months) correlate with higher treatment-seeking behavior.
3. Professions and countries influence treatment trends.
4. Coping struggles and social weaknesses show strong associations with mental health history and treatment.

Real-World Impact~
1. Understanding these patterns helps:
2. Workplace wellness programs focus efforts based on occupation.
3. Policy makers recognize stress and isolation as major mental health risk factors.
4. Awareness campaigns be targeted for groups with historically lower treatment-seeking behavior.
