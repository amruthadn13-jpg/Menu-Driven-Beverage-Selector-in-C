# Menu-Driven Beverage Selector in C

## Overview

This project is a simple C program that demonstrates the use of the `switch` statement for decision-making.

The program simulates a basic beverage ordering system where a predefined choice is used to display the selected drink.

---

## Concepts Covered

* `switch` statement
* `case` labels
* `break` statement
* `default` case
* Output using `printf()`

---

## Project Description

The program stores a numeric value in the variable `choice`.

Based on the value:

* `1` → Coffee
* `2` → Tea

The `switch` statement checks the value and displays the corresponding output.

If the entered value does not match any case, the program prints:

```text id="2m98bo"
Invalid choice
```

---

## Sample Output

```text id="2fjntm"
You ordered Tea
```

---

## How It Works

### Choice Variable

```text id="6uq1fu"
int choice = 2;
```

Stores the selected menu option.

### Switch Statement

```text id="fl2g8f"
switch(choice)
```

Checks the value of `choice`.

### Case Statements

```text id="d0my09"
case 1:
case 2:
```

Execute different blocks based on the selected option.

### Default Case

```text id="j6vlfj"
default:
```

Runs when no matching case is found.

---

## Learning Outcomes

* Understanding menu-driven programs
* Using switch-case for multiple conditions
* Writing cleaner decision-making logic
* Understanding the role of `break`

---

## Real-World Applications

Switch-case statements are commonly used in:

* ATM systems
* Calculator applications
* Menu-based programs
* Embedded systems
* Console applications

---

## Author

Amrutha D N
