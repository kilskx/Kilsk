# Kilsk

## Rooted — City Pride Tees

`index.html` is a single-file storefront for Rooted: the collection, product
pages with sizes, a bag, checkout with delivery options per country, and an FAQ.
Open it directly in a browser; no build step needed.

The palette is a cozy, ambient night theme: deep navy backgrounds with a soft
blue glow, gentle white text, and light sky-blue for buttons and highlights.
A sun/moon button in the header switches to a light mode (crisp white and
sky-blue with vivid cobalt accents); the choice is remembered per visitor.
All colours are CSS variables at the top of the `<style>` block.

Shop settings live near the top of the main `<script>`:
- `SHIPPING`: delivery methods and customer prices per zone. Replace them
  with confirmed courier quotes before opening orders.
- `CHECKOUT_URL`: once a payment provider is connected, set this to open
  orders. Until then checkout shows "Orders open soon".
