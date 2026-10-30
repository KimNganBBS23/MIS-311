# MIS-311

# 1. Data Overview

The Student Performance dataset contains some information related to students' demographic characteristics, their parents' education levels and their academic performance. Before data cleaning, the dataset had totally 202 rows and 8 columns[cite: 2].

To be more specific, the dataset includes information about students' gender, race/ethnicity, Parental Level of Education, scores in Math, Reading and Writing. Besides, it also has students' total scores and average scores across the three subjects. These data provide more particular to examine students' academic performance and identify patterns in their results[cite: 2].

The purpose of this analysis is to summarize the main characteristics of students' academic performance through using descriptive statistics and identify two key insights that may help explain differences in students' results[cite: 2].

# 2. Data Cleaning

## 2.1. Missing Values

The dataset was checked for missing or blank values across Gender, Race/Ethnicity, Parental Level of Education, Math Score, Reading Score, Writing Score, Total Score and Average Score. The initial dataset contained 7 missing values. Among them, three missing values were found in Parental Level of Education, while four remaining missing values were identified in Average scores[cite: 2].

For Parental Level of Education, the missing values were replaced with "unknown" to retain the observations for further analysis[cite: 2].

And then, the missing average scores were recalculated using the available scores from Math, Reading, and Writing[cite: 2].

## 2.2. Duplicate Rows

The dataset was also checked for duplicate rows across all variables. Three duplicate records were identified in the original dataset. Specifically, three pairs of identical rows were found at Excel rows 12 and 14, 56 and 57, and 65 and 66. One copy from each pair was removed to avoid redundant records. As a result, the dataset was reduced from 202 to 199 records while retaining all 8 original columns[cite: 2].

# 3. Descriptive Statistics

Descriptive statistics were used to summarize students' academic performance in Mathematics, Reading, and Writing. The mean, median, minimum, and maximum were examined to understand the main characteristics of students' scores. The analysis was conducted using the cleaned dataset containing 199 records[cite: 3].

![Descriptive Statistics Table](images/Descriptive%20Statistics.png)

## 3.1. Average Scores Across Subjects

![Average Score by Subject](images/Average%20Scores%20Across%20Subjects.png)

Students achieved the highest average score in Reading (67.63), followed by Writing (66.37) and Math (64.22). The relatively lower average score in Math suggests that additional support in this subject may be worth considering to help improve students' academic performance[cite: 3].

## 3.2. Variation in Academic Performance Across Three Subjects

![Score Range Across Three Subjects](images/Variation%20in%20Academic%20Performance%20Across%20Three%20Subjects.png)

Math had the widest score range (100), compared with Writing (90) and Reading (83). This indicates a greater gap between the highest and lowest Mathematics scores. The result highlights the difference in students' performance at the two extremes and provides another perspective on academic performance beyond average scores[cite: 4].

