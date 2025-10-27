#  Website Collaboration Guide

This repository hosts our website, built with **[Quarto](https://quarto.org)** and automatically published via **GitHub Pages**.

## How to Update the Website

1. **Edit** the main file: Open **`index.qmd`** and make your changes (text, images, or code).
2. **Commit and push** your edits to the `main` branch (or edit the file directly on GitHub):

   ```bash
   git add index.qmd
   git commit -m "Update website content"
   git push
   ```

3. **Wait about 1 minute.** GitHub Actions will automatically:

   * Render the updated website using Quarto.
   * Publish the new version to the **`gh-pages`** branch.
   * Update the live site automatically.