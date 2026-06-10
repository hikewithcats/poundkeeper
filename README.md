# PoundKeeper.com

Personal brand site for Patrick Hourihan, "The Pound Keeper."

For the strays, the builders, and the ones finding their way home.

## Stack

Plain static HTML, CSS, and a little vanilla JS. No build step, no dependencies.

- `index.html` is the whole homepage
- `css/styles.css` carries the design system (colors, stamps, case-file cards)
- `js/main.js` handles the mobile menu and scroll reveals

## Run locally

```sh
python3 -m http.server 4173
```

Then open http://localhost:4173.

## Deploy

Upload the folder anywhere static files are served: Netlify, Vercel, Cloudflare Pages, GitHub Pages, or plain S3. Point the poundkeeper.com domain at it and you're done.

## Things to update over time

- Domains confirmed: hikewithcats.com, mycartoonpet.com, and keepingupwiththerobots.com. mycartoonpet.com is not live yet, so its project card and footer entry are unlinked. When it launches, restore the links at the two HTML comments in index.html that mention mycartoonpet.com.
- The Contact button uses hikewithcats@gmail.com. Swap in a dedicated address when one exists.
- The Writing section lists placeholder titles marked SOON. Replace them with real post links as they publish.
