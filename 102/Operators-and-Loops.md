# Operators and Loops

### <u>JavaScript expression</u>
An **expression** is any valid unit of code that **resolves to a value**.

There are two primary categories of expressions:

* **Expressions with side effects:** These resolve to a value but also perform an action, such as **assigning a value** to a variable (e.g., `x = 7` assigns the value seven to `x` and evaluates to 7).

* **Purely evaluating expressions:** These resolve to a value without altering the state of the program (e.g., `3 + 4` evaluates to 7).

### <u>Using a loop</u>

We use loops because they offer a quick and easy way to **perform an action repeatedly**. They allow a programmer to execute the same block of code a specific number of times or until a certain condition is met, essentially acting as a computerized way to handle repetitive tasks.

### <u>Excecuting the ending of a `for` loop</u>

A `for` loop stops executing when its **specified condition evaluates to false**. During the loop's execution cycle, the condition expression is checked; if it is found to be false, the loop terminates immediately, and the program moves to the next statement after the loop.

### <u>`while` loop execution characteristic</U>
The number of times a `while` loop executes depends entirely on its condition:

* **Zero or more times:** Because the condition is tested **before** the statement inside the loop is executed, a `while` loop will not run at all if the condition is initially false.

* **As long as the condition is true:** It will continue to repeat as long as the condition evaluates to true.

* **Forever:** If the condition never becomes false, the loop will result in an **infinite loop**, executing indefinitely.

---

**Analogy for Understanding Loops:**

You can think of a **loop** like a **track runner**. The **initialization** is the runner stepping onto the starting line, the **condition** is the official checking if the race is still ongoing (e.g., "Have you finished 10 laps yet?"), and the **afterthought** is the runner completing a lap and incrementing their lap count. The runner keeps going as long as the condition to continue is "true," but as soon as they reach their goal and the condition becomes "false," they stop running.