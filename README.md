# BookNook

BookSearch is a powerful and intuitive application designed to help you discover, explore, and track books that interest you. Whether you're a casual reader or a dedicated bibliophile, BookSearch makes it easy to find books across genres, authors, and titles.

Book Nook is a Google Books API search engine built with a RESTful API, refactored to be a GraphQL API built with Apollo Server. The app was built using the MERN stack, with a React front end, MongoDB database, and Node.js/Express.js server and API.

## User Story

AS AN avid reader<br>
I WANT to search for new books to read<br>
SO THAT I can keep a list of books to purchase

## Acceptance Criteria

GIVEN a book search engine<br>
WHEN I load the search engine<br>
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button

- WHEN I click on the Search for Books menu option<br>
  THEN I am presented with an input field to search for books and a submit button
- WHEN I am not logged in and enter a search term in the input field and click the submit button<br>
  THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
- WHEN I click on the Login/Signup menu option<br>
  THEN a modal appears on the screen with a toggle between the option to log in or sign up
- WHEN the toggle is set to Signup<br>
  THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
- WHEN the toggle is set to Login<br>
  THEN I am presented with two inputs for an email address and a password and login button
- WHEN I enter a valid email address and create a password and click on the signup button<br>
  THEN my user account is created and I am logged in to the site
- WHEN I enter my account’s email address and password and click on the login button<br>
  THEN I the modal closes and I am logged in to the site
- WHEN I am logged in to the site<br>
  THEN the menu options change to Search for Books, an option to see my saved books, and Logout
- WHEN I am logged in and enter a search term in the input field and click the submit button<br>
  THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
- WHEN I click on the Save button on a book<br>
  THEN that book’s information is saved to my account
- WHEN I click on the option to see my saved books<br>
  THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
- WHEN I click on the Remove button on a book<br>
  THEN that book is deleted from my saved books list
- WHEN I click on the Logout button<br>
  THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button.

## Go to my project

You can try out my app [here](https://v-booknook.onrender.com/) or clone my repository [here](https://github.com/VanZittle/V-BookNook) if you like.

## License

![GitHub](https://img.shields.io/github/license/VanZittle/V-BookNook?style=for-the-badge)<br> Go to license [here](https://github.com/VanZittle/V-BookNook/blob/main/LICENSE)

Markdown generated with **[README Creator](https://github.com/VanZittle/module9-challenge-ReadmeGenerator)**
