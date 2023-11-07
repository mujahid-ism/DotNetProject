# DotNetProject

Initialize project:
dotnet new mvc -n webapp

https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-new

To run the server:
dotnet run

For SetUp the Database required package:
dotnet add package Microsoft.EntityFrameWorkCore
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.Tools

For Setting up Microsoft SQL Server:
https://learn.microsoft.com/en-us/sql/linux/quickstart-install-connect-ubuntu?view=sql-server-ver16&tabs=ubuntu2004

For Installing dotent entity framework globally:
dotnet tool install --global dotnet-ef

dotnet ef
dotnet ef database update

Migrate The Model:
add: dotnet ef migrations add AddCategoryTableToDb
remove: ef migrations remove
upate after migrate: dotnet ef database update
