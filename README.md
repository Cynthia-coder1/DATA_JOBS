# DATA_JOBS

## TABLE OF CONTENTS
- [PROJECT OVERVIEW](#project-overview)
- [EXPLORATORY DATA ANALYSIS](#exploratory-data-analysis)
- [RECOMMENDATIONS](#recommendations)

### PROJECT OVERVIEW
This data analysis provides insight into data-jobs over the past few years. By analyzing the data, we gain deeper understanding of the most demanding Data-Jobs .

### DATA SOURCE 
The dataset used for this analysis is 'Data-Jobs.xlsx' file which contains detailed information about data-jobs.

  ### TOOLS
- SQL - Utilized SQL for data Querying and Manipulation.
- POWERBI - Used POWERBI to create Interactive Visualization.

### DATA CLEANING/PREPARATION
In the data preparation phase , I performed the following tasks :
1. Data Handling and Inspection.
2. Checking for missing values.
3. Data Cleaning and Formatting.

### EXPLORATORY DATA ANALYSIS
EDA involved exploring the data to answer questions like :
- Which job-category has the highest number of employee and which has the least number of employee.
- Which work-setting has more employee.


### DATA ANALYSIS
Includes some intersting codes/features worked with

```SQL
SELECT JOB_TITLE,COUNT(JOB_TITLE) AS JOB_COUNT
FROM JOBS_IN_DATA
GROUP BY JOB_TITLE
```

```SQL
ALTER TABLE JOBS_IN_DATA
ADD JOBS_COUNT VARCHAR (50)
```
### RESULTS/FINDINGS
The analysis results are summarized as follows :
- Data science and Research has the highest number of Employee while Cloud and Database has the least.
- More Employee worked 'In-person'

### RECOMMENDATIONS
Based on the analysis,I recommend the following actions :
- Other Employment-Type should be explored other than Full_Time.
- Entry-Level should be given more opportunity to showcase their skills in the Industry.

