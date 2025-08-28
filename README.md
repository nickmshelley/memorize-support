# {{APP_NAME}} Support Site

This repository hosts the public support website for the **{{APP_NAME}}** iOS app.

## Quick Start (GitHub Pages)
1. Create a new **public** repository on GitHub (e.g., `{{REPO_NAME}}`).
2. Upload the files in this folder to the repo root. Commit to `main`.
3. In the repo, go to **Settings → Pages**.
   - **Source**: *Deploy from a branch*
   - **Branch**: `main` / `/ (root)`
4. Click **Save**. GitHub will publish your site at:
   `https://{{GITHUB_USERNAME}}.github.io/{{REPO_NAME}}/` (or just `https://{{GITHUB_USERNAME}}.github.io/` for a user site).
5. (Optional) Add a custom domain under **Settings → Pages → Custom domain**, and enable **Enforce HTTPS**.

## Customize
- Find and replace placeholders: `{{APP_NAME}}`, `{{SUPPORT_EMAIL}}`, `{{DEVELOPER_NAME}}`.
- Edit `faq.html` and `privacy.html` to match your app’s specifics.
- To prevent Jekyll processing advanced folders, we include a `.nojekyll` file.

## Notes
- A support URL should provide a way for users to contact you and find help. Keep it online and responsive.
