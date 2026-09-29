BACKDROP IMAGES
===============
The site loads the four compressed files:

  aig.jpg        stop 00 - Alliance Infrastructure Group
  lynx.jpg       stop 01 - Lynx
  sfi.jpg        stop 02 - SFI
  gridcore.jpg   stop 03 - Gridcore

These were generated from the originals, which are kept alongside them:

  AIG stock background.jpeg        4192x2325   1.94 MB
  Lynx stock background.jpeg       8897x4344   6.00 MB
  Gridcore stock background.jpeg   8897x4344   6.16 MB
  SFI stock background.jpeg        3645x1164   1.13 MB

  total 15.2 MB  ->  0.5 MB  (97 percent smaller)

The originals were the cause of the page feeling laggy. At 8897x4344 a
single image needs about 155 MB of memory once decoded, and the page had
two of them with CSS filters applied on top. Resized to 1800px wide at
JPEG quality 72 they are visually identical here, because the design
darkens them heavily anyway.

TO REPLACE AN IMAGE
-------------------
Save the new file over the matching .jpg above, at roughly 1800px wide.
Nothing in index.html needs changing. Do not point the site back at the
full size originals.

The paths live in the four --shot-* tokens at the top of the <style>
block in index.html, and nowhere else.
