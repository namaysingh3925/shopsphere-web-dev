# ShopSphere

A responsive e-commerce storefront built with plain HTML, CSS and JavaScript. It has no frameworks and no build step.

## Features

- **Product catalogue** rendered from JavaScript data, with category filter buttons
- **Shopping cart drawer** to add items, remove items, clear the cart and see the running total
- **Cart that survives a refresh**, saved in the browser with `localStorage`
- **Responsive layout** with a hero banner, product grid and slide-in cart

## Project structure

```
e-commerce/
├── index.html   page layout: header, hero, filters, product grid, cart
├── style.css    styling and responsive layout
└── script.js    products, filtering and cart logic
```

## Run it

No install is needed. Open `e-commerce/index.html` in a browser, or serve the folder:

```bash
npx serve e-commerce
```

## What I practised

- Changing the page with JavaScript (`renderProducts`, `renderCart`)
- Event handling for filters and cart buttons
- Keeping the cart in sync with `localStorage`
- Responsive CSS layouts
