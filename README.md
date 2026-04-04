# Mae MacDonald — Academic Website

Personal academic website for GitHub Pages, using the same template as [alyssaheinze.github.io](https://alyssaheinze.github.io/).

## How to Deploy

1. Go to your repository at `github.com/maemacdonald/maemacdonald.github.io`
2. Delete all existing files (or replace them)
3. Upload everything from this folder:
   - `index.html`
   - `stylesheets/` (folder with `styles.css` and `kube.css`)
   - `img/` (folder with your photo)
   - `cv/` (folder with your CV PDF)
4. Commit the changes
5. In **Settings → Pages**, make sure it's set to deploy from the **main** branch, **/ (root)**
6. Wait 1–2 minutes, then visit `https://maemacdonald.github.io`

## Updating

- **CV**: Replace `cv/MacDonald_CV.pdf` with a new file (keep the same name)
- **Photo**: Replace `img/macdonald_website.jpg`
- **Content**: Edit `index.html` directly — it's plain HTML, no build step needed

## File Structure

```
├── index.html
├── stylesheets/
│   ├── styles.css
│   └── kube.css
├── img/
│   └── macdonald_website.jpg
├── cv/
│   └── MacDonald_CV.pdf
└── README.md
```
