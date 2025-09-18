## Week 16th Sep 2025 - All Recipes Data
This week's data is about global recipes, collected from [AllRecipes.com](https://www.allrecipes.com/).   
The data contains recipe names with their authors, and comprehensive recipe information such as ingredients, nutritional facts (calories, fat, carbs, protein), cooking times (preparation and cooking), ratings, review metadata,
and a subset of that data mapped to countries or regions where is the cuisine is from.

Thanks to Brian Mubia for curating this dataset.
Further information and detailed specification can be found on the official [Tidy Tuesday](https://github.com/rfordatascience/tidytuesday/tree/main/data/2025/2025-09-16) repo.

Background: Allrecipes.com, Inc., founded in 1997, is a food-focused online social networking service headquartered in Seattle, Washington. [Source: Wikipedia]

#### The dataset contains 2 csv files: 
      - all_recipes.csv
      - cuisines.csv

'cuisines.csv' is a subset of 'all_recipes.csv' with all the columns and an additional column 'country' mapping the cuisine to its region/country.

  In this exploration, I have focused on looking at the countries/regions of some popular cuisines and recipes.
