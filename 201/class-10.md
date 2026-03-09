### **Troubleshooting JavaScript**

**1. Name some key differences between a Syntax Error and a Logic Error.**
*   **Syntax Errors** are typically **spelling or grammar mistakes** in the code that prevent the program from running at all or cause it to stop midway through execution. These errors usually come with **error messages** that identify where the problem is, making them relatively easy to fix.
*   **Logic Errors** occur when the syntax is correct, so the program runs successfully, but it **produces incorrect results** because the code does not perform as the developer intended. These are often **harder to fix** because there is typically no error message to point to the source of the problem.

**2. A few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.**

Some common errors include:

*   **TypeError: "x" is not a function:** This often occurs due to **incorrect casing or spelling** of a method, such as writing `addeventListener` instead of the correct `addEventListener`. 

*   **TypeError: "x" is null:** This happens when a variable meant to point to an HTML element contains nothing. In the lab, this was caused by a **missing dot (.) in a class selector** inside `querySelector()`. Adding the proper CSS selector fixed the reference.
*   **Logic Errors in Math:** In one instance, a random number generator always returned "1" because the code was rounding the decimal down to zero before adding one. I corrected this by **multiplying the random decimal by 100** before applying `Math.floor()`.
*   **SyntaxError (Missing Characters):** Errors such as "missing ) after argument list" or "missing } after function body" occur when **parentheses or curly braces** are left off. These were corrected by carefully checking the structure of function calls and conditional blocks.

**3. How will this topic continue to influence your long term goals?**

Developing strong troubleshooting skills is essential for any software developer's career. Learning these basics now will **save hours of frustration** and allow for **faster progression** through more complex coding challenges. Mastering the tools to find and fix errors independently makes a developer more efficient and self-reliant.

---

### **The JavaScript Debugger**

**1. Describe the JavaScript Debugger tool**

The JavaScript Debugger is a powerful tool built into modern web browsers that allows you to **pause the execution of your code** at any point to see exactly what is happening. Instead of just running the script and seeing it fail, the debugger lets you **watch the values of variables** in real-time and step through the code line-by-line to identify exactly where and why a problem is occurring.

**2. Define breakpoint.**

A **breakpoint** is a specific place you "mark" in your code where you want the browser to **pause execution**. This allows you to inspect the current state of the program at that exact moment to help identify bugs.

**3. Define call stack?**

The **call stack** is a section within the debugger that shows the **path the code took** to arrive at the current line. It lists the functions that were executed to get to the current point, helping you understand the sequence of events that led to a specific state or error.