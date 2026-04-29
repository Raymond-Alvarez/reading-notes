### Component-Based Architecture

#### What is a “component”?
A **component** is a **modular, portable, replaceable, and reusable** set of well-defined functionality. It encapsulates its internal implementation and exports it as a higher-level interface. From a software perspective, it is an object intended to interact with other components, conforming to a recommended behavior common to all components within an architecture. It can also be defined as a **unit of composition** that has a contractually specified interface and explicit context dependencies, allowing it to be deployed independently.

#### What are the characteristics of a component?
The core characteristics of components include:
*   **Reusability:** They are designed to be reused across different situations and applications.
*   **Replaceable:** Components can be freely substituted with other similar components.
*   **Not context specific:** They are designed to operate in various environments and contexts.
*   **Extensible:** A component can be extended from existing ones to provide new behaviors.
*   **Encapsulated:** They expose interfaces for callers to use functionality but do **not reveal internal processes**, variables, or states.
*   **Independent:** They are designed to have minimal dependencies on other components.

#### What are the advantages of using component-based architecture?
The advantages of this architecture include:
*   **Reduced Cost and Time:** Reusing existing components reduces development costs and the time it takes to bring a product to market.
*   **Increased Reliability:** Reusing existing components increases the overall reliability of the system.
*   **Ease of Deployment:** It is easier to replace existing versions with new compatible ones without impacting the rest of the system.
*   **Ease of Development:** Well-known interfaces allow for development without impacting other parts of the system, and different groups can develop components in parallel.
*   **Simplified Maintenance:** It is easy to update or change an implementation without affecting the entire system.

---

### What is Props and How to Use it in React

#### What is “props” short for?
The term **"props"** is an abbreviation for **"properties,"** which refers to the properties of an object.

#### How are props used in React?
Props are used to **pass data and values from one component to another** to achieve dynamic and unique outputs. They function as inputs that enable a component to access customized information. 
*   **Sending Props:** The syntax for passing props is similar to **HTML attributes**; you assign a value to a property within the component tag (e.g., `<Product name="Apple" />`). 
*   **Receiving Props:** The component receives these props as a **function parameter**, which is treated as an object.
*   **Destructuring:** Developers often use JavaScript destructuring to assign pieces of data from the props object to separate variables, making the code more readable and concise.

#### What is the flow of props?
React utilizes a **one-way data flow**. This means that data can only be transferred **from a parent component down to child components**. Furthermore, any data passed from the parent is read-only for the child; the child component **cannot change the props** it receives.