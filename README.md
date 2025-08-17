# Movies App 🎬

A sample ASP.NET Core MVC web application for managing movies.
This project is based on the official Microsoft **ASP.NET Core MVC tutorial** and demonstrates the fundamentals of building web apps with the Model-View-Controller pattern.

---

## Features ✨

* Create, Read, Update, and Delete (CRUD) movies
* Search movies by title
* Filter movies by genre
* Use **Entity Framework Core** for data access
* Apply **Model Binding**, **Validation**, and **Tag Helpers**
* Dynamic filtering with `SelectList` for genres

---

## Technologies Used 🛠️

* **ASP.NET Core MVC** (.NET 8)
* **Entity Framework Core** (Code-First with SQL Server)
* **Razor Views** for UI
* **LINQ** queries for filtering/searching

---

## Getting Started 🚀

### Prerequisites

* [.NET 8 SDK](https://dotnet.microsoft.com/download)
* Visual Studio 2022 / VS Code

### Run the App

1. Clone the repository


2. Apply migrations & create the database

   ```bash
   dotnet ef database update
   ```

3. Run the application

   ```bash
   dotnet run
   ```

   Open [https://localhost:5001](https://localhost:5001) in your browser.

---

## Example Usage 🎥

* Navigate to **/Movies** to see the list of movies
* Add new movies using the **Create** form
* Filter by genre using the dropdown
* Search by title with the search box
