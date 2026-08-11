BACKDROP IMAGES
===============
These four files are wired up and working:

  AIG stock background.jpeg        stop 00 - Alliance Infrastructure Group
  Lynx stock background.jpeg       stop 01 - Lynx
  SFI stock background.jpeg        stop 02 - SFI
  Gridcore stock background.jpeg   stop 03 - Gridcore

The paths live in the four --shot-* tokens at the top of the <style>
block in index.html, and nowhere else. Spaces are encoded as %20 there.
If you rename a file, update its token to match.

PLEASE COMPRESS THESE
---------------------
Current total: about 15 MB.
  Gridcore  6.2 MB
  Lynx      6.0 MB
  AIG       1.9 MB
  SFI       1.1 MB

Gridcore and Lynx are roughly six times larger than they need to be.
Target about 300-500 KB each: resize to 1800px wide and save as WebP
(or JPEG at quality 75). Squoosh.app does this in a browser with no
install. Keep the same filenames and nothing else needs changing.

The page already loads each photograph only when its stop is reached,
so the first view pulls just the AIG image - but a visitor who scrolls
through all four still downloads the lot.
