# Synapptech Labs Legal Site

Static GitHub Pages site for Synapptech Labs legal documents.

## Structure

```text
.
├── index.html
├── privacy/
│   └── index.html
├── terms/
│   └── index.html
└── assets/
    ├── favicon.svg
    └── styles.css
```

## Suggested URLs

```text
https://legal.synapptech.dev/
https://legal.synapptech.dev/privacy/
https://legal.synapptech.dev/terms/
```

## GitHub Pages

1. Create a public repository, for example `synapptech-legal`.
2. Add these files to the repository root.
3. In GitHub, open Settings > Pages.
4. Set Source to "Deploy from a branch".
5. Set Branch to `main` and Folder to `/ (root)`.
6. Optional: set the custom domain to `legal.synapptech.dev`.
7. Add a DNS CNAME record:

```text
legal -> YOUR-GITHUB-USERNAME.github.io
```

8. Enable "Enforce HTTPS" once GitHub allows it.

Before publishing, have the Privacy Policy and Terms of Service reviewed for your exact apps, data collection, third-party services, and jurisdiction.
