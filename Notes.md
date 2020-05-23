# My Notes on Head First JavaScript Programming

# Chapter 1

## Variables

When a variable is called in a function but hasn't been previously assigned with a value, the code stops running.

# Chapter 2

## Prompts

Prompts always need to be initiated with a variable. If you're going to ask a user for something, you need a variable to store what they're going to give you, otherwise you won't have anywhere to put it.

  <!-- here's an example of a prompt -->
  var netflixChoice = prompt("What you wanna watch tonight?", "type your answer");

## Evaluating Numbers in strings

When a number is saved by itself as a string, Javascript will still try to interpret the string as a number when it can.

  <!-- setting variable "five" to equal the string "5" will still evaluate when used in calculations -->
  var five = "5";
  five * 5;

## Boolean operations

### OR operations

**How to nest an OR statement?**

IE if x equals one of many values, then y. That's something I want to know.

### Equal to and Exactly Equal to

Strings can be evaluated to numbers equal (==) number values, while are not exactly to them (===)
