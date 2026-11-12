# Academic website (Quarto)

## Edit locally
1. Install [Quarto](https://quarto.org/docs/get-started/).
2. Run `quarto preview` in this folder to see the site live while you edit.
3. Edit the `.qmd` files (Markdown) and `_quarto.yml` (sidebar, links, theme).

## Publish on GitHub Pages
1. Create a repo (name it `USERNAME.github.io` for a root URL) and push this folder to `main`.
2. In the repo, go to Settings > Pages and set Source to **GitHub Actions**.
3. Every push to `main` now rebuilds and deploys the site automatically.

Remember to push: 
1. git add .
2. git commit -m "comment"
3. git push
