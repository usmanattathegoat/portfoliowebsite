# Usman Atta: Frontend Developer Portfolio

A single-page portfolio built with HTML, CSS and vanilla JavaScript. It is a static site: no Node.js, npm, Vite, framework, backend or build command is required.

## Run locally

Open `index.html` directly in a browser, or open the folder in VS Code and use an extension such as Live Server if you prefer a local URL.

## Folder structure

```text
.gitignore
README.md
index.html
main.js
styles.css
public/favicon.svg
public/images/usman-atta.jpg
```

## Upload to GitHub

Upload the project files and folders listed above, including `.gitignore`. Keep the folder structure exactly as shown so the relative CSS, JavaScript, favicon and portrait paths continue to work.

Do not upload `node_modules/`, `dist/`, local `.env` files or log files. They are not needed for this static site.

## Portrait

The portrait is extracted from the CV and displayed in the hero section from `public/images/usman-atta.jpg`. Replace that file to use a higher-resolution photo; keep the same filename or update the image path in `index.html`.

## Projects

The projects section currently links to the GitHub profile instead of showing invented project details. When projects are ready, add project cards there with real descriptions, screenshots and working demo/repository URLs.

## Update contact information

Search `index.html` for the email address, phone number and GitHub profile URL to update the displayed contact details and links.

## Change content and styling

- Text and page structure: edit `index.html`.
- Colors, fonts and styling: edit `styles.css`.
- Menu, active navigation, reveal effects and footer year: edit `main.js`.

Google Fonts load from Google Fonts with system fallbacks. Deploy the repository as a static site; no build command is needed. For Vercel, set the framework preset to **Other**, leave the build command and output directory empty, and deploy the repository root.
