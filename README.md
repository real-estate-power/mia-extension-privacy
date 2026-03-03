# Mia Extension – Privacy Policy

This repo hosts the privacy policy for the Mia Chrome extension at:

**https://patroytall.github.io/mia-extension-privacy/privacy.html**

## Fixing 404 – Enable GitHub Pages

If that URL returns 404:

1. **Push this repo to GitHub** (if you haven’t):  
   `git remote add origin https://github.com/patroytall/mia-extension-privacy.git`  
   then `git push -u origin main` (or `master`).

2. On GitHub: open the repo → **Settings** → **Pages** (left sidebar).

3. Under **Build and deployment** → **Source**, choose **Deploy from a branch**.

4. Under **Branch**, select **main** (or **master**, matching your default branch), and set the folder to **/ (root)**. Click **Save**.

5. Wait 1–2 minutes. The site will be at  
   `https://patroytall.github.io/mia-extension-privacy/`  
   and the privacy policy at  
   `https://patroytall.github.io/mia-extension-privacy/privacy.html`.

6. Use that privacy URL in the Chrome Web Store dashboard.

## Files

- **privacy.html** – Privacy policy (required). Replace `REPLACE_WITH_DATE` and `REPLACE_WITH_SUPPORT_EMAIL` before publishing.
- **index.html** – Redirects to `privacy.html` so the repo root URL also works.
