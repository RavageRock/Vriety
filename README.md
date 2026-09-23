# Vriety — coming soon page

Static one-page site. No build step, no dependencies beyond two Google Fonts loaded via `<link>`.

## Publish with GitHub Pages

1. Create a new GitHub repo (e.g. `vriety-coming-soon`) and push these files (`index.html`, `assets/`) to the root of the `main` branch.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
4. GitHub gives you a URL like `https://<your-username>.github.io/vriety-coming-soon/` within a minute or two.
5. Optional — custom domain: add a `CNAME` file at the root containing your domain (e.g. `vriety.my`), and point your domain's DNS at GitHub Pages per [GitHub's custom domain docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

## Editing later

- Copy/headline: edit the text inside `<div class="hero">` in `index.html`.
- Colors: change the `:root` variables at the top of the `<style>` block.
- Logo/favicons: replace the files in `assets/` (keep the same filenames, or update the `<link>`/`<img>` paths in `index.html`).
