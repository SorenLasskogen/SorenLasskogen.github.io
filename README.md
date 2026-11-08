# Søren Lasskogen — Portfolio

A plain static site (HTML + CSS + a few lines of JS). No build step, no frameworks — ready for GitHub Pages.

## Structure

```
index.html                  Home: hero, projects, about, contact
projects/*.html             One case-study page per project
assets/css/style.css        All styling. Colours and fonts are at the top (:root)
assets/js/main.js           Optional: header border on scroll, fade-in, footer year
assets/img/                 Project images (web-sized) + placeholder.svg + favicon.svg
assets/reports/             Compressed project reports (PDF)
```

## Publish on GitHub Pages

1. Create a repository — name it `<your-username>.github.io` to get the address `https://<your-username>.github.io`.
2. Upload the contents of this folder to the root of the repository (so `index.html` is at the top level).
3. In the repository, go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then save.
4. The site goes live after a minute or two.

## Things to fill in

Search the HTML files for `class="todo"`, `YOUR-HANDLE`, `YOUR-USERNAME` and `placeholder.svg`:

- **Bio** — in the About section of `index.html`.
- **LinkedIn / GitHub links** — in the Contact section of `index.html`.
- **My role** and **what I learned** — one to-do on each project page.
- **Videos** — upload each AV production to YouTube or Vimeo (GitHub refuses files over 100 MB), then replace the video placeholder with the `<iframe>` snippet in the HTML comment just above it. Update the "Video — coming soon" button to link to it too.
- **Extra images** — replace `placeholder.svg` with your own photos. Keep images around 1600 px wide and under ~400 KB.

## Adding a project

1. Copy one `<article class="project">` block in `index.html` and change the text, tags, images and links.
2. Copy a page in `projects/`, rename it, and update its content.
3. Update the "Next project" links at the bottom of the project pages so they still form a loop.
