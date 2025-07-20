This is a simple product filtering web application built using HTML, CSS, and JavaScript. It displays a list of products and allows users to filter them based on multiple criteria.

🔧 Features:
 Filter by Price Range

Users can enter minimum and maximum prices to view products within that range.

Filter by Brand

A dropdown menu allows selection of brands like Nike, Adidas, Puma, etc.

 Filter by Category

Another dropdown allows filtering by categories such as Shoes, Clothing, Accessories.

 Search by Product Name

A text input lets users search for products by typing part of the name (e.g., "nike").

 Apply Filters Button

When clicked, it filters and displays only the matching products.

 Reset Filters Button

Clears all filters and shows the full product list again.

 Technologies Used:
HTML – for creating the structure (input fields, buttons, and list).

CSS – for basic styling (spacing, fonts).

JavaScript – for filtering logic and dynamic display of results.

 How It Works:
A predefined list of product objects is stored in JavaScript.

The filterProducts() function checks user inputs and filters products based on:

Price range

Selected brand

Selected category

Name match (case-insensitive)

The filtered products are shown dynamically in a list.

If no product matches, a message like “No products match your filters” is displayed.

 Example Products:
Nike Shoes – ₹2500

Adidas T-shirt – ₹1500

Puma Shorts – ₹1000

Nike Cap – ₹700

Reebok Shoes – ₹2200

