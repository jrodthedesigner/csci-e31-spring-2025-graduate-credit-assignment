# Git Practice Tutorial
## Objective
Learn how to set up Git and GitHub for version control by connecting a local Node.js project to a remote GitHub repository.

## Steps

1. **Install Node.js and Git** (if not already installed).

2. **Initialize the project with Git**
   ```bash
   git init
   ```

3. **Add and commit your files**
   ```bash
   git add .
   git commit -m "Initial commit"
   ```

4. **Create a repository on GitHub** (name it `git-practice-tutorial`) and **do not initialize with a README**.

5. **Connect your local project to the GitHub repo**
   ```bash
   git remote add origin https://github.com/<your-username>/git-practice-tutorial.git
   git branch -M main
   git push -u origin main
   ```

6. **Verify** that the files appear in your GitHub repository.

## Files Included
- `index.js`: Basic Node.js file
- `package.json`: Project metadata
