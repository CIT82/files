# Assignment 1: Bootstrap Foundations (Part 1)

### **Content Overview (5:40 - 35:44)**
Now that your environment is staged, we will dive into the core of the Bootstrap framework:
* **The 12-Column Grid:** Mastering responsive layouts using `rows` and `columns`.
* **Professional Components:** Building styled tables and complex form inputs with zero custom CSS.
* **Form UX:** Implementing floating labels and validation states.

---

### **Commit Log & Instructions**

| Video Time | Checkpoint | **Instruction / Task** | Required Commit Message |
| :--- | :--- | :--- | :--- |
| **5:40** | **The Grid** | **Code:** Create a `.row` with columns totaling 12 (e.g., `col-md-8` and `col-md-4`).<br>**Notes:** In `README.md`, add `## Layout`. Under `### The Grid System`, record that Bootstrap uses a **12-unit system**.  | `Feat: Created 12-column grid layout` |
| **16:14** | **Spacing** | **Code:** Use `g-3` (gutters) on a row and practice nesting a `.row` inside a `.col`.<br>**Notes:** Define **Gutters**—the padding between columns. Note that `g-*` sets both horizontal and vertical gaps. | `Style: Adjusted grid gutters and nesting` |
| **21:00** | **Tables** | **Code:** Apply `.table`, `.table-striped`, and `.table-responsive`.<br>**Notes:** Add `## Components`. List the classes used and explain why `.table-responsive` needs a **parent wrapper** to work. | `Feat: Styled responsive data tables` |
| **27:30** | **Forms I** | **Code:** Use `.form-label` and `.form-control`.<br>**Notes:** Add `### Forms`. Note that Bootstrap inputs default to **100% width** of their parent container. | `Feat: Implemented basic Bootstrap forms` |
| **32:20** | **Forms II** | **Code:** Wrap inputs in `.form-floating`.<br>**Note:** Record the **Mandatory Rule**: The `<label>` must come AFTER the `<input>`, and the input must have a `placeholder`. | `Feat: Added modern floating labels` |
| **35:44** | **Validation** | **Code:** Add `required` and `.invalid-feedback`.<br>**Notes:** Explain how the `.was-validated` class on a `<form>` makes the `:invalid` CSS pseudo-class "wake up." | `Feat: Implemented form validation feedback` |

---

### **Quick Tip: Using IntelliSense**
Since you installed the **CSS IntelliSense** extension during setup, remember that you can press `Ctrl + Space` inside any `class=""` attribute to see a full list of available Bootstrap options!