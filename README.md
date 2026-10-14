# SOLEX – Sneaker Store

A single-page sneaker storefront. Everything lives in one file, `index.html`, with all product photos embedded, so there is nothing to install or build.

## Run it

Double-click `index.html` to open it in any modern browser. An internet connection is only needed for the Archivo font from Google Fonts. Without it, the page falls back to the system font.

## Features

- **Hero:** animated headline, framed shoe photo with three switchable shoes, and a mouse-follow effect on desktop
- **Shop by category:** Running, Lifestyle, Basketball, Training and Premium
- **Collection:** category tabs, search, sort by price, wishlist hearts, and a sale filter
- **Quick view:** size picker (UK 6–11) with an error if no size is chosen
- **Cart:** slide-in drawer with quantity buttons, remove, subtotal and a free-shipping progress bar
- **Extras:** FAQ, mobile menu, newsletter box with email validation, and a closing call to action
- **Quality:** responsive layout, keyboard focus styles, and support for reduced-motion settings

## Edit the content

Open `index.html` in a text editor and search for these names near the bottom, inside the `<script>` tag.

| What to change | Where to look |
| --- | --- |
| Products, names, prices, categories | The `P` array |
| Sale items | Set `o:1` on a product (shows 40% off) |
| Hero headlines and text | The `H` array |
| Free-shipping amount | The `FREE` constant (default `2999`) |
| Colors | The `:root` block at the top of the `<style>` tag |
| FAQ and footer text | The HTML above the `<script>` tag |

Product photos are stored as base64 in the `IMG` object. To swap a photo, replace its value with a normal path, for example `lp:"images/maverick.jpg"`.

## Known limitations

- Checkout is not connected. The Checkout button only shows a message.
- The cart and wishlist reset when the page is refreshed.
- Prices, sizes, delivery times and FAQ answers are placeholders. Check them before going live.
- Product names are original names for the demo, not brand names.

## Credits

Designed by Jagdish · Built by Mahisagarsoft
