# **Basic Calculator 🧮**

This project is a simple GUI-based calculator built using C# and Windows Forms. It performs basic arithmetic operations such as addition, subtraction, multiplication, and division. The calculator is designed to be intuitive, with a clean and aesthetically pleasing interface. ✨

---

## **Project Overview**

The application is a basic calculator with the following features:
- **Numeric Input (0-9)** 🔢: Buttons for numbers 0 through 9.
- **Operators** ➕➖✖️➗: Addition, subtraction, multiplication, and division.
- **Special Buttons** 🧹: Clear Entry (CE), Clear (C), Decimal Point (.), and Equals (=).
- **Aesthetic Design** 🎨: Customizable font styles, sizes, and colors.

---

## **Instructions for Setup** 🛠️

### **Form Properties**
1. **Appearance**:
   - `Text`: **Basic Calculator** 🧮
   - `FormBorderStyle`: **Fixed Single** 🔒
   - Customize font styles, sizes, backgrounds, and colors. 🎨
2. **Design**:
   - `Name`: **frmCalculator** 🖼️
3. **Layout**:
   - `StartPosition`: **Center Screen** 🎯
4. **Window Style**:
   - `MaximizeBox`: **False** 🚫

---

### **Controls** 🖱️

Add the following controls to the form:

| **Control**         | **Name**      | **Property Value** |
|----------------------|---------------|---------------------|
| **Text Box**         | `txtInput`    | ✏️                  |
| **Button 0-9**       | `btn<Number>` | Example: `btn1` 🔢  |
| **Clear Entry (CE)** | `btnCE`       | CE 🧹               |
| **Clear (C)**        | `btnClear`    | C 🧽                |
| **Addition (+)**     | `btnAdd`      | ➕                  |
| **Subtraction (-)**  | `btnMinus`    | ➖                  |
| **Multiplication (*)**| `btnMultiply`| ✖️                  |
| **Division (/)**     | `btnDivide`   | ➗                  |
| **Equal (=)**        | `btnEqual`    | = ✅                |
| **Point (.)**        | `btnPoint`    | . 🔘               |

---

### **Event Handlers** ⚙️

1. **Numeric and Decimal Buttons**:
   - Assign the `Click` event handler: **button_click** 🖱️.

2. **Operator Buttons (+, -, *, /)**:
   - Assign the `Click` event handler: **operator_click** ➕➖✖️➗.

---

### **Code Implementation** 💻

Refer to the following code snippets for handling button click events:

#### **Numeric and Decimal Buttons**
```csharp
private void button_click(object sender, EventArgs e)
{
    Button button = (Button)sender;
    if (txtInput.Text == "0")
        txtInput.Clear();

    txtInput.Text += button.Text;
}
