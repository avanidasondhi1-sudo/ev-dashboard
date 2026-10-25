# EV Market Intelligence Dashboard

Plain HTML, CSS and JavaScript. No build step or install needed.

## Run in VS Code
1. Open this folder in VS Code (File > Open Folder).
2. Install the "Live Server" extension (VS Code will suggest it).
3. Right-click `index.html` and choose "Open with Live Server".

You can also double-click `index.html` to open it in a browser.

## Structure
- `index.html`: page layout
- `css/style.css`: styling, light and dark themes
- `js/data.js`: sample dataset (edit or replace with your own)
- `js/app.js`: filters, charts, views and table

## Using your own data
Edit the rows in `js/data.js`. Each row is
`[manufacturer, country, category, battery, annual sales (k), range km, rating /5, YoY growth %]`.
The sample figures are illustrative only.
