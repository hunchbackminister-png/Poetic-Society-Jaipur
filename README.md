# Poetic Society Jaipur — GitHub Pages copy

This is a static recovery of the browser-delivered frontend of the Poetic Society Jaipur site.

## Publish on GitHub Pages

1. Create a GitHub repository.
2. Upload **the contents of this folder** directly into the repository root.
3. Commit to the `main` branch.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select `main` and `/ (root)`.
7. Click **Save**.
8. Wait for GitHub Pages to deploy.

There is intentionally no GitHub Actions workflow in this version; the branch deployment is simpler and avoids workflow-permission issues.

## Important

The site is already compiled into `static/js/bundle.js`, so you do not need `npm install` or a build command.

The `src-recovered` directory is included for reference; GitHub Pages serves `index.html` and the compiled bundle.
