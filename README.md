# Mae MacDonald — Academic Website

Personal academic website built for GitHub Pages.

## How to Deploy on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in (or create an account).
2. Click the **+** button → **New repository**.
3. Name the repository: `yourusername.github.io`
   - Replace `yourusername` with your actual GitHub username (e.g., `maemacdonald.github.io`).
   - **Important:** The repo name *must* match this exact format for GitHub Pages to work.
4. Set the repo to **Public**.
5. Click **Create repository**.

### Step 2: Upload Your Site Files

**Option A — Upload via GitHub.com (easiest):**

1. On your new repository page, click **"uploading an existing file"** (or go to the **Code** tab → **Add file** → **Upload files**).
2. Drag and drop **all** the files and folders from this download:
   - `index.html`
   - `research.html`
   - `cv.html`
   - `style.css`
   - `MacDonald_CV.pdf`
   - `images/` (the entire folder with all photos)
3. Click **Commit changes**.

**Option B — Upload via Git (command line):**

```bash
cd path/to/this/folder
git init
git add .
git commit -m "Initial site"
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. In your repository, go to **Settings** → **Pages** (in the left sidebar).
2. Under **Source**, select **Deploy from a branch**.
3. Choose the **main** branch and **/ (root)** folder.
4. Click **Save**.
5. Wait 1–2 minutes, then visit `https://yourusername.github.io`.

Your site is live!

## Updating Your Site

- To update content, edit the HTML files and push/upload the changes.
- To update your CV, replace `MacDonald_CV.pdf` with the new version (keep the same filename).
- Changes typically go live within 1–2 minutes of pushing.

## File Structure

```
├── index.html          # Home page
├── research.html       # Research page
├── cv.html             # CV page (embeds PDF)
├── style.css           # Stylesheet
├── MacDonald_CV.pdf    # Your CV
├── images/             # Photos
│   ├── mae_macdonald.jpeg
│   ├── gallery_kakuma_gbv.jpg
│   ├── gallery_calaid_greece.png
│   ├── gallery_tern_london.png
│   ├── gallery_tifa_nairobi.jpg
│   ├── gallery_rwamwanja_uganda.jpg
│   └── gallery_kalobeyei_kenya.jpg
└── README.md           # This file
```

## Custom Domain (Optional)

If you own a domain (e.g., `maemacdonald.com`), you can point it to your GitHub Pages site:

1. In your repo **Settings** → **Pages** → **Custom domain**, enter your domain.
2. Update your domain's DNS settings:
   - Add a CNAME record pointing to `yourusername.github.io`.
   - Or add A records pointing to GitHub's IPs (see [GitHub docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)).
3. Check **Enforce HTTPS**.
