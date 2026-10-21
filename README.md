# Temporary EDS website concept preview

This is a **public demo** of a proposed design, not the official Endurance Dealer Services website. Forms and some features are illustrative only. No official EDS Webflow site is connected to this repo.

## Publishing
Upload the approved V28 HTML file from the private development source as **`docs/index.html`**. Enable **Settings → Pages → Deploy from a branch → main → /docs**. Once deployed, the expected share URL is:

https://adamkarner.github.io/eds-website-preview/

## Seven-day expiration

`.github/workflows/expire-preview.yml` checks hourly for seven days after the first Git commit creating `docs/index.html`, then deletes that file. Due to GitHub's scheduled Actions and Pages deployment lag, removal isn't guaranteed exactly at 7×24 hours. **The repository and its Git history remain public after the page expires**; downloaded or cached copies cannot be recalled. Delete the public repository after the sharing period if you want to eliminate easy access to its previous commits.

**Do not commit** private developer documents, access credentials, or customer/dealer information. The approved preview can be seen by anyone with the URL.
