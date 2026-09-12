# Fanji Yang — Academic Homepage

Personal academic homepage powered by GitHub Pages.

## Website

`https://yangfanji.github.io/`

## Repository

This repository is a static academic website. No build system or server is required.

### Structure

```text
.
├── index.html
├── about.html
├── publications.html
├── projects.html
├── cv.html
├── contact.html
├── assets/
│   ├── css/style.css
│   ├── js/main.js
│   └── images/
├── cv/
├── publications/
│   └── publications.bib
└── projects/
```

## Deployment

1. Create a public GitHub repository named exactly `<your-github-username>.github.io`.
2. Upload all files in this repository to the root of that repository.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Select `main` and `/ (root)`.
6. Save and wait for GitHub Pages to deploy.

## Before publishing

Replace the following placeholders:

- `your-email@example.com`
- Google Scholar URL
- ORCID URL
- GitHub URL
- arXiv URL
- CV PDF in `cv/Fanji_Yang_CV.pdf`
- Portrait in `assets/images/profile.jpg`
- Biography and institutional information
- Additional publications and projects

## Maintenance

For each new paper, add a publication block to `publications.html` and update `publications/publications.bib`.

For major changes, use Git commits such as:

```text
feat: add new publication
update: refresh academic profile
fix: mobile navigation
```

## License

The website source code can be released under MIT if desired. The author's papers, CV, photographs, and other scholarly materials may have separate copyright and should not automatically be assumed to use the code license.
