# PhaseNX Download Page

Static landing page starter for sharing the PhaseNX Windows installer on GitHub Pages (or any static host).

## Files
- index.html - landing page with download CTA and feature overview.
- styles.css - styling (no build step required).
- PhaseNX-Setup-0.1.0.exe - copy your installer here so the download button works.

## Deploy to GitHub Pages
```bash
git init
git checkout -b main
copy "C:\path\to\PhaseNX Setup 0.1.0.exe" .\PhaseNX-Setup-0.1.0.exe
git add index.html styles.css README.md PhaseNX-Setup-0.1.0.exe
git commit -m "Add PhaseNX download page"
git remote add origin https://github.com/ECoder1234/PhaseNX.git
git push -u origin main
```

Then enable Pages (Settings > Pages > Source: main branch, / root).

## Updating
1. Replace the installer with the new build.
2. Adjust the version text in index.html and the filename in the download link.
3. Commit and push - GitHub Pages redeploys automatically.
