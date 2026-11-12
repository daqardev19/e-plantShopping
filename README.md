# Paradise Nursery Shopping Application

**Paradise Nursery** is an online plant shop built with React and Redux Toolkit. It lets users browse houseplants, add them to a shopping cart, and manage their cart before checkout.

## Features

- **Landing page** with a background image, the company name, an About Us section, and a "Get Started" button.
- **Product listing page** with houseplants grouped into categories (Air Purifying, Aromatic, Medicinal, Low Maintenance). Each plant shows a thumbnail, name, description, and price.
- **Add to Cart** buttons that add the plant to the cart, disable once it is added, and update the cart icon count.
- **Navigation bar** with links to Home, Plants, and Cart, plus a cart icon that shows the total number of items.
- **Shopping cart page** that shows each plant's thumbnail, name, unit price, and subtotal, with buttons to increase or decrease quantity and delete items. It also shows the total cart amount, a Checkout button ("Coming Soon"), and a Continue Shopping button.

## Tech stack

- React 18 + Vite
- Redux Toolkit and React Redux for cart state

## Project structure

```
src/
├── App.jsx          # Landing page + routing between landing and product list
├── App.css          # Landing page styles (background image)
├── AboutUs.jsx      # Company details
├── ProductList.jsx  # Navbar, plant categories, Add to Cart
├── CartItem.jsx     # Shopping cart page
├── CartSlice.jsx    # Redux slice: addItem, removeItem, updateQuantity
└── store.js         # Redux store
```

## Getting started

```bash
npm install
npm run dev
```

## Deploy to GitHub Pages

```bash
npm run deploy
```
