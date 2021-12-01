# Functions and Operators in JavaScript

- [Expressions & Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
- [Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)
- [Control Flow](https://developer.mozilla.org/en-US/docs/Glossary/Control_flow)

Here is a quick overview of the above listed articles.

Essentially, when you are coding "actions" into your webpage, using Javascript, you are invoking code within your javascript file, from a command in your index.html file. If that sound foreign to you, your index.html file is the "homepage" of your webpage, or what the user sees and then the javascript file runs in the background to add the interactions to your webpage.

In javascript, you can code certain things like creating a variable. That would look something like:

`var finger;`

which is literally just using the var command (short for variable) to create a variable called finger. You can also use a command called 'let'. Now, to actually assign a value to the variable, you need to use something called an "operator" that is what programmers use to assign a value. See the code below:

`let finger = 5;`

In Javascript, this piece of code would create a variable called "finger" and then assign it the number value 5.

## As for Functions

A function in Javascript, essentially, allows you to control when the code is invoked or executed in your webpage. When you create you javascript page, instead of just putting all of the code in your page, you can put it all in a function and then, at a certain part of your webpage or at the press of a button, your webpage will execute that function. Here's some code for how you can create a function:

` function getFaveNumber() {`
`   let faveNumber = prompt("What is your favorite number?");`
`}`

Basically, this function is called getFaveNumber and, what it does is prompts the user with this information to input their favorite number. Then, based on what the user inputs, this function will assign that value to the new variable "faveNumber".

Now in order to invoke this number on your webpage, you'll be coding in html and it will look something like this:

`<script>getFaveNumber()</script>`

Also, one other quick note. Your code runs from top to bottom. That is the flow, so if you have an issue at the beginning of your code, the rest of your code will not work until you fix that bug.

There is my quick overview.

[Back to Reading Notes](README.md)