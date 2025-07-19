# Foodie App 🍽️

A food recipe and ordering app built with **Next.js 15**, showcasing App Router, Page Router, dynamic routing, and full-stack interactions.

## 🚀 Live Demo

Access the live application [here](https://nextjs-foodie-app.vercel.app/).

## 🧩 Features

- Browse a menu of meals.
- View detailed meal (recipe) pages.
- Add new meals via form submission.
- Dynamic routes for individual meals.
- SQLite-backed local database (`meals.db`).
- Modern UI styling (next/font, CSS Modules, Tailwind, or your choice).
- Support for both App Router and Pages Router patterns.

## 🛠️ Tech Stack

- **Next.js 14** (App Router + Page Router)
- **React** with Hooks
- **SQLite** (`meals.db`) for lightweight data storage
- **CSS Modules** / Tailwind CSS
- (Optional) **Zustand / SWR / NextAuth** for state, data fetching, and auth

## ⚙️ Getting Started

### Prerequisites

- Node.js >= v18
- npm or yarn

### Installation & Setup

1. Clone repository:
    ```bash
   git clone https://github.com/Khanhbroo/nextjs-foodie-app.git
   cd nextjs-foodie-app
    ```
2. Install dependencies:
   ```bash
   npm install
    # or
    yarn
   ```
3. Initialize the database:
   ```bash
   node initdb.js
   ```
4. Start development server:
    ```bash
    npm run dev
    # or
    yarn dev
     ```
5. Visit in browser: http://localhost:3000

## 🎯 Usage
- Browse meals on the homepage.
- Click a meal to view details.
- Use the Add Meal form to insert new meals.
- Data is stored locally in meals.db.

## ⚙️ Optional Enhancements
- User authentication with NextAuth
- Migrate to PostgreSQL / MongoDB
- Add global state with Zustand
- Implement client-side data fetching with SWR
- Payment integration (e.g., Stripe)
- Admin panel for CRUD meal management

## 🙌 Contributions
- Contributions are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests

## 📝 License
- This project is open-source and available under the MIT License.

