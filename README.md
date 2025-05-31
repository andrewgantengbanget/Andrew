# Student Habits and Academic Performance

This project analyzes how student lifestyle habits relate to academic success and mental health. It is based on a dataset of 1,000 students from Kaggle:  
https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance

The dataset includes features such as study time, sleep, exercise, diet quality, part-time job status, social media use, and final exam scores. The goal is to explore which habits are associated with better academic performance and mental well-being.

## Data Preprocessing

The dataset was clean and complete, requiring minimal preprocessing. The `diet_quality` column was mapped to numerical values (`Poor`: 1, `Fair`: 2, `Good`: 3) to allow for correlation analysis. A correlation matrix was then generated using relevant numerical features. No rows were dropped as there were no missing values.

## Objective 1: Relationship Between Study Time and Academic Performance

A scatter plot with a regression line was used to examine the relationship between study hours per day and exam scores. The correlation coefficient was calculated to be **0.83**, indicating a strong positive relationship. This means that students who spend more time studying tend to perform better on exams, suggesting that consistent study habits are a key driver of academic success.

## Objective 2: Lifestyle Habits and Mental Health

The analysis looked at how variables like sleep hours, exercise frequency, diet quality, and social media use correlate with mental health ratings. Results showed extremely weak correlations across all variables. Diet quality had the highest correlation at just **0.027**, and others, such as exercise and sleep, had negligible or slightly negative values. This suggests that mental health may be influenced more by factors not captured in the dataset, such as stress, personal relationships, or academic pressure.

## Objective 3: Academic Performance by Job and Activities

Students were grouped based on part-time job status and participation in extracurricular activities. Average exam scores were then compared. Students without part-time jobs slightly outperformed those with jobs, especially when also involved in extracurriculars. For example, students with no job and with extracurriculars averaged **70.14**, while those with both job and extracurriculars averaged **67.58**. While the differences are small, the trend suggests that managing both commitments might reduce study time, slightly affecting performance.

## Summary

The project shows that:
- Study time has a strong positive impact on academic performance.
- Lifestyle habits like sleep and diet do not significantly correlate with mental health in this dataset.
- Balancing a job and extracurriculars may slightly reduce exam performance.

These findings may help students and educators better understand how daily habits affect learning and well-being.

