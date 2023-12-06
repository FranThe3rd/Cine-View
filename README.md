# CineView - Movie Search Website

CineView is a React application that allows users to search for movies and display movie data using the Open Movie Database (OMDb) API.

## Features

- Search for movies by title using a text input field
- Display movie results in a grid with the movie title, year, and poster image
- Provides clean user interface and styling for a smooth experience

## Usage

To use CineView:

1. Enter a movie title into the search bar 
2. Click the search icon or press enter to search movies
3. Movie results will be displayed in a grid, showing movie titles, years, and posters 
4. Click on a movie to view additional details

The app uses React Hooks like `useState` and `useEffect` to manage state and fetch movie data from the OMDb API. Results are displayed using a `MovieCard` component.

The search defaults to "Movie" on initial load to return popular movies.

## Project Setup

The project uses Create React App for easy setup. To run locally:

1. Clone the repository
2. Run `npm install` to install dependencies  
3. Run `npm start` to start local dev server

A valid OMDb API key is required in the `API_URL` constant to fetch movie data.

## Dependencies

- React 
- React DOM
- React Scripts
- OMDb API

## Future Improvements

Future iterations could include:

- More detailed movie views
- Genre filters
- Similar movie recommendations 
- pagination

## Credits

API provided by OMDb 

Search icon from Flaticon
