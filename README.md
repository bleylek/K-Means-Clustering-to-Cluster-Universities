University Clustering Analysis

This repository contains a Jupyter notebook and dataset used to perform K-means clustering on university data. The goal of this project is to explore patterns and group similar universities together based on various features like student population, tuition cost, and academic performance metrics.

Files

K Means Clustering to Cluster Universities.ipynb: A Jupyter notebook that outlines the entire process of loading, analyzing, and clustering the university data using the K-means algorithm.
College_Data: A CSV file containing data about various universities, including applications, acceptance rates, enrollment numbers, percentage of students from top 10% and top 25% of their high school class, full-time undergraduates, part-time undergraduates, out-of-state tuition, room and board costs, book costs, personal spending, faculty credentials, student/faculty ratio, alumni donation rate, expenditure per student, and graduation rate.

Dataset Overview

The dataset includes the following columns:

- Private: Indicates if the university is private or public.
- Apps: Number of applications received.
- Accept: Number of applications accepted.
- Enroll: Number of new students enrolled.
- Top10perc: Percentage of students from the top 10% of their high school class.
- Top25perc: Percentage of students from the top 25% of their high school class.
- F.Undergrad: Number of full-time undergraduates.
- P.Undergrad: Number of part-time undergraduates.
- Outstate: Tuition for out-of-state students.
- Room.Board: Cost of room and board.
- Books: Estimated book costs.
- Personal: Estimated personal spending.
- PhD: Percentage of faculty with Ph.Ds.
- Terminal: Percentage of faculty with terminal degree.
- S.F.Ratio: Student/faculty ratio.
- perc.alumni: Percentage of alumni who donate.
- Expend: Instructional expenditure per student.
- Grad.Rate: Graduation rate.

Analysis

The notebook begins by loading the dataset and performing exploratory data analysis to understand the distribution and relationships of various features. Following this, the K-means clustering algorithm is applied to identify groups of universities with similar characteristics.
