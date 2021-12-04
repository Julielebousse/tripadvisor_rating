# What factors have an impact on TripAdvisor average rate for restaurants in France ?
Julie Le Bousse & Anh Nguyen
## Content
- [Description](https://github.com/anhfrenay/tripadvisor_rating/blob/main/README.md#description)
- [Dataset](https://github.com/anhfrenay/tripadvisor_rating/blob/main/README.md#dataset)
- [Workflow](https://github.com/anhfrenay/tripadvisor_rating/blob/main/README.md#workflow)
- [Insights](https://github.com/anhfrenay/tripadvisor_rating/blob/main/README.md#insights)
- [Delivrables](https://github.com/anhfrenay/tripadvisor_rating/blob/main/README.md#delivrables)

## Description
In this project, we were trying to understand which factors have an important influence on the average rate of restaurants on TripAdvisor.
The scope of our analysis:
- Country : France
- Factors chosen : region, price range, diet options (vegetarian, vegan and gluten free), type of cuisines, open days per week, number of reviews and reservation feature
- Types of cuisine : French, Italian, Chinese, Japanese & Fastfood


## Dataset 
We use a dataset found on Kaggle : [TripAdvisor European restaurants](https://www.kaggle.com/stefanoleone992/tripadvisor-european-restaurants)


## Workflow
Our project can be divided into different phases  :

**Phase 1** : Looking for a dataset
- Research on multiple open data website : Kaggle, Google dataset search, UCI Machine Learning Repository
- Look for a dataset with interesting topic


**Phase 2** : Define a problematic
- Get validated by the Lead Teacher
- Create the plan for our presentation (introduction, analysis at a macro level, analysis at a more detailed level,...)
- Split the taskload between team members

**Phase 3** : Cleaning the dataset

Our dataset is quite large with more than 1 million rows.
We decided to limit our scope of analysis to restaurants in France and chose some of the features that we think can have a big impact on the rate.

**Phase 4** : Visualizing the data
- Looking for correlation between our target variable (average rate) and the other variables for a macro analysis --> heat map
- Analysis at a more detailed level with different visualizations for each explicative variable 

**Phase 5** : Analyzing the visualiwations & providing insight

**Phase 6** :Working on our Github repository and presentation slides

## Insights
- In contrary to what we first thought, the price range doesn't have much impact on the average rating
- In general, French cuisine has better rate than other type of cuisines
- Fastfood restaurant has a larger scope of ratings (from 1 to 4.5) whereas French restaurants have more concentrate rate, especially more expensive restaurants
- Restaurants with special diet like vegetarian, vegan and gluten free have higher rate (no rate below 2)
- Happy customers are more likely to give rate and therefore there are more excellent rating than mediocre rating
- The more days a restaurant is opened, the more likely their rate is lower

## Delivrables
- [Presentation slides](https://docs.google.com/presentation/d/1F1Tc0VYJAZ6wa5WXom2XwlFsfIymruCJ/edit#slide=id.p8)
- [Github repository](https://github.com/anhfrenay/tripadvisor_rating)
- [Trello](https://trello.com/invite/b/BSkqX9UJ/bf8c6a34aad398a878b8ac634480d5c9/tripadvisoranalysis)
