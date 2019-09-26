# dotnet core Todo API

This project contains a basic scaffold for a todo API developed using the dotnet core framework.

## Dependencies

Download the [dotnet core sdk](https://dotnet.microsoft.com/download/dotnet-core/3.0).

## Usage

* Download this repo
* From your terminal, navigate inside this repo and run `dotnet restore` to install all the project's dependencies
* Run the API by executing `dotnet run`

Using [Postman](https://www.getpostman.com/) or a similar tool, you can interact with the API to perform all basic CRUD operations.

Routes:

* /api/todoitems        \[POST]
* /api/todoitems        \[GET]
* /api/todoitems/{id}   \[GET]
* /api/todoitems/{id}   \[PUT]
* /api/todoitems/{id}   \[DELETE]