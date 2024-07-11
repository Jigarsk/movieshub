# Movies Hub

A React-based web application for searching and displaying movie information using the OMDB API.

## Features

- Search for movies by title
- Display movie cards with poster, title, year, and type
- Responsive design for various screen sizes
- Default search for "marvel" movies on initial load

## Technologies Used

- React.js
- OMDB API
- CSS for styling

## Components

### App.js

The main component that handles:
- Movie search functionality
- State management for movies and search term
- Rendering of the search interface and movie cards

### Moviecard.js

A reusable component for rendering individual movie cards, displaying:
- Movie poster (with fallback image)
- Release year
- Movie type
- Movie title

## Setup and Installation

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Create a `.env` file in the root directory and add your OMDB API key:
