# Python Fundamentals

## Overview

This project contains a Python program that calculates the area of a circle using a user-provided radius.

The program demonstrates:

- User input collection
- Input validation
- Exception handling
- String manipulation
- Mathematical calculations
- Program documentation

---

## Program Files

### area_circle.py

This program:

1. Prompts the user to enter their name.
2. Removes leading and trailing whitespace from the name.
3. Displays the name in uppercase as a string transformation example.
4. Counts the number of characters in the name as a string analysis example.
5. Prompts the user to enter a radius.
6. Validates that the radius is a numeric value.
7. Calculates the area of a circle using the formula:

Area = π × radius²

The value of π used is 3.14.

8. Displays the calculated area to the user.

---

## How to Run the Program

1. Open a terminal or command prompt.
2. Navigate to the project folder.
3. Run the following command:

```bash
python area_circle.py
```

or

```bash
python3 area_circle.py
```

depending on your Python installation.

---

## Assumptions

- The user enters a valid name.
- Radius values may be entered as whole numbers or decimal numbers.
- The program will continue prompting until a valid radius is entered.
- The area is displayed using the value 3.14 for π.

---

## String Manipulation Demonstrated

### Transformation

- Converts the user's name to uppercase using `.upper()`

Example:

```text
Input:  grae
Output: GRAE
```

### Analysis

- Counts the number of characters in the user's name using `len()`

Example:

```text
Name: Grae
Character Count: 4
```

---

## Exception Handling

The program uses `try` and `except` blocks to handle invalid numeric input.

Example:

```text
Enter radius: abc
Invalid input. Please enter a numeric value.
```

The user is then prompted again until a valid number is entered.

---

## Testing Performed

### Test Case 1: Valid Integer Input

Input:

```text
Radius = 5
```

Expected Result:

```text
Area = 78.5
```

Result: Pass

---

### Test Case 2: Valid Decimal Input

Input:

```text
Radius = 2.5
```

Expected Result:

```text
Area = 19.625
```

Result: Pass

---

### Test Case 3: Invalid Text Input

Input:

```text
Radius = hello
```

Expected Result:

```text
Error message displayed and user prompted again
```

Result: Pass

---

### Test Case 4: Empty Input

Input:

```text
Radius =
```

Expected Result:

```text
Error message displayed and user prompted again
```

Result: Pass

---

### Edge Case Tested

Input:

```text
Radius = 0
```

Expected Result:

```text
Area = 0
```

Result: Pass

---

## Author

Created for the Python Fundamentals assignment.
