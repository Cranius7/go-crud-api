# go-crud-api
# CRUD API Without a Database

This Go program implements a CRUD (Create, Read, Update, Delete) API without using a database. It utilizes the Gorilla Mux router for handling HTTP requests.

## Endpoints

- **GET /movies**: Retrieves all movies stored in memory.
- **GET /movies/{id}**: Retrieves a specific movie by its ID.
- **POST /movies**: Creates a new movie.
- **PUT /movies/{id}**: Updates a movie with the specified ID.
- **DELETE /movies/{id}**: Deletes a movie with the specified ID.

## Movie Structure

Each movie has the following attributes:
- **ID**: Unique identifier for the movie.
- **Isbn**: International Standard Book Number (ISBN) of the movie.
- **Title**: Title of the movie.
- **Director**: Information about the director, including first name and last name.

## API Functionality

- **getMovies**: Retrieves all movies.
- **getMovie**: Retrieves a specific movie by its ID.
- **createMovie**: Creates a new movie.
- **updateMovie**: Updates an existing movie with the specified ID.
- **deleteMovie**: Deletes a movie with the specified ID.

## Usage

1. Run the program. The server will start at port 8000.
2. Use HTTP methods like GET, POST, PUT, and DELETE to interact with the API.

