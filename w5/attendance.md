# Bootstrap 5.3 Setup & Attendance Guide

**Goal:** Initialize your environment, install developer tools, and verify your Bootstrap connection through a series of incremental steps and commits.

---

### 📂 Step 1: Folder & File Structure
1. Navigate to your `code-along` folder in your private repository.
2. Create a folder named `bootstrap`.
3. Inside `bootstrap`, create the following three files:
   * `index.html` (Your coding workspace)
   * `style.css` (Your custom overrides)
   * `README.md` (Your technical learning journal)
4. **Journal Start:** Add the heading `# Bootstrap Learning Journal` to your `README.md`.

**✅ Required Commit:** `Docs: Initialized Bootstrap folder and journal`

---

### 🛠️ Step 2: VS Code Extension Setup
To get the most out of Bootstrap, you need **IntelliSense** (auto-complete) to suggest class names as you type.
1. Open the **Extensions** view in VS Code (`Ctrl+Shift+X`).
2. Search for: **"IntelliSense for CSS class names in HTML"** (by Zignd).
3. Click **Install**.
4. **Verification:** In your `index.html`, typing `class="cont"` inside an HTML tag should now suggest `container`.

---

### 🌐 Step 3: The "Dual Link" Strategy (Boilerplate)
We are linking two things: the Bootstrap Framework (via CDN) and our own custom CSS.

1. **Bootstrap Boilerplate:** Go to the [Bootstrap 5.3 Quick Start](https://getbootstrap.com/docs/5.3/getting-started/introduction/#quick-start) and copy the HTML from **Step 2**. Paste it into your `index.html`.
2. **Move & Defer JS:** * Cut the `<script src="...">` tag from the bottom of the `<body>`.
   * Paste it into the `<head>` section.
   * Add the `defer` attribute: `<script src="..." defer></script>`.
3. **Link Your Custom CSS:** In the `<head>`, underneath the Bootstrap CSS link, use the Emmet shortcut `link:css` and hit **Tab**. 
   * Ensure the `href` points to your `style.css`.
   * **Important:** Your custom CSS link must come **AFTER** the Bootstrap CSS link so you can override Bootstrap styles later.



**✅ Required Commit:** `Setup: Linked Bootstrap 5.3 and custom style.css`

---

### ✍️ Step 4: Emmet & Layout Verification
1. **The Lorem Shortcut:** Inside your `<body>`, type `lorem20` and hit **Tab**. This generates 20 words of filler text instantly.
2. **The "Proof of Life":** Open Live Preview. 
   * Confirm the "Hello World" font is a clean **sans-serif** (proving Bootstrap is active).
   * Confirm your `lorem` text is visible on the page.

**✅ Required Commit:** `Verify: Confirmed Bootstrap link and Emmet shortcuts`

---
