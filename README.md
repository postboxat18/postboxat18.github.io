# Host Multiple Projects Using GitHub Pages with USERNAME

This guide outlines the process of using **<username> GitHub Pages** as the main repository for hosting multiple projects under a single GitHub Pages site. This approach is ideal for developers wanting a cohesive, organized way to showcase their projects within one domain.

---

## Overview

GitHub Pages makes it possible to host and display multiple projects, each with its own unique features, under one central site. This guide will help you set up **<username> GitHub Pages** to display your projects with an easy-to-navigate structure that is scalable for future additions.

## Key Features of Multi-Project GitHub Pages Hosting

- **Multi-Project Display**: Host multiple projects under a single GitHub Pages site.
- **Easy Navigation**: Each project has a dedicated section, making it simple for users to explore each one.
- **Consistent Domain**: Using a single domain (`https://<username>.github.io`) simplifies access and organization.
- **Modularity and Scalability**: Add or update projects without disrupting the structure.

## Getting Started with Multi-Project Hosting

To add a new project to your GitHub Pages site:

1. **Create a New Directory**: Add a directory within the main repository for each project.
2. **Add Project Files**: Include all necessary files for each project (HTML, CSS, JavaScript).
3. **Update Main Navigation**: In `index.html` or your main navigation file, add links and descriptions for each project.
4. **Edit the README**: Optionally, update the README to include an overview of each new project for easy reference.

### Example Directory Structure

```plaintext
<username>.github.io/
├── index.html           # Main homepage
├── Project1/            # Project 1 directory
│   ├── index.html
│   ├── assets/
│   └── ...
├── Project2/            # Project 2 directory
│   ├── index.html
│   ├── assets/
│   └── ...
└── README.md            # README file
```

## Hosting a Flutter Web Project on GitHub Pages

To host a Flutter web project under <username>’s GitHub Pages, follow these steps:

### Step-by-Step Guide to Hosting a Flutter Web Project

1. **Create a Flutter Project and GitHub Repository**: Start with a Flutter project and a new GitHub repository.
2. **Complete Your Flutter App**: Ensure your app functions as expected.
3. **Upgrade Flutter**: Run `flutter upgrade` to update to the latest version.
4. **Enable Web Support**:
   ```bash
   flutter config --enable-web
   ```
5. **Recreate Project**:
   ```bash
   flutter create .
   ```
6. **Build Your Web App**:
   ```bash
   flutter build web
   ```
7. **Modify `index.html`**: In `build/web`, remove `<base href="/">` to fix routing issues.
8. **Commit and Push to GitHub**: Add your files to your GitHub repository.
9. **Configure GitHub Pages**:
   - Go to **Settings** > **Pages** in your repository.
   - Choose your source branch (e.g., `main`).
10. **Deploy Your Project**: Once GitHub builds and deploys, access your live site at your GitHub Pages URL.

---

## Example Projects on <username> GitHub Pages

1. **Project 1**: Description and link to `https://<username>.github.io/Project1/`.
2. **Project 2**: Description and link to `https://<username>.github.io/Project2/`.
3. Easily add more projects by following the directory structure.

---

### License

This repository and its projects are open-source under the [MIT License](LICENSE).

---

For a live demo and more details, visit on Postboxat18 GitHub Pages 
[FlutterBootstrap](https://postboxat18.github.io/FlutterBootstrap/).
