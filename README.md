# Movix

Movix is a movie streaming application that utilizes the TMDB (The Movie Database) API to fetch and display information about movies, including details such as ratings, descriptions, and more. The frontend of the app is built with React and Vite, ensuring a smooth and fast user experience.

## Features

- **Movie Listings**: Browse through movies fetched from the TMDB API.
- **Movie Details**: View detailed information about each movie, including its rating, release date, and description.
- **Search Functionality**: Easily search for your favorite movies.
- **Infinite Scrolling**: Scroll through a list of movies seamlessly without manual pagination.
- **Lazy Loading**: Images are lazy-loaded to improve the app's performance.
- **Customizable UI**: Styled using **Sass** for maintainable and scalable styling.
- **Circular Progress Bar**: Displays movie ratings in a visually appealing manner.
- **Redux for State Management**: Integrated **@reduxjs/toolkit** for managing global states efficiently.

## Tech Stack

- **Frontend**:
  - React
  - Redux Toolkit
  - Axios (for API calls)
  - React Router DOM (for routing)
  - Vite (for build and development)
  - Sass (for styling)
  
- **Backend**:
  - TMDB API (The Movie Database API)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/movix.git
   cd movix
2. **Install dependencies**:

   ```bash
   npm install

3. **.env.example**:

   ```bash
   VITE_TMDB_API_KEY=your_tmdb_api_key
