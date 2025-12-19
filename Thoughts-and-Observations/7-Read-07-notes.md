# JavaScript Fundamentals for Beginners

Welcome! If you're curious about how websites actually "do" things, you're in the right place. We are looking at the basic building blocks of **JavaScript**, the language that makes the web interactive.

#### How a Computer Reads Code (**Control Flow**)

Normally, a computer reads a script like a person reads a book: **from the first line to the last line, in order**. This is known as **control flow**. However, scripts can become complex. For instance, a script might need to check if a user filled out a form correctly. If a field is empty, it shows a prompt; if it's full, it submits the data. To handle these "if/then" scenarios, we use structures like **conditionals** and **loops** to change that straight-line path into a more dynamic one.

#### The Tools and Math (**Expressions and Operators**)

In JavaScript, an **expression** is any unit of code that resolves to a value. We use **operators** to perform actions on these values. Think of these as the mathematical and logical symbols you already know, plus a few special ones:

* **Assignment (`=`):** Used to "save" a value into a variable.
* **Arithmetic:** Common symbols like **`+`** (addition), **`-`** (subtraction), and **`*`** (multiplication).
* **Comparison:** Symbols like **`>`** (greater than) or **`===`** (strictly equal) that return a simple **true** or **false**.
* **Concatenation:** Interestingly, the **`+`** symbol can also be used to "glue" strings (text) together. If you add a number and a string, JavaScript turns the whole thing into a string (e.g., `5 + "5"` becomes `"55"`).

#### The Reusable Factories (**Functions**)

A **function** is a **reusable block of code** designed to perform one specific task. Instead of writing the same steps ten times, you write them once inside a function and use it whenever you need it. This makes code more organized and efficient.

***

### Frequently Asked Questions

**What is control flow?**
**Control flow** is the specific **order in which a computer executes the statements** in a script. While code generally runs from top to bottom, control flow can be altered by structures like **conditionals** (if/else), **loops** (repeating code), and **functions**, which tell the computer to jump to different parts of the script.

**What is a JavaScript function?**
A **JavaScript function** is a fundamental building block of programming. It is a **reusable block of code** defined with the `function` keyword, followed by a name and a specific task it is meant to perform. Functions help keep code efficient because you can write a process once and use it many times with different inputs.

**What does it mean to invoke — or call — a function?**
To **invoke** or **call** a function means to **execute the code** inside of it. This is done using the **`()` operator**. A function can be called by other parts of the JavaScript code, triggered by a user action (like clicking a button), or even set to run automatically. If you try to access a function name *without* the parentheses, you are simply looking at the "function object" itself rather than running it to get a result.

**What are the parentheses `()` for when you define a function?**
When defining a function, the parentheses are used to list **optional parameters**. **Parameters** are essentially placeholder names for the values (called **arguments**) that the function will receive and use when it is eventually called. Even if a function doesn't need any outside information to do its job, the parentheses are still part of the required syntax.

***

**Analogy for Understanding Functions**
Think of a **function** as a **recipe** in a cookbook. **Defining** the function is like writing the recipe down: it lists the ingredients needed (**parameters**) and the steps to follow (**the code block**). **Invoking** the function is like actually cooking the meal—you take specific ingredients (**arguments**) and follow the instructions to get a finished dish (**the return value**). You can use that same recipe (function) over and over again whenever you're hungry!