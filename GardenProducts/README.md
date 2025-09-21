<img width="1434" height="722" alt="Bildschirmfoto 2025-09-20 um 19 58 09" src="https://github.com/user-attachments/assets/3ba09557-172e-4d72-b480-ba22ef735f3f" />



**This project is documented in English for global accessibility. I am fluent in German and happy to provide additional documentation or communication in German as needed.**

🌱 ProductsGarden

ProductsGarden is a responsive e-commerce web application designed for gardening enthusiasts. It offers a user-friendly interface to browse, filter, and purchase garden products, with support for themes, discounts, and smooth navigation.

👉  https://garden-grove-online-store-lsye.vercel.app/

🔗 Figma Design:https://www.figma.com/design/SDNWLzCWkh9ZXdCpWEaByv/project-frontend?node-id=5251-7386&p=f&t=BAqCx0v2PXL8MsTk-0

✨ Key Features

🛍️ Product Browsing with detailed views

🔎 Filtering & Sorting by categories, price, name, etc.

❤️ Favorites functionality with persistent storage

🛒 Shopping Cart with full order flow and local persistence

💸 5% Discount on first orders (via coupon)

🎁 50% Daily Random Discount on one product

🌙 Light/Dark Theme Toggle with Local Storage support

📱 Responsive Design for mobile, tablet, and desktop

🛠 Technology Stack
⚛️ React

Core UI Framework

Hooks Used:

useState, useEffect, useContext

StrictMode for dev validation

🔄 React Router DOM (v6.4+)

Navigation & routing

Hooks Used:

useLoaderData, useParams, useLocation, useNavigation, useRouteError, useMatches

Components: RouterProvider, Link, Outlet

📦 Redux Toolkit

Global state management (cart, favorites, filters)

Tools:

createSlice, useDispatch, useSelector, createSelector

🧾 React Hook Form

Form handling with validation and submission

useForm for field registration and state control

📚 Additional Libraries

react-icons — Icons (e.g. heart, cart)

react-loading-skeleton — Skeletons for loading states

vite — Lightning-fast bundler

sass — SCSS for styling components

👨‍💻 Project Team & Contributions

### 👨‍💻 Oleg Pykhonin

- **Routing**: Implemented React Router v6.4+ with loaders and error handling  
- **Home Page**: Built the category block and discounted products section  
- **Product Card**: Created a reusable component used across all sections  
- **All Products**: Developed the full product showcase with filtering and sorting  
- **Discounted Products**: Created a dedicated page for promotional items  
- **Favorites**: Built the favorites page with filtering and navigation  
- **Breadcrumbs**: Implemented using the `useMatches` hook  
- **Dark Theme**: Enabled theme switching with persistence in Local Storage  
- **Styling & Responsiveness**: Ensured design consistency and user experience across devices  
- **Optimization & Refactoring**: Improved component performance and maintainability  
- **Deployment**: Configured and deployed the project on Render  
- **Documentation**: Co-authored the `README.md`



### 👨‍💼 Nikita Shcherbakov — Team Lead

- **Architecture, Code Reviews, Task Management**: Oversaw development process, ensured code quality and timely delivery  
- **Product Page**: Built detailed product view with cart and favorites functionality  
- **Cart**: Implemented cart logic with cost calculation and local storage persistence  
- **Footer**: Created a fully responsive footer with links and contact info

---

### 👨‍💻 Andrii Boiko

- **Categories Page**: Developed category listing and filtering functionality  
- **5% Discount Form**: Built form with validation, confirmation, and user feedback  
- **Product of the Day**: Implemented 50% discount modal with cart integration  
- **Responsive Design**: Ensured mobile/tablet/desktop compatibility across pages  
- **Skeletons**: Added loading skeletons for better user experience  
- **Code Refactoring**: Improved code readability and consistency

---

### 👩‍💻 Alina Miroshkina

- **Header**: Designed and implemented header with logo, theme toggle, and cart/favorites icons  
- **Navigation**: Built responsive navigation for both desktop (`NavMenu`) and mobile (`ModalNavMenu`)  
- **Banner & 404 Page**: Created visually consistent banner section and custom 404 page  
- **Styling**: Used CSS Modules and global styles for theme consistency  
- **Design Integration**: Adapted all components to match the Figma designtext

📦 Project Highlights

⚙️ Fully functional e-commerce flow

🎨 Pixel-perfect design based on Figma

🌐 Deployed and accessible online

🧩 Modular, maintainable codebase with best practices

