# Giverny Kate Photography

Prototype website: nature and wildlife photography from Ōtepoti Dunedin, with prints and gifts ordered through Redbubble.

Folders:
- `index.html` - the whole site (text, layout and the list of photos)
- `photos/` - full-size web images
- `thumbs/` - small gallery images
- `products-1/` - canvas print, framed print and mug mock-ups
- `products-2/` - tote bag, cushion and greeting card mock-ups

- `products-3/` - mounted print and postcard mock-ups (the "Take home today" range)
- `qrcode.js` - QR code generator (qrcode-generator 1.4.4, MIT licence), used by the printable QR cards
- `PROVENANCE-CHECKLIST.md` - species, place and year still to be confirmed for each photo

To change a photo's title, collection or provenance caption, or point its Order button at a specific product, edit the `PHOTOS` list near the bottom of `index.html`.
To change what is sold at the stall, edit `STALL_ITEMS`.

Pages:
- `#today` - Take home today: items in stock at the stall
- `#qr` - printable QR cards (linked from At the market; not in the main menu). Print to A4, 8 cards per sheet.
- `#p/<photo>` or `#p/<photo>/<product>` - opens a photo's order page directly (what the QR codes point to)
