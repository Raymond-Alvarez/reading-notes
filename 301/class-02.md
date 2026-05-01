### Reading: React Lifecycle

*   **Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?**
    Based on the lifecycle diagram and descriptions, **`render` happens first**. It occurs during the "Render phase," while `componentDidMount` is invoked later during the "Commit phase" after the component has been inserted into the DOM,,.

*   **What is the very first thing to happen in the lifecycle of React?**
    The very first thing to happen is the **`constructor`**. It is called before the component is mounted,.

*   **Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates**
    According to the sources, the correct order is:
    1.  **`constructor`**
    2.  **`render`**
    3.  **`componentDidMount`**
    4.  **`React Updates`** (This occurs during the Updating phase after mounting)
    5.  **`componentWillUnmount`** (This occurs in the final Unmounting phase)

*   **What does componentDidMount do?**
    `componentDidMount` is invoked **immediately after a component is mounted**. It is primarily used for **network requests** (such as fetching data from an API), **DOM initialization/manipulations**, and setting up **subscriptions**,,.

***

### Videos: React State Vs Props

*   **What types of things can you pass in the props?**
    Props act like arguments to a function or a class constructor,. You can pass **initial values** (like an `initialCount`), **text content** (such as a `title`, `subtitle`, or `description`), and other variables that allow a component to be dynamic rather than hard-coded,.

*   **What is the big difference between props and state?**
    The fundamental difference is their **source and management**: **props are passed into a component** from the outside (usually by a parent), whereas **state is handled internally** within the component. Additionally, props are generally static and should not be changed by the component receiving them, while state is designed to be updated inside the component to reflect changes,.

*   **When do we re-render our application?**
    The application re-renders whenever its **data changes**, specifically when **state is updated** within a component or when **props change** from the outside,,. Using the `setState()` method specifically triggers this re-render process.

*   **What are some examples of things that we could store in state?**
    Common examples include:
    *   A **current count** in a counter application.
    *   **User input values** from form elements like text inputs, checkboxes, or select boxes.
    *   **UI toggle states**, such as a boolean value to `showDescription`.