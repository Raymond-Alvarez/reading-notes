# HTML Links, JS Functions, and Intro to CSS Layout

### Creating a hyperlink

To create a basic link, you must wrap your text or content inside an `<a>` element.

### The `href` Attribute

The **`href` attribute** (Hypertext Reference) contains the **web address** or target URL that the link points to. This URL can point to HTML files, images, videos, or any other resource on the web.

### Ensuring Link Accessibility

To make links accessible to all users, including those using screen readers or those who are skimming the page, follow these best practices:

* **Use Clear Wording:** Avoid generic phrases like "click here" or "link to". Use descriptive text like "Download Firefox".
* **Keep Text Concise:** Link text should be as short as possible while remaining descriptive.
* **Avoid Repeating URLs:** Do not use the actual URL as the link text; screen readers will read out every single letter.
* **Signpost Non-HTML Content:** If a link triggers a download, include a warning like "(PDF, 10MB)".
* **Be Cautious with New Tabs:** Opening links in a new tab can be disorienting. If necessary, provide a text or icon cue.
* **Present Important Info in Regular Text:** Avoid relying on the `title` attribute, as it is often only visible on mouse hover.
* **Distinguish Unique Links:** Avoid using "Read more" for multiple different destinations.

---

## CSS Layout: Normal Flow & Positioning

### What is meant by “normal flow”?

**Normal flow** is the default system the browser uses to lay out block and inline elements on a webpage when no CSS has been applied. It ensures content is accessible and readable by default.

### Differences Between Block-level and Inline Elements

**Block-level Elements:**

* Fill the **available inline space** (100% width) of their parent.
* Always start on a **new line** and stack vertically.
* Height grows to accommodate content.
* **Inline Elements:**
* Size is determined solely by the **content size**.
* Do **not** appear on new lines; they sit on the same line as adjacent text.
* Wrap to a new line only when space runs out.

### Default Positioning

**Static** positioning is the default for every HTML element. It places the element in its default position according to the normal document flow.

### Advantages of Absolute Positioning
Absolute positioning removes an element from the normal flow, allowing it to sit on its **own separate layer**.

* **Non-interference:** It does not affect the layout of other elements.
* **UI Versatility:** Ideal for **popup boxes**, control menus, or drag-and-drop elements.
* **Precise Placement:** Allows exact placement using `top`, `bottom`, `left`, and `right` relative to a container.

### Key Difference: Fixed vs. Absolute Positioning
5. Both remove elements from the normal flow, but their context differs:

* **Absolute Positioning:** Relates to its **nearest positioned ancestor**.
* **Fixed Positioning:** Relates to the **visible portion of the viewport**. It stays in the same spot even when the page is scrolled.

---

## Functions – Reusable Blocks of Code

### Function Declaration vs. Invocation
**Function Declaration:** Defining and storing code using the `function` keyword. These are **hoisted**, meaning they can be called before they are defined in the script.

**Function Invocation:** Executing the code. You must include the **name followed by parentheses**, e.g., `draw();`.

### Parameter vs. Argument
**Parameters:** Variables **defined in the declaration**. They act as placeholders.

**Arguments:** The **actual values passed** into the function when it is called. Multiple arguments are **separated by commas**.

---

## 6 Reasons for Pair Programming

### 2 Benefits to Pair Programming

1. **Greater Efficiency and Higher Code Quality**
* Pairing often results in **higher-quality code** that requires less debugging. Two people focusing on the same code makes it much easier to catch mistakes in real-time.

> **Reflection:** Having a **Navigator** to scan for typos and think big-picture while a **Driver** writes code prevents getting stuck for hours on minor syntax errors, boosting overall confidence.

2. **Learning from Fellow Students**
* Pairing exposes you to **different problem-solving approaches**. If you are the more experienced partner, you benefit from **explaining topics in your own words**, which solidifies your knowledge.

> **Reflection:** This transforms coding into a collaborative experience involving listening, speaking, reading, and writing, which prepares you for the professional communication demands of a dev job.