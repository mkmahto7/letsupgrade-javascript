## Question 1 
Explore and explain the various methods in console function
Explain them
Ex. console.log()

The console.log() is a function in JavaScript which is used to print any kind of variables defined before in it or to just print any message that needs to be displayed to the user.
console.warn().
etc...
~~~
console.log(A)
~~~
Parameters: It accepts a parameter which can be an array, an object or any message.
Return value: It returns the value of the parameter given.
JavaScript codes to show the working of this function:

1) Passing a number as an argument: If the number is passed to the function console.log() then the function will display it.
Code #1:
~~~
<script> 

var a = 2; 
console.log(a); 
</script> 

~~~



 ##  Question 2 

Write the difference between var, let and const with code examples.

In Javascript one can define variables using the keywords var, let or const.
~~~
var a=10;
let b=20;
const PI=3.14;
~~~
var: The scope of a variable defined with the keyword “var” is limited to the “function” within which it is defined. If it is defined outside any function, the scope of the variable is global.
var is “function scoped”.
let: The scope of a variable defined with the keyword “let” or “const” is limited to the “block” defined by curly braces i.e. {} .
“let” and “const” are“block scoped”.
const: The scope of a variable defined with the keyword “const” is limited to the block defined by curly braces. However if a variable is defined with keyword const, it cannot be reassigned.
“const” cannot be re-assigned to a new value. However it CAN be mutated.
Function scoped vs. Block scoped
Let us understand this by some code examples,
Block Scope
In Javascript you can define a code block using curly braces i.e {}.
Consider the following code that has 2 code blocks each delimited by {}.
~~~
{
  var a=10;
  console.log(a);
} //block 1
{
  a++;
  console.log(a);
} //block 2
~~~
/* Since we are using "var a=10", scope of "a" is limited to the function within which it is defined. In this case it is within the global function scope */
In the above example, since we are using the keyword var to define the variable a, the scope of a is limited to the function within which it is defined. Since a is not defined within any function, the scope of the variable a is global, which means that a is recognized within block 2.
## Question 3 :
Write a brief intro on available data types in Javascript.
Javascript Data Types
JavaScript provides different data types to hold different types of values. There are two types of data types in JavaScript.

Primitive data type
Non-primitive (reference) data type
JavaScript is a dynamic type language, means you don't need to specify type of the variable because it is dynamically used by JavaScript engine. You need to use var here to specify the data type. It can hold any type of values such as numbers, strings etc. For example:


JavaScript primitive data types
There are five types of primitive data types in JavaScript. They are as follows:

Data Type	Description
String	       represents sequence of characters e.g. "hello"
Number	       represents numeric values e.g. 100
Boolean	      represents boolean value either false or true
Undefined     represents undefined value
Null	      represents null i.e. no value at all
