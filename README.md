# jfbonder.github.io

Personal academic website of Julián Fernández Bonder.

## How to deploy on GitHub Pages

### Option A — repo named `[username].github.io` (recommended)

This gives you the cleanest URL: `https://jfbonder.github.io`

1. Create a repository named exactly **`jfbonder.github.io`** on GitHub.
2. Upload `index.html` (and optionally a `photo.jpg`) to the root of the repo.
3. Go to **Settings → Pages**.
4. Source: **Deploy from a branch** → branch `main` → folder `/ (root)`.
5. Click Save. Your site will be live in about a minute.

### Option B — any repo name

If you use a different repo name (e.g., `website`), the URL will be  
`https://jfbonder.github.io/website` and you don't need to change anything else.

---

## Photo

The site currently loads your photo from the Google Sites CDN, which may not work long-term.  
**Recommended:** add a `photo.jpg` file to this folder and update `index.html`:

```html
<!-- Replace this line: -->
src="https://lh3.googleusercontent.com/..."

<!-- With this: -->
src="photo.jpg"
```

---

## Updating content

Everything is in `index.html`. The main sections to update regularly:

| What | Where in the file |
|---|---|
| Current course | Search for `course-current` |
| New publications | Add items to the `Preprints` or `Published papers` list |
| Students | Search for `student-group` |

---

## Custom domain (optional)

If you have a domain (e.g., `jfbonder.dm.uba.ar`):

1. Add a file named `CNAME` to the repo containing just:
   ```
   jfbonder.dm.uba.ar
   ```
2. Configure a CNAME DNS record at your registrar pointing to `jfbonder.github.io`.
3. In GitHub Pages settings, add your custom domain.

---

## .nojekyll

The `.nojekyll` file (included) tells GitHub Pages not to run Jekyll on this repo.  
This is important because the site is plain HTML and doesn't need any build step.
