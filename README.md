Download Link: https://assignmentchef.com/product/solved-cs160-assignment-4-selection-and-repetition-control-structures
<br>
<strong> Computation</strong> <strong>(More decisions and repetition)</strong>

We have been learning about problem-solving steps and control structures. In this computational section, you will use your understanding of selection and repetition control structures to solve the following problem.




You are going to extend your lab 2 and build a calculator that has a programmer and scientific mode. The user can choose the mode, and once in that mode the user gets a few options for calculations.  You may not use any built-in functions for the number conversion, such as bin()!!!

In programmer mode, the user can enter any unsigned decimal number to convert to binary. Hint: you could find the left starting bit by increasing the exponent while the number is greater than equal to 2**exponent.

<ul>

 <li>Your binary number should not print leading zeros, and it only needs to convert unsigned base 10 numbers, <strong>positive integers!!! </strong><strong> </strong></li>

 <li><strong>You need to print an error message for any integer number that is not positive!</strong></li>

</ul>

In scientific mode, the user can choose between the following mathematical operations: +, -, *, /, and **.

<ul>

 <li>All operators are binary, so the user must be prompted for two operands following the operator. These operands can be integers or floating-point numbers.</li>

 <li><strong>You need to print an error message for the selection of a bad mathematical operator, i.e. invalid selection.</strong></li>

</ul>

You will ask the user if they want to 1) do another calculation, 2) go to a different mode, or 3) exit after each calculation.




<strong>Step 1: Understanding the Problem</strong>. <strong>(10 pts)</strong>

<ul>

 <li>Do you understand everything in the problem? List anything you do not fully understand.</li>

 <li>What are the functional requirements of the program, and what assumptions are you making?</li>

 <li>What are the inputs, outputs, etc.?</li>

</ul>

<strong> </strong>

<strong>Step 2: Devise a Plan</strong>. <strong>(20 pts)  </strong>

<ul>

 <li>What are the decisions that need to be made in this program?</li>

 <li>How are you going to calculate the binary number?</li>

 <li>Are you going to calculate this starting exponent?</li>

 <li>How are you going to handle bad input?</li>

</ul>

Based on your answers above, list the <strong>specific steps or provide a flowchart </strong>of what is needed to create this calculator with two modes. Be very explicit!!!

<strong>Step 3: Carry out the plan</strong>.

This is the Python or Scratch code that implements the programmer and scientific calculator.  Use the week 3 and week 4 notes to help with this code.

<strong>Step 4: Looking Back</strong>. <strong>(10 pts)</strong>

Create a test plan with the test cases (bad, good, and edge cases).  What do you hope to be the expected results?

<ul>

 <li>What are the good, bad, and edge cases for ALL input in the program?</li>

 <li>What are the actual results from testing this data?</li>

</ul>

<strong> Extra Credit: </strong>

Add a new mode to the programmer mode, and allow the user to convert from binary to decimal. You can make any assumptions you want.