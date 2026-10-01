

```markdown
# Deployment Guide

Follow these steps to deploy this academic project page on your GitHub account using **GitHub Pages**.

---

## 🚀 Deployment Steps

### Step 1: Create a New GitHub Repository
1. Log in to your GitHub account and create a new repository.
2. Set the repository visibility to **Public**.
3. Do **NOT** initialize with a README, .gitignore, or license (keep it an empty repository).

### Step 2: Push Code to GitHub
Extract the zip package, open your terminal / command prompt in the project root folder, and run:

```bash
git init
git add .
git commit -m "feat: initial commit for paper project page"
git branch -M main
git remote add origin [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
git push -u origin main

```

> **Note:** Replace `YOUR_USERNAME` and `YOUR_REPOSITORY_NAME` with your actual GitHub username and repository name.

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub.
2. Navigate to **Settings** -> **Pages** (in the left sidebar).
3. Under **Build and deployment** -> **Source**, select **Deploy from a branch**.
4. Set the **Branch** to `main` and folder to `/ (root)`, then click **Save**.
5. Wait 1-2 minutes. Your project page will be live at:
`https://YOUR_USERNAME.github.io/YOUR_REPOSITORY_NAME/`