# azure-webapps-net9

This is a .NET 9 web application designed for deployment on Azure Web Apps. 

## Project Structure

- **Controllers**: Contains the controllers that handle HTTP requests.
  - `HomeController.cs`: Manages requests related to the home page.

- **Models**: Contains the data models used in the application.
  - `SampleModel.cs`: Defines the properties and validation for the application's data.

- **Views**: Contains the Razor views for rendering HTML.
  - **Home**: Contains views related to the home page.
    - `Index.cshtml`: The main view for the home page.
  - **Shared**: Contains shared views and layouts.
    - `_Layout.cshtml`: The layout used by all views.

- **wwwroot**: Contains static files such as CSS, JavaScript, and third-party libraries.
  - **css**: Contains stylesheets.
    - `site.css`: The main stylesheet for the application.
  - **js**: Contains JavaScript files.
    - `site.js`: The main JavaScript file for client-side functionality.
  - **lib**: Directory for third-party libraries.

- **Configuration Files**:
  - `appsettings.json`: Configuration settings for the application.
  - `Program.cs`: The entry point of the application.
  - `Startup.cs`: Configures services and the request pipeline.

## Setup Instructions

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Restore the dependencies using the command:
   ```
   dotnet restore
   ```
4. Run the application using the command:
   ```
   dotnet run
   ```
5. Open your web browser and navigate to `http://localhost:5000` to view the application.

## Overview

This application serves as a basic template for building web applications using .NET 9. It includes a simple home page and is structured to allow for easy expansion and customization.