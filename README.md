# Vee Mirror site

A small public site for the private Vee Mirror project. It is static HTML and CSS for GitHub Pages.

Replace `[INSERT CONTACT EMAIL]` in `privacy.html` before you publish or send the site to Pinterest.

## Publish

1. Create a new public GitHub repository named `vee-mirror-site`.
2. Add `index.html`, `privacy.html`, `styles.css`, and `README.md`.
3. Commit and push to the `main` branch.
4. Open the repository on GitHub.
5. Go to Settings → Pages.
6. Under Build and deployment, set Source to Deploy from a branch.
7. Select branch `main` and folder `/` (root).
8. Save.
9. GitHub will publish the site. The addresses will look like:

https://USERNAME.github.io/vee-mirror-site/

https://USERNAME.github.io/vee-mirror-site/privacy.html

Replace `USERNAME` with your GitHub username.

## Pinterest fields

Company website or app link:

https://USERNAME.github.io/vee-mirror-site/

Link to Privacy Policy:

https://USERNAME.github.io/vee-mirror-site/privacy.html

From this folder:

```bash
git init
git add index.html privacy.html styles.css README.md
git commit -m "Add the public Vee Mirror site"
git branch -M main
git remote add origin https://github.com/USERNAME/vee-mirror-site.git
git push -u origin main
```
