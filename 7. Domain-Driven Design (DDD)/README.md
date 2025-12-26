# Domain-Driven Design (DDD)

This project demonstrates DDD principles, focusing on rich domain models and bounded contexts.

## Structure
- **src/Shared**: Shared kernel and domain primitives.
- **src/OrderContext**: Projects for the Order bounded context (Domain, Application, Infrastructure).
- **src/CatalogContext**: Projects for the Catalog bounded context.
- **src/WebApi**: The main entry point integrating all contexts.

## Key Principles
- **Bounded Context**: Explicit boundaries within the system where a specific domain model applies.
- **Aggregates and Value Objects**: Encapsulating logic within domain objects.
- **Domain Events**: Communication between aggregates and bounded contexts.
