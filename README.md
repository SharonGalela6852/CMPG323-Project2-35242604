# CMPG323-Project2-35242604

# EcoPower Logistics API

Welcome to the EcoPower Logistics API project. This API allows you to manage logistics data related to solar energy systems. It provides endpoints for customers, orders, and products, enabling you to create, read, update, and delete data.

## Table of Contents
- [Getting Started](#getting-started)
- [API Endpoints](#api-endpoints)
- [Security](#security)
- [Web API Cloud Hosting](#web-api-cloud-hosting)
- [Documentation](#documentation)
- [References](#references)

## Getting Started

To use this API, follow these steps:

1. Clone or download this repository to your local machine.
2. Install any necessary dependencies by running `npm install` in your terminal.
3. Configure your database connection in the `appsettings.json` file.
4. Run the API locally using `dotnet run`.
5. Access the API documentation at `http://localhost:5000/swagger`.

## API Endpoints

### Customers

- **GET /api/customers**: Retrieve a list of all customers.
- **GET /api/customers/{id}**: Retrieve information about a specific customer.
- **POST /api/customers**: Create a new customer.
- **PATCH /api/customers/{id}**: Update customer information.
- **DELETE /api/customers/{id}**: Delete a customer.

### Orders

- **GET /api/orders**: Retrieve a list of all orders.
- **GET /api/orders/{id}**: Retrieve information about a specific order.
- **POST /api/orders**: Create a new order.
- **PATCH /api/orders/{id}**: Update order information.
- **DELETE /api/orders/{id}**: Delete an order.
- **GET /api/orders/customer/{customerId}**: Retrieve all orders for a specific customer.

### Products

- **GET /api/products**: Retrieve a list of all products.
- **GET /api/products/{id}**: Retrieve information about a specific product.
- **POST /api/products**: Create a new product.
- **PATCH /api/products/{id}**: Update product information.
- **DELETE /api/products/{id}**: Delete a product.
- **GET /api/products/order/{orderId}**: Retrieve all products for a specific order.

## Security

Authentication is required to access the API endpoints. Use your credentials to authenticate and access the data.

## Web API Cloud Hosting

The API is hosted on Azure cloud. You can access the live API at `https://your-api-url`.

## Documentation

For detailed information about API usage, refer to the [Swagger Documentation](https://your-api-url/swagger).

## References

Here are some references that were helpful during the development of this project:

- [Microsoft Docs - Create a web API with ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/web-api/?view=aspnetcore-6.0)
- [Entity Framework Core Documentation](https://docs.microsoft.com/en-us/ef/core/)
- [C# Programming Guide](https://docs.microsoft.com/en-us/dotnet/csharp/)
- [Azure Documentation](https://docs.microsoft.com/en-us/azure/)

---
Project developed by [Sharon Galela]
