# Layered Architecture (N-Tier)

This project demonstrates a classic horizontal separation of concerns.

## Structure
- **MyApp.Web**: Presentation layer (ASP.NET Core Web API).
- **MyApp.Business**: Business logic and service layer.
- **MyApp.DataAccess**: Data persistence and repository layer.
- **Tests**: Unit and integration tests for each layer.

## Key Principles
- **Separation of Concerns**: Each layer has a specific responsibility.
- **Dependency Flow**: Dependencies point downwards (Web -> Business -> DataAccess).
- **Loose Coupling**: Interfaces are used to decouple the business logic from the data access implementation.
