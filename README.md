# recipe_site_traffic
Established in 2020 during the Covid Pandemic, Tasty Bytes initially began as a recipe search engine, assisting individuals in discovering creative ways to utilize the limited supplies available at home. Fast forward three years, and Tasty Bytes has evolved into a fully-fledged business.

## 🎯 Goals for this project
Currently, the team selects their preferred recipe from a collection to feature on the home page. It has been observed that when they highlight a popular recipe, traffic to the rest of the website increases by up to 40%. However, the challenge lies in determining how to identify whether a recipe will be popular. Given the direct correlation between website traffic and subscriptions, this is a crucial concern for the company.

The Product Manager at Tasty Bytes has explicitly requested the following:

🟢 Develop a predictive model to identify recipes likely to generate high traffic.

🟢 Achieve an 80% accuracy rate in correctly predicting high-traffic recipes

## 💾 The Dataset:
The TastyBytes Product Manager has supplied comprehensive data for each recipe, including an indication of whether high traffic was observed when the recipe was featured on the home page. The dataset encompasses the following variables:

recipe: Numeric, a unique identifier for each recipe. calories: Numeric, the calorie count. carbohydrate: Numeric, the amount of carbohydrates in grams. sugar: Numeric, the amount of sugar in grams. protein: Numeric, the amount of protein in grams. category: Character, denoting the type of recipe, categorized into one of ten possible groups: Lunch/Snacks Beverages Potato Vegetable Meat Chicken Pork Dessert Breakfast One Dish Meal servings: Numeric, indicating the number of servings for the recipe. high_traffic: Character, indicating whether the site experienced high traffic when the recipe was featured, marked as "High."

##4. 🚀Analysis plan
✅In the first step, we perfomed an Exploratory Data Analysis to uncover any valueble insights related to:

The interactions between the recipe characteristics. The interactions between all the characteristics of the recipe and the high traffic generated on the site when a particular recipe is displayed; ✅ Next, we also conducted statistical significance tests to explore the relationship between the variables:

First, we performed target-feature tests to determine whether there is a connection between the target feature, high_traffic, and the other recipe features. Second, we performed feature-feature tests to assess any relationships between the features themselves. ✅ We then put the two candidate models through a series of steps to fit and evaluate them, including:

We split the dataset into training and testing sets (80:20 ratio), stratifying by the class proportions of the target variable.

The categorical variable was encoding using one-hot technique, and, where necessary, all the input features were standardised by having a mean of 0 and standard deviation of 1.

We trained the two machine learning algorithms for this classification problem.

We measured the models performances using the accuracy, recall and precision.

We tuned the hyperparameters using 10-fold stratified cross-validation.

Finally, we assesed feature importances and made a final selection of the features.

The classifiers used are:

Logistic Regression KNN classification ✅ After this analysis, we provided some recommendations on how to increase the traffic on this site based on our results.
