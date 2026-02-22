# Pokedex - Pokemon Database

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue.svg" alt="Version">
  <img src="https://img.shields.io/badge/vue-3-green.svg" alt="Vue">
  <img src="https://img.shields.io/badge/license-MIT-orange.svg" alt="License">
</p>

> A beautiful, interactive Pokemon database built with Vue.js 3

Browse, search, and explore Pokemon from the original 151 to the latest generations. Features include type filtering, favorites, detailed stats, and a responsive design.

## ✨ Features

- 🔍 **Search** - Find Pokemon by name instantly
- 🎯 **Filter by Type** - Filter by any of the 18 Pokemon types
- ❤️ **Favorites** - Save your favorite Pokemon
- 📊 **Detailed Stats** - View HP, Attack, Defense, and more
- 📱 **Responsive** - Works on mobile, tablet, and desktop
- ⚡ **Fast Loading** - Efficient API caching
- 🎨 **Beautiful UI** - Modern dark theme with Pokemon colors

## 🚀 Quick Start

### Option 1: Open Directly
Simply open `index.html` in your browser - no server required!

```bash
# Or serve it
npx serve .
```

### Option 2: VS Code Live Server
1. Open the project in VS Code
2. Install "Live Server" extension
3. Right-click `index.html` → "Open with Live Server"

## 🛠️ Tech Stack

- **Frontend**: Vue.js 3 (CDN)
- **Styling**: TailwindCSS
- **Data**: [PokéAPI](https://pokeapi.co/)
- **Fonts**: Poppins

## 🎮 Usage

### Browsing Pokemon
Scroll through the grid of Pokemon cards. Click "Load More" to see more Pokemon.

### Searching
Use the search bar in the header to find Pokemon by name.

### Filtering by Type
Click on type buttons below the search bar to filter Pokemon by type.

### Viewing Details
Click on any Pokemon card to see detailed information including:
- Large sprite image
- Type(s)
- Height and weight
- Base stats with visual bars
- Abilities
- Type defense chart

### Favorites
Click the heart icon on any Pokemon to add it to your favorites. Click the heart button in the header to view all your favorites.

## 📱 Responsive Design

| Screen Size | Columns |
|------------|---------|
| Mobile | 2 |
| Tablet | 3 |
| Desktop | 4 |
| Large | 5 |

## 🎨 Type Colors

Each Pokemon type has its own color:

| Type | Color |
|------|-------|
| Normal | #A8A77A |
| Fire | #EE8130 |
| Water | #6390F0 |
| Electric | #F7D02C |
| Grass | #7AC74C |
| Ice | #96D9D6 |
| Fighting | #C22E28 |
| Poison | #A33EA1 |
| Ground | #E2BF65 |
| Flying | #A98FF3 |
| Psychic | #F95587 |
| Bug | #A6B91A |
| Rock | #B6A136 |
| Ghost | #735797 |
| Dragon | #6F35FC |
| Dark | #705746 |
| Steel | #B7B7CE |
| Fairy | #D685AD |

## 📦 Project Structure

```
pokedex-app/
├── index.html      # Main application
├── SPEC.md        # Technical specification
└── README.md      # This file
```

## 🙏 Credits

- [PokéAPI](https://pokeapi.co/) - Pokemon data
- [Pokemon DB](https://pokemondb.net/) - Type effectiveness data
- [Bulbapedia](https://bulbapedia.bulbagarden.net/) - Pokemon images

## 📄 License

MIT License - feel free to use!

---

<p align="center">Made with ❤️</p>
