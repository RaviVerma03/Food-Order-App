# Food-Order-App
It's a modern, single-page food ordering application built with React.

ReactFood is a modern, single-page food ordering application built with React. It allows users to browse meals, manage a shopping cart, and securely place orders. The app demonstrates advanced concepts like global state management, modals with portals, custom hooks, and HTTP requests.

✨ Features
✅ Responsive UI — Built with reusable components and clean styling.
✅ Cart Management — Add, increase, decrease, or remove items from your cart dynamically.
✅ Checkout Process — Collect user data and submit orders via HTTP POST.
✅ Portals for Modals — Display modals using React’s createPortal for proper layering.
✅ Context API — Manage global state for cart and user interface progress.
✅ Custom Hooks — Abstract HTTP requests and loading states.
✅ Currency Formatting — Format prices dynamically (e.g. USD, INR).

🔧 Tech Stack
React (Functional Components + Hooks)
Context API + useReducer for state management
Express.js for backend API (local server)
JSON File as a lightweight database
CSS for styling and sticky header navigation
💻 How It Works
The header is sticky, remaining visible while scrolling.
Users browse available food items.
Cart context tracks selected items and quantities.
Clicking the cart opens a modal showing all items and totals.
Users proceed to Checkout, fill in personal info, and place the order.
The backend (Express) saves orders to a JSON file.


