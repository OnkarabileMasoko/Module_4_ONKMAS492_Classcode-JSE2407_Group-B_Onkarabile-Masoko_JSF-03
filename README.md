Table of Contents
Introduction
Technologies Used
Features
Setup Instructions
Usage
Contributing
Introduction
Welcome to the E-Commerce Website project, SwiftCart! This project is a fully functional e-commerce web application that allows users to browse products, view detailed information about each product, filter and sort products, and maintain their preferences during navigation. All data is fetched from a fake API to ensure dynamic content.

Technologies Used
Frontend Framework: Vue 3
State Management: Vuex
Routing: Vue Router
Styling: Tailwind CSS
Build Tool: Vite
API Calls: Fetch API
Features
Product Grid: Displays a grid of product cards.
Product Details: Users can view detailed information about each product.
Category Filtering: Filter products by category.
Price Sorting: Sort products by price (low to high, high to low).
Persisted State: Filters and sorting preferences are maintained during navigation.
Loading States: Visual indicators during data fetching.
Setup Instructions
Follow these steps to set up and run the project locally:

Clone the Repository:

git clone https:https://github.com/OnkarabileMasoko/Module_4_ONKMAS492_Classcode-JSE2407_Group-B_Onkarabile-Masoko_JSF-03.git

npm install
Configure Environment Variables:

Create a .env file in the root directory.
Add the necessary environment variables. For example:
VITE_API_BASE_URL=https://fakestoreapi.com
Run the Development Server:

npm run dev
Build for Production:

npm run build
Usage
Once the development server is running, you can access the application at your local host

Browsing Products
Grid View: Browse a grid of products with images, titles, prices, and categories.
Detailed View: Click on a product to view detailed information, including a description, ratings, and reviews.
Filtering and Sorting
Filter by Category: Use the category filter to view products from specific categories.
Sort by Price: Use the sorting options to sort products by price, either from low to high or high to low.
Reset Filters and Sorting: Easily reset to default view without refreshing the page.
Loading States
Initial Load: A loading indicator is shown while initial data is being fetched.
Data Fetching: A loading indicator is shown when new data is being fetched.
