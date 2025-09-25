💻 Decision Making in C++

🎯 Aim:-

The goal is to explore key decision-making structures in C++ such as:

if else

if else if ladder

switch case

We’ll explore these concepts through simple examples:

Checking if a number is odd or even

Finding the largest of three numbers

Identifying whether a character is a vowel or consonant

Using a switch statement to select a month

📚 Theory:-

Conditional Statements:
These statements control the flow of execution depending on evaluated conditions. They allow the program to make decisions dynamically based on different inputs or situations. These structures are fundamental in making your program respond intelligently to varying inputs.

🔄 If Else Statement:

The if else structure is used for making binary decisions:

If the condition is true, one block of code executes.

If the condition is false, another block of code executes.

This is useful when you need to choose between two possible outcomes, like a simple "yes" or "no" check.

🧭 If Else If Else Ladder:

An extension of the if else structure, the if else if else ladder is used when there are more than two conditions to check:

The program evaluates each condition in order.

Once a condition is true, its corresponding block is executed, and the rest are skipped.

The final else acts as a fallback if none of the conditions are true.

This is useful when you have multiple possible outcomes based on different conditions.

🎚️ Switch Case Statement:

The switch case structure is an alternative to using multiple if else checks when you need to compare a variable to many discrete values (like menu choices or fixed options).

It matches the variable’s value with one of several predefined cases.

A default case is used if none of the predefined values match.

This is helpful for cleaner, more organized code when dealing with fixed options.

📋 Algorithms:
✅ Odd or Even Number Detection-

The algorithm to check if a number is odd or even is simple:

Take an integer input from the user.

Check if the number is divisible by 2 (num % 2 == 0):

If true, the number is even.

Otherwise, it’s odd.

✅ Largest of Three Numbers-

To find the largest of three numbers:

Get three integer inputs from the user.

Compare the numbers:

If the first number is greater than the other two, it’s the largest.

If the second number is greater than the third, it’s the largest.

If neither of the above conditions is true, the third number is the largest.

✅ Vowel or Consonant Using ASCII-

To determine if a character is a vowel or consonant:

Take a character input from the user.

Check if the character is a letter (from 'A' to 'Z' or 'a' to 'z').

If the character is a letter, check if it’s one of the vowels ('A', 'E', 'I', 'O', 'U' or lowercase equivalents):

If true, it’s a vowel.

Otherwise, it’s a consonant.

If the character is not a letter, display "Not a letter".

✅ Month Selector Using Switch Case-

To select a month based on a number:

Take an integer input for the month number (1 to 12).

Use a switch case to match the number to its corresponding month:

For example, if the number is 1, the month is "January"; if the number is 2, the month is "February", and so on.

If the number is outside the range of 1-12, display "Invalid Input".

🧠 Conclusion:

Mastering decision-making constructs is essential for creating dynamic programs.

If else is ideal for simple, binary decisions.

If else if ladder is used when multiple conditions need to be evaluated.

Switch case is perfect for handling multiple discrete options.

By understanding and using these decision structures, you can craft programs that adapt to different conditions and make intelligent decisions at runtime.
