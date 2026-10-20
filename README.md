# Representation Theory Seminar at IU Indianapolis

This directory contains the seminar website migrated from IU Pages to GitHub Pages.
The website preserves the archived HTML pages and their PDF notes.

## Deployment to GitHub Pages

1. Create a **public** repository named `ORGANIZATION.github.io` under the organization `ORGANIZATION`.
2. Place **the contents of this directory** (including `index.html` and the `*_notes` folders) directly at the **root** of the repository, not inside a nested `seminar_github_pages` folder.
3. In repository **Settings → Pages → Build and deployment**, select **Deploy from a branch**, branch `main`, folder `/(root)`.
4. Visit `https://ORGANIZATION.github.io/` after GitHub finishes publishing.

The root `index.html` is copied from `rt_seminar.html`.
Internal archive and PDF links now use relative URLs, so they also work with a future custom domain.
External arXiv and other non-IU links were left unchanged.

To update the current semester, edit `index.html` (and optionally `rt_seminar.html` if you want to keep its legacy alias synchronized).

The additional HTML pages and Markdown drafts present in the source archive are retained without adding them to site navigation.
