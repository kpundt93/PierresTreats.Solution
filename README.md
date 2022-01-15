# Pierre's Sweet and Savory Treats

#### By: Katie Pundt

#### _A web application for Pierre to keep track of treats and flavors at his bakery._

## Technologies Used
* HTML
* CSS
* Bootstrap
* C#
* .NET5
* ASP.NET Core MVC
* Razor
* NuGet
* git
* GitHub
* MySql

## Description
_A MVC web application with full CRUD for Pierre to keep track of treats and flavors at his bakery. Only logged in users can create, update, or delete treats and flavors._

## Setup/Installation Instructions
* Download, install, and configure MySQL
* Open the terminal on your desktop
* Once in the terminal, use it to navigate to your desktop folder
* Once inside your desktop folder, use the command `git clone https://github.com/kpundt93/PierresTreats.Solution.git`
* After cloning the project, navigate into it using the command `cd PierresTreats.Solution/PierresTreats`
* Create a file named "appsettings.json" in the `PierresTreats` directory
* Add the following code to appsettings.json and add your MySQL user ID and password:
```
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=katie_pundt;uid=[YOUR MYSQL USER ID];pwd=[YOUR MYSQL PASSWORD];"
  }
}
```
* Then run the command `dotnet ef database update`
* Then run the command `dotnet restore` to install project dependencies
* Then run the command `dotnet run` to run the project in the browser

## Known Bugs
* _No known bugs

## License
_MIT License: https://opensource.org/licenses/MIT_

Copyright (c) _2022_ _Katie Pundt_