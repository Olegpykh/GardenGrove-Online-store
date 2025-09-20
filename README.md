This project is documented in English for global accessibility. I am also fluent in German and happy to provide additional documentation or communication in German as needed.

ProductsGarden
ProductsGarden is an online store for garden products. Users can search, filter, and sort products, add them to favorites or cart, receive discounts, and place orders. Additionally, theme switching is available.
Links

Demo: https://code-masters.onrender.com
Figma Design: https://www.figma.com/design/SDNWLzCWkh9ZXdCpWEaByv/project-frontend?node-id=5251-7386&p=f&t=BAqCx0v2PXL8MsTk-0

Main Functionality

View all products with detailed information
Filter by categories and price
Sort products (by price, alphabetically, etc.)
Add products to favorites
Add products to cart and place orders
5% discount coupon for first orders
Random daily 50% discount on one product
Switch between light and dark themes
Responsive design

Technology Stack
React

Main framework for building the interface
Hooks:

useState — Managing local state (filters, modals, cart)
useEffect — Data loading and synchronization
useContext — Theme switching (light/dark)
StrictMode — Identifying potential issues during development



React Router DOM

Navigation between pages
Hooks:

useLoaderData — Data loading in routes
useParams, useLocation, useNavigation — URL and navigation handling
useRouteError, useMatches — Error handling and breadcrumbs


Components: RouterProvider, Link, Outlet, etc.

Redux Toolkit

Global state management (cart, favorites, filters)
Tools used:

createSlice — Reducers and actions
useDispatch, useSelector — State management in components
createSelector — Optimized data selection



React Hook Form

Form handling
useForm hook: Field registration, validation, submission, and reset

Additional Libraries

react-icons — Displaying icons (heart, cart, etc.)
react-loading-skeleton — Skeletons for loading states
vite — Project build and fast development
sass — Component styling with .scss files

Project Team

Oleg Pykhonin

Routing: React Router v6.4+ with loaders and error handling
Main Page: Category block and discounted products
Product Card: Universal component for all sections
All Products: Full showcase with filtering and sorting
Discounted Products: Dedicated page for promotional products
Favorites: Page with filtering and navigation
Breadcrumbs: Implementation using useMatches
Dark Theme: Switching and saving to Local Storage
Styling and Adaptivity: Adherence to design and UX
Optimization and Refactoring: Component improvements
Deployment: Setup and publishing on Render
Documentation: Co-authored README.md

Nikita Shcherbakov (Shcherbakov Mykyta) — Project Team Lead

Team management: Task delegation, deadline and quality control
Conducting meetings, code reviews, and technical consulting
Architectural decisions and maintaining the project's technical quality
Footer: Development of a responsive footer with links and contacts
Product Page: Detailed product card with cart and favorites functionality
Cart: Adding/removing products, cost calculation, saving to Local Storage

Andrii Boiko

Categories: Display on the main page and a dedicated categories page
Products by Category: Filtering and navigation to details
5% Discount Form: Implementation, validation, and submission confirmation
Product of the Day: Modal with promotion and cart addition
Skeletons: For loading states of products and pages
Adaptivity: Ensuring proper display on all screen sizes
Refactoring: Code improvements and adherence to style guide
Documentation: Preparation and formatting of README.md

Alina Miroshkina

Header (Header.jsx): Logo, theme switcher, cart, and favorites icons
Navigation: Desktop menu (NavMenu) and mobile (ModalNavMenu)
Banner: Section with image, text, and navigation button
404 Page: Design and responsive layout
Themes: Support for light and dark themes, saving user choice
Styling: CSS Modules and global styles
State Management: Redux Toolkit (header icons), React Context (theme)
Design Integration: Adapting components to the Figma design
