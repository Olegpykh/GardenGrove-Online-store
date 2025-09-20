ProductsGarden 🌱

ProductsGarden is an online store for garden products, offering a seamless user experience to browse, filter, and sort products, add them to favorites or cart, apply discounts, and place orders. The application supports light and dark themes and is fully responsive for all devices.



🔗 Links





Demo: code-masters.onrender.com



Figma Design: Figma Link



✨ Features





Browse all products with detailed information



Filter products by categories and price



Sort products by price, name, or other criteria



Add products to favorites



Manage cart and place orders



Apply a 5% discount coupon for first orders



Enjoy a random daily 50% discount on one product



Toggle between light and dark themes



Fully responsive design for all screen sizes



🛠 Technology Stack

React





Core framework for building the user interface



Hooks:





useState — Manages local state (filters, modals, cart)



useEffect — Handles data fetching and synchronization



useContext — Enables theme switching (light/dark)



StrictMode — Detects potential issues during development

React Router DOM





Powers navigation across pages



Hooks:





useLoaderData — Loads data for routes



useParams, useLocation, useNavigation — Manages URL and navigation



useRouteError, useMatches — Handles errors and breadcrumbs



Components: RouterProvider, Link, Outlet, and more

Redux Toolkit





Manages global state for cart, favorites, and filters



Tools:





createSlice — Defines reducers and actions



useDispatch, useSelector — Integrates state with components



createSelector — Optimizes data selection

React Hook Form





Simplifies form handling



useForm hook: Supports field registration, validation, submission, and reset

Additional Libraries





react-icons — Displays icons (e.g., heart, cart)



react-loading-skeleton — Shows loading skeletons for products and pages



vite — Enables fast project build and development



sass — Styles components using .scss files



👥 Project Team

Oleg Pykhonin





Routing: Implemented React Router v6.4+ with loaders and error handling



Main Page: Built category block and discounted products section



All Products: Created full product showcase with filtering and sorting



Discounted Products: Developed a dedicated page for promotional items



Favorites: Built favorites page with filtering and navigation



Breadcrumbs: Implemented using useMatches



Dark Theme: Enabled theme switching with Local Storage persistence



Styling & Adaptivity: Ensured design fidelity and UX consistency



Deployment: Configured and published project on Render



Documentation: Co-authored README.md

Nikita Shcherbakov — Team Lead





Managed team tasks, deadlines, and quality control



Conducted meetings, code reviews, and technical consulting



Made architectural decisions to ensure project quality



Footer: Built responsive footer with links and contacts



Product Page: Created detailed product cards with cart and favorites functionality



Cart: Implemented adding/removing products, cost calculation, and Local Storage persistence

Andrii Boiko





Categories: Developed category display on the main page and a dedicated categories page



Products by Category: Enabled filtering and navigation to product details



5% Discount Form: Built form with validation and submission confirmation



Product of the Day: Created modal for daily promotions with cart integration



Skeletons: Added loading skeletons for products and pages



Adaptivity: Ensured responsive design across all devices



Refactoring: Improved code quality and adherence to style guides



Documentation: Contributed to README.md preparation



Alina Miroshkina





Header: Designed header with logo, theme switcher, and cart/favorites icons



Navigation: Built desktop (NavMenu) and mobile (ModalNavMenu) menus



Banner: Created section with image, text, and navigation button



404 Page: Designed and implemented responsive error page



Themes: Supported light/dark theme switching with Local Storage



Styling: Used CSS Modules and global styles



State Management: Leveraged Redux Toolkit for header icons and React Context for themes



Design Integration: Adapted components to match Figma design



📬 Contact

This project is documented in English for global accessibility. I am fluent in German and happy to provide additional documentation or communication in German as needed.
