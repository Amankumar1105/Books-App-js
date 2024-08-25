Project Overview:- 
This project is a web application that displays a list of book categories and top-selling books. It includes a dynamic dark mode toggle, a signup/signin feature, and interactive book details. The application is built with HTML, CSS, and JavaScript, and it fetches data from an external API to display the book categories and details.

Key Features:
Dark Mode Toggle:

The dark mode toggle allows users to switch between light and dark themes. The preference is saved in localStorage, so the user's choice is preserved across sessions.
The toggleSignupSigninSections function applies the dark mode styling to dynamically created signup/signin forms.
Signup and Signin Forms:

Users can sign up or sign in through forms that appear as overlays. These forms are created dynamically using JavaScript.
The user's signup data is stored in localStorage, and the signin process checks this data to authenticate the user.
Dynamic Content Loading:

Categories and books are fetched from an external API using the fetch function.
The displayCategories and displayBooks functions dynamically generate HTML content based on the fetched data, ensuring that the page is always up-to-date with the latest book listings.
Book Details Display:

Clicking on a book card displays detailed information about the book, including an image, author, title, and a brief description.
A button allows users to add the book to their shopping list, which changes its state after being clicked.

JavaScript Functionality:-

Dark Mode:

The dark mode is toggled by listening to changes on a checkbox. The mode is then saved to localStorage and applied to the page and forms on subsequent loads.
Form Handling:

Forms for signup and signin are created and manipulated using DOM methods like createElement and appendChild. Event listeners handle form submission, field validation, and interaction between signup and signin views.
Data Fetching and Display:

Data is fetched from the backend API using fetch and displayed dynamically. The application handles different categories and books by iterating over the fetched data and creating HTML elements on the fly.
Event Handling:

Event listeners are used extensively for user interactions, including toggling dark mode, opening forms, submitting data, and navigating between different views.
This project demonstrates the power of combining JavaScript's DOM manipulation capabilities with asynchronous data fetching to create a dynamic, interactive web experience.

