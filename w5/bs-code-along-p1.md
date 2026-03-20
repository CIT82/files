# Assignment 1: Bootstrap Foundations (Part 1)

### **Content Overview (5:40 - 33:13)**
Now that your environment is staged, we will dive into the core of the Bootstrap framework:
* **The 12-Column Grid:** Mastering responsive layouts using `rows` and `columns`.
* **Professional Components:** Building styled tables and complex form inputs with zero custom CSS.
* **Form UX:** Implementing floating labels and validation states.

---

### **Commit Log & Instructions**

| Video Time | Checkpoint | **Instruction / Task** | Required Commit Message |
| :--- | :--- | :--- | :--- |
| **5:40** | **The Grid** | **Code:** Code Along and create a `.row` with columns totaling 12 (e.g., `col-md-8` and `col-md-4`).<br>**Notes:** In `README.md`, add `## The Grid System` and under that add `## Layout`., record your understanding of how the row, column, offset and gap classes are using in the grid system.  Make sure you have many of the different column, row, breakpoint and gap examples are showing on this commit.| `Feat: Created 12-column grid layout` |
| **15:14** | **Spacing** | **Code:** Use `gy-3`, `gx-3`, `g-3` (gutters) on a row and practice nesting a `.row` inside a `.col`.<br>**Notes:** Define **Gutters**—the padding between columns. Note that `g-*` sets both horizontal and vertical gaps and why the flow is important | `Style: Adjusted grid gutters and nesting` |
| **17:44** | **Tables** | **Code:** Apply `.table`, `.table-striped`, and `.table-responsive`.<br>**Notes:** Add `## Components`. List the classes used and explain why `.table-responsive` needs a **parent wrapper** to work. | `Feat: Styled responsive data tables` |
| **22:52** | **Forms I** | **Code:** Use `.form-label` and `.form-control`.<br>**Notes:** Add `### Forms`. Note that Bootstrap inputs default to **100% width** of their parent container. <br> **Code:** range, select inputs, checkboxes, input-groups  | `Feat: Implemented basic Bootstrap forms` |
| **30:56** | **Forms II** | **Code:** Wrap inputs in `.form-floating`.<br>**Note:** Record the **Mandatory Rule**: The `<label>` must come AFTER the `<input>`, and the input must have a `placeholder`. <br>**Code:** Add `required` and `.invalid-feedback`.<br>**Notes:** Explain how the `.was-validated` class on a `<form>` makes the `:invalid` CSS pseudo-class "wake up." <br> No need to write the JavaScript | `Feat: Floating Label and form validation feedback` | 

---
## 💡 Bootstrap 5.3 Quick Reference

### **1. Spacing Utilities**
**Format:** `{property}{side}-{size}`  
*Example:* `mt-3` (Margin Top, size 3) or `px-2` (Padding Left & Right, size 2)

| Property | Sides | Sizes (0-5) |
| :--- | :--- | :--- |
| **m** (margin) | **t** (top) / **b** (bottom) | **0**: 0px |
| **p** (padding) | **s** (start/left) / **e** (end/right) | **1**: 0.25rem |
| | **x** (left & right) / **y** (top & bottom) | **3**: 1rem (Default) |
| | **blank** (all 4 sides) | **5**: 3rem |

### **2. Semantic Colors**
Use these with `text-*`, `bg-*`, or `btn-*`:
* 🔵 `primary` / `info`
* ⚪ `secondary` / `light`
* 🟢 `success` | 🔴 `danger` | 🟡 `warning` | ⚫ `dark`

### **3. The Grid**
* **Breakpoint Keys:** `sm` (576px), `md` (768px), `lg` (992px), `xl` (1200px).
* **Rule:** Columns must total **12** within a single `.row`.
---


### **Quick Tip: Using IntelliSense**
Since you installed the **CSS IntelliSense** extension during setup, remember that you can press `Ctrl + Space` inside any `class=""` attribute to see a full list of available Bootstrap options!