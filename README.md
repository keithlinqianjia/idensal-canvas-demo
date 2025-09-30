
# idensal Canvas Demo – GitHub Pages

This folder is ready to deploy to GitHub Pages.

## Quick Deploy (New Repo)
1. Create a **new public repository** on GitHub (e.g., `idensal-canvas-demo`).
2. Upload **`index.html`** (this root file) and **commit**.
3. Go to **Settings → Pages**:
   - **Source:** Deploy from branch
   - **Branch:** `main` (or `master`), **Folder:** `/root`
   - Click **Save**.
4. Wait ~30–60 seconds, then open the URL shown (typically `https://<your-username>.github.io/idensal-canvas-demo/`).

## Update
Edit `index.html` and push again. Pages will redeploy automatically.

## Notes
- If your company blocks CDNs, ask for an **offline** build (no external scripts). 
- For a custom domain, add it under **Settings → Pages → Custom domain**, then create a DNS CNAME to `<your-username>.github.io`.
