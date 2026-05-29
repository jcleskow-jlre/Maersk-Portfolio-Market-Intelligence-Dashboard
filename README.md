# Maersk Market Intelligence Dashboard

GitHub Pages deployment package.

## Files

- `index.html` - the full standalone Maersk North American Portfolio & Market Intelligence Dashboard with animated globe/login entry experience.
- `.nojekyll` - prevents GitHub Pages from applying Jekyll processing.

## GitHub Pages upload

1. Create or open your GitHub repository.
2. Upload the contents of this folder to the repository root.
3. Go to Settings > Pages.
4. Set Source to `Deploy from a branch`.
5. Select `main` branch and `/root` folder.
6. Save.

GitHub Pages should serve the dashboard from the repository Pages URL.

## Important security note

This is a standalone front-end dashboard package. It is appropriate for a demo/login-gated experience, but true password security and automated password reset emails require hosted backend authentication.
