# InventoryOps Full-Stack Inventory Management System

InventoryOps is a full-stack inventory management project built with ASP.NET Core Web API, C#, Entity Framework Core, SQL Server LocalDB, and React. The project was designed to practice backend API development, database persistence, business reporting logic, and full-stack project structure.

## Features

- Create, retrieve, and delete inventory items
- Retrieve individual inventory records by ID
- Track item SKU, name, category, quantity, reorder level, unit cost, and supplier
- Identify low-stock inventory items using business reporting logic
- Store and retrieve data using SQL Server LocalDB
- Test API endpoints through Swagger UI
- Includes React frontend structure for future dashboard expansion

## Technologies Used

- C#
- ASP.NET Core Web API
- Entity Framework Core
- SQL Server LocalDB
- React
- Swagger UI
- Visual Studio 2022
- Git / GitHub

## API Endpoints

### Inventory

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/Inventory` | Gets all inventory items |
| POST | `/api/Inventory` | Creates a new inventory item |
| GET | `/api/Inventory/{id}` | Gets an inventory item by ID |
| DELETE | `/api/Inventory/{id}` | Deletes an inventory item |

### Reports

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/Reports/dashboard` | Gets inventory dashboard data |
| GET | `/api/Reports/low-stock` | Gets items where quantity on hand is below reorder level |

## What I Learned

This project helped me practice building a .NET full-stack application with a real database connection, REST API endpoints, Entity Framework Core models, DTOs, services, and business reporting logic. It also gave me experience testing backend functionality through Swagger UI and structuring a project for future frontend expansion.

## Future Improvements

- Add user authentication and role-based access
- Expand the React frontend dashboard
- Add update/edit functionality for inventory items
- Add purchase request approval workflows
- Deploy the backend and frontend online
