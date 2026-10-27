# ផ្ទះតែ · Tea Shop Stock & Sales

A browser-based tea shop manager with products and photos, MSRP / retail and reseller prices, stock receiving and counting, sales and printable receipts, expenses, monthly reports, and backup / restore.

## Open the app

https://tarzankdd.github.io/tea-shop/

GitHub Pages serves the `docs` directory on the `main` branch. No build step is required.

## Data and backups

All shop records and product photos are saved in the browser's local storage. They are not stored in this repository or synchronized between devices. Download backups regularly from Settings.

To move from another hosting address: download a backup on the old site, then restore that backup from Settings on this site. Keep the old backup until the restored records have been checked.

MSRP / retail and reseller prices are selling prices. New products do not collect buy-in costs; reports therefore show sales less expenses rather than claiming net profit when costs are unknown. Historical sales with recorded costs retain them.

The delete-all password is a browser-only accidental-deletion safeguard, not secure authentication. It is visible in the JavaScript source. The website itself is public.

## Development

Edit `docs/index.html`, `docs/style.css`, and `docs/app.js`. Validate JavaScript with `node --check docs/app.js`. A local static web server can preview the directory.
