# Student Grade Calculator

## Description
Student Grade Calculator is a simple Java console-based program that calculates a student's total marks, average percentage, and grade.

The user enters the number of subjects and then enters the marks for each subject. The program calculates the total and percentage and assigns a grade based on the percentage.

## Technologies Used
- Java
- Scanner class

## How the Program Works
1. The program asks for the number of subjects.
2. The user enters marks for each subject.
3. The program calculates the total marks.
4. It calculates the average percentage.
5. The program assigns a grade according to the percentage.
6. The final result is displayed on the screen.

## Grade Criteria

| Percentage | Grade |
|------------|-------|
| 90% and above | A |
| 80% - 89% | B |
| 70% - 79% | C |
| 60% - 69% | D |
| 40% - 59% | E |
| Below 40% | F |

## How to Run

### Using VS Code
1. Open `StudentGradeCalculator.java` in VS Code.
2. Make sure Java/JDK is installed.
3. Click the **Run** button above the `main()` method, or press `Ctrl + F5`.

### Using Terminal

Compile the program:

```bash
javac StudentGradeCalculator.java
```

Run the program:

```bash
java StudentGradeCalculator
```

## Example

```text
Enter number of subjects: 5
Enter marks for subject 1: 85
Enter marks for subject 2: 90
Enter marks for subject 3: 78
Enter marks for subject 4: 88
Enter marks for subject 5: 92

===== STUDENT RESULT =====
Total Marks: 433
Average Percentage: 86.6%
Grade: B
```

## Project Structure

```text
StudentGradeCalculator/
├── StudentGradeCalculator.java
└── README.md
```

## Features
- Accepts marks for multiple subjects
- Calculates total marks
- Calculates average percentage
- Assigns grade automatically
- Simple console-based interface
- Beginner-friendly Java program

## Author
Java Programming Project
