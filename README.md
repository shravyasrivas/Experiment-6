
---

# Experiment 6: Study of Conditional Statements in Python

---

### Aim: Study of Conditional Statements in Python

---

### Algorithms

#### Algorithm for Problem Statement 1: Check Whether a Number is Positive, Negative or Zero

Step 1: Start.

Step 2: Accept a number from the user.

Step 3: Check if the number is greater than zero using relational operator

Step 4: If true, print **"Positive number"**.

Step 5: Else if the number is less than zero, print **"Negative number"**.

Step 6: Otherwise, print **"Zero"**.

Step 7: Stop.

---

#### Algorithm for Problem Statement 2: Check Whether a Number is Even or Odd

Step 1: Start.

Step 2: Accept a number from the user.

Step 3: Use the modulus operator (%) to check divisibility by 2.

Step 4: If true, print **"Even number"**.

Step 5: Otherwise, print **"Odd number"**.

Step 6: Stop.

---

#### Algorithm for Problem Statement 3: Find the Greatest of Three Numbers

Step 1: Start.

Step 2: Accept three numbers from the user

Step 3: Compare the first number with the other two numbers.(and)

Step 4: If the first number is greatest, print **"a is greater"**.

Step 5: Else if the second number is greatest, print **"b is greater"**.

Step 6: Otherwise, print **"c is greater"**.

Step 7: Stop.

---

#### Algorithm for Problem Statement 5: Find Average and Grade (Three Subjects)

Step 1: Start.

Step 2: Accept marks of three subjects from the user.

Step 3: Calculate the average of the marks.

Step 4: Display the average marks.

Step 5: Determine and display the grade using conditional statements.

Step 6: Stop.

---

#### Algorithm for Problem Statement 6: Check Whether a Year is a Leap Year

Step 1: Start.

Step 2: Accept a year from the user.

Step 3: Check leap year conditions using modulus operator.((yr % 4 == 0 and yr % 100 !=0) or (yr % 400==0))

Step 4: If conditions are satisfied, print **"Year is leap"**.

Step 5: Otherwise, print **"Year is not leap"**.

Step 6: Stop.

---

#### Algorithm for Problem Statement 7: Print the Next Date

Step 1: Start.

Step 2: Accept date from the user in dd/mm/yyyy format.

Step 3: Separate day, month, and year using split() function.

Step 4: Determine the number of days in the given month.

Step 5: Validate the entered date.

Step 6: Increment the date accordingly.

Step 7: Display the next date.

Step 8: Stop.

---

#### Algorithm for Problem Statement 8: Check Whether a Character is a Vowel or Consonant

Step 1: Start.

Step 2: Accept a character from the user.

Step 3 Check whether the character belongs to a set of vowels using the set() function

Step 4: If true, print **"Vowel"**.

Step 5: Otherwise, print **"Consonant"**.

Step 6: Stop.

---

#### Algorithm for Problem Statement 9: Calculate Gross Salary

Step 1: Start.

Step 2: Accept Basic Salary using input().

Step 3: Calculate HRA and DA based on salary range:

• Salary ≤ 10,000

→ HRA = 20% of Salary

→ DA = 80% of Salary

• Salary ≤ 20,000

→ HRA = 25% of Salary

→ DA = 90% of Salary

• Salary > 20,000

→ HRA = 30% of Salary

→ DA = 95% of Salary

Step 4: Calculate:

Gross Salary = Basic Salary + HRA + DA

Step 5: Display Gross Salary.

Step 6: Stop.

---

#### Algorithm for Problem Statement 10: Calculate Income Tax

Step 1: Start.

Step 2: Accept Annual Income using input().

Step 3: Apply tax slab rules:

• Income ≤ 2,50,000 → Tax = 0

• Income ≤ 5,00,000 → Tax = 5% of Income

• Income ≤ 10,00,000 → Tax = 20% of Income

• Income > 10,00,000 → Tax = 30% of Income

Step 4: Calculate:

Tax = Income × Tax Rate / 100

Step 5: Display Tax Amount.

Step 6: Stop.

---

### Theory

Conditional statements in Python are used to make decisions based on conditions. The `if`, `elif`, and `else` statements allow the execution of specific blocks of code depending on whether a condition is true or false.

In this experiment, various decision-making programs were implemented using relational and logical operators to handle real-life scenarios such as grading systems, salary calculation, date validation, and tax computation.

---

#### Functions and Logic Used


Functions Used

• input() – Used to accept data from the user.

• split() – Used to separate date into day, month, and year.

• set() – Used to store vowel characters for membership checking.

---

#### Logic and Operators Used

• Conditional Statements (if, elif, else) – Used for decision making.

• Relational Operators (>, <, >=, <=, ==, !=) – Used for comparison.

• Modulus Operator (%) – Used to check divisibility (Even/Odd, Leap Year).

• *Arithmetic Operators (+, -, , /) – Used for calculations like average, salary, and tax.

• Nested Conditions – Used where multiple conditions are checked inside another condition.


---

### Conclusion

Through this experiment, the working and importance of conditional statements in Python were successfully studied. The experiment demonstrated how decision-making improves program flexibility and logic handling. Conditional statements are essential for implementing real-world applications in Python.

---

