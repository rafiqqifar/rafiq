# rafspace

A responsive personal portfolio for Rafiq, built with Vite and plain JavaScript.

## Development

Requires Node.js 22 or newer. Run `npm ci`, then `npm run dev`. Run `npm run build` to create the production site in `dist/`, and `npm run preview` to serve that build.

## Personalize

Edit the project collection and page copy in `src/main.js`, and the design in `src/style.css`. The case studies and career content are explicitly illustrative. Replace them with verified accomplishments before sharing professionally. Replace the contact dialog with your real email and LinkedIn links when available. No contact details or professional achievements have been invented.

## GitHub Pages

The `docs/` folder contains the production site built for `/rafiq/`. In repository Settings → Pages, choose **Deploy from a branch**, branch **main**, and folder **/docs**, then save. GitHub will publish the site at `https://rafiqqifar.github.io/rafiq/` after deployment succeeds.

After editing the site, run `npm run build -- --base=/rafiq/ --outDir docs`, ensure `docs/.nojekyll` exists, and commit and push the updated source and docs.
