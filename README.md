
# **Simple Python Calculator** 🧮

A command-line calculator that performs basic arithmetic operations (addition, subtraction, multiplication, division) based on user input.

## **Features** ✨
- Supports **integers and decimals** (smart conversion).
- Handles **four operations**: `+`, `-`, `*`, `/`.
- Prevents **division by zero** errors.
- Clear, formatted output (e.g., `5 + 3 = 8`).

## **How to Run** ▶️
1. Ensure you have **Python 3** installed.
2. Download or copy the code into a file (e.g., `calculator.py`).
3. Run in terminal/command prompt:
   ```bash
   python calculator.py
   ```
4. Follow the prompts to enter numbers and an operation.

## **Example Usage** 📝
```
Enter the first number: 10
Enter the second number: 5
Enter the operation (+, -, *, /): +
10 + 5 = 15
```

## **Code Overview** 🔍
```python
def get_number(prompt):
    # Converts input to int if possible, otherwise float
    ...

# Main logic: Takes input, performs operation, prints result
...
```

## **Customize** 🛠️
- To **force integers only**, replace `get_number()` with `int(input())`.
- To **add more operations** (e.g., exponent `**`), extend the `if-elif` blocks.
