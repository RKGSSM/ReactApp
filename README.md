# Swiggy Clone - Food & Grocery Delivery Application 🍔✨

A feature-rich, high-performance web application designed to replicate the seamless experience of Swiggy. This app enables users to explore top food delivery options, find pure vegetarian hotspots, check live restaurant delivery updates, filter based on cost or ratings, and discover premium dining experiences.

Built using the latest industry standards: **React 19**, **Redux Toolkit**, **React Router v7**, and styled elegantly with **Tailwind CSS v4**.

---

## 🚀 Key Features

- **Dynamic Location Search**: Interactive and modular delivery location tracking.
- **Advanced Query Filters & Facets**: Instant filtering for pure vegetarian options, ratings (4.0+, 4.5+), delivery schedules, and price levels (e.g., Less than ₹300, ₹300–₹600).
- **Advanced Layout Engine (Google Gandalf Widgets)**: Built with an advanced responsive layout mapped after live production APIs, integrating dynamic grid widgets, collection list widgets, and carousel views.
- **Global State Management**: Powered by React-Redux and Redux Toolkit for consistent data caching across restaurant list flows and global item cards.
- **Dineout Integration flow**: A complete subsystem highlighting premium restaurant details, distance estimation, walk-in discounts, and bank offer promotions.
- **Lightning Fast Build**: Packaged and layered using the **Parcel Bundler** for instant Hot Module Replacement (HMR).

---

## 🛠️ Technology Stack & Architecture

- **Frontend Core**: React 19 (Hooks, Context, Concurrent rendering optimization)
- **State Management**: Redux Toolkit & React Redux
- **Routing**: React Router v7 (Fluid client-side transitions and lazy loading architecture)
- **Styling**: Tailwind CSS v4 + PostCSS for highly optimal utility-first responsive viewports
- **Bundler & Build Tool**: Parcel
- **Iconography**: Lucide React & custom optimized SVGs

---

## 📁 File Structure Highlights


├── .gitignore         # Node modules and build configurations cache
├── .postcssrc         # Configuration rules for custom Tailwind CSS processors
├── package.json       # Dependencies tracker (React 19, Tailwind v4, Router v7)
├── tester.js          # Raw simulation models mirroring Swiggy production schemas
└── src/               # Comprehensive codebase including components, custom hooks & context
💻 Installation & Setup Instructions
Follow these quick steps to configure and start your local development environment:

1. Clone the Repository
Bash
git clone [https://github.com/YOUR_USERNAME/swiggy-clone-react.git](https://github.com/YOUR_USERNAME/swiggy-clone-react.git)
cd swiggy-clone-react
2. Install Project Dependencies
Ensure you have Node.js installed on your computer, then run:

Bash
npm install
3. Run the Application in Development Mode
Start the local Parcel development server:

Bash
npx parcel src/index.html
Your application will now be running smoothly at http://localhost:1234 (or the port specified by your terminal).

4. Build for Production Deployment
Generate static, minified production assets inside the /dist directory:

Bash
npx parcel build src/index.html
📝 Configuration Insights
This application relies on a modernized Tailwind processing pipeline layer via PostCSS:

JSON
{
  "plugins": {
    "@tailwindcss/postcss": {}
  }
}
