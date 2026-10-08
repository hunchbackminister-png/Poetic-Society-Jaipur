# Poetic Society Jaipur

Standalone recovery of the browser-delivered Poetic Society Jaipur frontend.

## Run locally

You can serve it with any static HTTP server. For Python:

```bash
python -m http.server 8000
```

Then open http://localhost:8000/

## Deploy to GitHub Pages

1. Create a GitHub repository.
2. Upload **all files and folders in this repository**.
3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **GitHub Actions**.
5. The included workflow will deploy the site.

The image references in the recovered bundle have been made relative (`./images/...`) so the site also works when hosted as a project site such as `https://USERNAME.github.io/REPOSITORY/`.

## Important

This is the browser-delivered frontend recovered from the live deployment. It is not Emergent's private server/backend source or the original pre-transpilation project files.
