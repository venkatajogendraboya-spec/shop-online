SHOPNEX — Front-end starter

HOW TO RUN
1. Extract shopnex-html-css-js.zip.
2. Open the shopnex folder.
3. Double-click index.html, or use VS Code + Live Server.
4. Internet is required for Google Fonts and the remote Unsplash product photos.

FILES
- index.html: page structure
- style.css: responsive styling, light/dark themes
- script.js: sample product catalogue and front-end interactions

WORKING IN THIS DEMO
- Responsive homepage and category navigation
- Product cards, search, suggestions, category filters, price filter and sorting
- Product quick-view modal
- Add/remove products and change quantities in cart
- Coupon code NEX10 (demo 10% discount)
- Wishlist
- Cart and wishlist persistence using browser localStorage
- Demo sign-in and checkout forms
- Demo order confirmation
- Dark mode and newsletter interaction

IMPORTANT LIMITATIONS
This package is a front-end prototype built with plain HTML, CSS and JavaScript, as requested. It is NOT a production e-commerce backend.
Authentication is not secure or connected to a user database. Orders are stored only in the current page flow. Admin dashboard, real order tracking, inventory management, email verification, reviews, refunds and invoice generation require a backend and database.
No real payment is processed. Do not collect card details in this demo. For a real store, use a server-side integration with a payment provider such as Razorpay in test mode, verify payment signatures on the server, and never store raw card information.
Before production, add a backend API, database, server-side validation, authorization for admin routes, secure sessions, HTTPS, privacy/returns policies, and tested payment/order workflows.
