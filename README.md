# HW - giphy API

## Live Link
 - https://lieu510.github.io/giphyAPI/

## Description on how to use the app
- click a button to see 10 related gifs 
- to add a category, type into the input field and click submit
- click the new button to display 10 related gifs

## Requirements

- When the user clicks on a button, the page should grab 10 static, non-animated gif images from the GIPHY API and place them on the page.
- When the user clicks one of the still GIPHY images, the gif should animate. If the user clicks the gif again, it should stop playing.
- Under every gif, display its rating (PG, G, so on).
	- This data is provided by the GIPHY API.
	- Only once you get images displaying with button presses should you move on to the next step.
- Add a form to your page takes the value from a user input box and adds it into your topics array. Then make a function call that takes each topic in the array remakes the buttons on the page.
- Deploy your assignment to Github Pages.

## Technologies Used

- Jquery for Dom Manipulation
- AJAX for API GET requests

## Code Explaination

$(document).on("click", ".category", displayGif);
- used to apply event listeners to dynamically created elements
