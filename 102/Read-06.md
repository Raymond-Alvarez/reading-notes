
**Variables** are fundamental components of JavaScript used to hold or refer to values, such as the value returned from a `prompt()` function. JavaScript supports dynamic capabilities like **function variables**. Variables are associated with **statements and declarations** using keywords like `var`, `let`, and `const`, and assigning a value to an undeclared variable can result in a `ReferenceError`.

---

To declare a variable involves using specific keywords listed under JavaScript's statements and declarations, such as `var`, `let`, or `const`. For example, a variable named `name` is declared using `var` in the statement `var name = prompt("Your name:", "");`.

---

The primary assignment operator is the equals sign (`=`). Its function is to associate a value with a variable, as seen when the value returned by `prompt()` is associated with the variable `name` using this operator: `var name = prompt(...)`.

JavaScript also features several compound assignment operators, including:

*   **Addition assignment** (`+=`)
*   **Bitwise AND assignment** (`&=`)
*   **Division assignment** (`/=`)
*   **Multiplication assignment** (`*=`)

---

Information received from the user is generally referred to as **input**. The sources describe two ways to receive this input: 
- using the `prompt()` function, which shows a pop-up window with a text box the user can fill in and returns the **value in the text box**
- using the `confirm()` function, which allows the developer to ask a Yes/No question and returns `true` or `false` based on the user's selection.