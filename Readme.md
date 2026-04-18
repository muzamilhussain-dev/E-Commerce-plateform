# Shinvo — Premium E-Commerce Platform

![Final Home View](./Frontend/public/screenshots/hero.png)

## Why Shinvo? (The Motivation)

This project was developed to push the boundaries of modern Full-Stack development. The core motivation was to create a high-performance, visually immersive e-commerce experience that bridges the gap between aesthetic design and robust backend logic.

Building **Shinvo** helped me master:
- **Advanced React Patterns**: Utilizing React 19 features, custom hooks, and the Context API for seamless global state (Cart & Auth).
- **Full-Stack Architecture**: Connecting a Vite-powered frontend with a scalable Node/Express 5 backend.
- **Modern Styling (Tailwind 4)**: Implementing a sophisticated "Glassmorphic" UI design system.
- **Cloud Integration**: Managing media uploads and storage using Multer and Cloudinary.

---

## What is Shinvo?

**Shinvo** is a high-fidelity, responsive e-commerce platform for tech and life accessories. It features a complete shopping lifecycle, from product discovery to secure checkout and administrative management.

### Key Features
- **Immersive UX**: Smooth "Bestsellers" carousel and responsive category-based browsing.
- **Dynamic Shopping Cart**: A functional real-time shopping drawer with automatic subtotal calculations.
- **Secure Authentication**: JWT-based user login and registration flows.
- **Admin Powerhouse**: A dedicated management suite for sales analytics, product CRUD, and inventory tracking.
- **Cloud-Ready**: High-resolution image management integrated with Cloudinary.

### Tech Stack
- **Frontend**: React 19, Vite, Tailwind CSS v4, React Icons, Axios.
- **Backend**: Node.js, Express 5, MongoDB, Mongoose, JWT, Cloudinary.
- **State Management**: React Context API (Auth & Cart).

---

## Project Structure

```text
Shinvo-Project/
├── Backend/                    (Express API)
│   ├── controllers/            (Business logic)
│   ├── models/                 (Mongoose schemas)
│   ├── routes/                 (API endpoints)
│   ├── middleware/             (Auth & Error handling)
│   └── server.js               (Entry point)
└── Frontend/                   (React Application)
    ├── src/
    │   ├── api/                (Axios configurations)
    │   ├── components//        (Reusable UI blocks)
    │   ├── context/            (Global state: Auth/Cart)
    │   ├── pages/              (User & Admin views)
    │   └── App.jsx             (Routes & Layout)
    └── public/
        └── screenshots/        (Visual assets)
```

---

## Project Showcase

### User Experience
| Premium Categories | Product Details | Smart Bestsellers |
| :---: | :---: | :---: |
| ![Categories](./Frontend/public/screenshots/categories.png) | ![Details](./Frontend/public/screenshots/product_details.png) | ![Bestsellers](./Frontend/public/screenshots/bestsellers.png) |

---

### Checkout & Payment
| Seamless Checkout | Secure Payment |
| :---: | :---: |
| ![Checkout](./Frontend/public/screenshots/checkout.png) | ![Payment](./Frontend/public/screenshots/payment.png) |

---

### Admin Management Suite
| Sales Analytics | Inventory Control | Product CMS |
| :---: | :---: | :---: |
| ![Dashboard](./Frontend/public/screenshots/admin_dashboard.png) | ![Product List](./Frontend/public/screenshots/admin_product_list.png) | ![Add Product](./Frontend/public/screenshots/admin_add_product.png) |

---

## How to Run

Follow these steps to set up the project locally:

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/shinvo-ecommerce.git
cd "E-Commercce Project"
```

### 2. Backend Setup
```bash
cd Backend
npm install
# Create .env with MONGO_URI, JWT_SECRET, and CLOUDINARY credentials
npm run dev
```

### 3. Frontend Setup
```bash
cd ../Frontend
npm install
npm run dev
```
The application will be live at `http://localhost:5173`.

---

Designed and Developed with a focus on UI Excellence & Full-Stack Mastery.
# E-Commerce-plateform
