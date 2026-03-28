# Babji Public Site

This folder is a self-contained static website for publishing Babji on GitHub Pages from a separate public repository.

## Recommended Deployment

1. Create a new public GitHub repository.
   Suggested names:
   - `babji-site`
   - `<your-username>.github.io`

2. Copy the contents of this folder into the new repository.
   Copy these files and folders to the repo root:
   - `index.html`
   - `privacy.html`
   - `site.css`
   - `.nojekyll`
   - `assets/`

3. Push the repository to GitHub.

4. Enable GitHub Pages.
   - Open the new repository on GitHub
   - Go to `Settings` -> `Pages`
   - Under `Build and deployment`, choose `Deploy from a branch`
   - Select branch `main`
   - Select folder `/ (root)`
   - Save

5. Wait for the site to publish.
   The public URL will be:
   - `https://<your-username>.github.io/` for a user site repo
   - `https://<your-username>.github.io/<repo-name>/` for a project site repo

## What To Put In Apple’s Form

- `Website`: use the published GitHub Pages URL
- `App Name`: `Babji`
- `Bundle ID`: `srivatsa.BabjiAssistant`

## Notes

- This keeps the main `Babji` repository private.
- Only the static site files in this folder need to be public.
