## Variables

**Variables** are basic building blocks of JavaScript. They are used to **store or refer to values** so those values can be used later in a program. For example, a variable can store the value returned from a `prompt()` function after a user enters information.

JavaScript allows variables to be used in flexible ways, including inside **functions** (often called **function variables**). Variables are created using **statements and declarations** with keywords such as `var`, `let`, and `const`. If you try to assign a value to a variable that has not been declared, JavaScript can throw a **`ReferenceError`**, which means the variable does not exist.

---

## Declaring a variable

To declare a variable involves using specific keywords listed under JavaScript's statements and declarations, such as `var`, `let`, or `const`. 

For example, a variable named `name` is declared using `let` in the statement `let name = prompt("Your name:", "");`.

In this example:

- var declares the variable

- name is the variable’s name

- The value returned by prompt() is stored in name

---

## “assignment” operator

The assignment operator is the equals sign (=). Its purpose is to assign a value to a variable. This means it connects the value on the right side of the operator to the variable on the left side.









The primary assignment operator is the equals sign (`=`). Its function is to associate a value with a variable, as seen when the value returned by `prompt()` is associated with the variable `name` using this operator: `var name = prompt(...)`.

JavaScript also features several compound assignment operators, including:

*   **Addition assignment** (`+=`)
*   **Bitwise AND assignment** (`&=`)
*   **Division assignment** (`/=`)
*   **Multiplication assignment** (`*=`)

---

## Information received from the user

Information received from the user is generally referred to as **input**. The sources describe two ways to receive this input: 
- using the `prompt()` function, which shows a pop-up window with a text box the user can fill in and returns the **value in the text box**
- using the `confirm()` function, which allows the developer to ask a Yes/No question and returns `true` or `false` based on the user's selection.