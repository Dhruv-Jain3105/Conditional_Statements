# Experiment 5 - Conditional_Statements
## Aim
To study and understand the working of conditional statements (if-else, switch) and control statements (break, continue, return) in programming.

## Theory
### 1. Introduction
Conditional statements are control structures that guide the flow of execution in a program based on certain conditions. They allow the program to make decisions and perform different actions depending on whether conditions are true or false. Additionally, loop control statements like break, continue, and return allow altering the normal flow inside loops or functions.

### 2. If-Else Statements
The if-else statement is the most commonly used conditional statement.
- The if block executes when the condition evaluates to true.
- The else block executes when the condition evaluates to false.
- Else-if ladder is used when there are multiple conditions to check.

Working:

1. The given condition is evaluated.
2. If true → the corresponding block executes.
3. If false → either another condition is checked (else-if) or the final else executes.
4. After execution, control moves to the next part of the program.

### 3. Switch Statement
The switch statement provides a multi-way branching mechanism. It is useful when there are multiple constant values to compare.

Working:

1. The expression inside the switch is evaluated.
2. The value is compared with each case.
3. When a matching case is found, its block is executed.
4. Break is used to stop further case checking; without it, execution continues to the next cases (fall-through).
5. If no case matches, the default block executes.

### 4. Difference Between If-Else and Switch

Basis   |   If-Else   |   Switch

Usage   |   Best for complex conditions and range checking   |   Best for checking equality with fixed constants

Data Types   |   Works with all data types and logical expressions   |   Mostly works with integers, characters, enums

Readability   |   Can become lengthy for many conditions   |   Cleaner and more readable for multiple options

Execution   |   Conditions are checked sequentially   |   Jumps directly to the matching case


5. Break Statement
The break statement is used to immediately terminate the execution of a loop or a switch block.
It transfers control to the first statement after the loop or switch. Commonly used in switch to prevent execution of multiple cases.

6. Continue Statement
The continue statement is used inside loops to skip the remaining statements of the current iteration and move to the next iteration.
Useful when you want to ignore some specific cases within a loop but continue looping.

7. Return Statement
The return statement is used to exit from a function and optionally send a value back to the function that called it.
In main(), return 0; often indicates that the program executed successfully.

Conclusion
* Conditional statements are essential for decision-making in programs.
* If-else is best suited for complex conditions and range-based checks.
* Switch is efficient for multiple constant comparisons.
* Break allows early exit from loops or switch.
* Continue skips unnecessary loop iterations.
* Return ends the execution of a function and can return values to the calling function.

Algorithm to Check Whether a Number is Even or Odd
1. Start
2. Declare an integer variable `num`
3. Display the message: `"Type number : "`
4. Read the value of `num` from the user
5. Check if `num % 2 == 0:`
  * If true, display `"The number is Even"`
  * If false, display `"The number is Odd"`
6. End

Algorithm to Find the Greatest of Three Numbers
1. Start
2. Declare integer variables: `num1`, `num2`, `num3`, and `greatest`
3. Display the message: `"Enter three numbers: "`
4. Read values of `num1`, `num2`, and `num3` from the user
5. Initialize `greatest = num1`
6. Check if num2 > greatest:
  * If true, set `greatest = num2`
7. Check if `num3 > greatest:`
  * If true, `set greatest = num3`
8. Display the result: `"The greatest number is: " + greatest`
9. End

Algorithm to Check Whether a Character is a Vowel or Consonant
1. Start
2. Declare a character variable `ch`
3. Display the message: `"Enter a character: "`
4. Read the character `ch` from the user
5. Check if `ch` is equal to any of the following:
`'a', 'e', 'i', 'o', 'u'`
`'A', 'E', 'I', 'O', 'U'`
6. If the condition is true:
* Display: `"The character is a vowel."`
7. Else:
* Display: `"The character is a consonant."`
8. End

Algorithm to Display Day of the Week Using Switch Case
1. Start
2. Declare an integer variable day
3. Display the message: "Enter a number (1-7): "
4. Read the value of day from the user
5. Use switch(day) to match the input:
* case 1: Display "Monday" and break
* case 2: Display "Tuesday" and break
* case 3: Display "Wednesday" and break
* case 4: Display "Thursday" and break
* case 5: Display "Friday" and break
* case 6: Display "Saturday" and break
* case 7: Display "Sunday" and break
* default: Display "Invalid input! please enter from 1 to 7"
6. End


