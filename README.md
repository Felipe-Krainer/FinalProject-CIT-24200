
# Customer Order Management System

## Project Overview
The **Customer Order Management System** is a web-based application built using ASP.NET Core Razor Pages. It is designed to manage customer information, product inventory, and orders efficiently. The application demonstrates CRUD functionality (Create, Read, Update, Delete) and includes search capabilities for customers, products, and orders.

## Features
### Customers
- List all customers.
- Create, edit, view, and delete customer information.
- Search customers by `Company Name` or `Contact Name`.

### Products
- List all products.
- Add, edit, view, and delete products.
- Search products by `Product Name`.

### Orders
- List all orders.
- Create, edit, view, and delete orders.
- Search orders by `Customer ID`.

### Navigation
- Intuitive navigation bar for seamless transitions between Customers, Products, and Orders pages.

## Technology Stack
- **Frontend**: Razor Pages with Bootstrap for responsive design.
- **Backend**: ASP.NET Core 6.0
- **Database**: SQLite
- **ORM**: Entity Framework Core
- **IDE**: Visual Studio 2022

## Project Structure
```
CustomerOrderManagement/
├── Pages/              # Razor Pages for Customers, Products, and Orders
│   ├── Customers/      # CRUD pages for managing customers
│   ├── Products/       # CRUD pages for managing products
│   ├── Orders/         # CRUD pages for managing orders
├── Data/               # Database context (NorthwindContext)
├── Models/             # Models for Customers, Products, and Orders
├── wwwroot/            # Static files (CSS, JS, etc.)
├── appsettings.json    # Configuration file for database
└── Program.cs          # Application entry point
```

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Open the solution in **Visual Studio 2022**.
3. Build and run the project:
   ```bash
   dotnet run
   ```
4. Navigate to `http://localhost:<port>` in your browser to use the application.

## Demo
[Insert video link here]

## Code Highlights
### Database Context
The `NorthwindContext` manages database access and defines relationships between tables like Customers, Products, and Orders.

### CRUD Functionality
Each feature (Customers, Products, Orders) is built with Razor Pages to handle Create, Read, Update, and Delete operations.

### Search
Search functionality is implemented in each feature using query strings, enabling dynamic filtering of data.

## Acknowledgments
This project was developed as a final project for the course. Thanks to the instructors for their guidance and the provided `Northwind` database schema.
