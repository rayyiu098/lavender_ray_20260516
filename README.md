# Wedding Website

This is a static wedding website template built with HTML, CSS, and JavaScript.

## 📝 How to Customize

1.  **Open `index.html`**:
    *   Replace `[Name]` with your names.
    *   Replace `[Date]`, `[Month]`, `[Day]`, `[Year]` with your wedding date.
    *   Replace `[City, State/Country]` with the location.
    *   Update the "Our Story" section.
    *   Update the "Details" section with ceremony and reception info.
    *   Replace the RSVP link with your Google Form or Typeform URL.

2.  **Open `script.js`**:
    *   Update the `weddingDate` variable at the top of the file to your actual wedding date.

3.  **Images**:
    *   Replace the background image URL in `style.css` (search for `background-image`).
    *   Add your own photos to an `images` folder and link them in `index.html`.

## 🚀 How to Host on GitHub Pages

1.  **Create a Repository on GitHub**:
    *   Go to GitHub and create a new repository (e.g., `our-wedding`).

2.  **Push your code**:
    *   Run the following commands in your terminal (inside this folder):
        ```bash
        git init
        git add .
        git commit -m "Initial commit"
        git branch -M main
        git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
        git push -u origin main
        ```

3.  **Enable GitHub Pages**:
    *   Go to your repository **Settings**.
    *   Click on **Pages** in the left sidebar.
    *   Under **Source**, select `main` branch.
    *   Click **Save**.
    *   Your website will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`.
