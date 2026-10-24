# Unit-of-Measurement-Converter

## Project Overview
This is a beginner Python project that converts measurements between inches, feet, and yards. It is a command-line application that accepts user input, checks the selected units, performs the conversion, and displays the result.

I built this project to practise Python fundamentals, including conditional statements, user input, data type conversion, and formatted output.

## Features
- Convert inches to feet.
- Convert inches to yards.
- Convert feet to inches.
- Convert feet to yards.
- Convert yards to inches.
- Convert yards to feet.
- Accept different spellings and abbreviations of measurement units.
- Display conversion results rounded to two decimal places where appropriate.
- Handle invalid unit selections with error messages.

## Technologies Used
- **Python 3**
- `input()` for collecting user input.
- `if`, `elif`, and `else` statements for decision-making.
- `int()` for converting numeric input from strings to integers.
- F-strings for formatted output.
- `round()` and numeric formatting for displaying results.

## Conversion Rules

| Conversion | Formula |
|---|---|
| Inches to feet | Inches ÷ 12 |
| Inches to yards | Inches ÷ 36 |
| Feet to inches | Feet × 12 |
| Feet to yards | Feet ÷ 3 |
| Yards to inches | Yards × 36 |
| Yards to feet | Yards × 3 |

## How to Run the Project

1. Download or clone this repository.
2. Open the .ipynb file using Jupyter Notebook, JupyterLab, or Visual Studio Code with the Jupyter extension installed.
3. Run the notebook cells in order.
4. Enter the measurement value and units when prompted.
5. View the converted measurement in the output.
   

## Example 

```
Enter Starting Unit of Measurement (inches, feet, yards): inches
Enter Unit of Measurement to Convert to (inches, feet, yards): feet
Enter Starting Measurement in Inches: 24

Result: 24 inches = 2.0 feet
```

## What I Learned
Through this project, I practised:

- Collecting and processing user input.
- Converting data types using `int()`.
- Using conditional statements to control program flow.
- Handling multiple accepted inputs with lists and the `in` operator.
- Formatting output using f-strings.
- Applying mathematical formulas to solve a practical problem.


## Author
Created as part of my journey to develop my Python programming skills and build a portfolio of practical projects.
