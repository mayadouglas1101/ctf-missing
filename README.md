# The Denver Courier — CTF News Site

A fictional local news site built as a CTF challenge prop.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Homepage with article grid |
| `missing.html` | Missing person article (the hook) |
| `article-wildfire.html` | Filler article |
| `article-transit.html` | Filler article |
| `article-festival.html` | Filler article |
| `style.css` | Shared stylesheet |
| `robots.txt` | ⚠️ Contains the CTF clue — replace `PUT BASE64 HERE` |
| `sitemap.xml` | Standard sitemap |
| `_config.yml` | GitHub Pages config |

## Deploying to GitHub Pages

1. Create a new GitHub repository (public)
2. Push all files to the `main` branch
3. Go to **Settings → Pages → Source → Deploy from branch → main / root**
4. Your site will be live at `https://yourusername.github.io/repo-name/`

## CTF Setup

Before deploying, edit `robots.txt` and replace `PUT BASE64 HERE` with your actual base64-encoded clue string.

Example — to hide the URL `http://your-site.com/ftp-config.html`:
```
echo -n "http://your-site.com/ftp-config.html" | base64
```
Then paste the output into the robots.txt comment.
# ctf-missing
