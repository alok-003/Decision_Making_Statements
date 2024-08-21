# Decision Making Statements
Experiment 5

# AIM
To use decision making If-else.

# Software Used
VS Code

# Theory
  Decision-making is a concept that allows the execution of different code paths based on conditions. The if and else statements are primary constructs used for decision-making in C++. These constructs enable the 
  implementation of conditional logic. They help us check whether a condition is true and if it is, then the block inside the same is executed.
  
  example:

   if (condition) {
       // Code to be executed if the condition is true
   } else {
       // Code to be executed if the condition is false
   }

   }

   
# Algorithm

 -To Check the Quadrants
 
 -Start

 -Initialize:

 -Declare two integer variables x and y.
 
 -Input:
    -Ask the user to enter the X-axis coordinate and store it in x.
    -Ask the user to enter the Y-axis coordinate and store it in y.
    -Decision Making (using if-else statements):

 -If x > 0 and y > 0:
   Print "The point is in the first quadrant."
 -Else If x < 0 and y > 0:
   Print "The point is in the second quadrant."
 -Else If x < 0 and y < 0:
   Print "The point is in the third quadrant."
 -Else If x > 0 and y < 0:
   Print "The point is in the fourth quadrant."
 -Else If (x == 0 and y != 0) or (x != 0 and y == 0):
   Print "The point is on the axis."
 -Else:
   Print "The point is at the origin."
   
-End

## Positive and Negative

-Start

-Initialize:

-Declare a float variable num.

-Input:

-Ask the user to enter a number and store it in num.
-Decision Making (using if-else statements):

-If num > 0:
  Print "The num is POSITIVE."
-Else:
  Print "The num is NEGATIVE."
-End

## Vowel and Consonant Checker

-Start

-Initialize:

-Declare a char variable character.

-Input:

-Ask the user to enter a character and store it in a.
-Decision Making (using if-else statements):

-If character is one of the following vowels (both lowercase and uppercase):
   'a', 'e', 'i', 'o', 'u', 'A', 'E', 'I', 'O', 'U':
   Print "character is a vowel."
-Else:
   Print "character is a consonant."
End
