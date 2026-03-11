# Tip Calculator (Python)

A simple Python program that calculates a tip based on a bill amount.
This project is designed for beginners learning **user input, variables, and basic math in Python**.

## Features

* Asks the user for the bill amount
* Calculates a tip percentage
* Displays the tip clearly in one sentence
* Beginner-friendly Python code

## Example Output

```
Enter the bill amount: 45
On a bill of $45.00, a 20% tip is $9.00
```

## How It Works

1. The program asks the user to enter the bill amount.
2. The input is converted to a number using `float()`.
3. A tip percentage is applied.
4. The result is printed in a clear sentence.

## Python Code

```python
bill = float(input("Enter the bill amount: "))
tip_percent = 0.20

tip = bill * tip_percent

print(f"On a bill of ${bill:.2f}, a 20% tip is ${tip:.2f}")
```

## Requirements

* Python 3.x

Check your version:

```
python3 --version
```

## How to Run

1. Save the file as `tip_calculator.py`
2. Open a terminal
3. Run the program:

```
python3 tip_calculator.py
```

## What This Project Teaches

* `input()` for user interaction
* `float()` for number conversion
* Basic math operations
* f-strings for clean output formatting

## Future Improvements

* Let the user choose the tip percentage
* Split the bill between multiple people
* Add error handling for invalid input

## License

This project is open-source and free to use for learning.

