# Object-Oriented Programming, HTML Tables

## Domain Modeling

Domain modeling is a critical step in software development because it serves as the **proper planning** required before writing any code; without it, the process is compared to trying to assemble furniture while blindfolded, which often leads to forgetting crucial pieces and having to start over.

Domain modeling is needed for the following reasons:

*   **Understanding the "Domain":** Much like learning the rules and concepts of a new game, developers need to understand exactly what they are building. A domain model captures the collection of **related concepts, relationships, and workflows** involved in the system.
*   **Visualizing the Problem:** It provides a **structured visual representation** of the real world. This allows teams to better visualize the specific problem they are trying to solve by illustrating entities (conceptual classes) and how they associate with one another.
*   **Establishing a Common Vocabulary:** The model incorporates the **vocabulary, key concepts, and behaviors** of all entities, ensuring everyone involved has a clear, shared understanding of the system's structure.
*   **Bridging Concepts and Code:** Domain modeling, specifically through tools like **Class Diagrams**, acts as the primary building block for object-oriented modeling. It helps translate high-level conceptual models into detailed structures that can be directly **translated into programming code**.
*   **Defining Relationships and Multiplicity:** It clarifies how different parts of the system interact, such as defining **multiplicity** (e.g., how many instances of one entity relate to another) and identifying **composition relationships** where one class cannot exist without another.

## HTML Table Basics

**Why tables should not be used for page layouts**
Tables were historically used for layouts when CSS support was limited, but this is now considered a poor practice for several reasons. First, **layout tables significantly reduce accessibility** for visually impaired users because screen readers struggle to interpret the complex markup correctly, leading to confusing output. Second, tables create **"tag soup,"** which refers to overly complex code structures that are difficult to write, maintain, and debug compared to proper CSS layout techniques. Finally, **tables are not automatically responsive**; unlike layout containers like `<header>` or `<section>` that default to the width of their parent, tables size themselves based on their content, requiring extra effort to make them work across different devices.

**Three semantic HTML elements used in a `<table>`**
1.  **`<tr>` (Table Row):** This element acts as a container for a single horizontal row of cells within the table.
2.  **`<td>` (Table Data):** This represents a standard table cell and is the smallest container used to hold actual data.
3.  **`<th>` (Table Header):** This denotes a special cell used for headers at the start of rows or columns. They are visually bold and centered by default and help screen readers associate headers with their corresponding data for better accessibility.

---

## Introducing Constructors

**What is a constructor and its advantages**
A **constructor is a function called using the `new` keyword** that serves as a blueprint for creating objects. When invoked, it implicitly creates a new object, binds `this` to that object, executes the internal code, and then returns the new object. 
The primary advantages of using constructors include:
*   **Efficiency:** You can define the "shape" of an object (its properties and methods) once and then **create as many instances as needed** without rewriting the same code for every object.
*   **Consistency:** It ensures that every object created from that constructor follows the same structure, making it easier to update the object definition in one place rather than modifying individual object literals.
*   **Automation:** It handles the manual steps of creating an empty object, initializing it, and returning it "under the hood".

**How `this` differs in object literals versus constructors**
In an **object literal**, the `this` keyword typically refers to the **specific object in which the code is currently being executed**. In contrast, within a **constructor**, `this` is bound specifically to the **newly created object instance** that is being "constructed" at that moment.

---

## Object Prototypes Using A Constructor

**Explanation of Prototypes and Inheritance via Analogy**
Based on the sources, **prototypes** are objects where shared methods and properties live, allowing multiple instances to "delegate" to that prototype when they don't have a specific property themselves.

**Work Experience Analogy: The Corporate Policy Manual**
Imagine a large office building with hundreds of employees (the **instances**). Instead of printing a 500-page "Employee Handbook" for every single person to keep at their desk—which would be a massive waste of resources and memory—the company keeps one master copy in the HR office (the **prototype**). 

When an employee needs to know the "Vacation Request Procedure" (a **property/method**), they first check their own desk. If they don't find it there (**failed lookup**), they "delegate" the search to the HR office's master manual (**prototypal inheritance**). Because every employee is linked to that same HR manual, they all have access to the same procedures without the company needing to recreate those instructions for every new hire. This ensures that if the company updates a policy (a **method on the prototype**), every employee immediately has access to the updated version without needing a new manual at their desk.