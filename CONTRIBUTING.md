# Contributing to the OHDSI UK Website

Thank you for your interest in contributing to the OHDSI UK website!

This site is built using [Quarto](https://quarto.org/) and automatically deployed via [GitHub Actions](https://github.com/features/actions) to GitHub Pages.


## 🛠 Project Setup

To contribute, you'll need the following installed locally:

- [Quarto CLI](https://quarto.org/docs/get-started/)
- [R](https://cran.r-project.org/)
- [Git](https://git-scm.com/) or [GitHub Desktop](https://desktop.github.com) for a user-friendly interface

You can edit the code using any Integrated Development Environment that supports Quarto (e.g. RStudio, Positron, VS Code, or JupyterLab).  
We recommend using **RStudio** as the repository includes a `.Rproj` file to simplify your workflow.


## 🧾 How to Contribute

### 0. Open an Issue (Recommended)

Before starting, we encourage you to [open an issue](https://github.com/ohdsi/ohdsi-uk/issues) to propose your idea or content. This helps avoid duplicated efforts and ensures your contribution aligns with the project's direction.

While pull requests (PRs) are always welcome, we can't guarantee that all will be accepted — starting a discussion increases the chances your work will be merged.

### 1. Clone the Repository

### 2. Create a New Branch

### 3. Make Changes, Preview, and Commit

After editing content or code, you can preview the website locally:

```bash
quarto preview
```

This will start a live preview server where you can see your changes.

Once you're satisfied commit them to Github.

### 4. Push Your Changes and Open a Pull Request

Push your branch and open a **Pull Request** (PR).

💡 If the GitHub Actions check fails and you're unsure why, just leave a comment in the PR and a maintainer will assist.


### 5. Request a Review

Ask a maintainer to review your changes.

## ✅ Website Deployment

You do **not** need to manually render or deploy the website.

When changes are merged into the `main` branch:

* A GitHub Action renders the site using Quarto.
* The rendered output is automatically deployed to GitHub Pages.

## 📄 Style and Content Guidelines

* Use [Quarto Markdown syntax](https://quarto.org/docs/authoring/markdown-basics.html).
* Keep filenames lowercase and use underscores (`_`) rather than spaces.
* Use relative links to other pages (e.g., `resources.qmd`, not absolute URLs).
* Place images in the `images/` folder and optimize them for web use.

## 🤝 Code of Conduct

Please be respectful and professional in your interactions.
See our [CODE\_OF\_CONDUCT.md](./CODE_OF_CONDUCT.md) for details.

Thank you for contributing! 🎉
