# JavaScript Basics: Giving Orders and Doing Repetitions

Hey there! If you’ve ever wondered how computers make decisions or perform the same task a thousand times without getting tired, it all comes down to two main concepts: **operators** and **loops**. Here is a breakdown of what I’ve been learning.

### 1. Giving Values and Making Comparisons

In JavaScript, we use **operators** to handle data. Think of them like the verbs or symbols in a math sentence.

* **Assignment Operators**: These are used to give a value to something. The most basic one is the equals sign (`=`), which simply assigns the value on the right to the name on the left. There are also "shorthand" versions, like `+=`, which adds a new value to the existing one instead of just replacing it.
* **Comparison Operators**: These are used to "ask" the computer a question that results in a **true** or **false** answer. For example, you can check if one number is greater than another (`>`) or if two things are exactly equal (`===`). Interestingly, JavaScript has a "strict" equality check (`===`) that ensures both the value and the "type" (like a number vs. a word) are identical.

### 2. Loops: The Art of Repetition

**Loops** are like a computerized version of a simple command, such as "take five steps to the east". They allow us to repeat an action multiple times without writing the same code over and over again.

* **The `for` Statement**: This loop is great when you know exactly when you want to stop. It usually involves a counter that starts at a specific number, a rule for when to stop, and a way to update that counter after every "lap". 
* **The `while` Statement**: This is a bit simpler. It tells the computer to keep doing something as long as a specific rule is still **true**. It checks the rule *before* it starts each lap, so if the rule is false at the very beginning, the loop won't even run once.

***

### Common Questions

**What is an expression in JavaScript?**
At a high level, an expression is any valid unit of code that resolves to a specific value. For example, `3 + 4` is an expression because it resolves to `7`.

**Why would we use a loop in our code?**
We use loops because they offer a quick and easy way to perform the same action repeatedly. They save time and prevent us from having to write out the same command multiple times.

**When does a `for` loop stop executing?**
A `for` loop will continue to run its instructions until its specified condition evaluates to **false**. Once that condition is no longer met, the loop terminates immediately.

**How many times will a `while` loop execute?**
A `while` loop executes its statements **as long as the specified condition remains true**. This means it could run many times, or it could even run **zero times** if the condition is false from the very start.

***

**A helpful way to think about it:**
Imagine you are a coach at a track. An **Assignment operator** is like handing a baton to a runner—you are giving them something to hold. A **Comparison operator** is like the photo-finish camera—it simply reports "true" or "false" on who crossed first. A **`for` loop** is telling a runner to "run exactly 4 laps," while a **`while` loop** is telling them to "keep running as long as the sun is up."