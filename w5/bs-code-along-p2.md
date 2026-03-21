# Assignment 2: Interactive Components (Part 2)

### **Content Overview (36:00 - End)**
This final section focuses on the "JavaScript" side of Bootstrap and high-speed styling with utilities:
* **Buttons:** Creating button and links.
* **Alerts and Cards:** Creating button and links.
* **Modals:** Creating pop-up dialog boxes linked to buttons.
* **Navbars:** Building a responsive navigation menu with a mobile "hamburger" toggle.

---

### **Commit Log & Instructions**

| Video Time | Checkpoint | **Instruction / Task** | Required Commit Message |
| :--- | :--- | :--- | :--- |
| **36:00** | **Buttons** | **Code:** Create buttons using `.btn` plus modifiers like `.btn-primary`. <br>**Notes:** In `README.md`, add `## Interactivity`. List your 3 favorite button color modifiers. | `Feat: Added styled Bootstrap buttons` |
| **40:36** | **Alerts Cards** | **Code:** Create alerts using and card componments  | `Feat: Implement Alerts and Cards` |
| **46:38** | **Modals** | **Code:** Create a `.modal`. Link it to a button using `data-bs-toggle="modal"` and `data-bs-target`. <br>**Notes:** Add `## Modals`. Explain the purpose of the `.modal-backdrop`. | `Feat: Implemented interactive modal popup` |
| **Skip** | **Collapse**| Good content if you want to review | `No commit ` |
| **54:26** | **Navbars** | **Code:** Build a `.navbar`. Ensure you include the `.navbar-toggler` and the `.collapse` div. <br>**Notes:** Add `## Navigation`. **Rule:** The `id` of the collapse div must match the `data-bs-target` of the toggle button. | `Feat: Created responsive navigation bar` |

    
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