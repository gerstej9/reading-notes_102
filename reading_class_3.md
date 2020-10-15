# Class 3 Reading Notes

## HTML, Javascript, and CSS
* HTML is the first layer and contains content
* CSS is the presentation layer
* Javascript is the behavior layer and provides interactivity
* The three layers provide the basis of progressive enhancement when it comes to building webpages
* Starting with HTML allows for focus on content
* CSS next seperates the content from design
* Javascript adds enhanced usability and the experience of intera ting with the site
* Like CSS, Javascript files can be linked to in HTML
* You can also add JavaScript in the HTML between script tags

## JavaScript
* Calling a method of an object
    * Object.method(parameters);
    * ```document.write('Good Afternoon!');
    * Lots of objects like document and methods like write that will help write whole scripts
    * Javascript runs where it is found in HTML i.e. where the script element is

## JS Statements and Comments
* Scripts provide a series of instructions, each one is known as a statement and should end with a semi-colon
* Javascript is case sensitive
* Each statement starts on a new line
* Statements can be organized into code blocks using curly braces these are not followed by semi-colons
* Code blocks can be used to group together multiple statements for organization and readability
* Comments should be included in code to help yourself and others when reading it
* Multi-line comments ```/* hello*/```
* Single-line comments ```//```

## Variables
* Data can be stored as variables
* Variables can be considered short term memory because the page holds the data only while user is on the page
* Data in variables can change each time the script is run
* To declare a variable you need variable keyword and name
    * ```var quantity;```
    * Variable names should be written in camelCase if using multiple words
* Once a variable has been created you can assign a value to it, = sign is the assignement operator
    *  ```quantity = 3;```
* Until a variable is assigned it is considered undefined
* Variable shorthand is sometimes used to create variables
    * Variable is declared and values assigned in same statement
    * Three variables are declared on same line then values assigned to each
    * Two variables are declared then a third is declared and assigned on next line
    * Variable used to hold a reference to an element in the HTML page
* Variables can be changed later in the same script
* Rules for naming variables
    1. name must begin with a letter, dollar sign, underscore and not a number
    1. Name can contain letters, numbers, dollar sign, or underscored but no dashes or periods
    1. No keywords or reserved words can be used for instance var
    1. All variables are case sensitive, do not create variables with the same name but in different cases
    1. Use a name that describes the kind of information the variable stores
    1. Use camelCase when naming variables with multiple words included

## Data Types
* Numeric data
* String data includes letters and characters
* Boolean are true or false
* Variables can store numbers, strings, or booleans
* Strings are kept in quotations either single or double
* To add quotes inside either use escape character such as backslash or use the opposite quote marks to surround the string i.e. single or double
* 



