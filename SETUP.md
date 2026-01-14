# Setup Instructions for Students

## Publishing Your Own Quarto Website

After forking this repository, follow these steps to publish your own website:

### 1. Fork the Repository
Click the "Fork" button at the top right of the GitHub repository page.

### 2. Enable GitHub Pages
1. Go to your forked repository on GitHub
2. Click on **Settings** → **Pages**
3. Under "Build and deployment":
   - **Source**: Select "GitHub Actions"

### 3. Make Changes and Push
Once GitHub Pages is enabled with GitHub Actions as the source, any push to the `main` branch will automatically build and publish your website.

Your website will be available at: `https://[your-username].github.io/third-year-lab-ising/`

### 4. Local Development (Optional)
To preview your website locally before pushing:

```bash
# Install Quarto (if not already installed)
# Visit: https://quarto.org/docs/get-started/

# Render the website
quarto render

# Preview the website
quarto preview
```

## Adding Content
- Edit `index.qmd` to modify the homepage
- Add new `.qmd` files for additional pages
- Update `_quarto.yml` to add pages to the navigation bar

## Troubleshooting
- If the website doesn't deploy, check the **Actions** tab for build errors
- Make sure GitHub Pages is set to use "GitHub Actions" as the source
- The workflow runs automatically on every push to `main`
