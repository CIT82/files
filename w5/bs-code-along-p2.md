# Assignment 1: Bootstrap Foundations (Part 1)

### **Content Overview**
In this section (0:00 - 35:44), we move from custom CSS to Bootstrap’s utility-first framework. You will cover:
* **The Global Reset:** How Bootstrap standardizes browser styles automatically.
* **The 12-Column Grid:** Mastering responsive layouts using `rows` and `columns`.
* **Professional Components:** Building styled tables and modern form inputs with zero custom CSS.
* **Form UX:** Implementing floating labels and validation states.

---

### **Phase 1: Repository Setup**
1.  **Navigate** to your `code-along` folder.
2.  **Create a folder** named `bootstrap`.
3.  **Inside `bootstrap`**, create `index.html` and `README.md`.
4.  **Setup README:** Open `README.md`, add the heading `# Bootstrap Learning Journal`, and paste the **Quick Reference** (found at the bottom of this log) into the end of the file.

---

### **Commit Log & Instructions**

| Video Time | Checkpoint | **Instruction / Task** | Required Commit Message |
| :--- | :--- | :--- | :--- |
| **0:54** | **Setup** | **Code:** Link Bootstrap 5.3 CSS in the `<head>` and the JS bundle before the `</body>`. <br>**Notes:** In `README.md`, create `## Setup`. Note that we are using **v5.3**. Mention the `data-bs-theme="dark"` attribute as a new 5.3 feature. | `Setup: Linked Bootstrap 5.3 CDN and JS` |
| **4:20** | **Containers** | **Code:** Wrap content in `.container` vs `.container-fluid`.<br>**Notes:** Add heading `## Layout`. Explain the difference between a **fixed** container (jumps at breakpoints) and **fluid** (always 100% width). | `Feat: Implemented responsive containers` |
| **8:30** | **The Grid** | **Code:** Create a `.row` with columns totaling 12 (e.g., `col-md-8` and `col-md-4`).<br>**Notes:** Add `### The Grid System`. Record that Bootstrap uses a **12-unit system**.  | `Feat: Created 12-column grid layout` |
| **16:14** | **Spacing** | **Code:** Use `g-3` (gutters) on a row and practice nesting a `.row` inside a `.col`.<br>**Notes:** Define **Gutters**—the padding between columns. Note that `g-*` sets both horizontal and vertical gaps. | `Style: Adjusted grid gutters and nesting` |
| **21:00** | **Tables** | **Code:** Apply `.table`, `.table-striped`, and `.table-responsive`.<br>**Notes:** Add `## Components`. List the classes used and explain why `.table-responsive` needs a **parent wrapper** to work. | `Feat: Styled responsive data tables` |
| **27:30** | **Forms I** | **Code:** Use `.form-label` and `.form-control`.<br>**Notes:** Add `### Forms`. Note that Bootstrap inputs default to **100% width** of their parent container. | `Feat: Implemented basic Bootstrap forms` |
| **32:20** | **Forms II** | **Code:** Wrap inputs in `.form-floating`.<br>**Note:** Record the **Mandatory Rule**: The `<label>` must come AFTER the `<input>`, and the input must have a `placeholder`. | `Feat: Added modern floating labels` |
| **35:44** | **Validation** | **Code:** Add `required` and `.invalid-feedback`.<br>**Notes:** Explain how the `.was-validated` class on a `<form>` makes the `:invalid` CSS pseudo-class "wake up." | `Feat: Implemented form validation feedback` |

---

### **Copy this into your README.md:**
```markdown
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