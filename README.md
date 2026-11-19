# AREDL Chests

Open a chest and get a random extreme demon from the [AREDL](https://aredl.net).

- Chests: Top 50, Top 150, Top 300, Top 500, Top 1000, All, and a Custom range
- Result shows placement, name, video thumbnail, level ID, verifier and publisher
- Pulls the list live from `https://api.aredl.net/v2/api/aredl/levels` on every page load, so it updates itself when AREDL does (a cached copy is used only as a fast first paint / offline fallback)
- Single static file, no build step

## Host it on GitHub Pages

1. Create a new GitHub repository and upload `index.html` (and this README).
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then Save.
4. After a minute your site will be live at `https://<your-username>.github.io/<repo-name>/`.

Fan-made and unaffiliated with AREDL.
