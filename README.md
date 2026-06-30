# e-plantShopping

**Paradise Nursery Shopping Application**

A React + Redux Toolkit shopping cart application for an online plant shop offering a variety of house plants.

## Overview

Paradise Nursery lets users browse house plants grouped into categories, add them to a
shopping cart, and manage their cart before checkout. The application demonstrates:

- A **landing page** with a welcome message and a *Get Started* button.
- A **product listing page** with at least six unique plants across multiple categories
  (Air Purifying, Aromatic Fragrant, Insect Repellent, Medicinal, and Low Maintenance plants),
  each with a thumbnail, name, description, cost, and an *Add to Cart* button.
- A **navigation bar** with links to the landing page, the plants listing, and a cart icon
  that dynamically displays the total number of items in the cart.
- A **shopping cart page** that shows the total cart amount, the per-plant subtotal, controls
  to increase/decrease the quantity of each plant, a *Delete* button, a *Checkout* button, and
  a *Continue Shopping* button that returns to the product listing.

## Tech stack

- React (functional components + hooks: `useState`, `useEffect`)
- Redux Toolkit (`createSlice`, `configureStore`) with `react-redux` for global cart state
- Vite for development and production builds

## Getting started

```bash
npm install
npm run dev      # start the dev server
npm run build    # production build
npm run preview  # preview the production build (port 4173)
```
