+++
title = '[Hugo] Build Hugo Blog and Deploy to GitHub Page'
date = 2025-01-25T02:15:41+08:00
draft = false
+++

### Steps

- Create a repo on GitHub
- Modify the BaseURL in `hugo.toml`
- Test on local server to create a static page
- Setup GitHub action to generate static page on Github
- Push the project to GitHub

### How to run static page on local server

Once you installed and setup Hugo template on the local serevr, you can enter `hugo server -D` to show the website on the local server.

- `hugo -D` : Create a `public` directory and create a static website

### Setup GtiHub Actions

If you want to automatically re-generate a new static page after pushing new content to Github, you can setup Github Action file.

- Create a directory in your project
  - `.github/workflows`
- Add yml file under the directory
- Remember to go the Pages in the setting on Github to decide `gh-pages` to show page
