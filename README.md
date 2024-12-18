##### Name: Neeraj Kumar 
##### Company: CODTECH IT SOLUTIONS 
##### ID: CT08DYJ 
##### Domain: Python Programming 
##### Duration: Dec to Jan 2025 
##### Mentor: Santhosh N

### Overview of the GPA Calculator Program
This program calculates the average grade, corresponding letter grade, and GPA based on the grades entered by the user. It’s an interactive console-based application designed for simplicity and usability.

### Purpose
To compute the average grade of multiple subjects.
To determine the letter grade (A-F) and corresponding GPA (Grade Point Average).
To practice and demonstrate concepts like:
Loops and conditionals.
Input validation.
Function usage in Python.
### Key Features
### Grade Entry:

Users can input grades for multiple subjects.
The program accepts grades from 0 to 100.
### Input Validation:

Ensures grades are numeric and within the valid range (0–100).
### Average and GPA Calculation:

Computes the average of all entered grades.
Determines the corresponding letter grade and GPA using a function.
### User-Friendly Interaction:

Allows users to keep entering subjects until they type done.
Displays clear results or a message if no grades are entered.
### How the Program Works
### Initialize Empty Dictionary:

grades = {} stores subject names as keys and grades as values.
### Loop for Subject Input:

Continuously prompts the user to input subject names and grades.
Ends when the user types "done".
### Input Validation:

Ensures grades are numbers between 0 and 100.
Rejects invalid inputs with appropriate error messages.
### Calculate Average:

Computes the average of all grades in the dictionary.
### Determine Letter Grade and GPA:

Uses the calculate_letter_gpa function to map the average to a letter grade and GPA.
### Display Results:

If grades are entered, prints:
Grades dictionary.
Average grade.
Letter grade.
GPA.
If no grades are entered, displays a message.

### Code Walkthrough
### Main Components
Function: calculate_letter_gpa

Takes the average grade as input and returns the corresponding letter grade and GPA.
Grade mapping:
A → 4.0
B → 3.0
C → 2.0
D → 1.0
F → 0.0
### Grades Input Loop

Allows the user to input multiple subjects and grades.
Validates each grade to ensure correctness.
### Final Calculation

Computes the average and uses the function to determine the final grade and GPA.
### Enhancements and Future Additions
### Expand Grade Categories:

Allow users to input weighted grades (e.g., quizzes, exams, assignments).
### Error Handling for Edge Cases:

Handle grades entered as strings or decimals robustly.
### Grade Reports:

Provide detailed reports like highest/lowest grade and total number of subjects.
### Save Grades to File:

Save the grades to a text file or load them from an existing file for persistence.
