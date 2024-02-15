# My Movie API

My Movie API is a project developed as part of a FastAPI course on Platzi. It leverages the power of APIs to create, search, add, modify, and delete movies from an online catalog. Users can filter movies by name, year, genre, or any other category that may be added in the future.

## Features

- **Search**: Search for movies by name, year, genre, or any other available category.
- **Add**: Add new movies to the catalog with details like title, release year, genre, and more.
- **Update**: Modify existing movie entries to update information or correct errors.
- **Delete**: Remove movies from the catalog that are no longer needed or relevant.
- **Flexible Filtering**: Filter movies using a variety of criteria to find exactly what you're looking for.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/hgallegos90/my-movie-api.git
   
2. Navigate to the project directory:

   ```bash
   cd my-movie-api

3. Install dependencies:

   ```bash
   pip install -r requirements.txt


## Usage
1. Start the FastAPI server:

   ```bash
   uvicorn main:app --reload

2. Open your web browser and go to http://localhost:8000/docs to access the Swagger UI.

3. Use the interactive API documentation to test the different endpoints and functionalities.

## API Endpoints

- **GET /movies:** Retrieve a list of all movies in the catalog.
- **GET /movies/{movie_id}:** Retrieve details of a specific movie by its ID.
- **POST /movies:** Add a new movie to the catalog.
- **PUT /movies/{movie_id}:** Update details of a specific movie.
- **DELETE /movies/{movie_id}:** Remove a movie from the catalog.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/awesome-feature).
3. Make your changes.
4. Commit your changes (git commit -am 'Add awesome feature').
5. Push to the branch (git push origin feature/awesome-feature).
6. Create a new Pull Request.
   
Please make sure to follow the Contributing Guidelines.
