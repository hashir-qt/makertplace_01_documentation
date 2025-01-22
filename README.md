# Avion - E-Commerce Web Application

Welcome to **Avion**, an e-commerce web application that allows users to browse, add items to the cart, and complete the checkout process seamlessly. This application features a modern UI, a shopping cart, and integration with Sanity for content management.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Product Catalog**: Browse a wide range of products, including detailed information, prices, and images.
- **Shopping Cart**: Add products to the cart, update quantities, and remove items.
- **Checkout Process**: Proceed to checkout and review order details.
- **Responsive Design**: Optimized for mobile, tablet, and desktop devices.
- **Admin Panel**: Manage product listings and content with Sanity Studio.
- **Search Functionality**: Search for products by name or category.
- **Error Handling**: Clear error messages and handling for missing or incorrect data.

## Technologies Used

- **Frontend**:
  - Next.js (React Framework)
  - TypeScript
  - Tailwind CSS (for styling)
  - Sanity (Content Management System)
  - ShadCN UI (for UI components)
  - Lucide Icons (for icons)

- **Backend**:
  - Sanity (Headless CMS for product management)
  - Vercel (for deployment)

## Folder structure

/avion-ecommerce
├── /components                  
│   ├── CartContext.tsx          # Used in the entire application for cart state management
│   ├── CartPage.tsx             # /cart – Displays the shopping cart
│   ├── Navbar.tsx               # Navbar component, used in multiple pages
│   └── /ui                      
│       └── Button.tsx           # Reusable Button component
├── /lib                         
│   └── client.ts                # Sanity client setup, used for fetching data
├── /pages                       
│   ├── _app.tsx                 # Global configuration, wraps the entire app (used in all pages)
│   ├── index.tsx                # / – Home page showing the product list
│   ├── product/[slug].tsx       # /product/[slug] – Dynamic page for individual product details
│   └── checkout.tsx             # /checkout – Checkout page to review and complete orders
├── /public                      
│   └── placeholder.svg          # Image for missing product images, stored in public
├── /sanity                       
│   ├── sanity.config.ts         # Sanity configuration file
│   └── /studio                  # /studio – Sanity Studio content management UI
├── /styles                       
│   ├── globals.css              # Global styles (base styles, custom styles)
└── .env.local                   # Stores local environment variables (e.g., API keys, Sanity project ID)

