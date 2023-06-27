# Guess My Number 
### 1. It starts by setting up the initial variables secretNumber, score, and highscore.
### 2. There is a function called displayMessage that updates the text content of an HTML element with the given message.
### 3. It attaches an event listener to the element with the class "check" (presumably a button) using an anonymous function.
### 4. Inside the event listener, it retrieves the value entered in an input field with the class "guess" and converts it to a number.
### 5. It then checks if the guess is empty (falsy value) and displays an error message if it is.
### 6. If the guess is equal to the secretNumber, it displays a success message, shows the secret number, and updates the score and highscore if necessary.
### 7. If the guess is not equal to the secretNumber, it checks if the score is greater than 1. If it is, it displays whether the guess is too high or too low, decrements the score, and updates the score display.
### 8. If the score reaches 0, it displays a message indicating that the game is lost and sets the score to 0.
### 9. There is another event listener attached to an element with the class "again" (presumably another button) using an anonymous function.
### 10. Inside the "again" event listener, it resets the score, generates a new random secretNumber, displays a start guessing message, resets the score and guess displays, and resets the background color and width of another HTML element.
### 11. The code relies on the presence of HTML elements with specific classes to update their text content and respond to user interaction.

