# InfoMod

A comprehensive entertainment information platform that helps you discover the latest movie releases, top airing TV shows, and explore detailed information about your favorite actors and their projects.

![JavaScript](https://img.shields.io/badge/JavaScript-97.8%25-yellow)
![CSS](https://img.shields.io/badge/CSS-1.6%25-blue)
![HTML](https://img.shields.io/badge/HTML-0.6%25-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## Features

- **Latest Releases**: Stay updated with the newest movie and TV show releases
- **Actor Information**: Get comprehensive details about actors and their filmography
- **Reviews & Ratings**: Access reviews and ratings for movies and TV shows
- **Trailers**: Watch trailers and promotional videos
- **Top Airing Shows**: Discover currently trending and top-rated TV series
- **Search Functionality**: Find movies, shows, and actors quickly
- **Responsive Design**: Optimized for desktop and mobile devices

## Tech Stack

- **Frontend**: JavaScript (ES6+), HTML5, CSS3
- **API**: TMDB (The Movie Database) API
- **Styling**: Modern CSS with responsive design
- **Architecture**: Vanilla JavaScript SPA

## Quick Start

**1. Clone and navigate**

```
git clone https://github.com/cpsurfer/infomod.git
cd infomod
```

**2. Get API Key**

- Sign up at [TMDB API](https://developer.themoviedb.org/docs/getting-started)
- Get your free API key from the settings page

**3. Configure API**

Create a `config.js` file and add your API key:

```
const API_KEY = 'your_tmdb_api_key_here';
const BASE_URL = 'https://api.themoviedb.org/3';
```

**4. Launch the application**

```
# Using Live Server or any local server
# Open index.html in your browser
```

**5. Access at** `http://localhost:3000` or your local server address

## Usage

### Discovering Content
1. **Browse Homepage** - View trending movies and TV shows
2. **Search** - Use the search bar to find specific content
3. **Explore Details** - Click on any movie/show for detailed information
4. **Watch Trailers** - View trailers directly from the detail pages

### Getting Actor Information
1. **Actor Search** - Search for your favorite actors
2. **Filmography** - View complete list of their projects
3. **Latest Projects** - Stay updated with their recent work

## API Endpoints Used

- `GET /movie/popular` - Popular movies
- `GET /tv/popular` - Popular TV shows
- `GET /search/movie` - Search movies
- `GET /search/tv` - Search TV shows
- `GET /search/person` - Search actors
- `GET /movie/{id}` - Movie details
- `GET /tv/{id}` - TV show details
- `GET /person/{id}` - Actor details
- `GET /movie/{id}/videos` - Movie trailers

## Project Structure

```
infomod/
├── index.html              # Main HTML file
├── css/
│   ├── styles.css         # Main stylesheet
│   └── responsive.css     # Mobile responsiveness
├── js/
│   ├── app.js            # Main JavaScript file
│   ├── api.js            # API calls and data handling
│   ├── components.js     # Reusable UI components
│   └── utils.js          # Utility functions
├── assets/
│   ├── images/           # Static images
│   └── icons/            # Icon files
└── config.js             # API configuration
```

## Features Breakdown

### Movie Information
- Release dates and runtime
- Cast and crew details
- Plot summaries and genres
- User ratings and reviews
- High-quality poster images

### TV Show Details
- Episode information and seasons
- Cast and character details
- Air dates and network information
- Series ratings and reviews

### Actor Profiles
- Biography and personal details
- Complete filmography
- Latest and upcoming projects
- Profile images and gallery

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/new-feature`)
3. Commit changes (`git commit -m 'Add new feature'`)
4. Push to branch (`git push origin feature/new-feature`)
5. Open a Pull Request

## API Usage Guidelines

- Respect TMDB API rate limits
- Cache responses when possible
- Always attribute TMDB as data source
- Follow TMDB terms of service

## Future Enhancements

- [ ] User accounts and watchlists
- [ ] Personalized recommendations
- [ ] Social features and reviews
- [ ] Offline functionality
- [ ] Mobile app development
- [ ] Advanced filtering and sorting

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**cpsurfer** - [GitHub Profile](https://github.com/cpsurfer)

## Acknowledgements

- [The Movie Database (TMDB)](https://www.themoviedb.org/) for providing the API
- Movie and TV show data courtesy of TMDB
- Icons and assets from various open-source libraries

## Support

- ⭐ Star this repo if you find it helpful!
- 🐛 [Report bugs](https://github.com/cpsurfer/infomod/issues)
- 💡 [Request features](https://github.com/cpsurfer/infomod/issues)
- 📖 Check the [documentation](https://developer.themoviedb.org/docs)

---

**Discover your next favorite movie or show with InfoMod** 🎬
