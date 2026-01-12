# Dynamic web pages with JavaScript

### <u>Variables</u>

**Variables** are basic building blocks of JavaScript. They are used to **store or refer to values** so those values can be used later in a program. For example, a variable can store the value returned from a `prompt()` function after a user enters information.

JavaScript allows variables to be used in flexible ways, including inside **functions** (often called **function variables**). Variables are created using **statements and declarations** with keywords such as `var`, `let`, and `const`. If you try to assign a value to a variable that has not been declared, JavaScript can throw a **`ReferenceError`**, which means the variable does not exist.

---

### <u>Declaring a variable</u>

To declare a variable involves using specific keywords listed under JavaScript's statements and declarations, such as `var`, `let`, or `const`. 

For example, a variable named `name` is declared using `let` in the statement

- `let name = prompt("Your name:", "");`

In this example:

- `let` declares the variable

- `name` is the variable’s name

- The value returned by `prompt()` is stored in name

---

### <u>“assignment” operator</u>

The **assignment operator** is the equals sign (`=`). Its purpose is to assign a value to a variable. This means it connects the value on the right side of the operator to the variable on the left side.

Example:

- `var name = prompt(...);`

Here, the value returned by `prompt()` is assigned to the variable name.

JavaScript also includes **compound assignment operators**, which combine an operation with assignment. These operators modify the existing value of a variable rather than replacing it entirely. 

Common examples include:

- **Addition assignment** `(+=)`

- **Bitwise AND assignment** `(&=)`

- **Division assignment** `(/=)`

- **Multiplication assignment** `(*=)`

---

### <u>Information received from the user</u>

Information entered by a user is referred to as **input**. JavaScript provides built-in functions that allow programs to receive this input and respond to it.

Two common ways to receive user input are:

- `prompt()`

    Displays a pop-up window with a text box that the user can fill in. The function returns the value typed into the text box.

- `confirm()`

    Displays a Yes/No (OK/Cancel) pop-up window and returns true or false based on the user’s selection.

These input methods allow JavaScript programs to interact with users and make decisions based on their responses.
