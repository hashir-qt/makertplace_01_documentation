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

/avion-ecommerce ├── /components # Reusable UI components │ ├── CartContext.tsx # Cart context for global state management │ ├── CartPage.tsx # Displays the shopping cart page │ ├── Navbar.tsx # Navigation bar component │ ├── /ui # Custom UI components (buttons, forms, etc.) │ │ └── Button.tsx # Button component ├── /lib # Utility functions and integrations │ └── client.ts # Sanity client setup for data fetching ├── /pages # Next.js pages and routes │ ├── _app.tsx # Global configuration for the Next.js app │ ├── index.tsx # Home page showing the product list │ ├── product/[slug].tsx # Dynamic page for individual product details │ └── checkout.tsx # Checkout page for reviewing and completing the order ├── /public # Public assets (images, icons, etc.) │ └── placeholder.svg # Placeholder image for missing product images ├── /sanity # Sanity Studio and content management │ ├── sanity.config.ts # Sanity configuration file │ └── /studio # Sanity Studio content management UI ├── /styles # Global styles (Tailwind & custom styles) │ ├── globals.css # Global styles (base styles, custom styles) ├── .env.local # Environment variables for local development └── README.md # Project documentation


