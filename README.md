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
