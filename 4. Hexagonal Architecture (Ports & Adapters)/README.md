# Hexagonal Architecture (Ports & Adapters)

This project demonstrates Hexagonal Architecture, isolating the application core from external influences using ports and adapters.

## Structure
- **src/Application.Core**: The central business logic (The Hexagon).
- **src/Application.Ports**: Interfaces for driving and driven adapters.
- **src/Adapters.Infrastructure**: Implementation of driven ports (DB, Messaging).
- **src/Adapters.Web**: Implementation of driving adapters (Controllers).

## Key Principles
- **Agnostic Core**: The core doesn't know about databases or UIs.
- **Ports**: Definitions of how the application is used (Input) or how it uses external tools (Output).
- **Adapters**: Concrete implementations that plug into the ports.
