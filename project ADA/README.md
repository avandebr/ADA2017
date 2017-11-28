# A food social media  

# Abstract
A 150 word description of the project idea, goals, dataset used. What story you would like to tell and why? What's the motivation behind your project?

The 21st century represents one of the most progressive eras in human history. We are busier than ever, and yet the flood of information we need to process daily does not seem to be stopping any soon. We live fast and we eat fast. In order to balance out their habits, people often decide on following a healthy diet, or taking up sports. But these decisions are hard to follow as they also require time to invest in a good and structured menu that would satisfy daily nutritional needs of an active adult person. Our goal is to create a food recommendation system that would allow users to generate daily menu with three healthy meals according to their preferences. On the other hand, even though food is essential for our well being, it has also become a passion for many users worldwide. Therefore, we also aim to allow users who share the same taste for food and passion for cooking to connect over the stories of their recipes.

# Research questions
- How can we connect people from different cultures using food ? 
- Can we discover similarities between different cuisines?
- Can we recommend recipes that are both healthy and enjoyable for the user?
- Can we guess the favorite ingredients of our users?
- Can we discover clusters of users that enjoy the same cuisine?
- Can we find users that have similar taste based on recipes?

# Dataset
For the main goal of our project we have collected data about different recipes, using the https://www.yummly.com/ website. We obtained data on recipes, users and ratings, so we can build user based recommendations system. Each recipe has data about ingredients, nutrition, number of servings, preparation time, cuisine and course to which the recipe belongs. Data on users provides information on user location which can be used for visualizing different users around the world that enjoy the same cuisine. here what looks like a recipe data example:

{
  "totalTime": "30 Min",
  "ingredientLines": [
    "1/4 cup fresh orange juice",
    "2 tablespoons extra-virgin olive oil",
    "2 teaspoons red-wine vinegar",
    "1 1/2 teaspoons Dijon mustard",
    "Coarse salt and ground pepper",
    "Coarse salt and ground pepper",
    "1 medium bunch beets with greens (about 1 pound)",
    "2 medium carrots, grated"
  ],
  "attribution": {
    "url": "http://www.yummly.com/recipe/Beet-and-Carrot-Slaw-Martha-Stewart",
    "text": "Beet and Carrot Slaw recipes: information powered by Yummly",
    "html": "<a href='http://www.yummly.com/recipe/Beet-and-Carrot-Slaw-Martha-Stewart'>Beet and Carrot Slaw recipe</a> information powered by <img alt='Yummly' src='http://static.yummly.com/api-logo.png'/>",
    "logo": "http://static.yummly.com/api-logo.png"
  },
  "name": "Beet and Carrot Slaw",
  "prepTimeInSeconds": 900,
  "rating": 4,
  "numberOfServings": 4,
  "yield": "servings: 4",
  "nutritionEstimates": [
    {
      "attribute": "FAT_KCAL",
      "unit": {
        "name": "calorie",
        "decimal": true,
        "abbreviation": "kcal",
        "pluralAbbreviation": "kcal",
        "plural": "calories",
        "id": "fea252f8-9888-4365-b005-e2c63ed3a776"
      },
      "description": null,
      "value": 60.0
    },
    "attributes": {
    "cuisine": [
      "American"
    ],
    "course": [
      "Salads"
    ]
  },
  "id": "Beet-and-Carrot-Slaw-Martha-Stewart",
  "prepTime": "15 Min",
  "totalTimeInSeconds": 1800
}

# A list of internal milestones up until project milestone 3
- Improve the recommandation system 
- Add some new features to the recommender (i.e. like make recommendations based on some constraints chosen by the user)
- Introduce interactivity to allow the user to select those constraints depending on what he wants (i.e. type of cuisine, nutrition constraints, type of meal, etc). This also implies to find a good way to define healthness.

# Questions for TAs
How to deal with the very sparsity of our data ?
In fact in average each user has only rated 1.2 recipes, so make recommendations based on this is quite hard and most of all not really accurate. 


