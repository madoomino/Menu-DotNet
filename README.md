# Menu Project

The Menu project is a simple application that manages a menu of dishes and their ingredients. It allows users to view a list of dishes, search for specific dishes by name, and view detailed information about individual dishes.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- View a list of dishes
- Search for dishes by name
- View detailed information about individual dishes, including their ingredients and prices

## Technologies Used

- ASP.NET Core
- Entity Framework Core
- C#
- HTML/CSS
- Razor
- Postgresql

## Installation

To run the Menu project locally, follow these steps:

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/madoomino/Menu-DotNet
   ```

2. Navigate to the project directory:
   ```
   cd Menu-DotNet
   ```

3. Add the `appsettings.json` file in the Menu directory, and add the connection string as `DefaultConnection` under `ConnectionStrings`
    ```
    "ConnectionStrings": {
     "DefaultConnection": "Host=<Hostname>;Port=<Port-Number;Database=<DB-Name>;Username=<Your-Username;Password=<Your-Strong-Password>;"
    }
    ```

4. Install the necessary dependencies:
   ```
   dotnet restore
   ```

5. Set up the database:
   ```
   dotnet ef database update
   ```

## Usage

1. Run the application:
   ```
   dotnet run
   ```

2. Open a web browser and navigate to`localhost:<app-port>` to access the application.

3. Explore the menu, search for dishes, and view detailed information about each dish.

## Contributing

Contributions to the Menu project are welcome! If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature-name`.
3. Commit your changes: `git commit -am 'Add new feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## License

The Menu project is licensed under the MIT License.