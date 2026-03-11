# Even or Odd Checker (Python)

A simple Python program that determines whether a number entered by the user is **even or odd**.

This beginner-friendly project helps new programmers practice **user input, conditionals, and the modulo operator** in Python.

---

## Features

* Prompts the user to enter a number
* Uses Python’s modulo operator `%` to check divisibility
* Determines whether the number is **even** or **odd**
* Displays the result in a clear message

---

## Example Output

```
Enter a number: 7
7 is an odd number.
```

```
Enter a number: 12
12 is an even number.
```

---

## Python Code

```python
number = int(input("Enter a number: "))

if number % 2 == 0:
    print(f"{number} is an even number.")
else:
    print(f"{number} is an odd number.")
```

---

## How It Works

The program uses the **modulo operator `%`**, which returns the remainder after division.

* If a number divided by **2** has a remainder of **0**, the number is **even**.
* If the remainder is **1**, the number is **odd**.

Example:

```
10 % 2 = 0  → Even
7 % 2 = 1   → Odd
```

---

## Requirements

* Python 3.x

Check your Python version:

```
python3 --version
```

---

## How to Run the Program

1. Save the file as:

```
even_or_odd.py
```

2. Open a terminal in the folder containing the file.

3. Run the program:

```
python3 even_or_odd.py
```

---

## What This Project Teaches

This project helps beginners practice several important Python concepts:

* `input()` for gathering user input
* `int()` for converting text to numbers
* The `%` modulo operator
* `if` / `else` conditional logic
* Using f-strings for clear output

---

## Future Improvements

Possible improvements to this program:

* Allow the user to check multiple numbers
* Add input validation to handle invalid entries
* Create a loop that keeps running until the user exits

---

## License

This project is open-source and intended for **learning and educational use**.


