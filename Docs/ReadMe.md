# Problem Overview

Netflix thrives on bridging the gap between individuals and the movies they adore. In order to assist customers in discovering those movies, they have crafted a top-notch movie recommendation system known as CinematchSM. The core function of Cinematch is to forecast a person's enjoyment of a movie based on their previous likes or dislikes of other movies. Netflix leverages these predictions to tailor movie recommendations according to each customer's distinct preferences. Although Cinematch has been performing admirably, there's always room for enhancement.

There exist numerous intriguing alternative methodologies to the functioning of Cinematch that Netflix hasn't explored yet. Some of these methodologies have been documented in scholarly articles, while others haven't. The curiosity lies in whether any of these alternative approaches can outperform Cinematch by delivering more accurate predictions. Candidly, discovering a significantly superior approach could potentially make a substantial impact on both the customers and the business.

# Objective
The objective of this project is to engineer a recommendation system #DataScience for Netflix.


# Motivation
Netflix has supplied a substantial amount of anonymized rating data, along with a benchmark for prediction accuracy that is 10% superior to what Cinematch can achieve on the identical training dataset. (Accuracy is gauged by how closely the predicted ratings of movies align with the subsequent actual ratings.)

## Project Overview
1. Forecast the rating that a user would assign to a movie that they have not yet rated.
2. Diminish the discrepancy between predicted and actual ratings (evaluated using RMSE and MAPE)."


# Project Steps:
1. Interpretability Aspect:
   - Incorporate a level of interpretability to understand the underlying patterns and behaviors driving the recommendations.
   
2. Machine Learning Challenge:
   - Formulate the recommendation problem as a machine learning task, identifying the appropriate algorithms and evaluation metrics to employ.
   
3. Data Handling:
   - Acquire, preprocess, and explore the data to ensure it's well-suited for building and evaluating the recommendation model.

# Data Files
- combined_data_1.txt
- combined_data_2.txt
- combined_data_3.txt
- combined_data_4.txt
- movie_titles.csv

The initial line of each file [combined_data_1.txt, combined_data_2.txt, combined_data_3.txt, combined_data_4.txt] showcases the movie id, followed by a colon. Every line thereafter in the file represents a rating from a customer along with the date, formatted as follows:

CustomerID,Rating,Date

MovieIDs are sequentially numbered from 1 to 17770. CustomerIDs span from 1 to 2649429, albeit with gaps, encompassing a total of 480189 users. Ratings are denoted on a five-star (integral) scale ranging from 1 to 5. Dates are formatted as YYYY-MM-DD.

# Translating the Real-World Problem to a Machine Learning Problem:
## Type of Machine Learning Problem:
- Given a specific movie and user, the task is to predict the rating that would be assigned by the user to the movie.
- This problem is fundamentally a Recommendation problem.
- It can also be perceived as a Regression problem.

# Performance Metrics:
- Mean Absolute Percentage Error (MAPE)
- Root Mean Square Error (RMSE)

# Machine Learning Objective and Constraints:
- The primary objective is to minimize the RMSE.
- Endeavor to offer some level of interpretability.

# Acknowledgement
B. Sivasubramanian (https://github.com/storieswithsiva)
