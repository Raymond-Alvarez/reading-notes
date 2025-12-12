# Design web pages with CSS

- CSS is known as a **styling language**. Its main goal is to tell your HTML document *how things should look*. This includes styling elements by setting things like **colors**, **margins**, **font sizes** for headings, **line heights**, and managing the **overall layout**. Using CSS is also helpful because it can reduce inconsistencies in how different web browsers display the default look of elements.
---

- You have **three main ways** to put CSS into your web project:

  - **External Stylesheets**
This is the most common and helpful method. You write your CSS in a separate file that ends with `.css` and then link that file to your HTML document. This lets you style many pages using the same set of rules.

  - **Internal Stylesheets**
You place your CSS rules inside `<style>` elements, which are located within the `<head>` section of your HTML document. While sometimes useful, this method is less efficient if your website has more than one page because you would have to repeat the CSS on every page.

  - **Inline Styles**
You write CSS directly within a single HTML element using the `style` attribute. It is generally considered **bad practice** to rely on this method because it makes maintenance difficult and mixes design code with content.
---


- *Example CSS Rule*

  A CSS rule that would give all `<p>` elements red text would look like this:

  
      p {
      color: red;
      }
