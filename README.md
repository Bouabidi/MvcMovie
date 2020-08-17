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

#### 1. Create a new Movie

![create](https://user-images.githubusercontent.com/16801135/90374536-ee2cdd80-e073-11ea-98e5-4199249c3c70.png)

#### 2. Delete a Movie

![delete](https://user-images.githubusercontent.com/16801135/90374652-1e747c00-e074-11ea-9419-9a0be834bb8d.png)

#### 3. get details

![details](https://user-images.githubusercontent.com/16801135/90374686-2af8d480-e074-11ea-9724-a4b0f78137c7.png)

#### 4. edit a movie

![edit](https://user-images.githubusercontent.com/16801135/90374717-3815c380-e074-11ea-9e96-4bc4f920c03d.png)

#### 5. get the list of all movies

![List](https://user-images.githubusercontent.com/16801135/90374732-3ba94a80-e074-11ea-82de-5c772a0f71de.png)
