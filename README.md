# Gujarat Sales Intelligence Dashboard

A static dashboard (GitHub Pages). It reads the Excel file at `data/Sales_Data.xlsx`. Visitors cannot upload anything. Only people who can commit to this repository can change the data.

## Folder layout

```
index.html
README.md
data/
  Sales_Data.xlsx     <- the only file you replace each month
```

## One-time setup

1. On github.com click **New repository**. Name it (for example `gujarat-sales-dashboard`) and click **Create repository**.
2. Click **uploading an existing file**. Drag in `index.html`, `README.md` and the whole `data` folder, then click **Commit changes**.
3. Go to **Settings > Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to `main` and folder to `/ (root)`, then click **Save**.
4. After about a minute the site is live at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Monthly data update

1. Open the repository, then the `data` folder.
2. Click **Add file > Upload files** and drop your new workbook.
3. **Name it exactly `Sales_Data.xlsx`.** Uploading the same name replaces the old file.
4. Click **Commit changes**. Wait about a minute and refresh the dashboard.

Keep the three sheet names and the column headings from the sample file (see its Read Me sheet).

## Who can upload

- Only you (the repository owner) and collaborators you add can commit files. Do not add collaborators you do not trust.
- Turn on two-factor authentication for your GitHub account (**Settings > Password and authentication**).
- The dashboard page has no upload control.

## Important: privacy

On a normal GitHub account the published site is public. Anyone with the link can open the dashboard, and anyone who knows the path can download `data/Sales_Data.xlsx`. A private repository does not change this on its own. Login-only Pages sites need GitHub Enterprise Cloud. If the real data is sensitive, either use anonymised data here or host the page behind a login (for example Cloudflare Access or Netlify password protection).
