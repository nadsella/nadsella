# Name Plate Finder

A single-page site that suggests UK private number plates for a name.

Type a name and it fits it into every DVLA format (dateless, current, prefix and suffix), swapping in look-alike digits (A→4, S→5, O→0…) where needed. Each suggestion shows how close a match it is, the earliest vehicle registration date it can go on, and a link to check availability on the DVLA site.

Everything runs in the browser from `index.html`, with no build step. Open the file directly, or serve it with GitHub Pages (Settings → Pages → deploy from the `main` branch), where it appears at `/plate-suggester/`.

Suggestions follow the published format rules but don't guarantee a number exists or is for sale.
