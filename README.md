# Typing-Test

### Project Description: Speed Typing Test

This project is a Speed Typing Test application built using HTML, CSS (Bootstrap), and JavaScript. The application tests the user's typing speed by providing a random quote that the user needs to type within a given time frame. The key functionalities include fetching random quotes, timing the user's typing, and providing immediate feedback on the user's input. 

#### Features:
1. **Random Quote Fetching:**
   - On page load and reset, the application fetches a random quote from the API endpoint `https://apis.ccbp.in/random-quote`.
   - The quote is displayed in an HTML paragraph element with the id `quoteDisplay`.

2. **Typing Timer:**
   - The timer starts as soon as the page is loaded and displays the elapsed time in seconds in an HTML paragraph element with the id `timer`.

3. **User Input and Validation:**
   - Users can type the displayed quote in a textarea element with the id `quoteInput`.
   - On clicking the submit button (with id `submitBtn`), the input is validated against the displayed quote.
   - If the input matches the displayed quote, the timer stops and a success message is displayed in an HTML paragraph element with the id `result`.
   - If the input does not match, the timer continues, and an error message is shown in the same `result` element.

4. **Reset Functionality:**
   - Clicking the reset button (with id `resetBtn`) fetches a new random quote, resets the timer, and clears the input field.

5. **Loading Spinner:**
   - A Bootstrap spinner component is displayed while fetching the random quote to indicate loading status.

#### How It Works:
1. **Page Load:**
   - On loading the page, an HTTP request is made to fetch a random quote.
   - The quote is displayed and the timer starts.
   
2. **Typing and Submission:**
   - Users type the displayed quote in the textarea.
   - On submission, the input is checked against the displayed quote, and appropriate feedback is given.
   
3. **Reset:**
   - Clicking the reset button fetches a new quote, resets the timer, and clears the input field, allowing the user to start a new test.

#### Technologies Used:
- **HTML:** Structure of the application.
- **CSS (Bootstrap):** Styling and UI components.
- **JavaScript:** Functionality for fetching quotes, timing, and input validation.

#### Setup Instructions:
1. Clone the repository from GitHub.
2. Open `index.html` in a web browser to run the application.

This project is a practical implementation of web development concepts, demonstrating asynchronous data fetching, DOM manipulation, and user interaction handling.

Refer to the below image.
https://assets.ccbp.in/frontend/content/dynamic-webapps/speed-typing-test-output.gif

</br></br>
![image](https://user-images.githubusercontent.com/46521639/119023633-d0ecbd00-b9bf-11eb-9f45-af6aaf790e0f.png)
