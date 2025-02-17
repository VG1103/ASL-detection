Requirements:
The requirements of this project were to create a Quiz Application which included two sides,namely the admin side and the student/user side. In the admin part of this website the admin wanted the access to all the categories and sub-categories from the given csv file and further, on selecting them they wanted to be able to recieve 20 random questions each time a sub-category was selected.Basically the admin should be able to create different quizzes for the students. Now coming to the user side of the website,the user should be able to select from the quizzes presented to them.On the quiz page 20 questions should appear with a total timer of 20 minutes per quiz including the user score and option to restart the quiz.


Work Done:
Login Page-It is a simple login page with an email input and a password input.Two buttons to log in as "ADMIN" or "USER".Links for creating a new account or user registration.The css contains styling for the login page elements such as fonts, colors, and layout.

Start Page-It contains a title directed to create a quiz and a small description.Contains a navigation menu for various categories and their sub-categories.Each sub-category is a link to another page and are hard-coded.The css of the start page provides styling for the start page, including the navigation menu and its sub-menu.

New Page-It contains a container to show quiz questions. It fetches quiz questions using the Fetch API from a CSV file using the Papa Parse library,then it filters questions based on a selected sub-category obtained from the URL query parameter.After that 20 random questions from the filtered list are selected and are displayed,each with its options,correct answer,feedback and points. The page also features a "Create Quiz" button that triggers an alert when clicked.

Quiz Page-It is an interactive web page designed to display and manage a quiz consisting of multiple-choice questions. Users can answer questions and then only progress through the quiz.They are given 20 random questions from the csv file and a total time of 20 minutes.Css has been used to style the various elements including fonts, background colors, margins, and padding.Styling is done to hide the .score-container element by default.Also for buttons and their appearance on hover.The javascript code includes  the "DOMContentLoaded" event, the script initializes variables such as an array to store parsed questions, the current question index, timer duration, remaining time, and a timer interval. It defines functions for parsing CSV text and loading questions, getting random sets of questions, displaying questions and answer choices, updating the timer display, handling the "Next" button click event, calculating and displaying the user's score, and managing quiz restart.Also , the "Restart" button enables users to restart the quiz, restoring the initial state.

References:
1.APIs for Beginners 2023 - How to use an API (Full Course / Tutorial) By freecodecamp.
2.https://www.geeksforgeeks.org/ For basic html,css and javascript.
3.https://stackoverflow.com/ for queries related to the project.



