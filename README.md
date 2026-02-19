# Calc-App

Simple calculator front-end (HTML/CSS/JS).

## Files

- `index.html` — application entry
- `index.js` — app logic
- `style.css` — styles

## Prerequisites

- A modern browser
- (Optional) Node.js for `npx live-server`
- (Optional) Python 3 for `http.server`

## Run locally

- Open the `index.html` file directly in your browser.
- Python server (recommended for relative URLs):
```powershell
cd "C:\Users\pothu\OneDrive\Desktop\frontend-projects\Calc-App"
py -3 -m http.server 8000
```
Open http://localhost:8000

- Node (live reload):
```powershell
cd "C:\Users\pothu\OneDrive\Desktop\frontend-projects\Calc-App"
npx live-server
```

- VS Code: install the Live Server extension and click **Go Live** on `index.html`.

## Push to GitHub (quick)

1. Create a repo on GitHub (or use `gh`):

```powershell
git remote add origin https://github.com/USERNAME/Calc-App.git
git push -u origin main
```

Or with the GitHub CLI:

```powershell
gh repo create USERNAME/Calc-App --public --source=. --remote=origin --push
```

Replace `USERNAME` with your GitHub username.

## Notes

- `.gitignore` is included for common files.
- If you want, I can create the remote and push for you (I can run `gh repo create` if `gh` is installed and authenticated).
