# Using Images In HTML

### **`alt attribute`**
 A real-world use case for the **alt attribute** shown in the sources is providing a text description for a complex image, such as a **"Diagram showing the data channels,"** so the information remains available if the image cannot be displayed.

### **Improve Accessibility** 
 To **improve accessibility** of images in an HTML document, you can:
* Use the **`alt` attribute** within the `<img>` tag to provide a meaningful description of the image's content.
* Utilize the **`<picture>` element** to provide **fallbacks**. This ensures that if a browser does not support a modern, high-performance format (like SVG or WebP), it can still display a more universally compatible version (like PNG or GIF).

### **`<figure>` element**
The `<figure>` element is your go-to tool whenever you have a piece of content that is self-contained but referenced by the main text. Think of it as a container for information that could be moved to an appendix or a different page without losing its meaning, but is currently placed right where it is for better flow.

* A classic example is an image with a caption illustrating a specific concept.

### **gif** vs **svg**
 To explain the difference between a **GIF** and an **SVG** to an elder: 
* A **GIF** is like a small, digital flipbook. It has been used for decades to show simple animations or short clips. It only uses a limited set of colors, which is why it’s great for simple memes but not for high-quality photos. 
* An **SVG** is more like a **set of drawing instructions**. Instead of storing a picture made of tiny dots, it stores commands that tell the computer how to draw lines and shapes. Because it is based on these instructions, you can make an SVG as big as a house or as small as a postage stamp, and it will always look **perfectly crisp and sharp**.
**
### **Screenshot image type**
 For a **screenshot**, you should use **PNG** or **lossless WebP**. You should choose these **lossless formats** because screenshots often contain text; if you use a "lossy" format that throws away data to save space, that **text can become fuzzy and hard to read**.

 # Color and Styling

 ### **Difference between foreground and background colors**
 
Think of the foreground as the actual "ink" used to write the words or draw shapes, while the background is the "paper" or surface those words are sitting on. In a website, the foreground color usually refers to the text itself, and the background color is the shade filling the space behind that text.

### **Use color to add character**

If I were giving a friend's blog some **character using color**, I would suggest several creative touches based on the sources:
*   **Wavy Underlines:** Instead of a plain line, you can use a wavy, colorful underline for links or important headings to add a playful feel.
*   **Shadow Effects:** Adding a **text-shadow** can make titles pop off the page, or a **box-shadow** can give the blog posts a "lifted" 3D effect.
*   **Distinct Outlines:** You could add a dashed or colored **outline** around specific boxes or images to create a unique, stylized border that doesn't mess with the rest of the layout.
*   **Emphasis Marks:** For certain languages, you can even add colorful emphasis symbols next to characters to draw the reader's eye.

### **Consider when **choosing fonts** for an HTML document**

*   **Availability:** Not every computer has the same fonts, so you should prioritize "**web-safe fonts**" that are known to be on almost all systems, like Arial or Georgia.
*   **Font Stacks:** It is best practice to provide a "stack" or list of fonts; if the browser can’t find your first choice, it will move to the next one in the list.
*   **Generic Fallbacks:** You should always end your font list with a generic category (like `serif` or `sans-serif`) so the browser can at least provide something in the right style if all else fails.
*   **Predictability:** Be careful with "cursive" or "fantasy" fonts, as they can look very different depending on the browser or operating system.

### **`font-size`, `font-weight`, and `font-style` properties**

*   **font-size:** Determines how large or small the text appears, often measured in pixels (px) for absolute size or "ems" and "rems" for relative size.
*   **font-weight:** Controls the thickness or "boldness" of the text, ranging from "light" to "bold" or using numbers like 100 to 900.
*   **font-style:** Primarily used to turn **italics** on or off, or to slant the text using a "simulated" italic called oblique.

### **Two ways you could add spacing around characters**

1.  **letter-spacing:** This allows you to increase or decrease the space between every individual letter in the heading.
2.  **word-spacing:** This adjusts the amount of space between the actual words in the heading.

