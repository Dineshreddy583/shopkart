E-Commerce Platform with Admin Panel
A full-fledged, multi-user e-commerce application built with Angular, featuring:

✅ User-facing store (product listing, cart, checkout, payment)
✅ Admin panel (CRUD for products, view sales analytics)
✅ Indian rupee (₹) support
✅ SEO-friendly with Angular Universal
✅ State management with NgRx / Akita
✅ Modern Angular best practices

✨ Features
👤 User-side
Browse products with categories & filters.

Product details page with pricing in Indian Rupees (₹).

Add/remove products from cart.

Checkout flow with reactive form validation.

Mock payment integration.

🔐 Admin Panel
Secure admin login.

Manage products: Create, Read, Update, Delete (CRUD).

View sales and traffic analytics.

Lazy-loaded admin module.

📚 Tech Stack
Technology	Purpose
Angular	Front-end framework
Angular Routing	SPA navigation with lazy-loaded modules
Reactive Forms	Forms with validation (user & admin)
NgRx / Akita	State management
Angular Guards	Route protection for admin and users
Interceptors	HTTP auth tokens, error handling
Angular Universal	Server-Side Rendering (SSR) for SEO
Chart.js / ngx-charts	Admin analytics dashboard

🚀 Getting Started
Prerequisites
Node.js >= 18.x

Angular CLI >= 17.x

Installation
bash
Copy
Edit
git clone https://github.com/yourusername/ecommerce-platform.git
cd ecommerce-platform
npm install
Development Server
bash
Copy
Edit
ng serve
Visit http://localhost:4200/

Build
bash
Copy
Edit
ng build
SSR Build & Serve
bash
Copy
Edit
npm run build:ssr
npm run serve:ssr
🧪 Project Structure
perl
Copy
Edit
src/
├── app/
│   ├── core/                # services, interceptors, guards
│   ├── shared/              # shared modules, components
│   ├── features/
│   │   ├── store/           # user-side store
│   │   └── admin/           # admin panel
│   └── state/               # NgRx / Akita store
├── assets/                  # images, mock data
└── styles/                  # global styles
🔒 Security & UX
JWT-based auth with HTTP interceptors.

Angular guards for protecting routes.

Lazy loading for performance.

📈 Admin Analytics
View orders, revenue, top-selling products.

Graphs & charts (e.g., using ngx-charts or Chart.js).

🏷️ Pricing Example
Product prices are shown in Indian Rupees (₹).
Example:

makefile
Copy
Edit
Product: Cotton T-Shirt
Price: ₹499
👨‍💻 Contribution
Feel free to fork this repo, open issues, or send pull requests to improve the project.

📄 License
MIT License — LICENSE

📬 Contact
For any queries or feedback:
Your Name
