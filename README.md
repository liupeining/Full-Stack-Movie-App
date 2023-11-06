# Full-Stack-Movie-App

This application is a full-stack project that allows users to search for movies, view details, and post reviews. It utilizes a MongoDB database to manage user comments and integrates with external movie data APIs.

## Features

- **Homepage**: The main entry point of the application where users can start their journey. It features a search bar and a display of popular movies.
  ![Homepage](https://github.com/liupeining/Full-Stack-Movie-App/assets/56020224/e6ff9592-5a7e-4b7b-9e7b-6ebc4412da55)

- **Search Page**: Users can search for movies by name. The application queries its database and displays matching results.
  ![Search Page](https://github.com/liupeining/Full-Stack-Movie-App/assets/56020224/0b16f234-e16e-4b99-bddd-63f53f9b0e93)

- **Comments Page**: Allows users to read and post comments on movies. Comments are managed using MongoDB for efficient data handling.
  ![Comments Page](https://github.com/liupeining/Full-Stack-Movie-App/assets/56020224/454d7528-ba75-41b5-884f-73232d1f65d6)

## Backend

The backend is built with Node.js and Express, connecting to a MongoDB database. It handles API requests for searching movies, posting reviews, and user management.

- Entry point: [index.js](https://github.com/liupeining/Full-Stack-Movie-App/blob/main/Backend/index.js)
- Dependencies: [package.json](https://github.com/liupeining/Full-Stack-Movie-App/blob/main/Backend/package.json)

  - **Post Review**: Users can submit new reviews for movies. [See Code](https://github.com/liupeining/Full-Stack-Movie-App/blob/main/Backend/api/reviews.controller.js)
  - **Get Review**: Retrieve individual reviews by ID. [See Code](https://github.com/liupeining/Full-Stack-Movie-App/blob/main/Backend/api/reviews.controller.js)
  - **Update Review**: Users can update their reviews. [See Code](https://github.com/liupeining/Full-Stack-Movie-App/blob/main/Backend/api/reviews.controller.js)
  - **Delete Review**: Users can delete their reviews. [See Code](https://github.com/liupeining/Full-Stack-Movie-App/blob/main/Backend/api/reviews.controller.js)
  - **Get Reviews by Movie**: Fetch all reviews for a specific movie by its ID. [See Code](https://github.com/liupeining/Full-Stack-Movie-App/blob/main/Backend/api/reviews.controller.js)

## Frontend

The frontend is a functional interface built with HTML, CSS, and JavaScript. It communicates with the backend to display movie data and handle user interactions.

- Main page: [index.html](https://github.com/liupeining/Full-Stack-Movie-App/blob/main/Frontend/index.html)
- Movie details and reviews: [movie.html](https://github.com/liupeining/Full-Stack-Movie-App/blob/main/Frontend/movie.html)
- Styling: [style.css](https://github.com/liupeining/Full-Stack-Movie-App/blob/main/Frontend/style.css)
- Frontend logic: [script.js](https://github.com/liupeining/Full-Stack-Movie-App/blob/main/Frontend/script.js)

