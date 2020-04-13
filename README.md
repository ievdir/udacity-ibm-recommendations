# udacity-ibm-recommendations

This is a project delivered to pass Udacity Data Science Nanodegree program. 

### Dataset
There are 2 datasets:

user-item-interactions.csv - users and their viewed articles ids.

articles_community.csv - article_id and its titles. 

### Required libraries
These libraries provided below was used to complete the project for the mentioned reasons:

pandas - data wrangling and preprocessing

numpy - operations calculations

matplotlib.pyplot - plot graphs inline

project_tests - test defined cases

pickle - read sparse matrix

seaborn - plot histograms

### Project compnents: 
#### I. Exploratory Data Analysis
Firstly read data and make aggregations to find out most popular articles, descriptive statistics: min, median, max, average. 

#### II. Rank Based Recommendations
In this section I calculated functions to find the most viewed articles while using function: get_top_articles and these articles ids. 

#### III. User-User Based Collaborative Filtering
In this section I used User based collaborative filtering, There I created user-item (article matrix). If user has interaction it is has value 1, otherwise 0. Also, there it is calculated similar users, these users viewed articles. Based on similar users experience, it is recommended to view article which was not originally seen by the user. 

#### V. Matrix Factorization
There I applied SVD method and evaluated how the model accuracy depends on the number of latent features. Due to very limited test sample and train sample size, it was difficult to make accurate and more recommendations.
