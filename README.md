# Bhanu Prakash — Portfolio

This repository contains a single-file portfolio (`index.html`) and the uploaded CV file.

## What's included
- `index.html` — Responsive single-page portfolio built with HTML, CSS and JavaScript. Includes:
  - Theme toggle (light/dark)
  - Curated skills & publications
  - Contact form skeleton (instructions for Formspree/Netlify)
  - Download link to your uploaded CV (DOCX)

- `BHANUPRAKASH-CV-2025.docx` — The original CV file you uploaded.

## Deploy to GitHub Pages
1. Create a new GitHub repository (e.g., `bhanu-portfolio`).
2. Upload `index.html` and `BHANUPRAKASH-CV-2025.docx` to the repository root.
3. In GitHub, go to **Settings → Pages** (or **Pages** in the repo sidebar).
4. Select the branch (e.g., `main`) and folder `/ (root)`, then save.
5. Your site will be available at `https://<your-username>.github.io/<repo-name>/`.

## Enable contact form submissions (optional)
### Using Formspree:
1. Create an account at https://formspree.io and create a form to get your endpoint.
2. Replace the `sendForm()` function in `index.html` with a `fetch()` POST to your Formspree endpoint.
3. Example (replace `YOUR_FORMSPREE_URL`):

```js
fetch("https://formspree.io/f/YOUR_FORMSPREE_ID", {
  method: "POST",
  headers: { "Content-Type": "application/json" },
  body: JSON.stringify({ name, email, subject, message })
})
.then(res => { /* handle success */ })
```

### Using Netlify Forms:
See Netlify docs: https://docs.netlify.com/forms/setup/

## Customizations I can do next (pick one)
- Convert the DOCX to PDF and include both versions in the repo.
- Add a profile photo and small assets folder.
- Replace the contact demo with a working Formspree integration and test it.
- Convert this into a React single-file project or a two-file version with external CSS.

Tell me which option you'd like and I'll prepare it.
