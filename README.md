# Sendmate - GitHub Pages Deployment 🚚

This repository contains the source code for the **Sendmate** static landing page — a modern, responsive site designed for a fictional parcel delivery service. It is automatically deployed using a simple CI/CD pipeline powered by GitHub Actions.

---

## ✨ Features

- **Modern Design:** A sleek and responsive landing page built with simplicity and clarity in mind.
- **Continuous Deployment:** Any changes pushed to the `index.html` file on the `main` branch are automatically deployed via GitHub Pages.

---

## 🚀 Deployment Workflow

This project uses a GitHub Actions workflow defined in `.github/workflows/deploy.yml`.

The workflow is triggered on every push to the `main` branch and performs the following steps:

1. **Checkout Code:** The repository's source code is checked out.
2. **Setup Pages:** GitHub Pages environment is configured.
3. **Upload Artifact:** All files in the repository's root directory are bundled into a deployable artifact.
4. **Deploy:** The artifact is deployed to the `gh-pages` environment, making the site live.

🔗 **Live Website:**  
Access your live site at:  
`https://<your-username>.github.io/<your-repo-name>/`  
*(Replace with your actual GitHub username and repo name.)*

---

## 🛠️ How to Use

1. **Clone this repository:**
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
