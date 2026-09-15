# Python Programming Tasks

This project contains three beginner-friendly Python programs demonstrating **loops, control statements, functions, and basic calculations**.

## 📌 Tasks Included

### Task 1: Number Guessing Game

A simple number guessing game using a `while` loop.

#### Concepts Used

* `while` loop
* `if`, `elif`, and `else`
* `break`
* `continue`
* `random.randint()`
* User input

#### How It Works

* The program generates a random number between **1 and 10**.
* The user gets **3 valid attempts** to guess the number.
* The program provides feedback if the guess is:

  * Too high
  * Too low
  * Correct
  * Out of range
* `continue` is used when the user enters a number outside the range of 1–10.
* `break` ends the loop when the correct number is guessed.
* The `while-else` block displays **"Better luck next time!"** when all attempts are used.

#### Example

```text
Guess the number (between 1 and 10): 2
Too low. Try again.
Guess the number (between 1 and 10): 8
Too high. Try again.
Guess the number (between 1 and 10): 5
Congratulations! You guessed the correct number.
```

---

### Task 2: Multiplication Table Generator

A program that generates the multiplication table for a number entered by the user.

#### Concepts Used

* `for` loop
* `range()`
* User input
* Arithmetic operations

#### How It Works

* The user enters a number.
* A `for` loop runs from **1 to 10**.
* The entered number is multiplied by each value.
* The result is displayed in multiplication-table format.

#### Example

```text
Enter the number for which you want the multiplication table: 5

5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50
```

---

### Task 3: BMI Calculator

A program that calculates a person's **Body Mass Index (BMI)** using a Python function.

#### Formula

```text
BMI = Weight (kg) / Height (m)²
```

#### Concepts Used

* Functions
* Function parameters
* `return`
* User input
* Floating-point numbers
* Arithmetic operations

#### How It Works

* The user enters their weight in kilograms.
* The user enters their height in meters.
* The `calculate_bmi()` function calculates the BMI.
* The result is displayed up to **2 decimal places**.

#### Example

```text
Enter your weight in kg: 58
Enter your height in meters: 1.62
Your BMI is: 22.10
```
