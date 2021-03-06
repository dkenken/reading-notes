# **Programming with JavaScript**

## **Functions**

A JavaScript function is a block of code designed to perform a particular task.
A JavaScript function is executed when “something” invokes it (calls it).

function myFunction(p1, p2) { return p1 \* p2; // The function returns the product of p1 and p2 }

## **_Function Return_**

**Example:**
let x = myFunction(4, 3); // Function is called, return value will end up in x

function myFunction(a, b) {
return a \* b; // Function returns the product of a and b
}

The result in x will be:
12

## **Operators**

Arithmetic operators are used to perform arithmetic on numbers:

**Operator**

- Addition +
- Subtraction -
- Multiplication \*
- Exponentiation (ES2016) \*\*
- Division /
- Modulus (Division Remainder) %
- Increment ++
- Decrement --

**_Example_**
let text1 = "John";
let text2 = "Doe";
let text3 = text1 + " " + text2;

The result of text3 will be:
John Doe

### **Adding Strings and Numbers**

Adding two numbers, will return the sum, but adding a number and a string will return a string:

Example
let x = 5 + 5;
let y = "5" + 5;
let z = "Hello" + 5;

The result of x, y, and z will be:
10
55
Hello5
