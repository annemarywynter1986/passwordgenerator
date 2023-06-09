# Password-Generator
This project is designed as an assigment to create a password generator based on clients selections/input

This application emphasizes the use of Javascript to generate a random, secure password for the user.

This project has been deployed to GitHub Pages. 
To get this project up and running, you can follow the deployment link. Or, download from gihub repository links mentioned below

# Getting Started
This project has been deployed to GitHub Pages. To get this project up and running, you can follow the deployment link.Or, download from gihub repository links mentioned below

GitHub Repository: https://github.com/annemarywynter1986/passwordgenerator.git
Deployed URL: https://annemarywynter1986.github.io/passwordgenerator/


# Summary
HTML and CSS and Javascript documents create a random password generator
This project emphasizes the use of using Javascript to make dynamic changes to an HMTL document

# This project has the following features:
* A generate button
This will send the user a series of prompts and confirms

![image](https://user-images.githubusercontent.com/130412307/235821220-a9b39db2-3b44-4509-995a-7f253652d9b8.png)


After user data is collected, a random password will be generated using Javascript
* A Textarea
This textarea will display the users password once it is generated
![image](https://user-images.githubusercontent.com/130412307/235821282-0b1bdf51-6222-4a27-a639-839abb783972.png)


* A Copy button
This will copy the users password to the user's devices clipboard
![image](https://user-images.githubusercontent.com/130412307/235821326-1b6e3b5e-91b5-4613-a085-0533dae46813.png)


# This project has script features of:
Variable declaration area
An event listener (onclick) called generatePassword
This will prompt the user for input between 8-128
This variable is changed to an interger using ParseInt()
This will validate that the input is a number within range, or is a number
This then uses the input to determine the types (or choices) or letters of characters used, using an if statement
This then assigns values to the variables using arrays for character, number or alphabet
Another variable is created to concatenate the above variables
A for loop will loop through the enter prompt until it reaches the number entered by user.
A password variable takes the value from the for loop, and converts it to a string.
The string value then populates into the text area for the user using a UserInput function.
An event listener (onlick) has also been created for the copy to clipboard feauture.

# Features:
One HTML Pages
Index.html

One CSS Page
Styles.css located in folder "assets"

One Javascript Page
scripts.js 

# Credits:
Starter code by Coding bootcamp, adjustments by Anne Mary Wynter
