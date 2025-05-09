# Recipe-App
🔧 Working of the Recipe App
  UI Setup with HTML & CSS

1.Create a simple layout with:

-A search input field

-A search button

-A container to display recipe results (image, title, ingredients, instructions)

2.API Integration with JavaScript

-Use fetch() or async/await to call a public recipe API (e.g., https://www.themealdb.com/api/json/v1/1/search.php?s=pasta)

-Trigger the API call when the user enters a dish name and clicks the search button

-Parsing and Displaying Data

3.On a successful API response:

-Extract key details: image, name, ingredients, instructions

-Dynamically generate and insert HTML into the page to show this data

-Error Handling

-If no dish is found, show a friendly message like “Recipe not found.”

-Handle network errors gracefully

✅ Steps Summary
1.Build UI – HTML structure + styled with CSS

2.Connect to API – Use JavaScript to call the recipe API

3.Show Results – Extract and display dish info

4.Handle Errors – Manage empty results and failed requests
