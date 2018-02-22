This solution is using ASP.NET Core 2.0 with React and EntityFramework Core features. 
As primary databse has been used PosgreSQL.
To update DataContext you need to:
1) Change connection string in the appsettings.json file of the web application.
2)Run the following command for migration and create database.
	Tools –> NuGet Package Manager –> Package Manager Console
	PM> Add-Migration MyFirstMigration
	PM> Update-Database