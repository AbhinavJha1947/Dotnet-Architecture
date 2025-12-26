# Onion Architecture

This project implements the Onion Architecture, emphasizing the Domain at the center of the application.

## Structure
- **src/Domain.Core**: Pure domain entities and core business rules.
- **src/Domain.Services**: Domain-specific service logic.
- **src/Application.Services**: Application-level use cases and flow control.
- **src/Infrastructure**: External implementations (SQL, File System, API Clients).
- **src/Web**: The presentation and entry layer.

## Key Principles
- **Domain at the Center**: The core of the application is the domain.
- **Dependency Inversion**: Outer layers implement interfaces defined in inner layers.
- **Pluggable Infrastructure**: Infrastructure can be swapped without affecting the core or application layers.
