Introduction — This program is made to calculate the grade you will get in the COSC-1436 6001 1 Programming Fundamentals I class using all the points you get on assigments along with assignment mnames.

Getting Started — Make sure you look at the instructions in the README.md file. Or Run: ./GradeCalculator

Step-by-Step Walkthrough — 
Prompt: Please input the Total Points Possible:
What it asks for: The maximum number of points available in the course.
Expected data type / format: A whole number (integer).
Constraints: Must be a positive integer greater than 0

Prompt: Please input the Minimum Points for a 'A':
What it asks for: The minimum score required to earn an A grade.
Expected data type / format: A whole number (integer).
Constraints:
Must be between 0 and the Total Points Possible.
Should be greater than the minimum points for lower grades (B, C, D).

Prompt: Please input the Minimum Points for a 'B':
What it asks for: The minimum score required to earn a B grade.
Expected data type / format: A whole number (integer).
Constraints:
Must be between 0 and the Total Points Possible.
Should be less than the A threshold and greater than the C threshold.

Prompt: Please input the Minimum Points for a 'C':
What it asks for: The minimum score required to earn a C grade.
Expected data type / format: A whole number (integer).
Constraints:
Must be between 0 and the Total Points Possible.
Should be less than the B threshold and greater than the D threshold.

Prompt: Please input the Minimum Points for a 'D':
What it asks for: The minimum score required to earn a D grade.
Expected data type / format: A whole number (integer).
Constraints:
Must be between 0 and the Total Points Possible.
Should be less than the C threshold.

Prompt: Please input the points earned for Assignment 1:
What it asks for: The score earned on the assignment.
Expected data type / format: A whole number or decimal number.
Constraints:
Normally should be between 0 and the Total Points Possible.
A negative number is a special sentinel value used to stop assignment entry and calculate the grade.

Prompt: Please input the name for Assignment 1:
What it asks for: The assignment’s name or label.
Expected data type / format: Text/string.
Constraints:
Cannot be empty.
May include letters, numbers, spaces, or symbols depending on implementation.

Prompt Pattern Repeats for Additional Assignments
For every additional assignment, the program repeats two prompts in order:
Please input the points earned for Assignment N:
Please input the name for Assignment N:
Assignment score input:
Whole number or decimal number.
Negative number ends input collection.

Termination Prompt Example: Please input the points earned for Assignment 11:
What it asks for: Either another assignment score or the stop signal.
Expected data type / format: Whole number or decimal number.
Any negative value (e.g., -1) immediately stops assignment entry.

Automatic Output
After termination, the program automatically displays:
Total Points Earned
Total Points Possible
Total Percentage
Final Letter Grade
Assignments sorted from highest to lowest score

Sentinel Value Explanation — If you input a negative number into an assingment score it ends input and triggers the calculation.

Sample Session — 
Good Evening!

Welcome to Your Grade Calculator!

Grading Scheme Setup
====================
Please input the Total Points Possible: 100
Please input the Minimum Points for a 'A': 90
Please input the Minimum Points for a 'B': 80
Please input the Minimum Points for a 'C': 70
Please input the Minimum Points for a 'D': 60

The Grading Scheme You Input
============================
Total Points Possible in the Course: 100
Points needed for an 'A': 9
Points needed for a 'B': 80
Points needed for a 'C': 70
Points needed for a 'D': 60

Grade Calculation
You will be prompted to input scores for all assignments.
(Input a negative number to cease input and calculate letter grade.)

Please input the points earned for Assignment 1: 10
Please input the name for Assignment 1: h
Please input the points earned for Assignment 2: 10
Please input the name for Assignment 2: j
Please input the points earned for Assignment 3: 10
Please input the name for Assignment 3: k
Please input the points earned for Assignment 4: 10
Please input the name for Assignment 4: l
Please input the points earned for Assignment 5: 10
Please input the name for Assignment 5: p
Please input the points earned for Assignment 6: 10
Please input the name for Assignment 6: o
Please input the points earned for Assignment 7: 10
Please input the name for Assignment 7: i
Please input the points earned for Assignment 8: 10
Please input the name for Assignment 8: u
Please input the points earned for Assignment 9: 10
Please input the name for Assignment 9: y
Please input the points earned for Assignment 10: 10
Please input the name for Assignment 10: t
Please input the points earned for Assignment 11: -1

Final Results
Total Points Earned: 100
Total Points Possible: 100
Total Percentage: 100%
Final Letter Grade: A

Assignments Sorted by Score (Highest to Lowest)
===============================================
h: 10 points
j: 10 points
k: 10 points
l: 10 points
p: 10 points
o: 10 points
i: 10 points
u: 10 points
y: 10 points
t: 10 points

Troubleshooting — 
A common mistake is putting a letter in the "Please input the points earned for Assignment 1:" prompt you should only use numbers here.
A common mistake is making the total points possible to small so total points earned are higher than the total points that are possible.
