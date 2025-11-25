# SafariPlug254 — Local Preview

This is a simple static site for SafariPlug254 (renamed from Nomad Luxe Safaris).

How to preview locally

1. Open a PowerShell terminal in this folder:

   ```powershell
   cd "C:\Users\lameck\Downloads\nomad-luxe-website"
   ```

2. Start a simple HTTP server (requires Python 3):

   ```powershell
   python -m http.server 8000
   ```

   Then open http://localhost:8000/index.html in your browser.

Alternative (VS Code Live Server):

- Install the Live Server extension in VS Code.
- Right-click `index.html` → Open with Live Server.

Git instructions

Initialize the repository and push to GitHub (optional):

```powershell
git init
git add .
git commit -m "Initial commit: rename to SafariPlug254, remove merchandise"
git branch -M main
# create repo on GitHub and add remote, then:
# git remote add origin https://github.com/youruser/yourrepo.git
# git push -u origin main
```

Contact / Notes

If you want me to push this to GitHub Pages or deploy to Netlify/Vercel, tell me and I will prepare the repo or deploy configuration.
