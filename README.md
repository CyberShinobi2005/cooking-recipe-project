# Cook Recipe Project

This is a simple web-based cooking recipe application that allows users to browse, search, and filter meals by area and category. The app fetches meal data from the [TheMealDB API](https://www.themealdb.com/api.php) and displays meal details including ingredients, instructions, and video recipes.

## Features

- Display random meals on page load
- Search meals by name
- Filter meals by area (country)
- Filter meals by category (e.g., Seafood, Vegetarian, etc.)
- View detailed meal information with ingredients and instructions
- Favorite meals and manage favorite list


## How to Use

1. Open `index.html` in a modern web browser.
2. Use the search bar to find meals by name.
3. Click on "Filter Meals" to filter by area or category.
4. Click on a meal to view detailed information.
5. Use the heart icon to add or remove meals from your favorites.

## Project Structure

- `index.html` - Main HTML file for the app UI.
- `style.css` - Stylesheet for the app.
- `script.js` - JavaScript logic for fetching and displaying meals.
- `data.js` - (Not used for meals, contains unrelated data)
- `images/` - Contains category images used in the filter.

## Dependencies

- Uses [TheMealDB API](https://www.themealdb.com/api.php) for meal data.
- Uses Font Awesome for icons (loaded via CDN).

## Notes

- The app dynamically loads categories and areas from the API.
- The "Beef" category was removed by filtering it out in the category list in `script.js`.

## Team Members

This is a group project by the following team members:
- Mayank
- Krish
- Raviraj
- Puhumi Agarwal
- Ayush Raj Singh

## License

This project is open source and free to use.

