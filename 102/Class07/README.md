## Programming with JavaScript

## Control Flow

**Control flow** is the order in which the computer executes statements in a script.

A typical script in Javascript includes many control structures, including condtionals, loops, and functions.

if (isEmpty(field)) {
  promptUser();
} else {
  submitForm();
}

## JavaScript Functions

A **JavaScript function** is a block of code designed to perform a particualr task

A **JavaScript function** is executed when **something** invokes it (calls it)

A **JavaScript function** is defined with the function keyword, followed by a name, followed by parentheses()

**Fucntion names** can contain letters, digits, underscores, and dollar signs (same rules as variables)

The **parentheses** may include parameter names separated by commas: (parameter1, parameter2,..)

The code to be executed, by the function, is placed inside curly brackets: **{}**

Function **parameters** are listed inside the parentheses () in the function defintion 

Function **arguments** are the values received by the function when it is invoked

Inside the function, the arguments(the parameters) behave as local variables

## Function Invovation

The code inside the function will execute when "something" invokes (calls) the function:

- **When an event occurs(when a user clicks a button)**

- **When it is invoked (called) from JavaScript code**

## Function Return

When JavaScript reaches a **return** statement, the function will stop executing

If the function was invoked from a statement, JavaScript will "return" to execture the code after the invoking statement

Functions often compute a return value. The return value is "returned" back to the "caller"

## Example

let x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}

## Why Functions 

**You can reuse code: Define the code once, and use it many times.**

**You can use the same code many times with different arguments, to produce different results**

## Example

function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius(77);

## The () Operator Invokes the Function

Using the example above, **toCelsius** refers to the function object, and **toCelsisus()**







