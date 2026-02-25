# 🎮 Pokémon Card Game Clone

A modern React application displaying Pokémon cards with detailed information. Built with React, Vite, and featuring responsive card layouts with beautiful gradient styling.

## 📋 Features

- **Dynamic Pokémon Cards**: Display Pokémon with images, types, and base experience stats
- **Class Components**: Built using React Class Components for state management
- **Responsive Design**: Beautiful gradient cards with smooth animations
- **Fast Development**: Powered by Vite for instant HMR (Hot Module Replacement)
- **ESLint Integration**: Code quality checks configured

## 🛠️ Tech Stack

- **React 19.2.0** - UI library
- **Vite 7.3.1** - Build tool and dev server
- **React DOM 19.2.0** - React rendering
- **CSS3** - Styling with gradients and box shadows
- **Node.js** - Runtime

## 📦 Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd PokeGame_Clone
```

2. Install dependencies:

```bash
npm install
```

## 🚀 Development

Start the development server:

```bash
npm run dev
```

The application will be available at `http://localhost:5173` (or next available port if 5173 is in use).

## 🏗️ Build

Create an optimized production build:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

## 📁 Project Structure

```
src/
├── App.jsx           # Main application component
├── App.css           # Application styles
├── Pokedex.jsx       # Pokémon list container (Class Component)
├── Pokedex.css       # Pokedex styles
├── Pokecard.jsx      # Individual Pokémon card component (Class Component)
├── Pokecard.css      # Card styling with gradients
├── main.jsx          # React entry point
├── index.css         # Global styles
└── assets/          # Static assets
```

## 🎴 Components

### Pokedex

Class component that manages a collection of Pokémon. Displays default Pokémon data with the following properties:

- `id` - Pokémon ID for API image fetching
- `name` - Pokémon name
- `type` - Pokémon type (fire, water, electric, etc.)
- `base_experience` - Base experience points

### Pokecard

Class component that renders individual Pokémon cards with:

- Official artwork from PokéAPI
- Pokémon name title
- Type information
- Base experience stats
- Beautiful gradient background and shadow effects

## 🎨 Styling

Cards feature:

- Gradient background (purple/pink theme)
- Multiple drop shadow layers for depth
- Responsive sizing (300px width)
- Border radius for modern look
- Bold Inter font family

## 🔗 API Integration

Pokémon images are fetched from the official PokéAPI:

```
https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/official-artwork/{id}.png
```

## 📝 Code Quality

ESLint is configured with:

- React plugin rules
- React Hooks best practices
- ES6+ JavaScript standards

Check for lint errors:

```bash
npm run lint
```

## 📄 License

This project is open source and available for educational purposes.

## 👨‍💻 Author

Created as a learning project for React component development and Pokémon API integration.
