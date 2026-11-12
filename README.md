# 🌿 Olive Terrace — Authentic Dining Experience

Welcome to **Olive Terrace**, a modern, responsive web application designed for a premier dining destination. This website showcases our authentic cuisine, ambiance, chef specialties, interactive customer feedback, and an intuitive online table reservation system.

---

## 🍽️ About Olive Terrace

**Olive Terrace** delivers an exceptional culinary journey combining the finest fresh ingredients, authentic recipes, and warm hospitality. From hand-crafted specialties to signature entrees, our menu is designed to delight every palate in an ambient, welcoming environment.

---

## ✨ Features

- **Hero Showcase**: Eye-catching hero section featuring daily special offers, brand introduction, and quick call-to-actions.
- **Interactive About & Story Tabs**: Dynamic tabbed view featuring **About**, **Experience**, and **Contact** with smooth transition animations.
- **Direct Calling & Alternative Contact**: Quick-dial button displaying primary phone and alternative contact details for easy reservations.
- **Popular Menu Carousel**: Responsive interactive slider powered by Splide.js highlighting customer-favorite dishes.
- **Online Table Reservation Form**: Convenient booking form allowing guests to reserve tables with custom dates, party sizes, and special requests.
- **Guest Testimonials**: Interactive review carousel sharing authentic experiences and feedback from our guests.
- **Responsive Header & Mobile Drawer**: Clean navigation bar on desktop with an animated slide-out menu drawer for mobile and tablet devices.
- **Comprehensive Footer**: Full contact cards with opening hours, primary & alternative phone lines, email addresses, physical location, and social media handles.

---

## 📞 Contact Details

| Detail | Primary | Alternative / Support |
| :--- | :--- | :--- |
| **Phone** | `+1 (555) 234-8765` | `+1 (555) 987-6543` |
| **Email** | `reservations@oliveterrace.com` | `info@oliveterrace.com` |
| **Address** | 123 Olive Terrace Way, Suite 100, New York, NY 10001, USA | — |
| **Hours** | Monday – Sunday: 11:00 AM – 11:00 PM | — |

---

## 🛠️ Tech Stack

- **Framework**: [React 18](https://react.dev/)
- **Bundler & Dev Server**: [Vite 5](https://vitejs.dev/)
- **Styling**: [Tailwind CSS 3](https://tailwindcss.com/) & [PostCSS](https://postcss.org/)
- **Routing**: [React Router DOM v6](https://reactrouter.com/)
- **Carousels & Sliders**: [@splidejs/react-splide](https://splidejs.com/)
- **Icons**: [React Icons](https://react-icons.github.io/react-icons/) (FontAwesome, Material Design, Ionicons, Lucide)

---

## 📁 Project Structure

```text
Olive-Terrace/
├── public/
│   ├── logo.png
│   └── vite.svg
├── src/
│   ├── assets/              # Restaurant imagery, illustrations, icons
│   ├── components/
│   │   ├── Hero/            # Hero banner & hero presentation
│   │   ├── Home/
│   │   │   ├── About/       # Tabbed about & experience component
│   │   │   ├── BookTable/   # Table reservation form
│   │   │   ├── CustomerSay/ # Reviews and testimonials slider
│   │   │   └── PopularItem/ # Popular dishes carousel & item cards
│   │   └── shared/
│   │       ├── Footer/      # Contact info, social links & copyright
│   │       └── Header/      # Brand logo, nav links & mobile drawer
│   ├── layout/
│   │   └── Main.jsx         # Primary application layout wrapper
│   ├── router/
│   │   └── Routes.jsx       # React Router route configuration
│   ├── utils/
│   │   ├── dummyData.jsx    # Menu items, contact info, reviews data
│   │   └── splideOptions.jsx# Splide carousel responsive configuration
│   ├── App.css
│   ├── App.jsx
│   ├── index.css            # Tailwind directives and custom fonts
│   └── main.jsx             # React DOM root entry
├── index.html
├── package.json
├── tailwind.config.js
└── vite.config.js
```

---

## 🚀 Getting Started

Follow these steps to run the project locally on your machine:

### 1. Prerequisites
- [Node.js](https://nodejs.org/) (version 18 or later recommended)
- [npm](https://www.npmjs.com/) (version 9 or later) or [yarn](https://yarnpkg.com/) / [pnpm](https://pnpm.io/)

### 2. Clone the Repository
```bash
git clone https://github.com/your-username/Olive-Terrace.git
cd Olive-Terrace
```

### 3. Install Dependencies
```bash
npm install
```

### 4. Run Development Server
```bash
npm run dev
```
Open your browser and navigate to `http://localhost:5173`.

### 5. Build for Production
```bash
npm run build
```
This generates an optimized production bundle inside the `dist/` directory.

### 6. Preview Production Build
```bash
npm run preview
```

### 7. Run Linter
```bash
npm run lint
```

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
