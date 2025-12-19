# Getting Started with JavaScript

Welcome to my notes on the building blocks of web interactivity! If you’ve ever wondered how a website remembers your name or asks you a question, that’s **JavaScript (JS)** at work.

#### What is JavaScript?

JavaScript is a lightweight programming language used to make web pages dynamic. While it is most famous for running inside your **web browser** (client-side), it can also run on **servers** (server-side) using tools like Node.js. 

#### Talking to the Computer (and the User)

To make things happen, we need ways for the computer to show us information (**output**) and for us to give it information (**input**).

* **Showing Info:** Developers use `alert()` to create pop-ups, `document.write()` to put text directly onto a page, or `console.log()` to send secret messages to a "developer console" for debugging.
* **Asking Questions:** We can use `prompt()` to ask a user to type something in, or `confirm()` to ask a simple Yes/No question.

#### Storing Information

Because computers need to remember things (like a username or a score), we use **variables**. Think of these as **labels for data values** or **containers** for storing information. We have different ways to "create" these containers depending on if the information inside will stay the same (`const`) or change later (`let`).

***

### Frequently Asked Questions

**What are variables in JavaScript?**
Variables are **containers for storing data**. They allow programmers to give a unique name (called an **identifier**) to a piece of information so it can be used and referred to later in the code. For example, you might have a variable named `carName` that stores the value "Volvo".

**What does it mean to declare a variable?**
**Declaring** a variable is simply the act of **creating** it. In modern JavaScript, you declare a variable using the keywords **`let`** or **`const`**. If you declare a variable without giving it a value immediately (e.g., `let carName;`), it is technically "undefined" until you put something in it.

**What is an “assignment” operator, and what does it do?**
The **assignment operator** is the **equal sign (`=`)**. Unlike in math, where it means two things are the same, in JavaScript it is an action: it **assigns a value** to a variable. It calculates the value on the right side of the `=` and "puts" it into the variable named on the left side.

**What is information received from the user called?**
Information received from the user is called **input**. JavaScript can receive input through various methods, such as a **`prompt()`** window where a user types text into a box, or a **`confirm()`** box where a user clicks "OK" or "Cancel".

***

**Analogy for Understanding Variables**
Think of a **variable** as a **cardboard box** with a **label** on the outside. **Declaring** the variable is like picking out a new box and writing a name on it (like "Holiday Decorations"). Using the **assignment operator** (`=`) is the act of actually putting your decorations into that box. When the computer needs those decorations later, it just looks for the box with that specific label!