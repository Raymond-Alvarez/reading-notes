### **JavaScript Canvas**

1.  **What does the `<canvas>` allow a developer to achieve?**

    The `<canvas>` element allows a developer to **draw 2D graphics** using JavaScript. It provides a space on a webpage where shapes, text, images, and other objects can be rendered dynamically.

2.  **Importance of the closing `</canvas>` tag?**

    Unlike the `<img>` element, the `<canvas>` element **requires a closing tag**. Any content placed between the opening and closing tags serves as **fallback content**, which is only displayed if the user's browser does not support the canvas element.

3.  **`getContext()` method**

    The `getContext()` method is used to **access the rendering context** of the canvas, which is necessary to actually draw something on the initially blank element. It takes one argument to specify the type of context, such as **"2d"**, which returns an object that provides methods for drawing shapes, paths, and rectangles.

### **Chart.js Documentation**

1.  **What is Chart.js and how it can be brought into your project?**
    Chart.js is an **open-source JavaScript library** used for creating various types of charts; it is currently the most popular library of its kind based on GitHub stars and npm downloads. To bring it into a project, you can **download the library**, copy the `Chart.min.js` file into your project directory, and then **import the script** into your HTML page. It is also compatible with popular frameworks like React, Vue, Svelte, and Angular.

2.  **3 different Chart types using Chart.js.**
    
    *   **Line charts**
    *   **Bar charts**
    *   **Pie charts**

### **Easily Create Stunning Animated Charts with Chart.js**

1.  **Some advantages to displaying data via a chart over a table?**

    Charts are considered superior for visual data display because they are **easier to look at** and **convey data quickly** to the viewer. Additionally, unlike tables, charts are unlikely to be incorrectly used as a layout tool.

2.  **How could Chart.js aid your previously created applications visually?**

    Chart.js can enhance applications by providing **highly appealing, animated visualizations** that bring immediate attention to the data story being told. Because it uses **canvas rendering**, it remains very performant even when handling large datasets, preventing the application from becoming sluggish. Furthermore, its **customization options**—such as adding transparency with RGBA colors or using plugins for zooming and annotations—allow developers to tailor the visual experience to their specific needs.