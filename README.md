
# 🔢 Calculator App — Mini Project

A simple calculator built using **HTML**, **CSS**, and **JavaScript**, capable of performing basic arithmetic operations like addition, subtraction, multiplication, and division.

## 🚀 Features

- Responsive and clean UI
- Click-based input system
- Real-time display updates
- Basic error handling (`Error` message on invalid input)
- Clear and backspace functionality

## 📁 Project Structure

```
Calculator/
├── index.html       # Main HTML structure
├── style.css        # Styling for calculator layout and buttons
└── script.js        # JavaScript logic for calculations
```

## 🧱 Technologies Used

- **HTML5**
- **CSS3** (Flexbox + Grid)
- **Vanilla JavaScript**

## 🖼️ UI Overview

- **Display Area**: Shows current input and results
- **Buttons**:
  - Digits: 0–9
  - Operators: +, –, ×, ÷
  - Clear (`C`), Backspace (`⌫`), Decimal (`.`), Equal (`=`)
- **Layout**: 
  - Grid-based button layout
  - Styled using CSS with modern UI design principles

## 🧠 JavaScript Functionalities

- `appendValue(val)`: Appends input to the display
- `clearDisplay()`: Clears all input
- `deleteLast()`: Removes last character from input
- `calculate()`: Evaluates the expression using `eval()`
  - Displays "Error" if evaluation fails

## 📷 Screenshot (optional)

> *(Add a screenshot of your calculator UI here if hosting on GitHub)*

## 🛠️ How to Use

1. Clone or download the repository
2. Open `index.html` in a web browser
3. Use the calculator with mouse clicks

## ⚠️ Note

> ⚠️ This app uses `eval()`, which is not secure for production applications. Avoid using `eval()` in larger or real-world apps — use a math parser library instead.

## ✅ Topics Covered (for Learning)

- HTML: Structure, semantic tags, buttons, inputs
- CSS: Flexbox, Grid, styling buttons and fields
- JavaScript: DOM manipulation, event handling, function calls
