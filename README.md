# KAJSYS

KAJSYS is a small static dashboard repository. The canonical local checkout is:

`C:\Projects\123W-cell\KAJSYS`

The canonical remote is:

`https://github.com/123W-cell/KAJSYS`

## Files

- `index.html` — static dashboard entry point.
- `dashboard_data.json` — dashboard data consumed by the page.
- `.nojekyll` — keeps the static output compatible with GitHub Pages if Pages is enabled.

## Local preview

From the canonical checkout:

Requires Node.js. Then run:

```powershell
npx --yes http-server . -p 8040 -c-1
```

Then open `http://127.0.0.1:8040/`. Stop the temporary server when verification is complete.

## Verification

Before changing the project, fetch `origin` and confirm the working tree is clean and the current branch is 0 ahead/0 behind. After changing `index.html` or `dashboard_data.json`, open the local preview and verify the browser console has no load or JSON errors.

## Deployment status

GitHub contains the canonical tracked source. A current public hosting target and automated deployment contract have not yet been independently verified. Do not claim that a push deploys the site, and do not enable or change GitHub Pages without an explicit release decision. Record the verified public URL and deployment procedure here when that decision is made.
