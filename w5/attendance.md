# Bootstrap 5.3 Setup & Attendance Guide

**Goal:** Initialize your environment, install developer tools, and link both Bootstrap and your custom stylesheet.

---

### 🛠️ Step 1: VS Code Extension
To get the most out of Bootstrap, you need **IntelliSense** (auto-complete).
1. Open **Extensions** (`Ctrl+Shift+X`).
2. Search for: **"IntelliSense for CSS class names in HTML"** (by Zignd).
3. Click **Install**.

---

### 📂 Step 2: Folder & File Structure
1. Navigate to your `code-along` folder.
2. Create a folder named `bootstrap`.
3. Inside `bootstrap`, create the following three files:
   * `index.html` (Main structure)
   * `style.css` (Custom overrides)
   * `README.md` (Learning journal)

---

### 🌐 Step 3: The "Dual Link" Strategy
We are linking two things: the Bootstrap Framework and our own custom CSS.

1. **Bootstrap Boilerplate:** Go to the [Bootstrap Quick Start](https://getbootstrap.com/docs/5.3/getting-started/introduction/#quick-start) and copy the HTML from **Step 2**. Paste it into your `index.html`.
2. **Move & Defer JS:** * Cut the `<script>` tag from the bottom of the `<body>`.
   * Paste it into the `<head>`.
   * Add the `defer` attribute: `<script src="..." defer></script>`.
3. **Link Your CSS:** In the `<head>`, underneath the Bootstrap CSS link, type `link:css` and hit **Tab**. 
   * Ensure it points to `style.css`.
   * **Note:** Your custom CSS must come *after* Bootstrap so your styles can override theirs if needed.


---

### ✍️ Step 4: Emmet & Tools Verification
1. **The Lorem Shortcut:** Inside your `<body>`, type `lorem20` and hit **Tab**. This generates 20 words of filler text instantly.
2. **Class IntelliSense:** Inside an HTML tag, type `class="btn-` and see if the dropdown list appears. If not, press `Ctrl + Space`.

---

### 📤 Step 5: Attendance Commits
Push these two commits to your repository to verify your attendance:

| Task | Required Commit Message |
| :--- | :--- |
| **Initial Setup** | `Setup: Linked Bootstrap 5.3 and custom style.css` |
| **Journal Start** | `Docs: Initialized Bootstrap learning journal` |

---