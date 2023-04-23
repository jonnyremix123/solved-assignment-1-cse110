Download Link: https://assignmentchef.com/product/solved-assignment-1-cse110
<br>
<h1>Topics</h1>

<ul>

 <li>Entering, compiling, and running a Java program.</li>

 <li>Using System.out.println().</li>

 <li>Java syntax.</li>

 <li>Recognizing syntax and logical errors.</li>

</ul>

<h2>Important Note</h2>

All submitted assignments must begin with the descriptive comment block similar to the one shown below under Part 1. It must contain your name and the other information illustrated. To avoid losing trivial points, make sure this comment header is included in every assignment you submit, and that it is updated accordingly from assignment to assignment.

<h1>Part #1 – Compile and Run (5 pts)</h1>

Type the following code into a file called TempConverter.java. After the program is entered, compile and run the application to make sure it works. Once you see it working correctly, answer questions a-e below. (The comment block shown here is a good example to base yours off of for Part 3, namely Assignment1.java). You DO NOT have to submit this file.

//***********************************************************

// Name: Faye Navabi

// Title: TempConverter.java

// Author: (if not you) Modified from an example in Lewis &amp;

// Loftus book

// Description: Computes the Fahrenheit equivalent of a specific Celsius

// value

// Time spent: 20 minutes

// Date: 8/15/2013

//************************************************************** public class TempConverter {

// Computes the Fahrenheit equivalent of a specific Celsius // value using the formula F = (9/5)C + 32. public static void main (String[] args) {

//constant variables final int BASE = 32;

final double CONVERSION_FACTOR = 9.0 / 5.0;

//declare variables int celsiusTemp = 24; // value to convert double fahrenheitTemp; fahrenheitTemp = celsiusTemp * CONVERSION_FACTOR + BASE;

System.out.println (“Celsius Temperature: ” + celsiusTemp);

System.out.println (“Fahrenheit Equivalent: ” + fahrenheitTemp);

}

}

There are numerous opportunities for errors in any program, many times in places that seem too simple to require close attention.

<strong>Questions</strong>: Introduce the following errors, one at a time, in the program TempConverter.java. <strong>Write in</strong>

<strong>your own words any error messages that the compiler produces</strong>. Fix the previous error each time

before you introduce a new one. If no error messages are produced, try to run the code and explain what happens. If still no errors are produced, explain why.

<ul>

 <li>Change TempConverter to tempConverter.</li>

 <li>Remove the first quotation mark in the first string literal in the first out.println( ) statement.</li>

 <li>Remove the semicolon at the end of the first println( )</li>

 <li>Remove the last brace in the program.</li>

 <li>Change the variable name fahrenheitTemp to fahrenheit in any one place in the code.</li>

</ul>

<strong>Note: The answers to the 5 questions (a through e) above should be typed in the block of comments in the Assignment1.java file.</strong>

<h1>Part #2 – Arithmetic Expressions (5 pts)</h1>

Include the answers to these questions as comments above your code for Part 3 below.

<ol>

 <li>Assume that you have a program that contains the following three lines of code. What is the value stored in the variable mystery after each line in the following code segment (You should have an answer like a) mystery has the value …b) mystery now has the value …)?</li>

</ol>

/*a)*/ int mystery = 5;

/*b)*/ mystery = mystery – mystery / 2;

/*c)*/ mystery = mystery + 1;

<ol start="2">

 <li>Assume that you have the following variables declared:</li>

</ol>

int a = 3, b = 10, c = 7; double w = 12.9, y = 3.2;

What do the following expressions evaluate to in Java?

<ol>

 <li>a / b</li>

 <li>(double) b / a</li>

 <li>a – b / c</li>

 <li>w / (int) y</li>

 <li>y / w</li>

 <li>b % c / a</li>

 <li>b % a</li>

</ol>

<h1>Part #3 – Programming (10 pts)</h1>

Write a Java program called Assignment1.java that will calculate the tip to leave at a restaurant. Your program must ask the user for the amount of the bill (this could contain decimals), and the percent they want to tip. The user will enter the percent they want to tip as an integer, e.g. 15 for 15

<ul>

 <li>Comments explaining the main parts of the code (Getting input, calculating results, etc)</li>

 <li>Descriptive variable names with appropriate types</li>

 <li>Appropriate indentation between braces</li>

 <li>Use the NumberFormat class to format the output to be display as currency as demonstrated in the Coding Sample video.</li>

</ul>

<strong>For this and all subsequent assignments, provide a heading (in comments) described above and demonstrated in Part #1. Make sure your program is called Assignment1.java.</strong>

<h2>Sample Output</h2>

Below is sample output with input in bold. Your output does not need to match directly.

<strong>Sample 1</strong>

Enter the bill amount: $<strong>100.00</strong>

What percent would you like to tip: <strong>15</strong>

Tip Amount: $15.00

Total amount with tip: $115.00

<strong>Sample 2</strong>

Enter the bill amount: $<strong>15.50</strong>

What percent would you like to tip: <strong>10</strong>

Tip Amount: $1.55

Total amount with tip: $17.05


