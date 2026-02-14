# Deploy this site to GitHub Pages

Steps to publish this project to GitHub Pages using the included GitHub Actions workflow:

1. Create a new empty repository on GitHub (for example: `yourusername/valentine-letter`).

2. On your machine, in this project folder, run:

```bash
cd "c:\Users\user\Downloads\code"
git init
git branch -M main
git add --all
git commit -m "Initial site"
# Replace the URL below with the repository URL you created
git remote add origin https://github.com/yourusername/valentine-letter.git
git push -u origin main
```

3. After you push, GitHub Actions will run the `deploy-pages` workflow and publish the repository root to GitHub Pages. Visit the repository Settings → Pages to see the published URL.

Notes:
- If your repo is private, enable Pages in repository settings or make it public.
- You can customize the workflow or deploy only the `build` directory by changing the `path` in the workflow.
