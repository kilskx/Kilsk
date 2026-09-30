# Kilsk

## Rooted — City Pride Tees

`index.html` is a single-file storefront for Rooted: the collection, product
details with a size guide, shipping info and an FAQ.
Open it directly in a browser; no build step needed.

The palette is a cozy, ambient night theme: deep navy backgrounds with a soft
blue glow, gentle white text, and light sky-blue for buttons and highlights.
A sun/moon button in the header switches to a light mode (crisp white and
sky-blue with vivid cobalt accents); the choice is remembered per visitor.
All colours are CSS variables at the top of the `<style>` block.

To connect the buy buttons, set `SHOP_URL` (and optionally each product's `buy`
link) near the top of the main `<script>`. Until then the button reads
"Coming soon".
