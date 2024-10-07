
# Netflix Clone

A Netflix clone web application built using modern web development technologies like **React**, **Firebase**, and **TMDB API** to replicate the user interface and functionality of Netflix. Users can browse and search for movies or TV shows and stream trailers directly from the app.

![Netflix Clone](path_to_screenshot_image)

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Technologies](#technologies)
- [Installation](#installation)
- [API](#api)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication (Signup, Login, Logout)
- Browse trending, top-rated, and upcoming movies
- Search for movies and TV shows
- Watch movie trailers
- Responsive design for both mobile and desktop views


## Technologies

This project was built with the following technologies:

- **React** – Frontend framework for building UI
- **Firebase** – Authentication and hosting
- **TMDB API** – For fetching movie and TV show data
- **CSS (Styled Components)** – Styling of components
- **React Router** – For navigation and routing
- **Axios** – For API requests

## Installation

To get started with the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/netflix-clone.git
   ```

2. Navigate to the project directory:
   ```bash
   cd netflix-clone
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

4. Set up Firebase:
   - Go to [Firebase](https://firebase.google.com/) and create a project.
   - Enable Authentication (Email and Password).
   - Copy the Firebase config and replace it in your `.env` file.

5. Obtain API Key from [TMDB](https://www.themoviedb.org/):
   - Sign up on TMDB and get an API key.
   - Create a `.env` file and store the API key as:
     ```
     REACT_APP_API_KEY=your_tmdb_api_key
     ```

6. Start the development server:
   ```bash
   npm start
   ```

7. Open the browser and navigate to `http://localhost:3000`.

## API

This project uses the **TMDB API** to fetch data. You will need an API key to use the service, which can be acquired by registering on the [TMDB](https://www.themoviedb.org/) website.

- **Popular Movies**: `/movie/popular`
- **Trending**: `/trending/all/day`
- **Movie Details**: `/movie/{movie_id}`

For more information on available endpoints, visit the [TMDB API documentation](https://developers.themoviedb.org/3).

## Contributing

Contributions are welcome! Here's how you can help:

1. Fork the project.
2. Create a feature branch: `git checkout -b feature/new-feature`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature/new-feature`.
5. Submit a pull request.

## License

This project is licensed under the MIT License
