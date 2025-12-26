# CQRS (Command Query Responsibility Segregation)

This project demonstrates the CQRS pattern, explicitly splitting the data modification (Commands) from the data retrieval (Queries).

## Structure
- **src/Domain**: Core entities and business rules.
- **src/Application**: Command and Query handlers, DTOs.
- **src/Infrastructure.Write**: Persistence logic optimized for data modification.
- **src/Infrastructure.Read**: Persistence logic optimized for data retrieval.
- **src/WebApi**: API endpoints that dispatch commands and queries.

## Key Principles
- **Responsibility Segregation**: Separate paths for reading and writing data.
- **Scalability**: Allows scaling read and write operations independently.
- **Optimized Models**: Read models can be tailored for UI needs, while write models focus on consistency.
