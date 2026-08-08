# Forever

Forever is a React-based e-commerce storefront UI, built to practice real-world frontend patterns — product browsing, cart state management, and multi-page navigation — using static product data instead of a live backend, with the focus kept on component architecture and UI polish.

## Live Demo

**Forever:** https://ecommerce-website-main-kappa.vercel.app

## Features

- **Home Page** — Hero banner, latest collection, and best-seller sections
- **Product Listings** — Browse all products in a responsive grid
- **Category & Subcategory Filtering** — Narrow products by type
- **Product Search** — Find products by name
- **Product Details** — Individual product page with images, price, and size selection
- **Cart Management** — Add, update quantity, and remove items from the cart
- **Order Placement** — Delivery information form and cart total summary
- **Responsive UI** — Optimized layout across mobile, tablet, and desktop

## Tech Stack

**Frontend**
- React.js
- React Router
- Context API (cart and global state)
- Tailwind CSS

**Deployment**
- Vercel

## Project Structure

```text
src/
├── assets/
├── components/
├── context/
├── pages/
├── App.jsx
└── main.jsx
```

> The exact structure may vary depending on the current version of the project.

## Getting Started

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
cd forever
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm run dev
```

The application will be available at the local development URL provided by Vite.

## Purpose of the Project

Forever was built to strengthen core frontend skills — component-driven architecture, cart state management with Context API, dynamic routing between product, category, and cart pages, and building a UI that feels like a real production storefront rather than a demo.

## Future Improvements

- User authentication and order history
- Wishlist functionality
- Backend integration with a real database and product API
- Payment gateway integration
- Admin panel for product and order management
- Improved loading states and error handling

## Author

**Ananya Thapa**
[GitHub](https://github.com/ananyathapaa) · [LinkedIn](https://linkedin.com/in/ananyaa-thapaaa)
