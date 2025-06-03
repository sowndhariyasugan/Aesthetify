## 🎨 Aesthetify – Color Palette Generator

Aesthetify is a sleek and minimal Single Page Application (SPA) that lets users generate, explore, and save aesthetic color palettes for their creative projects. Built with React, it focuses on UI/UX and dynamic user interaction.

### 📁 Project Structure

Aesthetify/
├── public/
│   └── favicon.svg              # Project favicon
├── src/
│   ├── assets/                  # Images, icons, static resources
│   ├── components/              # Reusable UI components
│   │   ├── NavBar.jsx           # Navigation bar with in-page links
│   │   ├── Hero.jsx             # Header section
│   │   ├── PaletteGenerator.jsx # Color palette generator functionality
│   │   ├── ColorCard.jsx        # Individual color display card
│   │   ├── SavedPalettes.jsx    # Displays saved palettes
│   │   └── Footer.jsx           # Footer section
│   ├── utils/
│   │   └── colorUtils.js        # Color generation & manipulation functions
│   ├── App.jsx                  # Main component rendering all others
│   ├── App.css                  # App-level styles
│   ├── main.jsx                 # Entry point of the app
│   └── index.css                # Global CSS and Tailwind imports
├── .gitignore
├── index.html
├── package.json
├── vite.config.js
└── README.md
