# Jalo Concrete Pumping: landing page

Landing page for the Google and Meta ads (Miami-Dade and Broward).
It's a single static file, `index.html`, with its photos in `img/`. There's no build step and no server.

## Where it goes

Every ad points to **https://jaloconcrete.com/concrete-pumping**, so it has to be published at that exact address.

- **Inside jaloconcrete.com:** upload `index.html` and the `img/` folder to `/concrete-pumping/`.
- **Netlify, Vercel or GitHub Pages:** connect this repo and point `jaloconcrete.com/concrete-pumping` at it, or set up a redirect from that path.

## Before running ads

- Track phone clicks (`tel:`) and the "Text it to dispatch" button as conversions in Google Ads and Meta.
- The form opens a text message to (786) 560-7354, so it doesn't need a backend.
- Every claim on the page comes from `context/proof.md`. Don't add "licensed", "bonded", "since 2008", "#1", "free quote" or prices.
