# Recommendations_with_IBM

### Still under construction

## Introduction
For this project you will be looking at the interactions that users have with articles on the IBM Watson Studio platform. 

Though the above dashboard is just showing the newest articles, you could imagine having a recommendation board available here that shows the articles that are most pertinent to a specific user.

In order to determine which articles to show to each user, you will be performing a study of the data available on the IBM Watson Studio platform. You can create your own account to become a part of their community, and get a better understanding of their data by creating an account on the platform here.

The Project contains the following parts:

* I. Exploratory Data Analysis

Before making recommendations of any kind, you will need to explore the data you are working with for the project. Dive in to see what you can find. There are some basic, required questions to be answered about the data you are working with throughout the rest of the notebook. Use this space to explore, before you dive into the details of your recommendation system in the later sections.

* II. Rank Based Recommendations

To get started in building recommendations, find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

* III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. 

* IV. Content Based Recommendations (Under Construction)

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system. 

* V. Matrix Factorization

Finally, a machine learning approach to building recommendations. Using the user-item interactions, build out a matrix decomposition. Using the decomposition, you will get an idea of how well you can predict new articles an individual might interact with (spoiler alert - it isn't great). 

* VI. Extras & Concluding (Under Construction)

Flask App.
