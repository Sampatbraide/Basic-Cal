# Basic Python Calculator

A simple, beginner-friendly command-line calculator written in Python that performs basic arithmetic operations on two user-input numbers.

## Features

* **Addition**: Adds two numbers together.
* **Subtraction**: Subtracts the second number from the first.
* **Multiplication**: Multiplies two numbers.
* **Division**: Divides the first number by the second.
* Supports both integers and decimal (floating-point) numbers.

## Prerequisites

* Python 3.x installed on your machine. You can download it from [python.org](https://python.org).

## How to Run

1. **Clone the repository** (or download the script):
   ```bash
   git clone https://github.com
   cd your-repo-name
   ```

2. **Run the script**:
   ```bash
   python calculator.py
   ```
   *(Note: Replace `calculator.py` with the actual name of your Python file).*

## Example Usage

```text
Enter first number: 10
Enter second number: 5
Addition: 15.0
Subtraction: 5.0
Multiplication: 50.0
Division: 2.0
```

## Known Limitations

* **Division by Zero**: Entering `0` as the second number will cause a `ZeroDivisionError`.
* **Invalid Input**: Entering text instead of numbers will raise a `ValueError`.

## Future Improvements

* Add error handling (`try-except` blocks) for division by zero and non-numeric inputs.
* Allow users to choose a specific operation rather than displaying all four at once.
* Add a loop so users can perform multiple calculations without restarting the program.

## License

This project is open-source and available under the [MIT License](LICENSE).
