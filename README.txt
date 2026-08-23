The Second Fracture — Rainbow Rot
=================================

A static deluxe-edition site. No build step. No server language.

How to open locally
-------------------
Open index.html in a browser, or from this folder:

  python3 -m http.server 4173

Then visit http://127.0.0.1:4173/

How to put it on the web
------------------------
This folder is the whole site. Host it as static files.

Netlify (easiest)
  1. Go to https://app.netlify.com/drop
  2. Drag this entire folder onto the page.
  3. You get a live URL. Attach a custom domain later in Site settings.

GitHub Pages
  1. Create a repo, upload this folder as the root (index.html must be at the root).
  2. Settings → Pages → Deploy from branch `main` / root.

After you have a real domain, edit every page's og:url
(currently a relative cover image) if you want Discord/iMessage previews
to show the cover. Search for og:image and prefix with https://YOURDOMAIN/

Keyboard
--------
Left / right arrows turn the chapter pages.

Pages
-----
  index.html              Book One cover
  jacket.html             jacket copy
  contents.html           table of contents
  chapter-01…11.html      Book One
  part2.html              Book Two cover
  part2-redplace.html     the Red Places
  part2-ch01…14.html      Book Two
  part2-final.html        last page
  characters.html         Vespera, Seraphine, Asmodeus
  history.html            History of the Garden
  about.html              Rainbow Rot
  credits.html            dedication
