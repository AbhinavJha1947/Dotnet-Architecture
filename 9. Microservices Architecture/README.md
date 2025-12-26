# Microservices Architecture

This project demonstrates a distributed system of independent, microservices.

## Structure
- **src/Services**: Independent services (`OrderService`, `CatalogService`, `CustomerService`).
- **src/ApiGateway**: Centralized entry point.
- **src/BuildingBlocks**: Shared libraries (EventBus, Common).
- **docker-compose.yml**: Orchestration for local development.

## Key Principles
- **Service Independence**: Each service has its own database and can be deployed independently.
- **Loose Coupling**: Services communicate via an asynchronous message bus.
- **Observability**: Distributed nature requires centralized logging and tracing (implied).
