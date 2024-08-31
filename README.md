# MealMate API: Personalized Recipe and Meal Planning

Welcome to **MealMate API: Personalized Recipe and Meal Planning**! This project is a simple web application that suggests recipes from around the world using TheMealDB API. The app is built using HTML, CSS, and JavaScript, and it allows users to explore a variety of recipes, view ingredients, and get cooking instructions.

## Features

- **Random Recipe Suggestion:** Get a random recipe suggestion from TheMealDB.
- **Search Recipes by Name:** Find recipes by entering a keyword or dish name.
- **View Recipe Details:** See detailed information about the recipe, including ingredients, instructions, and a link to a YouTube video tutorial.
- **Filter by Category/Area:** Explore recipes based on categories like "Dessert," "Seafood," or specific cuisines like "Italian" or "Mexican."

## Technologies Used

- **HTML:** Structure of the web pages.
- **CSS:** Styling and layout of the app.
- **JavaScript:** Functionality, API calls, and dynamic content loading.
- **TheMealDB API:** Fetching recipe data from TheMealDB's open API.

## Getting Started

### Prerequisites

To run this project, you need a modern web browser that supports HTML5, CSS3, and JavaScript.

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/MealMate-API-Recipe-Suggestion-App.git
   cd MealMate-API-Recipe-Suggestion-App


Open the Project: Simply open the index.html file in your web browser.
API Key (Optional for Additional Features)
For basic functionality, you can use the free version of TheMealDB API. If you want access to additional features, consider subscribing and obtaining an API key.

Free API Endpoint: https://www.themealdb.com/api/json/v1/1/
Subscriber API Endpoint: https://www.themealdb.com/api/json/v2/{API_KEY}/
Replace {API_KEY} with your personal API key.

Usage
Random Recipe Suggestion:

Click on the "Get Random Recipe" button to fetch and display a random recipe.
Search for Recipes:

Enter a recipe name or keyword in the search bar and click "Search" to find matching recipes.
Filter by Category or Area:

Use the filter dropdowns to explore recipes by specific categories or regional cuisines.
View Recipe Details:

Click on a recipe to view its details, including a list of ingredients, cooking instructions, and a YouTube tutorial link.
Project Structure

MealMate-API-Recipe-Suggestion-App/
│
├── index.html          # The main HTML file
├── style.css           # The main CSS file
├── script.js           # JavaScript file for API calls and interactivity
└── README.md           # This README file

Example API Calls
Random Recipe:
fetch('https://www.themealdb.com/api/json/v1/1/random.php')
  .then(response => response.json())
  .then(data => console.log(data));

Search by Name:
fetch('https://www.themealdb.com/api/json/v1/1/search.php?s=Arrabiata')
  .then(response => response.json())
  .then(data => console.log(data));
