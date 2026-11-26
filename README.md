# Software portfolio

Showcase site: a live steel weight calculator plus case studies for WorkNest, WorkNest Security (Android) and WorkNest Admin (desktop).

## Publish on GitHub Pages
1. Create a public repo, e.g. `portfolio`, and upload everything in this folder (keep `index.html` at the top level).
2. Repo > Settings > Pages > Deploy from a branch > `main` / root > Save.
3. Your site will be at `https://chethanprem.github.io/portfolio/`
   and the live calculator at `https://chethanprem.github.io/portfolio/calculator/`.

## Replace the placeholders
Dashed boxes on the page are screenshot slots. Save your images in `shots/` with the file names shown,
then replace each `<div class="slot">...</div>` in `index.html` with:

    <figure><img src="shots/worknest-dashboard.png" alt="..."><figcaption>...</figcaption></figure>

Use demo accounts or blur names, phone numbers, photos and ID details. Do not show real employee or visitor data
or the company logo unless you have permission.
