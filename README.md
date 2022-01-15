# Week 3 Challenge Assignment - Password Generator (Focus: JavaScript)

The purpose of this week's challenge is to code a random password generator given a set of criteria. The criteria were:

GIVEN I need a new, secure password
WHEN I click the button to generate a password
THEN I am presented with a series of prompts for password criteria
WHEN prompted for password criteria
THEN I select which criteria to include in the password
WHEN prompted for the length of the password
THEN I choose a length of at least 8 characters and no more than 128 characters
WHEN asked for character types to include in the password
THEN I confirm whether or not to include lowercase, uppercase, numeric, and/or special characters
WHEN I answer each prompt
THEN my input should be validated and at least one character type should be selected
WHEN all prompts are answered
THEN a password is generated that matches the selected criteria
WHEN the password is generated
THEN the password is either displayed in an alert or written to the page

When you run this code, you can see the full set of criteria is met. I enjoyed this challenge because it is my first real application of my knowledge of JavaScript, creating custom functions and using existing functions, as well a test of how well my pseudocode reflects the final code. Overall, my pseudocode helped me formulate the large picture of what needed to be done and how to go about doing it. My take-away in this challenge is pseudocode should not be pushed aside for the novice coder. **Use pseudocode!!**

Some points I'd like to highlight in this challenge are:

### Introduction to Event Listeners
When the user runs the index.html file, they are presented with screen that has a red button which they can press to generate the random password.

![HTML screen capture](/assets/images/HTML-screen-capture.jpg)


### Utilization of JavaScript Standard Built-In Object Math
I was introduced to the standard built-in JavaScript object Math in the lesson module, and had to apply its usage to this week's challenge.
My function *randomNumber(min, max)* takes two input arguments and then uses the static methods Math.floor and Math.random to return a random number whose value will range between *min* and *max* inclusively. This random number is used as the index position for selecting a random character from my array finalCharArray. All this happens in my custom function *makeRandomPassword(length, charArray)*.

### Creation of Custom JavaScript Functions
This lesson was good in that it challenged you to create your own custom functions and give you practice in how to break down a task into smaller chunks enclosed within a function. I initially estimated having to create about 3 custom functions to get everything done, but I ended up with about 6 in total, some functions comprising much less code and serving very specific, erh, *functions*.

#### Screenshot of the functions in my .js file
![List of functions used in developing JavaScript app](/assets/images/functions-used-in-code.jpg)
