# PySpark Transformation Practice (Movies Dataset)

This repository contains my practice work using **PySpark** on a Movies dataset.  
I solved different transformation problems using **Databricks Community Edition (Free)**.

## Dataset
Movies dataset (Kaggle).

## Environment
- Databricks Free Community Edition  
- PySpark  

## Practice Questions
Below are the problems I solved:

1. Clean the Runtime column so it only contains numbers in minutes.  
2. Break down the Genre column so each genre has its own row, even if a movie has multiple genres.  
3. Standardize the Released_Year column by removing extra characters or missing values.  
4. Convert the Gross column into numeric format and handle missing or corrupted values.  
5. Find the top 5 highest-grossing movies for each year.  
6. Find the top 3 movies by rating in each genre.  
7. List the movies with the highest and lowest votes for every year.  
8. Create a new column that shows the difference between Meta_score and IMDB_Rating.  
9. Identify movies that have the same Series_Title but were released in different years.  
10. Find all movies where IMDB_Rating is above the overall average rating.  
11. Find directors who have directed more than 5 movies and their average gross earnings.  
12. Identify which actor (from Star1–Star4) appears most often in the dataset.  
13. Create a column that categorizes movies as Short (<90 min), Medium (90–150 min), or Long (>150 min).  
14. For each year, find the total votes cast for all movies released in that year.  
15. Create a column that calculates revenue per vote (Gross / No_of_votes).  
16. For each genre, find the oldest and newest movie released.  
17. Find the top 10 movies with the highest ratio of Gross to Runtime.  
18. List all movies where at least two of the same stars appear together in another movie.  
19. Find movies that rank in the top 10 for both IMDB_Rating and Meta_score.  
20. Identify movies where the overview length (number of words) is unusually short or long.  
21. Group movies by certificate and compute their average runtime and average rating.  
22. List all movies that earned more than the average gross of their release year.  
23. Create a running ranking of movies based on votes within each year.  
24. Identify the most common certificate for movies in each genre.  
25. Find the director who has the highest-grossing movie in each decade.  
26. Combine the four star columns into a single array column of actors.  
27. Find movies where the same actor worked with the same director more than once.  
28. Rank genres based on total votes received across all movies.  
29. Find movies released in consecutive years by the same director.  

---
