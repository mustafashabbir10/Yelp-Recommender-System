# Yelp Recommender System

In this work, I have created a recommendation system for restaurants using collaborative filtering (CF). The general structure of a recommendation system is that there are users and there are items. Users express explicit or implicit preferences towards certain items. CF thus relies on users' past behavior.

The outline of this work is as follows:

Create a database of item-item similarities. Use this to implement a neighborhood-based CF recommender that can answer simple questions like "give me more restaurants like this one". This part of the work assumes that the similaties calculated make good "global recommendations".

In the second part, I go one step further and attempt to predict the rating that a user will give an item they have not seen before. This requires that we find the restaurants that this user would rate as similar (not just those which are globally similar).

In the third part, I implement a factor-based CF recommender using a Bayesian model. While quite a bit more complex, this allows us to pool information both about similar users and about similar restaurants.
