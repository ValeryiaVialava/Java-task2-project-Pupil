#### **TASK**

Using the **Pupil** and **Main** classes:

1. Create a custom exception **`WrongGradeException`**, which will be thrown when attempting to add a grade outside the range of 1–6.
2. Handle this exception in such a way that it does not terminate the program but instead allows the user to re-enter the grade.
3. Implement appropriate mechanisms (conditional statements or exception handling) for the following scenarios:
    - The student has **0 grades**: what happens if we try to display the average?
    - The student has **1 grade**: what happens if we try to display a second grade?
    - The user enters a **letter instead of a grade**.
    - The user enters a **letter in a method that displays the grade**.
    - Are these all possible exceptions?

4. Using the `finally` block, add a fragment so that after each menu operation, a message is displayed on the screen, e.g.,
   `****************END 1************************`

---

```
Name: 
Valeryia
Surname: 
Vialava
Number of grades: 
two
Please enter a valid number.
Number of grades: 
```

```
Name: 
Valeryia
Surname: 
Vialava
Number of grades: 
-1
Number of grades must be positive
Number of grades: 
3
Enter grades: 
-1
Grade must be between 1 and 6. Please, try again.
1
3
6
----------
1. Average
2. Print
3. Print grade
4. Exit
----------
1
average: 3.3333333333333335
****************END 1 ****************
----------
1. Average
2. Print
3. Print grade
4. Exit
----------
2
Valeryia Vialava has 3 grades
Grades: 1 3 6 
****************END 2 ****************
----------
1. Average
2. Print
3. Print grade
4. Exit
----------
3
Which grade: 
-1
Invalid grade
****************END 3 ****************
----------
1. Average
2. Print
3. Print grade
4. Exit
----------
3
Which grade: 
2
Grade: 3
****************END 3 ****************
----------
1. Average
2. Print
3. Print grade
4. Exit
----------
4
****************END 4 ****************
```

```
Name: 
Vialava
Surname: 
Valeryia
Number of grades: 
0
Enter grades: 
----------
1. Average
2. Print
3. Print grade
4. Exit
----------
1
average: NaN
****************END 1 ****************
----------
1. Average
2. Print
3. Print grade
4. Exit
----------
2
Vialava Valeryia has 0 grades
Grades: 
****************END 2 ****************
----------
1. Average
2. Print
3. Print grade
4. Exit
----------
3
Which grade: 
second
Please enter a valid number.
****************END 3 ****************
----------
1. Average
2. Print
3. Print grade
4. Exit
----------
```

