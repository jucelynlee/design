# Putting your site online (the easy way)

"Deploy" just means: copy your website folder onto the internet so it gets
a real link (URL) you can share on a résumé or Upwork profile.

## Step 0 — Your folder should look like this
Keep these together in ONE folder (order doesn't matter, names do):

    my-portfolio/
    ├─ index.html            ← the one-page site
    ├─ images/               ← your photos go here
    │   ├─ cricut-1.jpg, cricut-2.jpg, vephos-1.jpg … hongyu-2.jpg
    │   └─ jucelyn.jpg       ← your portrait
    └─ projects/             ← the 5 detail pages (already made)
        ├─ cricut.html
        ├─ vephos.html
        ├─ usexpo.html
        ├─ decoded.html
        └─ hongyu.html

Think of it like a lunchbox: index.html is the main dish, images/ and
projects/ are the side compartments. As long as they travel together in the
same box, everything works.

## Step 1 — Go to Netlify Drop
Open this page in your browser:  https://app.netlify.com/drop

(You can make a free account with your Google email — it keeps your site
saved so you can update it later.)

## Step 2 — Drag the whole folder in
Drag your ENTIRE `my-portfolio` folder onto the big drop area.
Wait a few seconds. Netlify gives you a live link like:
    https://your-name-1234.netlify.app

That link is your live portfolio. Share it anywhere.

## Step 3 — Rename it (optional, nicer link)
In Netlify: Site settings → Change site name → type something like
`jucelyn-design`. Your link becomes  https://jucelyn-design.netlify.app

## Updating later
Changed a file or added images? Just drag the folder onto Netlify Drop
again (or, if you made an account, into your site's "Deploys" tab).
It overwrites the old version. No coding needed.

## Common gotchas
- Images not showing? The file name must match EXACTLY (lowercase, .jpg),
  and the image must be inside the `images/` folder.
- "View Project" goes nowhere? Make sure the `projects/` folder came along.
- Chinese looks wrong on someone else's computer? It won't — the fonts load
  from Google, so it looks the same everywhere.
