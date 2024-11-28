Activity 4.3: Dark and Light Mode Template

Objective: Activity 4.3 of the Essentials Javascript Course was to create a web applicaton using HTML, CSS and Javascript by using DOM manipulation techniques. In order to do this, the brief required a template system to be created so that the web page styles could be change from a dark mode to a light mode on a push of a button from the user.

Features

Webpage style can be changed from light mode to dark mode

Smooth transition between modes

Clear design for user

Dynamic design for user's interaction

Files

index.html: The HTML file contains the structure and the featured image of the webpage.

style.css: The CSS file contains the webpage's styles of the fonts, colors and both the light and dark modes.

script.js: The Javascript file contains the code for DOM Manipulation and toggling for the light and dark mode button.

README.md - The README.md file gives an overview of the project and it's features.

How to Use

1. Open the index.html file in your web browser
2. Click the Switch to Dark Mode toggle button to switch to dark mode.
3. To switch back to light mode, click the Switch to Light Mode toggle button.

Javascript Code Explanation

The toggleButton variable was created to select the toggle button element.

An toggleMode function was created so the user could click the button and it toggles the dark-mode class on the header, body and button elements.

The toggleMode function also allows the button text to update to reflect the current mode.

An eventListener was added to the code so the toggle button could call the toggleMode function when clicked.

