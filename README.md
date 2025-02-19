# Expenses Tracker Application

A full-stack expense tracking application built using C# .NET Core (ASP.NET MVC) and JavaScript with CSHTML & Syncfusion Charts. It allows users to track expenses, manage categories, analyze spending trends, and visualize financial data using interactive charts.

## Features
- User Authentication – Secure login & registration using Identity/JWT
- Expense Management – Add, edit, delete, and categorize transactions
- Financial Dashboard – Track income, expenses, and balance trends
- Data Visualizations – Interactive Doughnut & Spline Charts using Syncfusion
- Search & Filters – Find expenses by date, category, and amount
- Entity Framework Core (EF Core) – ORM for database handling
- Migrations – Schema updates using EF Core Migrations
- Responsive UI – Built with CSHTML, JavaScript, and Bootstrap

## Tech Stack
- C# .NET Core (ASP.NET MVC)        =>          Backend & API Development
- Entity Framework Core (EF Core)	    =>        ORM for database operations
- Migrations	                          =>      Database schema versioning
- JavaScript (Syncfusion, jQuery, Bootstrap) =>	Frontend interactivity & charts
- CSHTML & Razor	                          =>  UI rendering
- SQL Server / SQLite	                       => Database storage
- Syncfusion Charts	                         => Financial visualizations

## API Endpoints
HTTP   Method	Endpoint	        Description  
GET	   ```/Dashboard/Index```	        Fetches total income, expenses, and balance  
GET	   ```/Dashboard/Charts```	      Returns formatted data for visual charts  
GET	   ```/Transaction/Index```	      View all transactions  
POST	 ```/Transaction/AddOrEdit```	  Add or update a transaction  
POST   ```/Transaction/Delete/{id}```	Deletes a transaction  

## How to Run the Application
- Clone the Repository
  ```git clone https://github.com/gowri-malla216/Expense-Tracker.git```
  ```cd Expense-Tracker```
- Install Dependencies & Apply Migrations
```dotnet restore```
```dotnet ef database update```
- Run the Application
```dotnet run```
## Contribution
Want to improve this feature? Fork the repo and submit pull requests!
