# Orebi Ecommerce Store

![Orebi Logo](./public/smallLogo.ico)

## Overview

Orebi is a modern, responsive ecommerce platform built with React. The application provides a seamless shopping experience with features like product browsing, cart management, user authentication, and a streamlined checkout process. The store appears to specialize in electronic products, particularly printers, ink cartridges, and related accessories.

## Tech Stack

- **Frontend Framework**: React.js (Create React App)
- **Styling**: Tailwind CSS with custom configuration
- **State Management**: Redux Toolkit with Redux Persist
- **Routing**: React Router v6
- **UI Components**:
  - React Icons for iconography
  - React Slick for carousels
  - Framer Motion for animations
  - React Paginate for pagination
- **Build Tools**: Webpack (via Create React App)

## Key Features

- **Responsive Design**: Fully responsive layout that works across devices (mobile, tablet, desktop)
- **Product Management**:
  - Product listings with filtering options
  - Detailed product views
  - New arrivals and best sellers sections
- **Shopping Cart**:
  - Add/remove products
  - Adjust quantities
  - Persistent cart (using Redux Persist)
- **User Authentication**:
  - Sign up and sign in functionality
  - User account management
- **Navigation**:
  - Intuitive category-based navigation
  - Breadcrumb navigation for improved UX
- **Special Sections**:
  - Featured products
  - Special offers
  - Product of the year showcase
- **Checkout Process**:
  - Cart review
  - Payment gateway integration

## Project Structure

The project follows a modular architecture:

- `components/`: Reusable UI components
- `pages/`: Main application pages
- `redux/`: State management with Redux
- `assets/`: Images and static resources
- `constants/`: Application constants and configuration

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm or yarn

### Installation

1. Clone the repository
   ```
   git clone https://github.com/yourusername/OrebiEcommerceStore.git
   cd OrebiEcommerceStore
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Start the development server
   ```
   npm start
   ```
   The application will be available at [http://localhost:3000](http://localhost:3000)

### Build for Production

```
npm run build
```

This creates an optimized production build in the `build` folder.

## Customization

The project uses Tailwind CSS for styling with custom configuration:

- Custom breakpoints for responsive design
- Custom font families: DM Sans for body text and Poppins for titles
- Custom color palette with primary colors and text variations
- Custom container widths and shadows

## License

This project is open source and available under the [MIT License](LICENSE).
