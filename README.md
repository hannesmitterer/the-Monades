# the-Monades
Euystacio Roman

## GitHub Pages Deployment

This repository is configured with automatic deployment to GitHub Pages. Any changes pushed to the `main` branch will automatically trigger a deployment.

### Setup Instructions

To enable GitHub Pages for this repository:

1. Go to **Settings** → **Pages** in your GitHub repository
2. Under **Source**, select **GitHub Actions**
3. The workflow will automatically deploy your site when you push to the `main` branch

### Manual Deployment

You can also manually trigger a deployment by going to the **Actions** tab and running the "Deploy to GitHub Pages" workflow using the "Run workflow" button.

### Workflow Details

The deployment workflow (`.github/workflows/deploy.yml`) includes:
- **Checkout**: Retrieves the latest code from the repository
- **Setup Pages**: Configures GitHub Pages settings
- **Upload artifact**: Packages the static site files
- **Deploy**: Publishes the site to GitHub Pages

Your site will be available at: `https://hannesmitterer.github.io/the-Monades/` 
