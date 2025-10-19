# GitHub Pages Deployment Workflow

This project demonstrates how to automatically deploy a static website to **GitHub Pages** using **GitHub Actions**.

## Project Structure

```
.github/
  workflows/
    deploy.yml     # GitHub Actions workflow file
index.html         # Static website file
README.md          # Project documentation
```

## Purpose

This repository helps you understand the basic concepts of **Continuous Integration (CI)** and **Continuous Deployment (CD)** by automating the deployment process of a simple HTML page.

## How It Works

1. Whenever you **push changes** to the `main` branch and those changes include `index.html`, GitHub Actions will trigger the workflow.
2. The workflow defined in `.github/workflows/deploy.yml` automatically:

   * Checks out the repository.
   * Sets up GitHub Pages.
   * Uploads the static files.
   * Deploys them to the live website.

## Result

After a successful run, your site will be available at:

```
https://<your-username>.github.io/gh-deployment-workflow/
```

Replace `<your-username>` with your actual GitHub username.

## Key Concepts

* **GitHub Actions** – Automates tasks like testing, building, and deployment.
* **GitHub Pages** – Hosts static websites directly from your GitHub repository.
* **CI/CD** – Ensures continuous integration and automatic deployment whenever code changes.

## License

This project is open source and available under the MIT License.
