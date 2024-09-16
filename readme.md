This repository contains all the references and resources for a production ready, scalable, and secure backend application.

# Features
- Sending JSON response.
- Parsing JSON request.
- Logging.
- Database connection.
- SQL Migration.
- CRUD Operations.
- Error handling.
- Filtering, Sorting & Pagination.
- Authentication & Authorization.
- Rate Limiting.
- Graceful Shutdown.
- Sendingg Email.

# Prerequisites
This project was built using the following technologies:
```Go version 1.21.5```
```PostgreSQL version 16.0```

To run this project, you will need to have the following installed on your machine:
- Go
- PostgreSQL

# Installation
To install this project, follow these steps:
1. Clone the repository:
```https://github.com/tahmid56/movie-rest-api.git```
2. Navigate to the project directory:
```cd movie-rest-api```
3. Install the dependencies:
```go mod download```
4. Install the PostgreSQL.
5. Terminal:
```go run ./cmd/api```