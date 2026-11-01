# WT-1

## Deploy to GitHub Pages

This is a static site; GitHub Actions publishes `index.html` and its stylesheet
whenever a commit is pushed to `main`.

1. In the repository, open **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Push to `main`, or run **Deploy to GitHub Pages** manually from the
   **Actions** tab.

After the workflow completes, the site will be available at
<https://surf2108.github.io/WT-1/>.

The sign-up form currently displays a confirmation in the browser only; it does
not submit or store email addresses.
