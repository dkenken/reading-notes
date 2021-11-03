# **Operators and Loops**

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

## **Loops**

**The While Loop**

The while loop loops through a block of code as long as a specified condition is true.

**_Example_**

In the following example, the code in the loop will run, over and over again, as long as a variable (i) is less than 10:

while (i < 10) {
text += "The number is " + i;
i++;
}

## **The For Loop**

The For loop loops loops through a block of code a number of times.

**_Example_**

The for loop has the following syntax:

for (statement 1; statement 2; statement 3) {
// code block to be executed
}
Statement 1 is executed (one time) before the execution of the code block.

Statement 2 defines the condition for executing the code block.

Statement 3 is executed (every time) after the code block has been executed.

Example
for (let i = 0; i < 5; i++) {
text += "The number is " + i + "<br>";
}

From the example above, you can read:

Statement 1 sets a variable before the loop starts (let i = 0).

Statement 2 defines the condition for the loop to run (i must be less than 5).

Statement 3 increases a value (i++) each time the code block in the loop has been executed.
