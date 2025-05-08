# Basic Calculator 🧮

This project is a simple GUI-based calculator built using C# and Windows Forms. It performs basic arithmetic operations such as addition, subtraction, multiplication, and division. The calculator is designed to be intuitive, with a clean and aesthetically pleasing interface. ✨

## Project Overview
The application is a basic calculator with the following features:
- **Numeric Input (0-9) 🔢**: Buttons for numbers 0 through 9.
- **Operators ➕➖✖️➗**: Addition, subtraction, multiplication, and division.
- **Special Buttons 🧹**: Clear Entry (CE), Clear (C), Decimal Point (.), and Equals (=).
- **Aesthetic Design 🎨**: Customizable font styles, sizes, and colors.

## Instructions for Setup 🛠️

### Form Properties
1. **Appearance**:
    - Text: `Basic Calculator 🧮`
    - FormBorderStyle: `Fixed Single` 🔒
    - Customize font styles, sizes, backgrounds, and colors. 🎨
2. **Design**:
    - Name: `frmCalculator` 🖼️
3. **Layout**:
    - StartPosition: `Center Screen` 🎯
4. **Window Style**:
    - MaximizeBox: `False` 🚫

### Controls 🖱️
Add the following controls to the form:

| Control                | Name        | Property Value               |
|------------------------|-------------|------------------------------|
| Text Box               | txtInput    | ✏️                            |
| Button (0-9)           | btn<Number> | Example: `btn1` 🔢            |
| Clear Entry (CE)       | btnCE       | `CE` 🧹                       |
| Clear (C)              | btnClear    | `C` 🧽                        |
| Addition (+)           | btnAdd      | `➕`                          |
| Subtraction (-)        | btnMinus    | `➖`                          |
| Multiplication (*)     | btnMultiply | `✖️`                         |
| Division (/)           | btnDivide   | `➗`                          |
| Equal (=)              | btnEqual    | `=` ✅                        |
| Point (.)              | btnPoint    | `.` 🔘                        |

### Event Handlers ⚙️
1. **Numeric and Decimal Buttons**:
    - Assign the `Click` event handler: `button_click` 🖱️.
2. **Operator Buttons (+, -, *, /)**:
    - Assign the `Click` event handler: `operator_click` ➕➖✖️➗.

## Expected Output ✅
The calculator should:
1. Accept numeric input via buttons. 🔢
2. Perform basic arithmetic operations. ➕➖✖️➗
3. Clear the input field when CE or C is pressed. 🧹
4. Display results in the `txtInput` text box. 📋

## Customization 🎨
Feel free to adjust the layout and appearance to suit your preferences, as long as the calculator behaves as described. 🌟

## Tools Used 🛠️
- **Microsoft Visual Studio**: IDE for developing the Windows Forms application. 🖥️
- **C#**: Programming language for logic implementation. 🖋️

## How to Run ▶️
1. Open the project in Visual Studio. 🛠️
2. Build and run the application using the Start button. 🚀
3. Interact with the calculator to perform calculations. ✍️

## Contact ✉️
If you encounter any issues or need further assistance, feel free to reach out!
