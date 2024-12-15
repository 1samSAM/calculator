
# Simple Calculator App

This is a **Simple Calculator Application** built using the **Kivy framework** in Python. The app features a responsive UI that allows users to perform basic arithmetic operations. It is a beginner-friendly project designed to demonstrate the use of **BoxLayout**, **GridLayout**, and interactive widgets like buttons and labels in Kivy.

---

## Features

- Perform basic arithmetic operations: addition, subtraction, multiplication, and division.
- Responsive user interface.
- Includes a **Clear** button to reset calculations.
- Error handling for invalid input (displays "Python Syntax error!" for invalid syntax).
- Dynamically resizes the label font based on its height for better visibility.

---

## Installation and Usage

### Prerequisites

- Python 3.x installed on your system.
- Kivy framework installed. You can install it using:
  ```bash
  pip install kivy
  ```

##Steps to Run

1. Clone this repository to your local machine:
```
git clone <repository_url>
cd <repository_name>
```

2. Run the Python script:

python calculator.py


3. Use the buttons on the UI to input numbers and operators. Click = to get the result or Clear to reset the calculation.




---

##Code Explanation

The main components of the app include:

1. Layouts:

BoxLayout for vertical stacking of widgets.

GridLayout for arranging the calculator buttons in a grid

2. Widgets:

Label: Displays the current input or result.

Button: For numeric and operator inputs as well as actions (= and Clear).



3. Event Handling:

Buttons are bound to functions for updating the display or performing calculations.



4. Dynamic Resizing:

The label font size adjusts dynamically with its height.





---

##File Structure

.
├── calculator.py       # Main Python script for the calculator
└── README.md           # Documentation file


---

##Example Screenshot

Once you run the app, the UI will resemble a typical calculator layout with a display label and buttons arranged in a grid format.


---

##License

This project is open-source and available under the MIT License. Feel free to use, modify, and distribute it as per the license terms.


---

Enjoy coding and happy learning!

You can copy and paste this code into a `README.md` file in your GitHub repository. Replace `<repository_url>` and `<repository_name>` with your actual repository details.


  
