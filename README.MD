Lab 6a
======

Submit your finished code to the Dropbox. You will need to pass off the lab with the TA or tutor during their office hours (their information is in the CS 105 Course Information section of the Class Resources module), or the instructor in class. Follow the CS 105 
Formatting Guide which is also found in the CS 105 Course Information section.

Read the instructions carefully. Make sure your output matches the example run.

Objectives:
===========

In this lab, you will learn how to do the following:

-   Write a method
-   Pass arguments to the method
-   Return a value from the method back to your main method

Structure:
==========

Create the following structure in Eclipse for this lab.

**Package Name:** week6\
**Class Name:** Lab6a

Program: largestNumber() Method
===============================

Write a program that asks the user for three whole numbers. Use input validation to ensure the user entered three valid whole numbers.  Have your main() method call a second method that you write called largestNumber(), passing the three numbers as arguments. Your 
largestNumber () method will determine which of the three numbers is the largest and return that value back to main() via the return statement. You must write your own code to figure out which of the three numbers is the largest. You may NOT use Java's built in 
Math.max() method.  **Print out the largest number in main().**\
After the program has finished, ask the user if they would like to play again. Use input validation to ensure the user answered with a 'Y' or 'N'. Keep the program running in an infinite loop until the user indicates they want to quit.

Key program requirements:
=========================

-   Do input validation on all three numbers and the 'Y'/'N' play again question
-   Use of Java's Math.max() method is NOT allowed
-   You must print out the largest number from main()
-   The names of the three variables inside main() which are passed to largestNumber() as arguments MUST be different than the names of the three parameters inside of your largestNumber() method
-   You must complete the Ponder activity below.
-   Submit the following .java file:
    -   Lab6a.java

Ponder:
=======

Discuss the following with your partner. **Failure to do this activity and discuss these questions before you attempt to pass off your program will result in a failed pass off**.

-   With your partner, use your finger or a pen to point at each line of code as you trace through the program from beginning to end. **Yes, really use your finger or a pen.**
-   Step through each line IN THE ORDER THAT IT WILL BE EXECUTED from beginning to end.
-   Discuss what each line of code does.
-   Make assumptions of what numbers the user will enter, then **write those numbers in the appropriate memory locations as you trace through the code with your finger.**
-   Show the paper with your memory locations to the TA or instructors when you pass off the program.

Example Run:
============

*This program will ask the user for three numbers and determine which of the three is the largest.*\
*Enter the first number: the first number*\
*Invalid Response: Please enter a whole number.*

*Enter the first number: 9*\
*Enter the second number: 2 hundred*\
*Invalid Response: Please enter a whole number.*

*Enter the second number: 200*\
*Please enter the third number: 42*

*The largest of the three numbers is: 200*

*Would you like to play again? (Y/N): n*Lab 6b
======

Submit your finished code to the Dropbox. You will need to pass off the lab with the TA or tutor during their office hours (their information is in the CS 105 Course Information section of the Class Resources module), or the instructor in class. Follow the CS 105 
Formatting Guide which is also found in the CS 105 Course Information section.

Read the instructions carefully. Make sure your output matches the example run.

Objectives:
===========

In this lab, you will learn how to do the following:

-   Write a method
-   Pass arguments to the method
-   Use a method call as an argument passed to another method

Structure:
==========

Create the following structure in Eclipse for this lab.

**Package Name:** week6\
**Class Name:** Lab6b

Program: power() Method
=======================

Write a program that asks the user for two whole numbers. The numbers will represent X and Y in the mathematical method xy. Use input validation to ensure the user entered two valid whole numbers.\
Have your main() method call a second method that you write called power(), passing the two numbers as arguments. Your power() method will raise the first number to the power of the second number and return that value back to main() via the return statement. **You 
must use a for-loop to perform this calculation.** You may NOT use Java's built-in Math.pow() method.

**Print out the value returned from your power() method in main() WITHOUT storing the returned result in a variable.**

After the program has finished, ask the user if they would like to play again. Use input validation to ensure the user answered with a 'Y' or 'N'. Keep the program running in an infinite loop until the user indicates they want to quit.

### Using a method call as a parameter:

To this point, we have stored the value returned from a method in a variable, then printed out the value of that variable using a System.out.println() statement. 

*num3 = power(num1, num2);*

*System.out.println(num1 + " raised to the power of " + num2 + " is: " + num3 + ".");*

For this Lab, you will forgo the extra step of storing the returned value of power() in a variable and simply call the power() method from within the System.out.println() statement.

*System.out.println(num1 + " raised to the power of " + num2 + " is: " + power(num1, num2) + ".");*

Key program requirements:
=========================

-   Do input validation on both numbers and the 'Y'/'N' play again question
-   Use of Java's Math.pow() method is NOT allowed
-   You must print out the result in main() without storing the returned result in a variable
-   The names of the two variables inside main() which are passed to power() as arguments MUST be different than the names of the three parameters inside of your power() method
-   You must complete the Ponder activity below.
-   Submit the following .java file:
    -   Lab6b.java

Ponder:
=======

Discuss the following with your partner. **Failure to do this activity and discuss these questions before you attempt to pass off your program will result in a failed pass off**.

-   With your partner, use your finger or a pen to point at each line of code as you trace through the program from beginning to end. **Yes, really use your finger or a pen.**
-   Step through each line IN THE ORDER THAT IT WILL BE EXECUTED from beginning to end.
-   Discuss what each line of code does.
-   Make assumptions of what numbers the user will enter, then **write those numbers in the appropriate memory locations as you trace through the code with your finger.**
-   Show the paper with your memory locations to the TA or instructors when you pass off the program.

Example Run:
============

*This program will ask the user for 2 numbers and raise the first number to the power of the second.*

*Please enter the first number: ok... but when do you want me to enter it?*\
*Invalid Response: Please enter a whole number.*

*Please enter the first number: 5*\
*Please enter the second number: 0*\
*5 raised to the power of 0 is: 1.*

*Would you like to play again? (Y/N): Sure!!!*\
*Invalid response: Please answer with a 'Y' or 'N'.*\
*Would you like to play again? (Y/N): y*\
*Please enter the first number: 5*\
*Please enter the second number: 1*\
*5 raised to the power of 1 is: 5.*

*Would you like to play again? (Y/N): y*\
*Please enter the first number: 5*\
*Please enter the second number: 3*\
*5 raised to the power of 3 is: 125.*

*Would you like to play again? (Y/N): n*
