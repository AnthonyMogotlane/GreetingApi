## Greeting Api
Api for Greetings App

Packages to be added:
```
dotnet tool install --global dotnet-ef
dotnet add package Npgsql.EntityFrameworkCore.PostgreSQL
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet add package Microsoft.EntityFrameworkCore.Tools
```

Command to create a migration:
```
dotnet ef migrations add "initial_migration"
```
Implementing migration into database:
```
dotnet ef database update
```

[External link](https://learn.microsoft.com/en-us/aspnet/core/tutorials/min-web-api?view=aspnetcore-6.0&tabs=visual-studio)
[External link](https://www.npgsql.org/efcore/)
[External link](https://www.youtube.com/watch?v=FoYsxFBY1os)