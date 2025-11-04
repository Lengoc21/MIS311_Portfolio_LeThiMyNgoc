**1. Data Overview**

The **“Student Performance”** dataset contains information about students’ demographics and academic results in Math, Reading, and Writing. After cleaning, it includes **199 rows and 8 columns**. The data aims to analyze how parental education and demographic factors affect students’ academic performance.

<img width="1934" height="766" alt="image" src="https://github.com/user-attachments/assets/68a6ddd4-d459-41b6-8c4e-c9e1a4987fb3" />
I used a Pivot Table to identify the most frequent value, which is "associate's degree", and filled the missing values accordingly.
<img width="678" height="292" alt="image" src="https://github.com/user-attachments/assets/f0244015-5949-4777-a587-8bed5d06bffc" />

<img width="272" height="121" alt="image" src="https://github.com/user-attachments/assets/2a1b016e-3fd5-4e55-8857-95335c9797ed" />

I found 3 duplicated value and then removed.
 
![33E2DD24-D8B9-4526-875F-5991AE28F11A](https://github.com/user-attachments/assets/fd758aa1-eab1-4dcc-b97e-ea847877d34a) 

After cleaning, the dataset contains 199 rows and 8 columns.
All missing and duplicate values were successfully handled, resulting in a clean, consistent, and ready-to-analyze dataset.


**2. Data Cleaning**
<img width="1906" height="766" alt="image" src="https://github.com/user-attachments/assets/5344bc2a-e09b-48b3-8432-c563fe4ee999" />

<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/440e4eff-9e5a-4059-9a56-7afbec7aa140" />

Using PivotTable, I observed that **“associate’s degree”** had the highest frequency among all education levels.

**3.Descriptive Analytics**
 
  **- Key Insight 1**: The chart shows how the total student performance varies according to the parents’ education level.
Students whose parents have an associate’s degree or some college education achieved the highest total scores **(around 3350 and 3317)**, suggesting that higher parental education may lead to better academic support and performance.

   <img width="591" height="355" alt="image" src="https://github.com/user-attachments/assets/eb19cdde-21bd-4a0a-827a-4a8740c707fe" />
   

**-Key Insight 2**: The chart illustrates the relationship between **parental education level and students’ total subject scores**, **filtered by race/ethnicity**.  Students whose parents completed some college or an associate’s degree tend to achieve **the highest total scores across math, reading, and writing**.  This suggests that higher parental education is positively linked to better student performance, regardless of ethnic background.	


<img width="1202" height="464" alt="image" src="https://github.com/user-attachments/assets/5a473e3f-dbcc-4dda-b46c-b82a2f518d5f" />



**Summary:** 
In this analysis, I used **Pivot Tables and Slicers** to summarise and visualise the data effectively. The Pivot Table helped identify trends and compare total scores across different education levels, while the Slicer allowed for dynamic filtering by race/ethnicity. These techniques provided **a clear and interactive overview of the relationships within the dataset.**



