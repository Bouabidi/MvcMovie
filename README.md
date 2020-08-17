## Create MVC Crud with .net core 3.1

### use the command dotnet new mvc projectname or direct with Visual Studio to create the project

### Add the different models required. in our case only one model Movie.cs

### install the required packages 
in our case :Microsoft.EntityFrameworkCore.SqlServer

### create data folder 
inside create the file MvcMovieContext.cs

### register the database context with the ID container 

### add the database connection string to the appsettings.json file 
change the value of MvcMovieContext string in appsettings.json and add you own connection string.

### scaffold pages 
generate the controller and the view with Visual Studio.

### migratation

run the following command 

#### initial  migration : Add-Migration InitialCreate

#### Update-Database

## Some interfaces
