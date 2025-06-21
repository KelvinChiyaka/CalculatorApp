Simple Calculator App

A basic web-based calculator built using **HTML**, CSS, and JavaScript. This version supports simple arithmetic operations including addition, subtraction, multiplication, and division. Future updates will support more advanced and complex calculations.

Features

- User-friendly calculator interface styled using HTML `<table>` layout
- Input display at the top for showing current calculations and results
- Digit buttons (`0–9`)
- Operators: `+`, `-`, `x`, `/`
- Clear button (`AC`) to reset the input
- `=` button to compute the result

🚀 Getting Started

To run the calculator:

1. Clone or download the repository.
2. Open the `index.html` file in any modern web browser.

📁 File Structure
.
├── index.html        # Main calculator interface and logic
├── style.css         # Styling for the layout and buttons
└── README.md         # Project documentation

🛠️ How It Works

- **digitBtnPressed(button)**: Handles number key presses and updates the input display.
- **operatorBtnPressed(operator)**: Stores the first number and operator for the operation.
- **calculate()**: Performs the calculation based on the operator and displays the result.
- **btnACPressed()**: Clears the input and resets the state.

🎨 Styling (CSS Highlights)

- Calculator styled to take 100% width and height using `vw` and `vh` units.
- Different button colors for digits, operators, and the AC (reset) button.
- Responsive, clean visual layout with large, readable font.

🧠 Future Enhancements

- Add support for decimal values (`.`)
- Add keyboard input support
- Implement parentheses and operator precedence
- Add scientific functions (e.g., square root, exponents)
- Use `parseFloat()` instead of `parseInt()` for full decimal support
- Transition from `table` to modern `div` layout with Flexbox or Grid

✅ Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript

📬 Contributions

Pull requests and suggestions for improvement are welcome.

DevKel.
