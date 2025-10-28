# 🌐 Host a Static Website with GitHub Pages

## 📘 Project Overview

This project demonstrates how to host a **static website** for free using **GitHub Pages**.
You’ll learn how to deploy HTML and CSS files directly from your GitHub repository to a live website link.

---

## 🚀 Steps to Deploy

1. **Create an HTML file**

   ```bash
   touch index.html
   ```

   Add your website content inside the file.

2. **(Optional) Add CSS styling**

   ```bash
   touch style.css
   ```

   Link it in your HTML file:

   ```html
   <link rel="stylesheet" href="style.css">
   ```

3. **Push to GitHub**

   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

4. **Enable GitHub Pages**

   * Go to **Settings → Pages**
   * Select **main branch** and **root (/)** folder
   * Save the settings

5. **Access your live site**
   GitHub provides a link like:

   ```
   https://<your-username>.github.io/<repo-name>/
   ```

---

## 🧩 Example Folder Structure

```
.
├── index.html
├── style.css
└── README.md
```

---

## 🎯 Outcome

You’ll have a **live static website** hosted for free with GitHub Pages — perfect for personal portfolios, resumes, or small web projects.

---

## 🧠 Next Steps

* Add images or JavaScript for interactivity
* Customize your CSS for a unique design
* Connect a custom domain name if you want a personalized URL

---

**Live Demo:** https://yasaswvene.github.io/github-pages/
