# Workboat World tests

Live at https://tartanski-cpu.github.io/WBWtests/ (GitHub Pages, from `main`).

Small test pages for Workboat World, published here on their own so they go live a minute
after a change, apart from the game's site and its publishing queue (the game's code is at
tartanski-cpu/SWVR).

- **Hand fit** (`index.html`, also `handlab.html`): fitting the VR hands to the controllers.
  Open https://tartanski-cpu.github.io/WBWtests/ in the Quest browser, press Enter
  passthrough, adjust the hands, and copy the numbers back.

These files are built, not written by hand: from SWVR,
`npx vite build --config vite.handlab.config.ts`, then the contents of `dist-handfit/` copied
here (`handlab.html` also as `index.html`).
