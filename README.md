# Workboat World tests

Live at https://tartanski-cpu.github.io/WBWtests/ (GitHub Pages, from `main`).

Small test pages for Workboat World, published here on their own so they go live a minute
after a change, apart from the game's site and its publishing queue (the game's code is at
tartanski-cpu/SWVR).

- **Index** (`index.html`): links to the pages below.
- **Tool bench** (`toolbench.html`): the hand tools on their own (torch, binoculars, camera,
  fire extinguisher, paint roller, welding torch, scraper, fishing rod, line-throwing gun):
  the toolbar on desktop (keys 1-9, mouse wheel, controller) and the backpack in VR.
- **Hand fit** (`handlab.html`): fitting the VR hands to the controllers.
  Open https://tartanski-cpu.github.io/WBWtests/handlab.html in the Quest browser, press Enter
  passthrough, adjust the hands, and copy the numbers back.
  It starts from the game's current fit: the owner's own, pitch 40°, no move (4 Nov 2026).

These files are built, not written by hand: from SWVR,
`npx vite build --config vite.handlab.config.ts`, then the contents of `dist-handfit/` copied
here (the index page is written by hand).
