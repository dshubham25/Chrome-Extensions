# Chrome-Extensions

Learned from the youtube channel EvilTester-Software Testing 
- YouTube Video showing creation of the Chrome Extension
- [youtu.be/Olz4wo-ILwI](https://youtu.be/Olz4wo-ILwI)
 this is the exact code which was written in the video
## Detailed Description

A CounterString is a string of text e.g. `*3*5*7*9*12*15*` where:

- the string is a specific length e.g. 15
- the last character in the string is an *
- the numbers before each * are the position of the *

This can act as Test Data for helping test the length allowed in forms and other data fields. If the value is truncated then you can tell from the numbers and the '*' how long the string is e.g. `*3*5*7*9*12*15` is 14 characters long because the '*' after 15 is missing.

Counterstrings are commonly used in  exploratory testing.

This extension is a simple CounterString generator, which:

- displays a dialog asking for the number of characters,
- then generates a CounterString of that length
- the CounterString is logged to the dev console to allow copy and pasting,
- the extension also inserts the CounterString into the value of the field that was selected when the right click context menu was displayed
- this supports supports testing online forms.

Instructions for use:

- right click on and input field
- enter value of CounterString
- CounterString will be logged to the console (use dev tools to see it)
- CounterString will be inserted as the value of the WebElement you clicked on

Note:

- works with forms on the actual page
- this extension does not work with forms embedded in frames

### more code extensions will be added on my own once I get the hang of how to do chrome extensions
