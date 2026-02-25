### Learn CSS - Flexbox

1. **Flexbox is a one-dimensional layout method**, which means it is designed to arrange items in **one direction at a time—either as a row or as a column**. Even when items are set to wrap onto multiple lines, each flex line acts like a new, independent flex container. Consequently, it is **not possible to align an item in one row with an item in another row**; for control over both rows and columns simultaneously, a two-dimensional system like CSS Grid is required.

2. The main axis and cross axis are defined as follows:
    * **Main Axis:** This is the primary axis along which flex items are laid out. Its direction is determined by the **`flex-direction` property**; if the direction is set to `row`, the main axis runs horizontally, and if set to `column`, it runs vertically.
    * **Cross Axis:** This axis runs **perpendicular to the main axis**. For instance, if your items are arranged in a row (horizontal main axis), the cross axis runs vertically along the column.

3. Certain flexbox properties can **negatively impact accessibility by creating a disconnect between the visual order and the logical (DOM) order**. Properties like **`order`**, **`row-reverse`**, and **`column-reverse`** change how items appear on the screen without changing the underlying HTML source. This is problematic because **screen readers and keyboard navigation (tabbing) follow the source code order**, which can confuse users if the focus jumps around the screen in a non-linear fashion.

### CSS Layout - Flexbox

1. Using flexbox offers several **advantages over traditional layout methods like floats**:
* **Vertical Centering:** Flexbox makes it simple to vertically center content inside a parent container.
* **Equal Height Columns:** It allows all children in a container to adopt the same height automatically, regardless of the amount of content each contains.
* **Flexible Sizing:** You can easily make children take up an **equal amount of available space** or distribute space around them using properties like `justify-content`.
* **Visual Reordering:** Flexbox allows you to **change the display order** of elements without modifying the HTML, a task that is nearly impossible with floats.

2. **How this topic connects with my long term goals?**

* Fostering a quality user-experience and creating a UI that offers that are target goals. 