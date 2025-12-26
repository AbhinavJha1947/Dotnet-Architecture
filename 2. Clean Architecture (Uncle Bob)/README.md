# Clean Architecture (Uncle Bob)

This project follows the principles of Clean Architecture, where the Domain core is completely independent of external frameworks.

## Structure
- **src/Domain**: Enterprise logic, entities, and value objects.
- **src/Application**: Use cases, DTOs, and interface definitions.
- **src/Infrastructure**: Implementation details (Database, Identity, Messaging).
- **src/WebApi**: Entry point and controllers.

## Key Principles
- **Inward Dependency**: All dependencies point towards the Domain layer.
- **Framework Independence**: The core business logic is not tied to any database or UI framework.
- **Testability**: The architecture promotes high testability by isolating business rules.
