In this lab, you will step away from the freeCodeCamp "sandbox" and build a project from scratch in your own local environment. You will practice project organization, external styling, and professional image optimization.

#### Part 1: Project Setup (Private Repo)
1.  **Folders:** Open your **private** repo in VS Code. Create a new folder named `code-along`. Inside that, create another folder named `practice`.
2.  **HTML:** Inside the `practice` folder, create a file named `index.html`. 
3.  **Emmet Magic:** Open `index.html`, type `!` and press **Enter**. Emmet will instantly generate your HTML boilerplate.
4.  **CSS:** In the same folder, create a file named `styles.css`. *(Note: We use the plural 'styles' to match the freeCodeCamp project format!)*

#### Part 2: Linking & Initial Styling
1.  **The Link:** Inside the `<head>` section of your HTML, type `link:css` and press **Enter**. 
    * **CRITICAL:** Emmet defaults to `style.css`. You must manually change the `href` to `styles.css` so it matches the file name you created in Part 1.
2.  **The Test:** Open `styles.css` and add the following code:
    ```css
    body {
        background-color: lightblue;
    }
    ```
3.  **Milestone 1:** Complete the **Git Workflow** (Stage, Commit, and Push) with the message:
    * `Initial setup and linked styles.css`

#### Part 3: Building Structure & Content
1.  **Live Server:** Right-click `index.html` and select **Open with Live Server**. Your browser should display a light blue page.
2.  **Structure:** Inside the `<body>`, add the following semantic elements covered in the fCC Cafe:
    * A `<main>` section.
    * Inside `<main>`, add an `<h1>` for your title.
    * Below the `<h1>`, add a `<section>` containing an `<h2>` and a `<ul>` with three `<li>` items.
3.  **Milestone 2:** Complete the **Git Workflow** (Stage, Commit, and Push) with the message:
    * `Added main and section HTML structure`
4.  **Content:** Add text to your headers and list items. You can use an AI to generate a "Top 3" list (e.g., Top 3 Biking Trails or Top 3 Pizza spots) or write your own.
5.  **Customize:** Change at least two more CSS properties (e.g., `font-family`, `color`, `text-align`, or `padding`).
6.  **Milestone 3:** Complete the **Git Workflow** (Stage, Commit, and Push) with the message:
    * `Customized content and updated styles`

#### Part 4: Image Optimization & Documentation
1.  **Screenshot:** Take a screenshot of your browser output. 
2.  **Resize:** Go to [Squoosh.app](https://squoosh.app/). Upload your image and **resize the width to 720px**. 
3.  **Save:** Download the optimized image and save it into your **Public** repo's `screenshots/` folder.
4.  **Final Milestone:** Complete the **Git Workflow** (Stage, Commit, and Push) using the file name as the message:
    * `w4-practice-coding.png`


