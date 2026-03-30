# TrailerWorld

A modern React application for discovering and watching movie trailers. Browse trending films, upcoming releases, and explore what's currently in cinemas with an intuitive, responsive interface.

## � Live Demo

Check out the live deployment: [https://moviesearchvercelapp.vercel.app/](https://moviesearchvercelapp.vercel.app/)

## �🎬 Features

- **Now in Cinemas** - Discover movies currently showing in theaters
- **Trending** - Explore the latest trending movies
- **Upcoming** - Get a preview of movies coming soon
- **What's Popular** - See what's most popular right now
- **Search Functionality** - Find and filter movies by title
- **Movie Trailers** - Watch trailers directly from the application
- **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Swiper Integration** - Smooth carousel navigation with Swiper

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd TrailerWorld-main
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The application will open at `http://localhost:5173` (default Vite port).

## 📁 Project Structure

```
src/
├── components/
│   ├── Card.jsx              # Movie card component
│   ├── Hero.jsx              # Hero banner component
│   ├── NowInCinemas.jsx      # Now in cinemas section
│   ├── SearchedMovies.jsx    # Search results display
│   ├── Trending.jsx          # Trending movies section
│   ├── TrailerCard.jsx       # Trailer card component
│   ├── UpComing.jsx          # Upcoming movies section
│   ├── WhatsPopular.jsx      # Popular movies section
│   └── SwiperManual.css      # Swiper styling
├── App.jsx                   # Main app component
├── main.jsx                  # Application entry point
├── App.css                   # App styling
└── index.css                 # Global styles
```

## 🛠 Build & Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally

## 📦 Dependencies

- **React** - UI library
- **Vite** - Build tool and dev server
- **Swiper** - Touch slider/carousel
- **ESLint** - Code linting

## 🎨 Styling

The application uses CSS modules and custom styling with:
- Responsive grid layouts
- Smooth animations and transitions
- Swiper carousel styling

## 🔧 Configuration

- **Vite** - See `vite.config.js`
- **ESLint** - Configuration in `eslint.config.js`

## 📝 Usage

1. Browse different movie categories from the navigation
2. Click on any movie card to view details and trailers
3. Use the search feature to find specific movies
4. Navigate through carousels using swipe gestures or arrows

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements.

## 📄 License

This project is open source and available under the MIT License.

## 👨‍💻 Author

Created as a movie discovery and trailer browsing application.

---

**Happy Exploring! 🍿**