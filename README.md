### Create MVC Crud with .net core 3.1

##### 1. use the command dotnet new mvc projectname or 

direct with Visual Studio to create the project

##### 2. Add the different models required. in our case only one model Movie.cs

##### 3. install the required packages 
in our case :Microsoft.EntityFrameworkCore.SqlServer

##### 4. create data folder 
inside create the file MvcMovieContext.cs

##### 5. register the database context with the ID container 

##### 6. add the database connection string to the appsettings.json file 
change the value of MvcMovieContext string in appsettings.json and add you own connection string.

##### 7. scaffold pages 
generate the controller and the view with Visual Studio.

##### 8. migratation

run the following commands:

initial  migration : Add-Migration InitialCreate

Update-Database

### Some interfaces
