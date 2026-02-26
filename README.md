# CineMetric 🎬

A modern, responsive React-based movie search application that lets you discover and browse movies instantly using the OMDB API.

## Overview

CineMetric provides an intuitive interface to search for movies and view detailed information about them. Whether you're looking for classic films, recent releases, or hidden gems, CineMetric makes it easy to find what you're looking for.

## Features

- ⚡ **Real-time Search** – Search for movies instantly with the OMDB API
- 📱 **Responsive Design** – Works seamlessly on desktop and mobile devices
- 🎯 **Quick Overview** – View movie posters, titles, years, and types at a glance
- 🔍 **Enter to Search** – Press Enter or click the search icon to find movies
- 💾 **Fast Loading** – Optimized performance with React and modern JavaScript

## Languages & Technologies

This project is built with:

- **JavaScript** – Core application logic and API interactions
- **JSX** – React component markup for UI components
- **CSS** – Styling and responsive design
- **HTML** – Web page structure and metadata
- **JSON** – Configuration files and package management

## Project Structure

```
movie-site/
├── public/
│   ├── index.html          # Main HTML entry point
│   ├── manifest.json       # PWA manifest configuration
│   └── robots.txt          # SEO configuration
├── src/
│   ├── App.js              # Main application component
│   ├── App.css             # Application styles
│   ├── movieCard.jsx       # Reusable movie card component
│   ├── index.js            # React DOM render entry point
│   ├── search.svg          # Search icon asset
│   └── setupTests.js       # Testing configuration
├── package.json            # Dependencies and scripts
└── README.md              # Documentation
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/mkd-Dev2/Cinemetric.git
cd Cinemetric
```

2. Install dependencies:
```bash
npm install
```

### Running the Application

Start the development server:
```bash
npm start
```

The app will open at [http://localhost:3000](http://localhost:3000) in your browser. The page updates automatically when you make changes.

### Building for Production

Create an optimized production build:
```bash
npm run build
```

The build folder is ready to be deployed.

## How to Use

1. **Home Page** – The app loads with a default search for "Batman"
2. **Search** – Enter a movie title in the search box and press Enter or click the search icon
3. **Browse** – View the movie cards with posters and details
4. **View Details** – Click on any movie card to see more information

## API

This project uses the [OMDB API](http://www.omdbapi.com/) to fetch movie data. The API key is configured in `App.js`.

## Contributing

Feel free to fork this repository and submit pull requests with improvements!

## License

This project is open source and available under the MIT License.

---

**Built with React & ❤️**

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
