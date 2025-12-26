# .NET Architectural Patterns Portfolio

This repository contains a comprehensive collection of 13 different architectural patterns implemented in .NET. Each pattern is a skeletal structure designed to demonstrate the core principles, project organization, and dependency flow of that specific architecture.

## Architectures Included

1.  **[Layered Architecture (N-Tier)](./1.%20Layered%20Architecture%20(N-Tier)/README.md)**: Classic horizontal separation of concerns.
2.  **[Clean Architecture (Uncle Bob)](./2.%20Clean%20Architecture%20(Uncle%20Bob)/README.md)**: Inward-pointing dependencies centered around the Domain.
3.  **[Onion Architecture](./3.%20Onion%20Architecture/README.md)**: Domain core with concentric layers of services and infrastructure.
4.  **[Hexagonal Architecture (Ports & Adapters)](./4.%20Hexagonal%20Architecture%20(Ports%20&%20Adapters)/README.md)**: Decoupling core logic via defined ports and external adapters.
5.  **[CQRS](./5.%20CQRS%20(Command%20Query%20Responsibility%20Segregation)/README.md)**: Explicit separation of read and write models.
6.  **[Vertical Slice Architecture](./6.%20Vertical%20Slice%20Architecture/README.md)**: Feature-based organization instead of technical layers.
7.  **[Domain-Driven Design (DDD)](./7.%20Domain-Driven%20Design%20(DDD)/README.md)**: Focus on Bounded Contexts, Aggregates, and Domain Events.
8.  **[Modular Monolith Architecture](./8.%20Modular%20Monolith%20Architecture/README.md)**: Autonomous business modules within a single deployment unit.
9.  **[Microservices Architecture](./9.%20Microservices%20Architecture/README.md)**: Distributed system of independent, containerized services.
10. **[Plugin Architecture (Extensible)](./10.%20Plugin%20Architecture/README.md)**: Core application extensible via dynamically loaded DLLs.
11. **[Event-Driven Architecture (EDA)](./11.%20Event-Driven%20Architecture%20(EDA)/README.md)**: Decoupled services communicating via asynchronous integration events.
12. **[Serverless Architecture (Azure Functions)](./12.%20Serverless%20Architecture%20(Azure%20Functions)/README.md)**: Event-triggered, scalable units of execution.
13. **[API Gateway + BFF (Backend for Frontend)](./13.%20API%20Gateway%20+%20BFF%20(Backend%20for%20Frontend)/README.md)**: Tailored API entry points for different client types.

## Getting Started

Each directory contains a standalone solution (`.sln`) and a local `README.md` with specific details about that architecture.

### Requirements
- .NET 9.0 SDK or later
- Visual Studio 2022 or VS Code

### How to use
Navigate to any pattern directory and run:
```bash
dotnet build
```
