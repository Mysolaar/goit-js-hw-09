# About

Task 1 Background color switching
- adds two buttons to the webpage, one to start the color-changing and another to stop it.
- when the start button is clicked, the webpage's background color starts changing every 500 milliseconds using the getRandomHexColor function.
- the start button is then disabled, and the stop button is enabled.
- when the stop button is clicked, the color-changing stops, and the buttons are reset to their initial states.


Task 2 Countdown timer
- imports and configures a date picker library (Flatpickr) and a notification library (Notiflix)
- selects HTML elements by their IDs or data attributes
- sets up event listeners for the date picker and a start button
- defines functions to add leading zeros to numbers and convert milliseconds to days, hours, minutes, and seconds
- when the start button is clicked, it disables the button, calculates the remaining time until the selected date, and updates the HTML elements with the remaining days, hours, minutes, and seconds in a countdown. If the selected date is in the past, it shows an error notification.


Task 3 Promises
- handles a form submission and creates promises with randomized success rates using createPromise() function. The user inputs the initial delay, delay step, and amount of promises to create. The promises are then executed using .then() and .catch() to log a success or failure message to the console, as well as show notifications to the user using the Notiflix library.
