# 📻 LastFM Dataset Analysis with PySpark

In this project, I have worked with the PySpark module in Python, utilizing the Google Colab environment to apply queries to a dataset related to the Last.fm website. Last.fm is an online music service where users can listen to different songs. 

The dataset consists of two CSV files, namely "listening.csv" (1GB containing 13,758,905 rows) and "genre.csv" (3 MB containing 138,415 rows).

## Analysis Steps

1. **Data Import with PySpark**: The first step of the analysis involved importing the dataset using PySpark. This included loading the "listening.csv" and "genre.csv" files into PySpark DataFrames.

2. **Data Cleaning**: In this step, data cleaning operations were performed to ensure the data quality. This included removing any null values and eliminating unnecessary columns that were not relevant to the analysis.

3. **Dataset Exploration**: This step focused on filtering, grouping, and aggregating the data to gain insights into popular artists, albums, and the best genres. 

4. **User Listening Habits**: For each user in the dataset, this step involved determining their preferred genre and the most frequently played songs. By grouping the data by user and analyzing their listening history, the analysis aimed to understand user preferences and identify the genres and songs that were most popular among the users.

5. **Bar Chart of Genre Preferences**: To visualize the genre preferences of users, this step utilized the Matplotlib library to create a bar chart. By aggregating the data by genre and counting the occurrences, the analysis generated a bar chart that represented the distribution of genre preferences among the users.

These steps provide a high-level overview of the main analysis performed on the LastFM dataset. Each step aimed to gain insights into the dataset, understand user behavior, and visualize the findings using the Matplotlib library.


## Key Learnings

Through this project, I have gained hands-on experience in working with PySpark, performing data analysis, leveraging distributed computing, and visualizing query results using Matplotlib. This project has allowed me to showcase my skills in data analysis, distributed computing with PySpark, and data visualization, while exploring a real-world dataset within the context of Last.fm.
