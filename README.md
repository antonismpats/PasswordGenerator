# Password Generator using HTML, CSS and Javascript

The application dynamically generates random passwords of a specified length (in this case, 12 characters) <br />
using a combination of uppercase letters, lowercase letters, numbers, and symbols with HTML, CSS and <br />
Javascript. This ensures that the generated passwords are secure and difficult to guess. <br />
The application is designed to be responsive and compatible with different devices and screen sizes. <br /> 
The use of relative units and flexible layout techniques ensures that the application adapts well to <br />
various viewport sizes, enhancing usability and accessibility. Overall, the Random Password Generator <br />
application offers a convenient and secure solution for generating strong passwords, enhancing user <br />
security and privacy in online activities. <br />

## About HTML

Let's view the HTML code's functionality and structure: <br /> 

<div class="container">: Container for the entire content.  <br />
<h1>: Heading for the page with the title "Generate a Random Password!" <br />
<div class="display">: Container for password input field and copy icon. <br />
<input type="text" id="password" placeholder="Password">: Input field for displaying the generated password. <br />
<img src="copy-icon.png" onclick="copyPassword()">: Image icon for copying the password. <br />
<button onclick="createPassword()">: Button for generating a random password. <br />
<div id="copyMessage">: Message display area for indicating successful copy operation. <br />

## Javascript Script Overview:

Declaration of constants and variables for password generation and copying functionality. <br />
Creation of a random password using a combination of uppercase letters, lowercase letters, numbers, and symbols. <br />
Implementation of a function to copy the generated password to the clipboard. <br />
Display of a message indicating successful password copying for a brief duration. <br />

### Password Generation:

Generation of a random password with a specified length of 12 characters. <br /> 
Combination of uppercase letters, lowercase letters, numbers, and symbols to ensure password complexity and security. <br />
Iterative process to add characters until the password reaches the desired length. <br />

### Password Copying:

Selection of the password input field for copying using document.getElementById(). <br />
Execution of the document.execCommand("copy") method to copy the selected text to the clipboard. <br />
Display of a message ("Text copied!") to provide visual feedback to the user. <br />
Utilization of setTimeout() to hide the copy message after 2 seconds for a non-intrusive user experience. <br />

## CSS Overview:
Universal Selector (*): Resetting default margin, padding, and font to ensure consistency across all elements. <br />
body: Styling for the overall body of the webpage, including background color and text color. <br />
.container: Styling for the main container element, controlling its margin, width, and maximum width. <br />
.display: Styling for the password display area, defining its width, margin, background color, and padding. <br />
.container h1: Styling for the heading element (h1) within the container, setting font weight, size, and color. <br />
.container h1 span: Styling for the span element within the heading, specifying a different color and padding. <br />
.display img: Styling for the image within the display area, setting its width and cursor style. <br />
.display input: Styling for the input field within the display area, removing borders and outlines, and setting font size. <br />
.container button img: Styling for the image within the buttons, setting its width and margin. <br />
.container button: Styling for the buttons, including background color, text color, font size, padding, and cursor style. <br />
#copyMessage: Styling for the copy message display area, setting its initial display to none, position, background color,  <br />
text color, border radius, and positioning in the center of the screen.
