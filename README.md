@@ -1,1 +1,81 @@
-[EMPTY_FILE]
\ No newline at end of file
+# Top Home Design - Full-Stack E-commerce (Mercado Livre Style)
+
+## 🎨 **Overview**
+Full-stack e-commerce platform for **Top Home Design**, an interior design company. Built with **HTML/CSS/JS frontend** + **Node.js/Express backend** for product management, photo uploads, and dynamic catalog. Inspired by **Mercado Livre** with search, filters, cart, checkout.
+
+**Live Demo:** Open `index.html` or run `npm start` for backend.
+
+## 🚀 **Quick Start**
+
+### Frontend Only (Static)
+```
+start index.html
+```
+- Product catalog, search, filters, cart (localStorage), checkout simulation.
+
+### Full Backend (Recommended)
+1. **Install dependencies:**
+   ```
+   cd top-home-design-ecommerce
+   npm install
+   ```
+
+2. **Start server:**
+   ```
+   npm start
+   ```
+   - Opens `http://localhost:3000`
+   - Backend APIs: `/api/products`, uploads to `/uploads/`
+
+3. **Admin Panel (Owner Adds Products):**
+   - Go to `http://localhost:3000/admin.html`
+   - Password: `admin123`
+   - Form: name, price, category, description, **photo upload**
+   - **Auto-saves** to `data/products.json` + `/uploads/[timestamp].jpg`
+   - New products appear instantly on frontend!
+
+## ✨ **Features**
+
+| Frontend | Backend |
+|----------|---------|
+| Responsive design (mobile-first) | Express.js server |
+| Search + category/price filters | Multer photo uploads |
+| Product details page | Dynamic product API |
+| Shopping cart (localStorage) | Orders JSON storage |
+| Checkout form (simulated) | Admin dashboard |
+| 20+ interior design products | Auto file naming |
+
+**Products:** Sofas, tables, lamps, rugs – interior design focused.
+
+## 📁 **Structure**
+```
+.
+├── server.js (Express + Multer)
+├── admin.html (admin panel)
+├── data/ (products.json, orders.json)
+├── uploads/ (product photos)
+├── index.html (home)
+├── cart.html, checkout.html
+├── css/style.css, js/script.js
+├── package.json
+└── README.md
+```
+
+## 🛠 **Tech Stack**
+- **Frontend:** HTML5, CSS3 (Grid/Flexbox), Vanilla JS
+- **Backend:** Node.js, Express, Multer, JSON files
+- **No database** – JSON + file system (easy deploy)
+
+## 📱 **Test Flow**
+1. `npm start`
+2. Browse products, add to cart → checkout
+3. Admin: upload new sofa photo → refresh home → new product live!
+
+## 🚀 **Deploy**
+- **Frontend:** GitHub Pages/Netlify (static files)
+- **Full-stack:** Railway/Vercel/Heroku (Node.js)
+
+**Perfect for portfolios/production start!**
+
+⭐ Star if useful!
+
