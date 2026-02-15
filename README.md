# legendary-spork

This repository contains a simple static site for **madongo.com** in the `public/` directory.

- The site is a single Bootstrap-powered page at `public/index.html`.
- A `CNAME` file (`public/CNAME`) is included with the custom domain `madongo.com`.
- GitHub Actions workflow at `.github/workflows/pages.yml` publishes the contents of `public/` to GitHub Pages on pushes to `main`.

To update the site, edit files under `public/`, commit, and push to `main`. The workflow will publish the updated site automatically.
