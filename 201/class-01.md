# My Web Development Study Guide

### **A Poem of HTTP**

Think of the internet as a busy neighborhood:

A client knocks, a server hears,  
The language of **HTTP** appears.  
Down the **TCP/IP** highway it speed-runs,  
In tiny **packets**, like data-filled buns.  
A request goes out, a "**200 OK**" comes back,  
Bringing the website files in a digital sack!

---

### **How Browsers Process Files**

Think of a browser as a **chef** following a recipe to build a webpage. It takes three different "ingredients" and mixes them together:

* **HTML** is the **skeleton** and defines the structure. It decides where the bones go (headings, paragraphs, and lists).
* **CSS** is the **outfit**. It’s the styling language that picks the colors, the cool fonts, and uses the **box model** to make sure everything has enough "personal space" (margins and padding).
* **JavaScript** is the **brain**. It’s the programming language that makes the page *do* things, like popping up an alert when you click a button or making an animation move.



---

### **Finding Images for a Website**

You can’t just grab any image you find on **Google Images**—that's like taking someone’s art without asking! Most images have a "no-touch" rule called copyright. 

* **The Safe Way:** Click the **"Tools"** button under the search bar, hit **"Usage rights,"** and pick **"Creative Commons licenses."** * This shows you "borrow-friendly" images you can use for your project without getting into legal trouble.

---

### **Creating Strings vs. Numbers in JavaScript**

In JavaScript, the computer needs to know if it’s looking at "words to read" or "math to do."

* **Strings (Text):** These are always "wearing a seatbelt." You wrap them in **quotes** (`"Hello"`) or **backticks** (`` `Mozilla is cool` ``). If you want to drop a name into a sentence, use the `${}` trick inside backticks.
* **Numbers (Math):** These are "free-range." You just type the digits (like `600` or `10`). If you put quotes around a number (like `"10"`), the computer treats it like a word and won't let you do math with it!

---

### **What is a Variable and Why is it Important?**

A **variable** is basically a **labeled shoebox**. You put something inside it so you can find it and use it later.

* **Storage:** You can save a player’s score or a username in a box labeled `userScore` or `userName`.
* **Holding Objects:** You can even use a variable to "hold onto" a piece of your website, like a specific button, so you can tell that button what to do later.
* **Reusability:** Instead of typing "Mozilla is the best browser in the world" ten times, you save it once in a variable and just use the label whenever you need it.



---

### **Designing a Website**

The biggest mistake people make is coding before they **think**. You need a plan!

* **The Golden Question:** Ask yourself, ***"What exactly do I want to accomplish?"*** * **Brainstorm:** List your goals. Do you want to share your music? Sell custom stickers? Find a lost cat?
* **Prioritize:** Put your "must-haves" at the top and "maybe-laters" at the bottom.
* **Reality Check:** Do you actually *need* a custom-built site? Sometimes a simple social media page or an existing service works faster. Build from scratch only when you need something unique!

---

### **\<h1> vs. \<span>**

Imagine reading a newspaper where every single word was the same size. You'd be lost!

* **`<h1>` is a "Signpost":** It tells the computer, "Hey! This is the most important title on the page!" This is called **semantic** HTML.
* **`<span>` is "Invisible":** You can use CSS to make a `<span>` look big and bold like a heading, but the computer won't know it's a heading. 
* **The Goal:** Use the right tag for the right job so the computer understands the *meaning* of your content, not just the look.

---

### **Benefits of Using Semantic Tags**

Using specific tags like `<header>`, `<nav>`, and `<footer>` instead of just using generic `<div>` boxes for everything is a "pro-move" for several reasons:

1.  **SEO (Google Search):** Search engines give extra "points" to words found inside semantic tags.
2.  **Accessibility:** Screen readers (for people who can't see the screen) use these tags like a GPS to navigate the page.
3.  **Clean Code:** It’s much easier to find your "Navigation" code if it's inside a `<nav>` tag instead of `div #42`.
4.  **Clarity:** It tells other coders exactly what kind of data is inside that section.
5.  **Standard:** It’s how the professionals do it!



---

### **Two Things That Require JavaScript**

HTML and CSS are like a printed poster. To make that poster "come alive," you need JavaScript for:

1.  **Live Updates:** Like when a sports score changes on a page without you having to hit "refresh," or when a new row appears in a table as you type.
2.  **Cool Interaction:** Things like **interactive maps** that track where you are, **3D games** in your browser, or a video player that changes movies as you scroll.

---

### **How to Add JavaScript to an HTML Document**

There are three ways to get your "brain" (JS) into your "skeleton" (HTML):

* **Internal:** Typing code directly into your HTML file inside `<script>` tags. Keep this at the very bottom so the page loads before the brain starts thinking.
* **External:** Putting your code in a separate file (like `script.js`) and linking it with `<script src="script.js" defer></script>`. This keeps your project organized and clean.
* **Inline:** Putting code directly inside an HTML tag, like `<button onclick="...">`. **Avoid this!** It's messy and makes your code much harder to fix later.

***

## Things I want to know more about-