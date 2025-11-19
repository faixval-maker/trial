# My GitHub Pages Website

This is a 100% free static website hosted on **GitHub Pages**, with a custom HTML/CSS/JS form that sends data to a **Google Sheets backend** using Google Apps Script.

## How it works

1. The form in `index.html` sends data using `fetch()` from `script.js`.
2. Google Apps Script receives the data through a Web App endpoint.
3. The script appends the values into Google Sheets automatically.

## Files

- `index.html` — main webpage  
- `style.css` — styling  
- `script.js` — form submission logic  
- `README.md` — project info  

## Deployment

Go to:  
**Repo Settings → Pages → Branch: `main` → Folder: `root` → Save**

Your site becomes available under:

