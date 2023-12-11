# Introduction

For my individual project, I have decided to select a dataset containing the top 50 best selling video games of all time. I have had a high interest in video games for many years so I am interested to see if there is any correlations between the best selling games that I may be unaware about. 

# My Research Questions

1. Are there certain publishers that frequently make best selling video games?
2. What is the correlation between ranking and sales for the top 50 video games? Is there a certain number that game sales struggle to overcome?
3. Is there any correlation between game sales and how recently the game released?

# Dataset

My dataset comes from kaggle and is found in the data folder. The characteristics of the data set are as follows:

- Rank
- Title
- Sales
- Series
- Platform(s)
- Initial Release Date
- Developer(s)
- Publisher(s)
- Release Year*
  
*To properly get the code to work, I had to add an extra column to the dataset that specific the release year. Initial Release date has day, month, and year. I did not find release day or month relevant in my anaylsis.

# Methods

Tools:

- Numpy for numerical operations
- Pandas to load, clean, and analyze the dataset
- Matplotlib to create visualizations
- Scikit learn for linear regression

# Results

Question 1: Are there certain publishers that frequently make best selling video games?

![image](https://github.com/jonahfiske/DS_JF_Individual_project_video_game_sales/assets/97976436/54e2672d-f346-4024-be73-fbafa019c39a)

I used a simple counting method to count all unique instances of a publisher and then total how many times that specific publisher was named.

Question 2: What is the correlation between ranking and sales for the top 50 video games?

![image](https://github.com/jonahfiske/DS_JF_Individual_project_video_game_sales/assets/97976436/ecffa4cb-6950-41cd-b154-5c993a006cbb)

Used and trained a model to show linear regression.

![image](https://github.com/jonahfiske/DS_JF_Individual_project_video_game_sales/assets/97976436/02cb1a71-a73b-4a9a-bcff-7ae8a22ba12a)

This image shows all data points.

Question 3: Is there any correlation between game sales and how recently the game released?

![image](https://github.com/jonahfiske/DS_JF_Individual_project_video_game_sales/assets/97976436/1fedd1ba-081e-4106-b61f-e0df9aec632a)

Used and trained a model to show linear regression.

![image](https://github.com/jonahfiske/DS_JF_Individual_project_video_game_sales/assets/97976436/dd436338-f979-4927-9444-b121921bf50a)

This image shows all data points.

# Discussion 

The findings in question 1 came as a shock to me. Nintendo dominated the list have 22 unique games in the top 50 highest selling of all time with 2nd place only have 5 unique entries. Not to mention that 3rd place was another company owned by Nintendo. The data shows that every 1 of 2 games in the top 50 games is going to be a Nintendo game meaning that Nintendo games have a far higher likelyhood of making it into the top 50.

For question 2, I was surprised to find out that the data points started to stagnate at the end proving the existence of the second half of the question. It looks like 30,000,000 dollars in sales is the amount that popular games have a hard time overcoming.

The results from question 3 do not seem very conclusive when looking at all the data points. While there is a general upwards trend, it is probably skewed due to outliers. Without the outliers the upwards trend would be very slim and could just be from the fact that there are more people in the world now than there was 40 years ago. Another possibility is that gaming is more of a popular interest than it was 20 years ago. Yet again, there are still older games that outperform newer ones.

Other research tends to show the same trend I am seeing. Nintendo dominates the list, a lot of games in the latter half of the list are really close to each other in sales, and there has never been a golden age where games during a specifc time period performed better. For the future, it would be worth expanding the data so it includes the genre of game and maybe that has a correlation with how well a video game performs. The age rating of games is also something to be looked into in the future as well.
