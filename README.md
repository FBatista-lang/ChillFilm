# ChillFilm
ChillFilm API (Built on .NET 6)

ChillFilm API, developed on .NET 6, offers extensive functionalities to access a diverse database of movies, series, directors, actors, reviews, and associated information. It enables developers to manage, retrieve, and explore various details about films, TV shows, cast, crew, and reviews.

Features
Movie Information: Obtain details about movies and series, including title, release date, genre, plot, ratings, and more.
Director and Actor Details: Access information about directors, actors, their filmography, and related works.
Reviews and Ratings: Retrieve user reviews, ratings, and critics' insights for movies and series.
Search and Filter: Capability to search, filter, and sort movies or series based on various parameters.
Authentication and Security: Secure endpoints with authentication and manage user access based on roles.
Scalability and Performance: Ensure high performance and scalability for handling a vast amount of data and user requests.

Endpoints

Movies and Series

GET /movies: Retrieve a list of movies.

GET /movies/{id}: Get details of a specific movie.

POST /movies: Add a new movie to the database.

PUT /movies/{id}: Update details of a movie.

DELETE /movies/{id}: Remove a movie from the database.

Directors

GET /directors: Get a list of directors.

GET /directors/{id}: Retrieve details of a specific director.

POST /directors: Add a new director to the database.

PUT /directors/{id}: Update details of a director.

DELETE /directors/{id}: Remove a director from the database.


Actors

GET /actors: Get a list of actors.

GET /actors/{id}: Retrieve details of a specific actor.

POST /actors: Add a new actor to the database.

PUT /actors/{id}: Update details of an actor.

DELETE /actors/{id}: Remove an actor from the database.

Reviews

GET /reviews: Retrieve reviews for movies or series.

POST /reviews: Add a new review for a movie or series.

PUT /reviews/{id}: Update a review.

DELETE /reviews/{id}: Remove a review.

Authentication

This API uses token-based authentication for securing sensitive endpoints. Users can generate an API key to access protected routes.

Getting Started

To use ChillFilm API:

Clone the Repository: git clone https://github.com/your-repo.git

Install .NET 6 SDK: Download and install the .NET 6 SDK from dot.net.

Set Up Database Connection: Configure the necessary database connection strings in the app settings.

Run the API: Execute dotnet run in the project directory.

Technologies Used

.NET 6

C#

Entity Framework Core (or your preferred ORM)

Authentication using JWT (JSON Web Tokens)
