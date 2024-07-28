# Modern Furniture Shop

Welcome to the Modern Furniture Shop project! This repository contains the source code for the Modern Furniture Shop website, an online platform dedicated to offering a wide range of stylish and contemporary furniture.

👉 **You can take a look at the finished live project [here](https://furniture-modern-shop.netlify.app/).** 👈

# Shopping Cart Functionality

The shopping cart is a central feature of the Modern Furniture Shop website, offering the following capabilities:

- **Add Items**: Users can browse products and add desired items to their shopping cart. Each product page includes an "Add to Cart" button, allowing users to specify the quantity they wish to purchase.
- **View Cart**: Users can view the contents of their shopping cart at any time. The cart displays a summary of items, including product names, quantities, prices, and subtotal calculations.
- **Update Quantities**: Users can adjust the quantity of each item directly within the shopping cart. Changes to item quantities automatically update the cart total.
- **Remove Items**: Users can remove items from their shopping cart. Each item in the cart has a "Remove" button, allowing users to delete unwanted products.
- **Persist Cart**: The contents of the shopping cart are saved in local storage, ensuring that users' selections are preserved even if they navigate away from the page or close their browser.

# Technologies Used

This project leverages the following technologies:

- HTML5: For structuring the content and layout of the website
- CSS3: For styling the website, including layout, colors, and fonts
- JavaScript: For adding interactivity and enhancing user experience
- Netlify: For deployment and hosting of the website
- Git: For version control and collaboration
- Visual Studio Code: As the primary code editor for development

# JavaScript Concepts covered

**DOM Manipulation**

- document.querySelector() is used to select DOM elements by their class names
- insertAdjacentHTML() and appendChild() are used to insert HTML content and add new elements to the DOM

**Variables**

- const and let are used for declaring variables. const is used for variables that won't be reassigned, and let is used for those that might change

**Arrow Functions**

- Used in map() and event listeners for concise function expressions

**Classes**

- The code uses ES6 classes ('Products', 'UI', 'Storage') to encapsulate related functionality

**Async/Await**

- Used in getProducts() method to handle asynchronous operations for fetching data from an external JSON file

**Try/Catch**

- Error handling in the getProducts() method to catch and log any errors during the fetch operation

**Template Literals**

- Used for creating HTML strings with embedded expressions, making the insertion of dynamic content more readable

**Event Listeners**

- Added to buttons and DOM elements to handle user interactions such as clicks on the cart button, close button, and product buttons

**Local Storage**

- localStorage is used to store and retrieve the cart and product data
- Methods like setItem(), getItem(), and JSON.stringify()/JSON.parse() are used for this purpose

**Array Methods**

- Methods like map(), forEach(), find(), and filter() are used to manipulate arrays of products and cart items

**Spread Operator**

**Event Delegation**

- Used in cartContent.addEventListener("click", (e) => {...}) to handle events for dynamically added cart items

**Event Delegation**

- Grouping related functions and properties inside classes ('Products', 'UI', 'Storage') to keep the code organized and modular

**Destructuring**

- Used to extract properties from objects more conveniently, for example, const { title, price } = item.fields

**Static Methods**

By using these JavaScript concepts, the code efficiently handles fetching products, displaying them, managing the cart, and maintaining state through local storage.
