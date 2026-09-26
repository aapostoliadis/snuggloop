# Snuggloop

Single-page marketing site for Snuggloop, snuggly knitted dolls that start from one coral thread.

## What is in here

- `index.html`: the whole site (HTML, CSS and JavaScript in one file, no build step)

## Run it locally

Open `index.html` in a browser, or serve the folder:

    npx serve .

## Deploy on Vercel

1. Push this repo to GitHub.
2. In Vercel, choose Add New, Project, and import the repo.
3. Framework preset: Other. Leave build command and output directory empty.
4. Deploy. To make the link public, turn off Vercel Authentication under Settings, Deployment Protection.

## Things to set before launch

- `ORDER_ENDPOINT` in `index.html`: URL that receives order requests as JSON. Empty means orders are not sent anywhere.
- Prices, lead time (4 to 6 weeks) and payment terms are placeholders.
- Images and the hero video are hosted on Higgsfield's CDN. Copy them into the repo if you want the site to stay up long term.
- Fonts: Cabinet Grotesk (Fontshare) and Inter Tight (Google Fonts).
