# 🧮 Calculator Using Python

A simple command-line calculator application developed using Python. This project performs basic arithmetic operations such as addition, subtraction, multiplication, and division through an interactive terminal interface.

The project was created to strengthen Python programming fundamentals, including functions, conditional statements, loops, user input handling, and error handling.

---

## 🚀 Features

✅ Addition Operation

✅ Subtraction Operation

✅ Multiplication Operation

✅ Division Operation

✅ Division by Zero Error Handling

✅ User-Friendly Command-Line Interface

✅ Input Validation

✅ Multiple Calculations in a Single Session

---

## 🛠️ Technologies Used

- Python 3

---

## 📂 Project Structure

Calculator-Python/
│
├── calculator.py
├── README.md
└── screenshot.png

---

## 📋 How It Works

1. User selects an operation:
   - Addition
   - Subtraction
   - Multiplication
   - Division

2. User enters two numbers.

3. The calculator performs the selected operation.

4. Result is displayed on the screen.

5. User can continue performing calculations until they choose to exit.

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/maidursumanth/Calculator-Python.git
```

### Navigate to the Project Folder

```bash
cd Calculator-Python
```

### Run the Program

```bash
python calculator.py
```

---

## 📸 Sample Output

```text
Select operation:

1. Add
2. Subtract
3. Multiply
4. Divide

Enter choice (1/2/3/4): 1

Enter first number: 10

Enter second number: 20

10 + 20 = 30

Do you want to perform another calculation? (yes/no): yes
```

---

## 💻 Source Code Overview

### Addition Function

```python
def add(x, y):
    return x + y
```

### Subtraction Function

```python
def subtract(x, y):
    return x - y
```

### Multiplication Function

```python
def multiply(x, y):
    return x * y
```

### Division Function

```python
def divide(x, y):
    if y == 0:
        return "Error! Division by zero."
    return x / y
```

---

## 🎯 Learning Outcomes

Through this project, I learned:

- Python Functions
- Conditional Statements (if-elif-else)
- Loops (while)
- User Input Handling
- Error Handling
- Program Flow Control
- Problem Solving
- Command-Line Application Development

---

## 🔮 Future Enhancements

- Scientific Calculator Functions
- Graphical User Interface (GUI)
- History of Calculations
- Percentage Calculations
- Square Root Function
- Power and Exponential Operations
- Improved Input Validation

---

## 📈 Project Highlights

- Beginner-Friendly Python Project
- Clean and Readable Code
- Interactive User Experience
- Handles Invalid Division Operations
- Demonstrates Core Python Concepts

---

## 👨‍💻 Author

### Sumanth

GitHub: https://github.com/maidursumanth

LinkedIn: https://www.linkedin.com/in/your-linkedin-profile

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

It helps others discover the project and motivates further improvements.
